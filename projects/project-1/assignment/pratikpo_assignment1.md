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


<header>
  <h1>Assignment Part 2</h1>
</header>

<header>
  <h3>Reflexive/Irreflexive</h3>
</header>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
  
<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">&#xa0;</th>
<th scope="col" class="org-left">Ref</th>
<th scope="col" class="org-left">&#xa0;</th>
<th scope="col" class="org-left">&#xa0;</th>
<th scope="col" class="org-left">&#xa0;</th>
<th scope="col" class="org-left">&#xa0;</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-left">Irr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">A</td>
<td class="org-left">Ai</td>
<td class="org-left">B</td>
<td class="org-left">Bi</td>
</tr>

<tr>
<td class="org-left">&#xa0;</td>
<td class="org-left">A</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
<td class="org-left">OK</td>
<td class="org-left">OK</td>
</tr>

<tr>
<td class="org-left">&#xa0;</td>
<td class="org-left">Ai</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
<td class="org-left">OK</td>
<td class="org-left">OK</td>
</tr>

<tr>
<td class="org-left">&#xa0;</td>
<td class="org-left">B</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
</tr>

<tr>
<td class="org-left">&#xa0;</td>
<td class="org-left">Bi</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
<td class="org-left">X</td>
</tr>
</tbody>
</table>


<a id="orgceec1a2"></a>

**- A: Reflexive and A: Irreflexive: <br>**
  Suppose A is both Reflexive and Irreflexive. Then by reflexivity xAx, however by irreflexivity ￢xAx. This generates a contradiction.<br>
  Similar explanations for:<br>
  **- Ai: Reflexive and Ai: Irreflexive<br>**
  **- B: Reflexive and B: Irreflexive<br>**
  **- Bi: Reflexive and Bi: Irreflexive<br>**
  
**- A: Reflexive and Ai: Irreflexive: <br>**
Suppose that A is reflexive so xAx and Ai is irreflexive so ￢xAix. Since A is the inverse of Ai, so Ai holds between the opposite instances in the relation A, which in this case are both x. That is, xAix. But this contradicts the irreflexivity of Ai.<br>
  Similar explanations for:<br>
  **-B: Reflexive and Bi: Irreflexive**

**- A: Reflexive and B: Irreflexive: OK<br>**
**- A: Reflexive and Bi: Irreflexive: OK<br>**

**- Ai: Reflexive and A: Irreflexive: <br>**
Suppose A is irreflexive and Ai is reflexive. By irreflexivity, ￢xAx. By reflexivity, xAix. Since Ai is the inverse of A, the relation A holds between the opposite instances in the relation Ai, which in this case are both x. That is, xAx. But this contradicts the irreflexivity of A.<br>
Similar explanations for:<br>
  **-Bi: Reflexive and B: Irreflexive**

**- Ai: Reflexive and B: Irreflexive: OK<br>**
**- Ai: Reflexive and Bi: Irreflexive: OK<br>**

**- B: Reflexive and A: Irreflexive: <br>**
Suppose B is reflexive and A is irreflexive. By irreflexivity, ￢xAx. By reflexivity, xBx. Being a subproperty of A, B implies that all the couple of entities connected by B are also connected by A. That is, xBx implies xAx. But this contradicts irreflexivity of A.<br>

**- B: Reflexive and Ai: Irreflexive: <br>**
Suppose B is reflexive and Ai is irreflexive. By irreflexivity, ￢xAix. By reflexivity, xBx. 
Since Ai is inverse of A, the fact ￢xAix implies the fact ￢xAx. 
Since B is a subproperty of A, so xBx implies xAx. This creates a contradiction with the previous step.

**- Bi: Reflexive and A: Irreflexive:<br>**
Suppose that Bi is reflexive and A is irreflexive. By irreflexivity, ￢xAx. By reflexivity, xBix. 
Since Bi is a subproperty of Ai,so xBix implies xAix. 
Since A the inverse of Ai, xAix implies xAx. But this contradicts th irreflexivity of A.

**- Bi: Reflexive and Ai: Irreflexive:<br>**
Suppose that Bi is reflexive and Ai is irreflexive. By irreflexivity, ￢xAix. By reflexivity, xBix. 
Since Bi the inverse of B, xBix implies xBx.
Since B is a subproperty of A, xBx implies xAx. But this contradicts irreflexivity of A.
