Products are mappings, a law of composition

Associative: (xy)z = x(yz) ie. who to associate, left or right
Monoid: An associative set with unit element e (thus nonempty)
Commutative: xy = yx ie. commute from left to right, movement. aka Abelian

Submonoid: if $x, y \in H$, then $xy \in H$
	eg. int * int -> int

Group: Monoid where inverses exist
	xy = yx = e
	INT under addition is a group (e = 0), but NOT under mult


Category: a collection of objects with Morphisms upholding the Law of Composition
Morphism: a set of A -> B, where A, B are objects in a category
Law of composition (map): Mor(B, C) X Mor(A, B) -> Mor(A, C) where
	1. Mor(A, B) is disjoint with Mor(A', B') unless A = A, B = B
	2. Identity Morphism exists eg. Mor(A, A)Mor(A, B) = Mor(A,B)
	3. Associative
