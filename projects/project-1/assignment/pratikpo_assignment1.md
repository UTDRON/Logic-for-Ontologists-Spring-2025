<header>
  <h1>Assignment Part 1- Pratik</h1>
</header>

<h4>1. R is both Symmetric and Asymmetric</h4>

Suppose R is both symmetric and asymmetric. Then by symmetry for any x and y, if xRy it follows that yRx. 
However, by asymmetry it also follows that it is not the case that yRx. This is contradictory. Hence, R cannot be both symmetric and asymmetric.

Error type: X<sup>UNSAT</sup>

<h4>2. R is both Asymmetric and Reflexive</h4>

Suppose R is both Asymmetric and Reflexive. Then by reflexivity xRx, however with antisymmetry if xRx then it is not the case that xRx; this generates a contradiction.
Thus, R cannot be both Asymmetric and Reflexive.

Error type: X<sup>UNSAT</sup>

<h4>3. R is both Reflexive and Irreflexive</h4>

Suppose R is both Reflexive and Irreflexive. Then by reflexivity xRx, however by irreflexivity ￢xRx. This generates a contradiction.
Thus, R cannot be both Reflexive and Irreflexive.

Error type: X<sup>UNSAT</sup>

<h4>4. R is both Functional and Transitive</h4>

Because of transitivity if xRy and yRz then xRz. This means the same individual is related to multiple individuals. However, the functionality 
restricts cardinality of an individual to 1 i.e, if xRy then x cannot be related to another incividual through R. 

Error type: X<sup>NS</sup>

<h4>5. R is both Inverse Functional and Transitive</h4>

Because of transitivity if xRy and yRz then xRz. This means the same individual is related to multiple individuals. However, the inverse functionality 
restricts cardinality of an individual to 1 i.e, if xRy then y cannot be related to another incividual through R. 

Error type: X<sup>NS</sup>

<h4>6. R is both Transitive and Asymmetric</h4>

Suppose we take a relation that follows strict ordering like greater than(>). Then it follows transitivity, and also follows asymmetry. Eg; 5 > 4 and 4 > 3 thus, 5 > 3. And if 5 > 3 it also follows that ￢3 > 5. In this case this combination holds true.
But let’s take another example relation (equality), if a = b and b = c, this means a = c, but with antisymmetry it also says ￢c = a which is not correct. Hence we can’t decide the veracity or unsatisfiability of this combination.

Error type: X<sup>NS</sup>

<h4>7. R is both Transitive and Irreflexive</h4>

Assume R is both transitive and irreflexive.
Suppose if xRy and yRz then xRz.
If we assume that zRx holds then by transitivity xRx. Meaning that transitivity can lead to self-relations. But this contradicts irreflexivity. 
However we can’t decide if zRx holds always. 
For instance, greater than(>) relation is transitive and also is irreflexive, however equality(=) relation is transitive but not irreflexive.
So, the combination’s truthfulness or unsatisfiability is undecidable.

Error type: X<sup>NS</sup>
