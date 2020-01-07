### __Definition__ : A rule of assignment
>subset $r$ of the cartesian product $C \times D$ of two sets, having the property that each element of C appears as the first coordinate of at most one ordered pair belonging to $r$

### __Definition__ : Restiriction
>If $f$ : A $\rightarrow$ B and if $A_{0}$ is a subset of A, we define the __restriction__ of $f$ to $A_{0}$ to be the function mapping $A_{0}$ into B whose rule is $\{(a, f(a)) | a \in A_{0} \}$  
Notation: f|$A_{0}$

## 2. Relations
### __Definition__ : Equivalence Relations and Partitions
>1) reflexivity: xCx for every x in A
>2) symmetry: If xCy, then yCx
>3) transitivity: If xCy and yCz, then xCz

### __Definition__ : Equivalence class
> $E = \{ y\;| y \sim x\}$

### __Lemma 3.1__
> Two Equivalence class $E$ and $E'$ are either disjoint or equal.

### __Definition__ : partition
> A __partition__ of a set $A$ is a collection of disjoint nonempty subsets of $A$ whose union is all of $A$

Given any partition $D$ of $A$, there is exactly one equivalence relation on A from which it is derived.

### __Definition__: Order Relations
>1) comparability: for every $x$ and $y$ in $A$ for which $x \neq y$, either xCy or yCx.
>2) nonreflexivity: For no x in A does the relation xCx hold.
>3) transitivity: If xCy and yCz, then xCz

### __Definition__: Open Interval
> open interval : $\{x | \;a < x < b\}$  
> a is __immediate predecessor__ of b  
> b is __immediate successor__ of a

### __Definition__: Order Type
> Suppose A and B are two sets with order relationis $<_{A}$ and $<_{B}$ respectivley.  
> A and B have the same __order type__ if there exists a biejective function $f$ : A $\rightarrow$ B such that,
>
>$$a_1 <_{A} a_2 \Rightarrow f(a_1) <_{B} f(a_2)$$
>
>that is, preserves the order

### __Definition__: dictionary order relation
> Suppose A and B are two sets with order relationis $<_{A}$ and $<_{B}$ respectivley. Define an order relation < on $A \times B$ by
>
> $$a_1 \times b_1 < a_2 \times b_2 $$


### __Definition__: bounded, largest, smallest
> set A, relation <  
> __largest element__ $b$ : $b \in A$ and if $x \leq b \;\;\forall x \in A$  
> __bounded above__ : if $\exists \; b$ of A such that $x \leq b \;\;\forall x \in A$  
> __least upper bound__ = __supremum__ of A = $sup \; A_0$ : if the set of all upper bounds for A has a smallest element
> __greatest lower bound__ = __infimum__ of A = $inf \; A_0$

### __Definition__: least upper bound property
> If every nonempty subset $A_0$ of $A$ that is bounded above has a least upper bound, ordered set A is said to have the least upper bound property

## 3. The Integers and the Real Numbers
### __Definition__: binary operation
> function mapping $A \times A$ into A