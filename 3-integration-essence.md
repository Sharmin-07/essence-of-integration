Note- The hyperreal world is like an extended version of the real numbers, where you get not only all the regular numbers you already know (like 1, π, and √2), but also tiny, infinitesimal numbers (smaller than any positive real number but still greater than zero) and huge, infinite numbers (larger than any real number).

# Long Version :

A circle can be thought of as a collection of infinitely many infinitesimally thin concentric rings or triangles with a common vertex at the centre. Let's take up the concentric rings method and understand how a circle's area arises from its infinitesimal elements.

Imagine a circle of radius R to be made up of infinitely many concentric rings. As they are infinite in number, each ring must be of infinitesimal (i.e., just a little over zero) thickness. Let's call this thickness dr. Note that this thickness is actually the difference in the radii of the outer and inner circles forming a ring. Focus on one ring having inner and outer radii r and r+dr, respectively. On unwrapping or unfolding this ring, we see that it looks almost like a rectangular strip. Therefore, we consider the area of this strip to be 2πr × dr. One may naturally question why don't we consider the circumference of the outer circle, i.e., the one with radius r + dr, while computing the approximate area of this almost-rectangular strip. We can absolutely take the radius of the outer circle, r + dr, to compute this area and we get 
 

2π(r + dr)·dr = 2πr·dr + 2π·(dr)²


However, we neglect the 2π·(dr)² term as it is a second-order infinitesimal. A second-order infinitesimal is neglected because, as reasoned by many, it vanishes faster than a first-order infinitesimal and, therefore, has no contribution in the final result. (Sounds cliché, doesn't it? We'll get to it in a while.) When we integrate 2πr·dr (with respect to dr, of course) for the area of the whole circle, taking the elemental area as that of a ring, with upper and lower limits R and 0, respectively, we get πR².

But what if we do not ignore the 2π·(dr)² term, i.e., the second order infinitesimal? What would it account for? Now, we cannot integrate 2π·(dr)² with respect to dr, since 2π·(dr)² is not a valid integrand here. But we do know that integration is essentially adding up infinitely many infinitesimal elements, and, summing up infinitely many second-order infinitesimals gives a quantity which is still smaller than any real number but may or may not be a first-order infinitesimal. Therefore, our true “error-free” area of a circle would be πR² + ε, where ε is an infinitesimal. But since we do not consider infinitesimals to be a part of the real number system, we take the area of the circle to be πR², which is EXACT with respect to the real world. However, if we were to derive this formula with respect to the hyperreal world, the exact result would have been πR² + ε, itself, since infinitesimals are, very much, a part of the hyperreal number system, and hence cannot be neglected with respect to the same. That is, πR² is an approximate answer with respect to the hyperreal world.

And that, right there, is why calculus is exact. We approximate with respect to the hyperreal world, to obtain an exact result in the real world. That’s why calculus works so beautifully: an approximate in one world is exact in the other.


# Short Version :

Infinitesimals, whether first or second ordered, are not considered to be a part of the real number system, but they are a part of the hyperreal number system. The approximations that we carry out while deriving formulae using integration give us the exact results with respect to the real world since we are approximating with respect to the hyperreal world. πR² is an approximated result with respect to the hyperreal world, but it is an exact result with respect to the real world.

























