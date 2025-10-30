In this derivation, I will first explain the geometric mechanism behind integration, followed by the justification for why certain approximations are valid. The goal is not computational efficiency but conceptual precision — to understand why integration yields exact results in the real number system despite infinitesimal approximations in the hyperreal framework.

NOTE-
1) I’m assuming that anyone reading this is aware of terminologies such as infinitesimals, first-order infinitesimals, second-order infinitesimals, and hyperreals.
2) Both of first and second order infinitesimals are a part of the hyperreal number system. 
3) Infinitesimals are not considered to be a part of the real number system.
4) I won't be diving into heavy calculus since the sole purpose of me writing this is to explain the mechanism of calculus, integration, to be precise.


Long version-

We can derive this by breaking the circle into concentric rings, thin triangles, or by using the formula for the area of a sector. I’ll use the concentric rings method.

Imagine a circle of radius  R  made up of infinitely many concentric rings. Since there are infinitely many, the difference between the radii of any two consecutive rings is infinitesimal — denote this difference by  dr .

Take a ring whose outer and inner radii are  r + dr  and  r , respectively, where  R > r + dr > r > 0 . We can take this ring and “unfold” it to form a rectangle. Strictly speaking, it isn’t an exact rectangle, but the error is of second-order infinitesimal magnitude using the formula for the area of an annular sector. Therefore, we neglect it.

The area of the rectangle is the circumference multiplied by the difference in radii, which is  dr  (since  (r + dr) - r = dr ). The length of the strip is taken to be the circumference of the circle with radius  r , i.e.,  2πr . It can be argued that we could also use the circumference of the outer circle with radius  r + dr , i.e.,  2π (r + dr) , but that would only introduce a second-order infinitesimal, which we would neglect anyway.

Integrating while varying  r  from 0 to  R , we find that the total area is  πR² . At first, this appears to be an approximation, though it isn’t. If we were to calculate this with respect to the hyperreal number system, where second-order infinitesimals are not neglected, the result would be  πR² + ε , where  ε  is a first-order infinitesimal — the result of summing infinitely many second-order infinitesimals. This is justified because, in the hyperreal framework, we perform summation, not integration.

However, since infinitesimals are not included in the real number system,  πR²  is perfectly exact in the real sense. That is the essence of calculus: we approximate with respect to the hyperreal world, which gives an approximate answer there — but it is an exact answer within the real world.


 
Short version-

Imagine a circle made up of infinitely many infinitesimally thin rings. When unfolded, each ring resembles a rectangle whose length equals the circumference of one of the circles forming it. We find the area of this rectangle, neglect second-order infinitesimals if any, and then integrate with suitable limits. The result is πR².













