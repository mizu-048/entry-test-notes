---
dg-publish: true
---


| Law                 | Symbolic Representation                              | Definition                                                                                       |
| ------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Commutative Law** | $a \oplus b = b \oplus a$                            | The order of applying the operation does not affect the result.                                  |
| **Associative Law** | $(a \oplus b) \oplus c = a \oplus (b \oplus c)$      | The grouping of operands does not affect the result.                                             |
| **Closure Law**     | $a,b \in S, a \oplus b \in S$ (where $S$ is the set) | The result of applying the operation to two elements from a set is still an element of that set. |
>[!question]- If A and B are real numbers then A+B is a real number This law is called  
>**a)Closure**$\qquad$b)Commutative$\qquad$c)Associative$\qquad$d)Distributive
  
**Supplementary angles**: whose sum is 180(degree)

$\sqrt{ n }=\dfrac{n}{\sqrt{ n }};\qquad \dfrac{1}{\sqrt{ n }}=\dfrac{\sqrt{ n }}{n}$
- ![[triangle in a triangle.png|center|200]]
	- ratio of area of ABC to DEF= 1/4
	- perimeter of ABC to DEF = 1/2
	- measure of angles of DEF= 60º
	- all triangles are congruent
	- ratio of length of AC to DE = 1/2
	- CDEF forms a rhombus
- 
# Part 1
## 1: Number System -+
- $a + bi = (a,b )$
	- $i^{2n}= -1$ ;
	- $i^{3n}= -i$ ;
	- $i^{4n}= 1$ 
>[!question]- $(-i)^{31}$  
>**a)**$i$$\qquad$b)$-i$$\qquad$c)1$\qquad$d)-1
  
  $(-1)^{31}\times(i)^{30}\times i= (-1)\times(-1)^{15}\times i=i$ -
  
- when solving $(a+bi)^{n}$ you can make it  simpler by doing $[(a+bi)^{2}]^{n/2}$
>[!question]-  $(\frac{1+i}{\sqrt{2}})^8=$ ? 
>a)$tb$$\qquad$b)$tb$$\qquad$c)$tb$$\qquad$d)$tb$
  m

$\dfrac{[(1+i)^{2}]^{4}}{\sqrt{ 2 }^{8}}=\dfrac{(1+(-1)+2i)^{4}}{16}=\dfrac{16(-1)^{2}}{16}$

- Modulus or Absolute value=$|Z|$ = $r = \sqrt{a^2 + b^2}$
- argument = $\theta = \tan^{-1}\left(\dfrac{b}{a}\right)$
- theorem for complex numbers also called polar forms are: 
	- De-moivre's: $(a + bi)^{n} = r^{n}(Cos(n\theta) + iSin (n\theta))$
	- Euler formula: $re^{i\theta} = r(Cos\theta + iSin\theta)$
- polar co-ordinates of a point $(r,\theta)$

- $cis\theta = Cos\theta+iSin\theta$
- $\dfrac{cis(x)}{cis(y)} =cis(x-y)$
- $(cis\theta)^x= cis(\theta x)$
>[!question]- $(\cos 20+i\sin 20)^{5} \div (\cos 30+i\sin 30)^{3}$ 
>a)$\cos 20+i\sin 20$$\qquad$b)$\cos 30+i\sin 30$$\qquad$**c)**$\cos 10+i\sin 10$$\qquad$d)$\cos 20-i\sin 20$
  
- multiplication of complex numbers 
$$(a+b i)(c+d i) = (ac-bd)+ (ad+ bc)i$$
- $Q$ field of rational numbers
  $C$ is field of complex numbers
  
- $\dfrac{1}{i}= -i;\qquad \because \dfrac{i}{i}\times \dfrac{1}{i}=\dfrac{i}{i^{2}}$

- Inverse of $(a, b)$ is: $(\dfrac{a}{a^{2}+b^{2}},\dfrac{-b}{a^{2}+b^{2}})$
  MCQ
- Multiplicative Inverse: when multiplied turns the number into 1
  Additive Inverse: When added turns the number into 0
>[!question]- If $a \in R$ then multiplicative inverse of a is 
>a)0$\qquad$b)a$\qquad$c)-a$\qquad$**d)**$\dfrac{1}{a}$
 
>[!question]- Additive inverse of (3, 3) in C is
>a)(3, 0)$\qquad$b)(0, 3)$\qquad$c)(-3, 3)$\qquad$**d)(-3, 3)**
  

## 2: Sets and Sub-Sets -+
- Power of a Set = No. of subsets = $2^{n};\qquad n= \text{no. of elements in set}$
- Absorption Law: $A \cup (A \cap B) = A \cap (A \cup B) = A$
- $$
\begin{array}{|c|c|c|c|c|c|c|}
\hline
 &  &  \text{ AND }  &  \text{ OR }  &  \text{ NOT } &   \text{ 2nd should not be false while first is true } & XOR  \\
\hline

P & Q & P \land Q \text{ (Conjunction)} & P \lor Q \text{ (Disjunction)} & \neg P \text{ (Negation)} & P \rightarrow Q \text{ (Implication)} & P \leftrightarrow Q \text{ (Biconditional)} \\
\hline
\text{True} & \text{True} & \text{True} & \text{True} & \text{False} & \text{True} & \text{True} \\
\text{True} & \text{False} & \text{False} & \text{True} & \text{False} & \text{False} & \text{False} \\
\text{False} & \text{True} & \text{False} & \text{True} & \text{True}  & \text{True}  & \text{False}  \\
\text{False} & \text{False} & \text{False} & \text{False} & \text{True}  & \text{True}  & \text{True}  \\
\hline
\end{array}$$
-  A\B = A-B;         A$'$ = U-A

-  $(A \cup B)' = A' \cap B'$
  $(A \cap B)' = A' \cup B'$
  
- there is only one inverse for each element in a set/group

|                    |                   |                            |
| ------------------ | ----------------- | -------------------------- |
| Converse           | $p \rightarrow q$ | $q\rightarrow p$           |
| Inverse            | $p\rightarrow q$  | $\neg p\rightarrow \neg q$ |
| Contra<br>positive | $p\rightarrow q$  | $\neg q\rightarrow \neg p$ |
- if function's elements are in sets of ordered pairs swapping their position is the function's inverse
- **Groupoid**: if elements are closed with respect to an operator(closure property)
  **Semi Group**: groupoid but order when applying operator doesn't affect the result(associative property)
  - order of a group is its number of elements 


| Name     | Notation | Definition                                           |
| -------- | -------- | ---------------------------------------------------- |
| Subset   | A ⊆ B    | all elements of A are in B                           |
| Superset | B ⊃ A    | B has every element of A(basically A is subset of B) |

- if A is a set, |A| represents the number of elements in A
- $\lvert A \cup B \rvert = \lvert A \rvert + \lvert B \rvert - \lvert A \cap B \rvert$
- $\text{ Probability }=P(A) = \frac{\text{Number of favorable outcomes for event } A}{\text{Total number of possible outcomes}}$
- $P(A∣B)= P(B) P(B∣A)P(A)$
## 3: Matrices -+
- Minor $= M_{ij}$ : determinant of matrix after removing $i^{th}$ row and $j^{th}$ column
-  Co factor $= A_{ij} = (-1)^{i+j}M_{ij}$
- Symmetric: $A^{t} = A$
  Skew-Symmetric $A^{t} = -A$
- Order: Row x Column
- $|4A| =4^{n}A;\qquad$for all square matrices where $n$ is the order of the matrix
- if a whole row/column is zero, determinant is zero
  if a two whole rows or columns are equal then determinant is zero
- $A \times B$ if $A_j = B_i$ 
- if A is diagonal matrix,  then its  inverse is reciprocal of its elements i.e 
  $A= \begin{pmatrix} a & 0 & 0 \\ 0 & b & 0 \\ 0 & 0 & c \end{pmatrix}; A^{-1} =\begin{pmatrix} \dfrac{1}{a} & 0 & 0 \\ 0 & \dfrac{1}{b} & 0 \\ 0 & 0 & \dfrac{1}{c} \end{pmatrix}$
- if A is diagonal then its determinant |A| is simple product of diagonal elements.i.e 
$|A|= \begin{vmatrix} a & 0 & 0 \\ 0 & b & 0 \\ 0 & 0 & c \end{vmatrix} = (abc)$
- solve determinant of $4\times4$ or higher using determinant properties
>[!question]- If $\left|\begin{array}{cc}x & 2 \\ 18 & x\end{array}\right|=\left|\begin{array}{cc}6 & 2 \\ 18 & 6\end{array}\right|$, then $x=$ ? 
>a)6$\qquad$b)16$\qquad$c)-6$\qquad$d)0
  

## 4: Quadratic Equations 
$$
   \text{Quadratic Formula} :\qquad x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
- Fourth roots of 16 are: $2i,-2i,2,-2$
- sum of fourth roots is zero
- A quadratic has a degree of 2, always
- if $a$ is root of polynomial equation $P(x)$ then $P(a)$ is zero
>[!question]-  $x^{4}-9x^{3}+6x^{2}+2$
>**a)1**$\qquad$b)2$\qquad$c)-2$\qquad$d)-1
  
$$\begin{align}
 \\
\omega^3 = \omega^2 \times \omega \times 1= 1 \\
 \\
\omega^2 + \omega + 1 = 0 \\
 \\
\omega  = \dfrac{-1 + i\sqrt{3}}{2}  \\
 \\
\omega^2  =\dfrac{-1 - i\sqrt{3}}{2} \\
 \\
\omega  = \dfrac{1}{\omega^2};\qquad \omega ^2= \dfrac{1}{\omega} 
\end{align}$$
- at the point of intersection of two rays their functions are equal. $ax+by = cx+dy$
- for $ax^2 + bx +c$ whose roots are $\begin{aligned}\alpha \text{ and }  \beta \end{aligned}$ then $$\begin{align*} S = \alpha + \beta &= -\dfrac{b}{a} \\ P = \alpha \times \beta &= \dfrac{c}{a} \\ \\ ax^2 + bx + c &= x^2 - Sx + P \end{align*}$$
>[!question]- If $\alpha$, $\beta$ are roots of $ax^{2}+bx+c=0$, then the equation with roots $\dfrac{1}{\alpha}, \dfrac{1}{\beta}$​ is: 
>a)$ax^{2}-bx-c=0$$\qquad$b)$cx^{2}+ax+b=0$$\qquad$c)$bx^{2}+ax+c=0$$\qquad$**d)**$cx^{2}+bx+a=0$
>
 
 since $\alpha+\beta=-b$ and $\alpha \beta=c$ do the same for the other roots and put values
  
- In a homogeneous system, if the determinant of the coefficient matrix is **non-zero**, the system **only has trivial solution** (i.e. $x=0, \ y=0$
>[!question]- System of equations: $\begin{cases} 3x + 2y = 0 \\ x + 2y = 0 \end{cases}$ has
>**a)Trivial Solution**$\qquad$b)Non-Trivial Solution$\qquad$c)infinite solutions$\qquad$d)none
 
 since $$ \begin{align}
 \begin{vmatrix} 
 {{3}} & {{2}} \\ 
 {{1}} & {{2}}
 \end{vmatrix} = & \ 6 -4= 4 \\ 4  & \neq 0
\end{align}
 $$
 -  
  
## 6: Sequences and Series+ 
- $$
\begin{array}{|c|c|c|c|c|}
\hline
\textbf{Type} & \textbf{General Term} & \textbf{Sum} & \textbf{Mean} & \textbf{Example} \\
\hline
\text{A.P.} & a_n = a + (n-1)d & S_n = \dfrac{n}{2}[2a_{1} + (n-1)d] = \dfrac{n}{2}(a_{1} + a_n) & \text{A.M} = \dfrac{a + b}{2} & 2, 5, 8 \\
\hline
\text{G.P.} & a_n = ar^{n-1} & S_n = \dfrac{a_{1}(1 - r^n)}{1 - r} \, \text{for} \, r < 1, \,  \text{or} \, S_n = \dfrac{a_{1}(r^n - 1)}{r - 1} \, \text{for} \, r> 1 & \text{G.M} = \sqrt{ab} & 3, 6, 12 \\
\hline
\text{H.P.} & a_n = \dfrac{1}{a + (n-1)d} & S_n = \dfrac{n}{\dfrac{1}{a_1} + \dfrac{1}{a_2} + \dots + \dfrac{1}{a_n}} & \text{H.M} = \dfrac{2ab}{a+B} & 1, \dfrac{1}{2}, \dfrac{1}{3} \\
\hline
\end{array}
$$

  - x/9 = 0.xxxxx... like if you divide x digit number by 9 with x 9s this repeats that number in decimal e.g.  34/99 = 0.343434... or 234/999= 0.234234....
* $A>G>H$ if a & b are +ve
  $A<G<H$ if a & b are -ve
  $G^2 = A \times H$
- to find d in AP from $a_{x}=m \text{ to } a_{y}=n$
	  $\dfrac{n-m}{y-x} =d$
- Sum of natural numbers starting from one to n is: $\dfrac{n(n+1)}{2}$
>[!question]- $\sum ^{100}_{n=2}:?$ 
  
  simply do $\sum ^{100}_{n=1}=\dfrac{100(100+1)}{2}=50\times 101=5050$ now just -1 from it since the orignal series starts from 2 ANS: 5049
### A.P
- to find d from $a_{n} = x$ and $a_{m} = y$
	- $d =\dfrac{(x-y)}{(n-m)}$
	- e.g.  $a_{2}​=5$ and $a_{6}=17$
	- $d=\dfrac{17-5}{6-2}=\dfrac{12}{4}=3$
- find any $a_{n}$ if from any $a_{m}$ with $d$
	- $a_{n}= a_{m}+d(n-m)$
	  e.g.  $a_{20} =a_5 +d(20-5) = a_5 +15d$
> [!question]- if $a_{3}=4\text{ and } a_{5}=8$ find  $a_{50}$
> a)100$\qquad$b)102$\qquad$**c)98**$\qquad$d) none

- $a_{n} = a_{1}+(n-1)d$
	  $n=\dfrac{a_{n}+a_{1}}{d}+1$
> [!question]- which term is 148, in A.P -2, 4, 10...
> **a)26th**$\qquad$b)25th$\qquad$**c)31th**$\qquad$d) 28th

- $A_{m} = a+\dfrac{m(b-a)}{(n+1)}$
	- m = AM to be found
	- n = Total number of AMs
> [!question]- if there are 6 AM b/w 2 and 5 then $A_{5}$ is:
> **a)$\dfrac{26}{7}$th**$\qquad$b)$\dfrac{6}{5}$th$\qquad$c)$\dfrac{29}{7}$th$\qquad$d) $\dfrac{31}{7}$th
- $a_{n} =S_{n}-S_{n-1}$    for all A.P
	- $a_{5} =S_{5}-S_{4}$
> [!question]- If $S_{n} = 2n^{2} -n$ then $a_{8} =?$
a)120$\qquad$b)53$\qquad$***c)29***$\qquad$d)43
- Sum of interior angles of a polygon = $(n-2)\times 180^{o}$ 
> [!question]- Find the sum of interior angles of 16 sided polygon:
> a)2880$\qquad$***b)2520***$\qquad$c)1800$\qquad$d)360

- if n is *odd* then Sum of n terms = n x middle term
   if n is *even* then Sum of n terms = $n\times \dfrac{(\text{middle term}+2)}{2}$.
> [!question]- If $5^{th}$ term of an A.P. is 5, then sum of 9 terms of A.P. is:
***a) 45***$\qquad$b) 40$\qquad$c) 50$\qquad$d) 35

### G.P
- for an infinite G.P series$$S_{\infty}=\sum_{n=1}^{\infty} a^n = \dfrac{a}{1 - r} , |r| < 1$$
>[!question]- $0.1+0.01+0.0001+\dots$ sum to infinity 

$\dfrac{a_{2}}{a_{1}}=r=0.1,\qquad S_{n}=\dfrac{0.1}{1-0.1}=\dfrac{0.1}{0.9}=\dfrac{1}{9}$ 
- for two terms in GP $a_{n}=x$ and  $a_{m}=y$
	  $r^{n-m} =(\dfrac{x}{y})$
	  e.g. $a_{4}=24 \text{ and }a_{7}=192$
	  $r^{7-4}=r^{3}=\dfrac{192}{24}=8$
	  $r=2$ 
- find any $a_{n}$ if from any $a_{m}$ with $r$
	- $a_{n}= a_{m}r^{n-m}$
	  e.g.  $a_{10}= a_{7} \ r^{10-7} = a_{7} \ r^{3}$
> [!question]- In GP, if $a_{4}$ = 24, and $a_{7}$ = 192 then $a_{10}$ =?
***a) 1536*** $\qquad$b) 1236 $\qquad$c) 1436$\qquad$d)1336
- term of GP remain in GP even after reciprocal
## 7: Permutation and Combination +
 - $n! = (n) \times (n-1)!$
 - ***permutation***: different arrangements of ***n*** numbers taken ***r*** at a time
   ***Combination***: selection of ***r*** objects from a total of **n** objects, where the order of selection does not matter.
$$\begin{align}
   \text{Permutation: \quad} & ^{n}P_{r}= \dfrac{n!}{(n-r)!} = (n)\times(n-1)\times(n-2)\dots (n-(r-1))
\\ \\
   e.g. \qquad&^{7}P_{3}= 7\times 6 \times\underbrace{5}_{7-(3-1)}\qquad  \text{ simply write r digits starting from n 5 } 
\\ \\ \\

   \text{Combination: \quad} & ^{n}C_{r} =\quad \binom{n}{r} = \dfrac{n!}{r!(n-r)!}=  \dfrac{(n)\times(n-1)\times(n-2)\dots (n-(r-1))}{r!}

   \end{align}$$
 - if in combination or permutation **q*** objects are always included: $^{n-p}C_{r-p}$ or $^{n-q}P_{r-q}$if never included $^{n-p}C_{r}$ or $^{n-q}P_{r}$
 - 

| $^{n}C_{0} = ^{n}C_{n} = 1$ | $^{n}C_{r} = ^{n}C_{r-1}$ | $^{n}C_{r}.r! = ^{n}P_{r}$ | $^{n}C_{1} = n$ |
| --------------------------- | ------------------------- | -------------------------- | --------------- |
| $^{n}P_{n}=n!$              | $^{n}C_{r} = ^{n}C_{n-r}$ |                            |                 |
- if some object in permutation is being repeated say $p$ times e.g. A,B,B,C,C,C,D (B is repeated 2 times and C 3 times so) then its permutation taking 5 at a time is
$$
 \dfrac{^{7}P_{5}}{2! \times 3!} = \dfrac{\dfrac{7!}{(7-5)!}}{2! \times 3!} ={\dfrac{7!}{({2! \times 3!})\times(7-5)!}}
$$

> [!question]- In how many ways can the letters of the word 'LEADER' be arranged?
> a)72$\qquad$b)44$\qquad$**c)360**$\qquad$d)72065$\qquad$e)None of these

and 


> [!question]- In how many different ways can the letters of the word 'LEADING' be arranged in such a way that the vowels always come together?
a)360$\qquad$b)480$\qquad$**c)720**$\qquad$d)5040$\qquad$e) None of these

also try for `corporation` , note that $r$ comes twice and o thrice
> [!question]- How many 3-digit numbers can be formed from the digits 2, 3, 5, 6, 7 and 9 which are divisible by 5 and none of the digits is repeated?
a)5$\qquad$b)10$\qquad$c)15$\qquad$**d)20**

since divisible by 5, 5 is fixed at the end, no digits repeat so $^{5}p_{2}$ = $5\times 4$since only two places remain,

> [!question]- How many positive integers 'n' can be form using the digits 3, 4, 4, 5, 6, 6, 7, we want 'n' to exceed 60,00,000?
a)320$\qquad$b)360$\qquad$**c)540**$\qquad$d.720


> [!question]- how many natural numbers less than a lakh can be formed with the digits 0, 6 and 9?
**a)242**$\qquad$b)243$\qquad$c)728$\qquad$d)none  

less than a lakh has 5 digits, each digit can be replaced by 3 possible numbers so $3 \times 3\times 3\times 3\times 3 = 3^{5}$
excluding 00000, so 243-1=242


 - Diagonals in an $n$ sided polygon: $^{n}C_{2} - n$
 - circular permutation  = $(n-1)!$
   circular permutation on a flipable ring = $\dfrac{(n-1)!}{2}$
  
- common factorials

| 0!  | 1!  | 2!  | 3!  | 4!  | 5!  | 6!  | 7!   |
| --- | --- | --- | --- | --- | --- | --- | ---- |
| 1   | 1   | 2   | 6   | 24  | 120 | 720 | 5040 |

- in permutation **order** of elements matters while in combination only the **presence** of an elements matters
- how to determine whether the question requires permutation or combinations
### Combination:
$$\begin{align}

   \text{Combination: \quad} & ^{n}C_{r} =\quad \binom{n}{r} = \dfrac{n!}{r!(n-r)!}
\end{align}
$$
- $^{n}C_{x} = ^{n}C_{y}; \qquad \text{if } x+y = n$
> [!question]- $^{n}C_{5} = ^{n}C_{4}; \qquad \text{find n}$
> a)5 $\qquad$**b)9**$\qquad$c)6$\qquad$d)8

- for consecutive $r$'s with same n: $^{n}C_{r}+ ^{n}C_{r-1} = ^{n+1}C_{r}$ keeping the larger $r$
> [!question]- $^{13}C_{5} + ^{13}C_{7} = \ ?$
> **a)Both B and C** $\qquad$b)$^{14}C_{6}$$\qquad$c)$^{14}C_{8}$$\qquad$d)$^{14}C_{7}$

solution: $=  ^{13}C_{8} + ^{13}C_{7} \qquad\because \ ^{n}C_{r} + ^{n}C_{n-r}$
and using above given rule, 8 is higher so we$^{14}C_{8}$ or $^{14}C_{14-8}$ = $^{14}C_{6}$ 

- $^{n}C_{r} \times r!= ^{n}P_{r}$
> [!question]- $^{n}C_{r} = 28+ ^{n}P_{r} = 112$ then $r!$
> a)none$\qquad$**b)4** $\qquad$c)12$\qquad$d)2

- $^{n}C_{x} = ^{m}C_{x}$ are equal for all n and m, if $x=0$ as $^{n}C_{0}=1$   



### Geometrical problems
- if n is the number of non-collinear points
$$
\begin{align}
^{n}C_{2} = &  \text{ Number of line segments }\\
 \\
^{n}C_{2}-n = &  \text{ Number of diagonals}\\
 \\
^{n}C_{3} = &  \text{ Number of triangles}\\
 \\
^{n}C_{4} = &  \text{ Number of quadrilaterals}\\
 \\
^{n}C_{5} = &  \text{ Number of Pentagonals}\\

\end{align}
$$

> [!question]- Diagonals in 8 sided polygon?
> a)28$\qquad$b)52 $\qquad$**c)20**$\qquad$d)56

> [!question]- Triangles in pentagon?
> a)40$\qquad$b)50 $\qquad$**c)10**$\qquad$d)70

$^{5}C_{3}$

| Pecrmutation                                                                                                                                 | Combinations                                                                                                            |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Arrangements<br>standing or sitting in row or in a circle<br>problem regarding digits<br>letters(A,B,C...)<br>Formation of words, number,etc | Selection, Choice, Draw,etc<br>Distributation, formation of  a group, commitee, team,etc <br>problem regarding geometry |
|                                                                                                                                              |                                                                                                                         |
### Probability:
- Rules of probability:
	- Probability of an event =$P(E) =\dfrac{n(E)}{n(S)}= \dfrac{\text{no. favourible outcomes}}{\text{total  outcomes}}$
	  
$$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
>[!question]- Tickets numbered 1 to 20 are mixed up and then a ticket is drawn at random. What is the probability that the ticket drawn has a number which is a multiple of 3 or 5?
>a)$\dfrac{1}{2}$$\qquad$b)$\dfrac{2}{5}$$\qquad$c)$\dfrac{8}{15}$$\qquad$**d)**$\dfrac{9}{20}$
  
  $\dfrac{20}{5}=4;\qquad \dfrac{20}{3} \approx 6$  and $15$ which comes with both so  $P=\dfrac{4}{20}+\dfrac{6}{20}-\dfrac{1}{20}$ 
- blueeeeh:
	- $P(E)+P\overline{(E)}=1;\qquad P\overline{(E)}=1-P(E)$
	-  probability can never be greater than 1
	- Improbability of an event = $P\overline{(E)}$
>[!question]-  In a box, there are 2 red, 2 blue and 3 green balls. Two balls are picked up randomly. What is the probability that neither is is blue?
>a)$\dfrac{10}{21}$$\qquad$b)$\dfrac{11}{21}$$\qquad$c)$\dfrac{2}{7}$$\qquad$d)$\dfrac{5}{7}$
  
  Total outcomes: $^{7}C_{2}=21$,probability for NOT BLUE(not including its two balls): $\dfrac{^{7-2}C_{2}}{21}=\dfrac{10}{21}$
  
<table style="border: 2px solid #57ffc0; border-collapse: collapse;">
  <tr>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">Die</th>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">1</th>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">2</th>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">3</th>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">4</th>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">5</th>
    <th style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">6</th>
  </tr>
  <tr>
    <td style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
  </tr>
  <tr>
    <td style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
    <td>8</td>
  </tr>
  <tr>
    <td style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
  </tr>
  <tr>
    <td style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
    <td>10</td>
  </tr>
  <tr>
    <td style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">5</td>
    <td>6</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
    <td>10</td>
    <td>11</td>
  </tr>
  <tr>
    <td style="background-color: #57ffc0; color: black; border: 2px solid #57ffc0;">6</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
    <td>10</td>
    <td>11</td>
    <td>12</td>
  </tr>
</table>
>[!question]-  What is the probability of getting a sum 9 from two throws of a dice?
>a)$\dfrac{1}{6}$$\qquad$b)$\dfrac{1}{8}$$\qquad$**c)**$\dfrac{1}{9}$$\qquad$d)$\dfrac{1}{12}$

>[!question]- Two dice are tossed. The probability that the total score is a prime number is: 
>a)$\dfrac{1}{6}$$\qquad$**b)**$\dfrac{5}{12}$$\qquad$c)$\dfrac{1}{2}$$\qquad$d)$\dfrac{7}{9}$
  
  
- Card in a deck: $52$
	- Spades, Hearts, Diamonds, Clubs: $(13\times4) =52$ 
	- Black Cards: 26,   Red Cards: 26
	- Face Cards: $12$
	- All Hearts and Diamonds are Red
	- All Spades and Clubs are Black
>[!question]- One card is drawn from a pack of 52 cards. What is the probability that the card drawn is either a red card or a king?
>a)$\dfrac{1}{2}$$\qquad$b)$\dfrac{6}{13}$$\qquad$**c)**$\dfrac{7}{13}$$\qquad$d)$\dfrac{27}{52}$
  
  Red card Prob: $\dfrac{26}{52}$, King Prob: $\dfrac{4}{52}$, Red King Porb: $\dfrac{2}{52}$; Total Prob: $\dfrac{26}{52}+\dfrac{4}{52}-\dfrac{2}{52}=\dfrac{28}{52}=\dfrac{14}{26}=\dfrac{7}{13}$
  
- 1/2 Probability of even and odd **sum** from one or multiple dice rolls$;\qquad \because  \text{one die}\dfrac {3}{6}, \text{two die} \dfrac{18}{36}$

 $P(A \cap B)$ is the probability of an event where both A and B occur, $P(A \cup B)$ is the probability where in a given set either A or B may occur
- possible outcomes of an experiment with $x$ outcomes performed $n$ times: $x^n$, then probability is $\dfrac{\text{favourable outcomes from } x^n}{x^n}$
	- Possible outcomes of a coin tossed $n$ times: $2^{n}$
	- Possible outcomes of a dice rolled $n$ times: $6^{n}$
>[!question]- In a simultaneous throw of two coins, the probability of getting at least one head is:
>a)$\dfrac{1}{2}$$\qquad$b)$\dfrac{1}{3}$$\qquad$c)$\dfrac{2}{3}$$\qquad$**d)**$\dfrac{3}{4}$

>[!question]- Four dice are thrown simultaneously. Find the probability that all of them show the same face: 
>**a)**$\dfrac{1}{216}$$\qquad$b)$\dfrac{1}{36}$$\qquad$c)$\dfrac{4}{216}$$\qquad$d)$\dfrac{3}{216}$
 
 Total outcomes: $6^{4}$, same face: $\underbrace{ 6 }_{ \text{since they have only 6 faces which should be same} }$ , $P(E)=\dfrac{6}{6^{4}}=\dfrac{1}{6^{3}}=\dfrac{1}{216}$
  
$S=\{H H, H T,TH, TT\}$
- probability of an
- dependent events:
  >[!question]- a work is to be and involves 3 steps, step 1 has probability of completion 0.7, step 2 has probability of completion 0.8, step 3 has probability of completion 0.9, total probability of work being done is?

simply multiply them $0.7\times 0.8 \times 0.9$
  

## 8: Mathematical Induction and Binomial Theorem
### Mathematical Induction
- **Use back solving method**
>[!question]- $1+2+3+4+\dots +(2\times 3^{n-1})=?;\qquad n \in N$
>a)$3^{n-1}$$\qquad$b)$3^{n-1}+1$$\qquad$**c)**$3^{n-1}-1$$\qquad$d)$3^{n+1}$

since n is a natural number, using 2 and adding only first two numbers (1+2) = 3, now put n=2 in each option and whichever equal 3 is correct


>[!question]- for positive integral values of n, $5^{n}-2^{n}$ is divisible by: 
>a)7$\qquad$**b)3**$\qquad$c)2$\qquad$d)5

>[!question]- $n^{2}>n+3$ is true for integral values: 
>a)$n\geq 2$$\qquad$b)$n>8$$\qquad$**c)**$n \geq 3$$\qquad$d)$n\leq 6$
  
  since $n\geq3$ includes more numbers than $n>8$  so we use it
### Binomial Theorem
$$
(a + x)^n = {}^nC_0 \cdot a^n x^0 + {}^nC_1 \cdot a^{n-1} x^1 + {}^nC_2 \cdot a^{n-2} x^2 + \cdots + {}^nC_{n-1} \cdot a^1 x^{n-1} + {}^nC_n \cdot a^0 x^n
$$
where $^{n}C_{0}, \ ^{n}C_{1}, \ ^{n}C_{2}\dots$ are binomial co-efficient
>[!question]- binomial expression of A is: $1-8x+24x^{2}-32^{3}+16x^{4}$ then A is? 
>**a)**$(1-2x)^{4}$$\qquad$b)$(1-4x)^{4}$$\qquad$c)$(1+2x)^{4}$$\qquad$d)$(1+4x)^{4}$
  
  since there are alternating minus sign, A contain a minus, and 2nd term is 8x, which is n($^{n}C_{1}=n =4$) times  $2x$

- number of terms is $n+1$
>[!question]- Number of terms in the expansion of $(1+2x+x^{2})^{4}$ are: 
>a)5$\qquad$b)8$\qquad$**c)9**$\qquad$d)none
>

first make it binomial and it becomes $[(1+x)^{2}]^{4}$

-  Middle term if n is even:$\qquad(\dfrac{n+2}{2})^{ \text{ th }}$ position

- if n is odd:$\qquad \qquad(\dfrac{n+1}{1})^{ \text{th}}  \text{ and } (\dfrac{n+3}{1})^{ \text{th}}$ position

- Sum of **binomial co-efficient**: $\qquad 2^{n}$ 
- Sum of even or odd binomial co-efficient: $2^{n-1}$
>[!question]-  In a binomial expansion, if the sum of binomial coefficients is 128, then the number of terms in expansion
>a)7$\qquad$b)9$\qquad$**c)8**$\qquad$d)6
  
  since $a^{7}=128$ , $n=7$ and number of terms is $n+1=8$

-  Find Sum of co-efficient$_{ \text{not binomial coefficient}}$ of $(a+bx)^{n}$ by replacing $x$ by 1 and solving
>[!question]-  Sum of co-efficients in the expansion of $(1-3x)^{5}$ is:
>a)32$\qquad$b)16$\qquad$**c)-32**$\qquad$d)-16

  
- Sum of exponent of $a$ and $x$ in each term is equal to $n$
>[!question]- Which of the following is the term in the expansion of $(x + 3y)^{5}$? 
>a)$80xy^{2}$$\qquad$**b)**$90y^{2}x^{3}$$\qquad$c)$80x^{5}y^{2}$$\qquad$d)$5xy^{5}$
  
  $n$ is 5 so the degree of the correct option should be 5

- $x^{\text{th}}$ term or $r^{ \text{th}}$ power of b:  
  $$T_{r+1}=\binom{n}{r} \times a^{n-r}\times b^{r}$$ where $r+1$ is for 4th term so we put r=3
>[!question]- the 8th term in the expansion of $(2x-\dfrac{1}{2x})^{12}$ 
>a)$198x^{-2}$$\qquad$b)$198x^{2}$$\qquad$c)$-198x^{-2}$$\qquad$d)$-198x^{2}$
  
  8th term so r=7, since all coefficient same in option, don't need to calculate $^{12}C_{7}$ , since all even terms in are negatives when a negative is present in equation, its negative, now $a^{n-r}\times b^{r}$$= 2x^{12-7}\times \dfrac{1}{(2x)^{7}}$
- if asked to find Xth terms **from last**, simply exchange $a$ and $b$: $T_{r+1}=\binom{n}{r} \times b^{n-r}\times a^{r}$
>[!question]- the 8th term **from last** in the expansion of $(2x-\dfrac{1}{2x})^{12}$ 
>a)$1526x^{2}$$\qquad$b)$-1498x^{2}$$\qquad$**c)**$-3168x^{2}$$\qquad$d)none
 
 this time we calculate the combination, $^{12}C_{7}\times(-\dfrac{1}{2x})^{12-7}\times 2x^{7}=729\times-\dfrac{1}{32}\times 128=3168$

- Term involving Cth power of x as $x^{c}$ in an equation of form
	-  $(ax+\dfrac{1}{bx})^{n}$: we get value of r by doing $n-tr=c;\qquad r=\dfrac{n-c}{t}$ where t is the combined degree of $ax$ and $\dfrac{1}{bx}$ here its 2
	- $(a-bx)^{n}:$ it is simply nth position, if $bx$ has a degree of 1
	- term independent of $x$ means $x^{0}$, where c=0
>[!question]- Term involving $x^{2}$ in the expansion of $(2x-\dfrac{1}{2x})^{12}$ 
>a)$\qquad$b)$\qquad$c)$tb$$\qquad$d)$tb$

here $n=12$, and $t=2$ so $r=\dfrac{12-2}{2}=5$, that means 6th term involves $x^{2}$
-   
## 9-14: Trigonometry
### 9: Fundamentals of Trigonometry

| System      | units                                    | conversion                                           | definition                                                               |
| ----------- | ---------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------ |
| sexagesimal | $\theta^{\circ} M_{inute}' S_{econds}''$ | $\dfrac{M'}{60}=\theta^\circ, \dfrac{S''}{60}=M$<br> | 1 degree is the angle, the 360th part of a circle subtends on the centre |
| circular    | rad.                                     | $2\pi \ rad.= 1 \ rev = 360^\circ$                   | the angle subtended by an arc equal in length to radius                  |
- basic unit of angle is second (60th part of a minute and 3600th part of a degree

- Calculate angle between clock hands: $30^{o} \times \text{Hrs} - (\dfrac{11}{2})^{o}\times \text{Mins}$
>[!question]- angle  between hands of watch at 11:10am, in degree
>a) 275$\qquad$b)225$\qquad$**c)A and D**$\qquad$d)85

$(30\times 11)- (10 \times \dfrac{11}{2}) = 275$
275 is in 4th quad so (360-275) = 85 so both

| Polygon      | Area                                      | Perimeter      | arc            |
| ------------ | ----------------------------------------- | -------------- | -------------- |
| **Circle**   | $A =\pi r^{2}$                            | $L =2 \pi r$   | $l = \theta r$ |
| **Sector**   | $A =\dfrac{1}{2}r^2\theta = \dfrac{1}{2}rl$ | $l = \theta r$ |                |
| **Triangle** | $A = \dfrac{1}{2}ab$                       |                |                |
![[sign of trigonometric functions.png|center|300]]



|              | co-ratios          | Identity                             | addition                                                                                                                                                             | double angle                                                                                                                                        | triple angle                                      | half angle                                                                                   |
| ------------ | ------------------ | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Sin $\theta$ | Cos $90- \theta$   | ==$\sin^2\theta +\cos^2\theta=1$==   | ==$\sin(\alpha + \beta) = \sin(\alpha)\cos(\beta) + \cos(\alpha)\sin(\beta)$==<br>==$\sin(\alpha - \beta) = \sin(\alpha)\cos(\beta) - \cos(\alpha)\sin(\beta)$==<br> | $\sin 2\theta =2\cos\theta\sin\theta$<br>$= \dfrac{2\tan\theta}{1+\tan ^{2}\theta}$                                                                 | $\sin(3\theta) = 3\sin(\theta) - 4\sin^3(\theta)$ | $\sin\left(\dfrac{\theta}{2}\right) = \pm \sqrt{\dfrac{1 - \cos(\theta)}{2}}$                |
| Cos $\theta$ | Sin $90- \theta$   | ==$\sec^2\theta = \tan^2\theta+1$==  | ==$\cos(\alpha + \beta) = \cos(\alpha)\cos(\beta) - \sin(\alpha)\sin(\beta)$==<br>==$\cos(\alpha - \beta) = \cos(\alpha)\cos(\beta) + \sin(\alpha)\sin(\beta)$==     | $\cos 2\theta =2\cos^{2}\theta -1$<br>$= 1 - 2\sin ^{2}\theta$<br>$=\cos^{2}\theta-\sin^{2}\theta$<br>$=\dfrac{1-\tan^{2}\theta}{1+\tan^{2}\theta}$ | $\cos(3\theta) = 4\cos^3(\theta) - 3\cos(\theta)$ | $\cos\left(\dfrac{\theta}{2}\right) = \pm \sqrt{\dfrac{1 + \cos(\theta)}{2}}$                |
| Tan $\theta$ | Cot $90- \theta$   | ==$cosec^2\theta = \cot^2\theta+1$== | irrelevant                                                                                                                                                           | $\tan 2\theta= \dfrac{2\tan\theta}{1-\tan ^{2}\theta}$                                                                                              | irrelevant                                        | $\tan\left(\dfrac{\theta}{2}\right) = \pm \sqrt{\dfrac{1 - \cos(\theta)}{1 + \cos(\theta)}}$ |
| Sec $\theta$ | Cosec $90- \theta$ |                                      |                                                                                                                                                                      |                                                                                                                                                     |                                                   |                                                                                              |
|              |                    |                                      |                                                                                                                                                                      |                                                                                                                                                     |                                                   |                                                                                              |
>[!question]- $\cos 75$ 

$\cos(45+30)=\cos(30)\times(\cos 45)-\sin(30)\times \sin(45)=(\dfrac{\sqrt{ 3 }}{2}\times \dfrac{1}{\sqrt{2}})-(\dfrac{1}{2}\times \dfrac{1}{\sqrt{ 2 }})=(\dfrac{\sqrt{ 3 }}{2}\times \dfrac{\sqrt{ 2 }}{2})-(\dfrac{1}{2}\times \dfrac{\sqrt{ 2 }}{2})$

- if sum of two angles is 90 then those co ratios are equal
>[!question]- $\dfrac{\tan 71}{\cot 19}$
>a)Cot 42$\qquad$**b)Both C and D**$\qquad$c)Cot 45$\qquad$d)Tan 45c


>[!question]- $\tan 9\tan 18\tan 72\tan 81$
>a)0$\qquad$**b)1**$\qquad$c)9$\qquad$d)none

$=\cot 81\cot 72\tan 72\tan 81$

>[!question]- $\dfrac{1-\cos t}{\sin t}$ 
>a)$\cot \dfrac{t}{2}$$\qquad$b)$\tan \dfrac{3}{t}$$\qquad$**c)$\tan \dfrac{t}{2}$**$\qquad$d)$\cos 3t$

simplify put t=90 and compare answers with each option

>[!question]- $8\cos 15 \cos \dfrac{15}{2} \sin \dfrac{15}{4} \cos \dfrac{15}{4}=?$ 
>a)0.2$\qquad$b)**0.5**$\qquad$c)0.1$\qquad$d)1
 
$=4\cos 15 \cos \dfrac{15}{2} \sin \dfrac{15}{2}\qquad \because 2\sin\theta \cos\theta=\sin 2\theta$ 
$=2\cos 15  \sin 15= \sin 30=0.5$

>[!question]- $6\sin 10 - 8\sin 10$ 
>a)2$\qquad$**b)1**$\qquad$c)$\dfrac{1}{2}$$\qquad$d)$\sqrt{ 3 }$

$2(3\sin 10- 4\sin^{3}10)$

>[!question]- $\sin\theta=\dfrac{1}{2}\cos ec\theta$ , $\theta$ is
  
  $\sin\theta=\dfrac{1}{2}\times \dfrac{1}{\sin\theta}; \qquad\sin\theta =\dfrac{1}{\sqrt{ 2 }}$

- for a right angled triangle
$Cos\theta = \dfrac{Base}{Hypotenuse}$
$Sin\theta = \dfrac{Prependicular}{Hypotenuse}$
$\tan\theta = \dfrac{\sin \theta}{cos\theta} = \dfrac{Prependicular}{Base}$

since 71+19= 90, so tan 71 = Cot(90 - 71) = Cot 19
and tan 45 and cot 45 both  equal to one

- Allied angle concept: if $\theta = n \dfrac{\pi}{2} \pm \phi_{rad}=((n\times 90)\pm \phi^{o})$
	  if $n$ is odd, then the function applied on $\theta$ is converted to it co-ratio with angle $\phi$, otherwise remains same
	  if the function at $\theta$ is negative, then has a negative **sign**
	  e.g. $\sin(90+20)=\ - \cos(20)\qquad$ since $\sin$ is negative in 2nd quad
- for a right angled triangle 
$$
\begin{align}

Cos\theta = \dfrac{Base}{Hypotenuse} \\
 \\
Sin\theta = \dfrac{Prependicular}{Hypotenuse} \\
 \\
\tan\theta = \dfrac{\sin \theta}{cos\theta} = \dfrac{Prependicular}{Base}
\end{align}

$$


|     | product to sum/diff                                                                                                                            | Sum/diff to product                                                                                                                                                                         |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| sin | $\cos(A) \cos(B) = \dfrac{1}{2} \left( \cos(A+B) + \cos(A-B) \right)$<br>$\cos(A) \sin(B) = \dfrac{1}{2} \left( \sin(A+B) - \sin(A-B) \right)$ | $\sin(A) + \sin(B) = 2 \sin( \dfrac{A+B}{2}) \cos( \dfrac{A-B}{2})$<br>$\sin(A) - \sin(B) = 2 \cos\left( \dfrac{A+B}{2} \right) \sin\left( \dfrac{A-B}{2} \right)$                          |
| cos | $\sin(A) \sin(B) = \dfrac{1}{2} \left( \cos(A-B) - \cos(A+B) \right)$<br>$\sin(A) \cos(B) = \dfrac{1}{2} \left( \sin(A+B) + \sin(A-B) \right)$ | $\cos(A) + \cos(B) = 2 \cos\left( \dfrac{A+B}{2} \right) \cos\left( \dfrac{A-B}{2} \right)$<br>$\cos(A) - \cos(B) = -2 \sin\left( \dfrac{A+B}{2} \right) \sin\left( \dfrac{A-B}{2} \right)$ |
|     |                                                                                                                                                |                                                                                                                                                                                             |

| $sin(-θ) = -sin(θ)$   | $\cos ec(-θ) = -\cos ec(θ)$ |
| --------------------- | --------------------------- |
| $\cos(-θ) = \cos(θ)$  | $\sec(-θ) = \sec(θ)$        |
| $\tan(-θ) = -\tan(θ)$ | $\cot(-θ) = -\cot(θ)$       |

| function | $\theta =0$ | $\theta = 30$         | $\theta = 45$         | $\theta = 60$         | $\theta = 90$ |
| -------- | ----------- | --------------------- | --------------------- | --------------------- | ------------- |
| $\sin$   | $0$         | $\dfrac{1}{2}$        | $\dfrac{1}{\sqrt{2}}$ | $\dfrac{\sqrt{3}}{2}$ | 1             |
| $\cos$   | $1$         | $\dfrac{\sqrt{3}}{2}$ | $\dfrac{1}{\sqrt{2}}$ | $\dfrac{1}{2}$        | 0             |
| $\tan$   | 0           | $\dfrac{1}{\sqrt{3}}$ | 1                     | $\sqrt{ 3 }$          | undefined     |
### 10: Trigonometric Identities
![[reference angle.png|center|600]]


|         |                            |
| ------- | -------------------------- |
### 11:
| func    | period formula             |
| ------- | -------------------------- |
| sin(ax) | period = $\dfrac{2\pi}{a}$ |
| cos(ax) | period = $\dfrac{2\pi}{a}$ |
| tan(ax) | period = $\dfrac{\pi}{a}$  |
>[!question]-  period of $\cos bn$

ANS: $\dfrac{2\pi}{b}$  
- $y=a \sin(bx−c)$
	**a**:  determines **amplitude**
	**b**: affects the **period**
	**c**: and **b** affects the ****phase** shift**
    
- phase shift simply refers to the angle $\theta$ or any equation in a trigonometric function()
>[!question]- Phase shift of $y= 2+3\cos(4x+9)$ 
>a)$-\dfrac{9}{2}$$\qquad$b)2$\qquad$**c)$-\dfrac{4}{9}$**$\qquad$d)$-\dfrac{27}{4}$

$4x+9=0;\qquad x=-\dfrac{9}{4}$


-	  any number added or subtracted from the variable is ignored when finding period
	  any number being multiplied to the variable is divides it in period e.g. $\tan (\dfrac{3}{2}x+50)$ has a period of $\dfrac{2}{3}x$, $\sin (8x +2)$ has period of $\dfrac{x}{4}$(since $4(2x)$) has $2x$ is period of normal $\sin$
	  if $Sin,Cos,Sec,Co\sec$ trigonometric function have even$_{2,4,6,\dots}$ exponential power, the period becomes half, $\sin^{2}x, \cos ^{6}x$ both have period of $\dfrac{x}{2}$
>[!question]- period of $y = 3\sin ^{2}5x$ 
>a)$\dfrac{2\pi}{5}$$\qquad$**b)$\dfrac{\pi}{5}$**$\qquad$c)$\dfrac{5}{\pi}$$\qquad$d)$2\pi$


  since $\sin$ has square, period becomes $2\pi \to \pi$ and since $\theta=5x$, period becomes $\pi \to \dfrac{\pi}{5}$
- Frequency of a trigonometric function is simply the reciprocal of its period
>[!question]- frequency of $y=3+2\tan(x-9)$ 
>a)$\dfrac{\pi}{9}$$\qquad$**b)$\dfrac{1}{\pi}$**$\qquad$c)$\dfrac{9}{\pi}$$\qquad$d)$\dfrac{2}{\pi}$

- Amplitude is the constant multiplied with the trigonometric function and **is not negative**
	$\tan,\cot$ have **no amplitude**, their amplitude does not exist
>[!question]- amplitude of $y=-3\sin x$ 
>a)-3$\qquad$b)1$\qquad$**c)3**$\qquad$d)$\pm 3$
 
>[!question]- amplitude of $y=4\tan x$ 
>a)4$\qquad$b)1$\qquad$c)$\pi$$\qquad$**d)Does not Exist**
  
>[!question]- $\sin x=\sin 2x$ is true in the interval $[0,\pi]$ for:
>a)$0,\pi$$\qquad$**b)**$0,\pi,\dfrac{\pi}{3}$$\qquad$c)$0,\pi,\dfrac{\pi}{6}$$\qquad$d)$0,\dfrac{\pi}{8}$
  
### 12: Applications of trigonometry

![[triangle.png|center|400]]
- 

| Law of Sines                                                          | Law of Cosines                         | Law of tangents                                                                         |
| --------------------------------------------------------------------- | -------------------------------------- | --------------------------------------------------------------------------------------- |
| $\dfrac{a}{\sin \alpha}=\dfrac{b}{\sin \beta}=\dfrac{c}{\sin \gamma}$ | $\cos \alpha=\dfrac{b^2+c^2-a^2}{2bc}$ | $\dfrac{a-b}{a+b}=\dfrac{\tan(\dfrac{\alpha-\beta}{2})}{\tan(\dfrac{\alpha+\beta}{2})}$ |


| Sine                                                     | Cosine                                               | Tangent                                                      |
| -------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ |
| $\sin \dfrac{\alpha}{2}=\sqrt{ \dfrac{(s-b)(s-c)}{bc} }$ | $\cos \dfrac{\alpha}{2}=\sqrt{ \dfrac{s(s-a)}{bc} }$ | $\tan \dfrac{\alpha}{2}=\sqrt{ \dfrac{(s-b)(s-c)}{s(s-a)} }$ |
where
$s = \dfrac{a+b+c}{2}= \dfrac{\text{perimeter}}{2}$

| Two sides and included angle         | one side and two angles                                     | three sides are given             |
| ------------------------------------ | ----------------------------------------------------------- | --------------------------------- |
| $\Delta = \dfrac{1}{2}bc\sin \alpha$ | $\Delta = \dfrac{a^2 \sin \beta \sin \gamma}{2\sin \alpha}$ | $\Delta= \sqrt{s(s-a)(s-b)(s-c)}$ |


|          | Circum Cricle                                                   | In Circle                       | Ex Circle |
| -------- | --------------------------------------------------------------- | ------------------------------- | --------- |
| relation | $R = \dfrac{abc}{4\Delta}$<br><br>$R = \dfrac{a}{2\sin \alpha}$ | $r=\dfrac{\Delta}{s}$           |           |
|          | ![[circum circle.png\|center\|200]]                             | ![[in-circle.png\|center\|300]] |           |
>[!question]- In $\Delta ABC$ if $b =2$, $\beta$=30° then area of circum-circle is: 
>a)$\pi$$\qquad$b)$2\pi$$\qquad$**c)$4\pi$**$\qquad$d)$8\pi$

>[!question]- The area of $\Delta ABC$ is $72cm$ and its perimeter is $36cm$, the radius of its in-circle is: 
>a)1cm$\qquad$b)2cm$\qquad$c)$\dfrac{1}{2}cm$$\qquad$**d)4cm**

>[!question]- Which of the triangle is oblique with sides:

>a)3, 4, 5$\qquad$b)5, 12, 13$\qquad$**c)6, 7 ,16**$\qquad$d)none

| Type        | Angle Condition                       | Description                                | Side Relation                     |
| ----------- | ------------------------------------- | ------------------------------------------ | --------------------------------- |
| **Acute**   | All angles < 90°                      | Every angle is sharp or narrow             | All sides follow **a² + b²> c²** |
| **Obtuse**  | One angle> 90°                       | Contains one wide angle                    | **a² + b² < c²**                  |
| **Right**   | One angle = 90°                       | Contains one perfect right angle           | **a² + b² = c²** (Pythagorean)    |
| **Oblique** | No 90° angle (either acute or obtuse) | A general term for **non-right** triangles | Covers **acute** and **obtuse**   |
where $c$ is the greatest side
### 13: Inverse Trigonometric Functions
$$\begin{align}

\sin^{-1}x+ \cos^{-1}x= &  \dfrac{\pi}{2};\qquad-1 \le x \le 1 \\
 \\
\cos ec^{-1}x\ + \sec^{-1}x =  & \dfrac{\pi}{2};\qquad x \le -1 \text{ or }   x \ge 1 \\
 \\
\tan^{-1}x + \cot^{-1}x =  & \dfrac{\pi}{2};\qquad x \in R
\end{align}
$$
- $\arcsin = \sin^{-1};\qquad \arccos = \cos^{-1}$


>[!question]- $\cos ec^{-1}(\dfrac{1}{2})$ 
>a)$\dfrac{\pi}{2}$$\qquad$b)$\dfrac{\pi}{3}$$\qquad$c)$\dfrac{\pi}{6}$$\qquad$**d)doesn't exist**

since $\cos ec^{-1}(\dfrac{1}{2})=\sin^{-1}(2)$ and $\sin$ never gives 2, and range of $\cos ec$ is  $x \le -1$  or $x \ge 1$
>[!question]- $\tan^{-1}(\dfrac{1}{6}) + \cot^{-1}(\dfrac{1}{6}) =?$ 
>a)cannot be calculated$\qquad$**b)$\dfrac{\pi}{2}$**$\qquad$c)$\dfrac{\pi}{6}$$\qquad$d)$\dfrac{\pi}{4}$
 
>[!question]- $\cos ec^{-1}(2x) + \sec^{-1}(5) =\dfrac{\pi}{2}$, then $x$ is:  
>a)5$\qquad$b)$\dfrac{2}{5}$$\qquad$**c)$\dfrac{5}{2}$**$\qquad$d)none
  
>[!question]- $\arcsin(\dfrac{3}{2})+\arccos(\dfrac{3}{2})=?$  
>a)$\dfrac{\pi}{2}$$\qquad$b)$\dfrac{\pi}{3}$$\qquad$c)$\dfrac{\pi}{4}$$\qquad$**d) Does not exist**
 
 since $\dfrac{3}{2}=1.5$ and that is out of the rage of $\cos$ and $\sin$

- if asked to express one trigonometric function in terms of other, draw a triangle use that,

| sin                                 | cos                                       | tan                                       |
| ----------------------------------- | ----------------------------------------- | ----------------------------------------- |
| $\sin= \dfrac{\text{perp.}}{hypo.}$ | $\cos= \dfrac{\text{base}}{\text{hypo.}}$ | $\tan= \dfrac{\text{base}}{\text{perp.}}$ |
| ![[CNX_Calc_Figure_07_03_001.jpg]]  | ![[Pasted image 20250605212455.png]]      | ![[CNX_Calc_Figure_07_03_004.jpg]]        |
| base= $\sqrt{ a-x^{2} }$            | perp. = $\sqrt{ a+x^{2} }$                | hypo. = $\sqrt{ 1+x^{2} }$                |
>[!question]- $\tan^{-1}x$ in terms of $\arccos:$ 
>a)$\cos^{-1}\sqrt{ 1+x^{2} }$$\qquad$**b)$\cos^{-1} \dfrac{1}{\sqrt{ 1+x^{2} }}$**$\qquad$c)$\cos^{-1} \dfrac{1}{\sqrt{ 1-x^{2} }}$$\qquad$d)$\cos^{-1}\sqrt{ 1-x^{2} }$

>[!question]-  $\cos^{-1}(\sin^{-1}x)=?$
>a)$\dfrac{1}{x}$$\qquad$b)$1-x$$\qquad$**c)**$\sqrt{ 1-x^{2} }$$\qquad$d)$\sqrt{ 1+x^{2} }$
  
# Part 2

## 1: Function & Limits +
- if $f(x) =f'(x)$ its called involution and give same results for same value of all values of x
- simplify a fractional limit by taking the derivative of numerator and denominator separately, called rule of De l$'$ Hospital  $$\begin{align*}&\text{if f(a) and g(a) are equal to zero \quad } \\ & \lim_{x \to a} \dfrac{f(x)}{g(x)} =\lim_{x \to a} \dfrac{f'(x)}{g'(x)}\end{align*}$$
- $\lim_{n \to \infty} \left(1 + \dfrac{1}{n}\right)^n = e =\lim_{x \to 0} \left(1 + x\right)^{\dfrac{1}{x}}$   

- $\lim_{x \to 0} \dfrac{\sin x}{x} = 1$

- $\lim_{x \to a} \dfrac{x^n-a^n}{n-a} = na^{n-1}$
- **Vertical asymptotes**: in a rational functions $\dfrac{P(x)}{Q(x)}$when the $Q(x)$ equals zero while the $P(x)$does not, if both are zero its a **hole**
- Domain and Range of $f(x)$ are Range And Domain of its inverse $f'(x)$ respectively
- Parametric Equation of a Circle: $$ x= a\cos \theta \\  y= a\sin \theta$$

- TODO: definitions on page 5-8
- Hyperboloc and Inverse hyperbolic on page 7
### domain and range
- linear functions: ax+b = 0 have domain and range of R
	- functions with $\sqrt{ x },|x|,(x)^{2}$  here x can never be negative so, range is $[0,+\infty]$ and domain (except $\sqrt{ x }$ ) is all real numbers R
- in linear and rational functions $\dfrac{1}{x}$, domain is excluding number that makes the function irrational
  and range has a shortcut if numerator and denominator have linear polynomial functions $\dfrac{P(x)}{Q(x)}$ then exclude ratio of coefficients of x from rangee.g.  $\dfrac{ax+b}{cx+d}$ or $\dfrac{x+1}{x-5}$then Range = $R - \dfrac{a}{c}$ or $R - \{1\}$ or $(-\infty,1)U(1,\infty)$
##  2: Differentiation and Derivatives
- if a third variable is installed, don't use chain rule, simply do $\dfrac{dy}{dx}= \dfrac{\text{y equation}}{\text{x equation}}$, now differentiate separately the numerator and denominator with respect to the third variable and divide 
>[!question]-  if $y=2at$ and $x=at^{2}$then $\dfrac{dy}{dx}=?$
>a)$\dfrac{1}{t}$$\qquad$b)$\dfrac{2a}{y}$$\qquad$c)$t$$\qquad$**d)**Both a) and b)
  
>[!question]- derivative of $\cos ^{4}x$ with respect to $\sin^{2}x$ is:

  
- For implicit function: $\dfrac{dy}{dx}=-(\dfrac{ \text{Derivative w.r.t x, treating y as constant}}{ \text{Derivative w.r.t y, treating x as constant}})$

- ==important== $\begin{array}{|c|c|} \hline\textbf{Mathematician} & \textbf{Notation} \\  \hline \text{Cauchy} & Df(x) \\  \hline \text{Newton} & \dot{f(x)} \\ \hline \text{Leibniz} & \dfrac{dy}{dx} or \dfrac{df}{dx} \\ \hline \text{Lagrange} & f'(x) \\ \hline \end{array}$
- $f(x) = aSin(x) + bCos(x)$ ==has==
	- max. value = $\sqrt{a^2+b^2}$
	- min. value = $-\sqrt{a^2+b^2}$ 
- **order of derivative** is highest derivative in the equation
  $$\dfrac{d^3y}{dx^3} + \left( \dfrac{xd^2y}{dx^2} \right)^2 + \dfrac{dy}{dx }$$
  has highest order of 3,
  **degree** is the highest power of x, which in this case is 2
- a function is:
	- increasing if $f'(x) > 0$
	- decreasing if $f'(x) < 0$
>[!question]- For which of the following intervals is the function $y=x^{2}-6x+5$ Increasing? 
>a)$1<x<5$$\qquad$b)$x>5$$\qquad$**c)**$x>3$$\qquad$d)$x<1$
  

| name            |                                                                                           |     |
| --------------- | ----------------------------------------------------------------------------------------- | --- |
| product rule    | $\dfrac{d}{dx}(f(x).g(x)) = f'(x).g(x) + f(x).g'(x)$                                       |     |
| quotience rule  | $\dfrac{d}{dx}\left[ \dfrac{f(x)}{g(x)} \right] = \dfrac{g(x)f'(x). - f(x).g'(x)}{(g(x))^2}$ |     |
| reciprocal rule | $\dfrac{d}{dx}\left( \dfrac{1}{f(x)} \right) = - \dfrac{f'(x)}{[f(x)]^2}$                    |     |
| power rule      | $\dfrac{d}{dx}(x^n) = nx^{n-1}$                                                            |     |
|                 |                                                                                           |     |

|       | simple                                          | inverse                                                  | hyperbolic                                         |
| ----- | ----------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------- |
| Sin   | $\dfrac{d}{dx}\sin x = \cos x$                  | $\dfrac{d}{dx}\sin^{-1} = \dfrac{1}{\sqrt{1-x^2 }}$      | $\dfrac{d}{dx}\sinh x = \cosh x$                   |
| Cos   | $\dfrac{d}{dx}\cos x = -\sin x$                 | $\dfrac{d}{dx}\cos^{-1} = \dfrac{-1}{\sqrt{1-x^2 }}$     | $\dfrac{d}{dx}\cosh x =\sinh x$                    |
| Tan   | $\dfrac{d}{dx}\tan x = \sec^2 x$                | $\dfrac{d}{dx}\tan^{1} = \dfrac{1}{1+x^2 }$              | $\dfrac{d}{dx}\tanh x = \sec h^2 x$                |
| Cot   | $\dfrac{d}{dx}\cot x = -\cos ec^2 x$            | $\dfrac{d}{dx}\cot^{-1} = \dfrac{1}{1+x^2 }$             | $\dfrac{d}{dx}\coth x = -cos ech^2 x$              |
| Cosec | $\dfrac{d}{dx}\cos ec x = -\cos ec\ (x).\cot x$ | $\dfrac{d}{dx}\cos ec^{-1} = \dfrac{-1}{x\sqrt{1-x^2 }}$ | $\dfrac{d}{dx}\cosh ec x = -\cosh ec\ (x).\coth x$ |
| Sec   | $\dfrac{d}{dx}\sec x = \sec x\tan x$            | $\dfrac{d}{dx}\sec^{-1} = \dfrac{1}{x\sqrt{1-x^2 }}$     | $\dfrac{d}{dx}\sec h x = -\sec  h x\tan h x$       |

- $\log_{a}a=1;\qquad \log_{a}1=0$
>[!question]-  $\log_{7}^{1}=?$
  
  ANS = 0

|                                                                |                                                           |
| -------------------------------------------------------------- | --------------------------------------------------------- |
| $\dfrac{d}{dx}e^x=e^x$                                         |                                                           |
| $\dfrac{d}{dx}e^{f(x)}=e^{f(x)} \times f'(x)$                  | $\dfrac{d}{dx}a^{f(x)}=a^{f(x)} \times \ln a\times f'(x)$ |
| $\dfrac{d}{dx}(\log_{a}x)=\dfrac{1}{x}\times \dfrac{1}{\ln a}$ |                                                           |
|                                                                |                                                           |
|                                                                |                                                           |
|                                                                |                                                           |
>[!question]- derivative of $e^{x^{-2}}:$ 
>a)$-2e^{x^{-2}}$$\qquad$b)$-\dfrac{1}{x^{2}}e^{x^{-1}}$$\qquad$**c)**$-\dfrac{2}{x^{3}}e^{x^{-2}}$$\qquad$d)$e^{x^{-2}}$
  
  

>[!question]- Ripples in shape of circles are produced when a stone is thrown in water. If the rate of change of circumference of these circles is $12\pi$, what is the rate of change of Area of the circle when theradius is 3cm?
>a)$28\pi$$\qquad$b)$36\pi$$\qquad$c)$54\pi$$\qquad$d)$60\pi$

Rate of change of circumference of circle = $\dfrac{dc}{dt}=12\pi$
Circumference = $C = 2\pi r$
$\dfrac{dC}{dt}=2\pi \dfrac{dr}{dt};\qquad \dfrac{dr}{dt}=\dfrac{1}{2\pi}(\dfrac{dC}{dt})=\dfrac{1}{2\pi}\times_{1}2\pi=6=$ rate of change of radius
Area of circle = $A=\pi r^{2};\qquad \dfrac{dA}{dt}=2\pi \dfrac{dr}{dt}=2\pi(3)(6)=36\pi$ 

- LOOK FOR RELATOON BETWEEN MACLAURAN AND GEOMETRIC SERIES AAAAAAAAAAAAAAAAAAH
## 3: Integration
- for any integral limit of form $\int^{a}_{-a}f'(x) \ dx$
$$
\begin{align}
 \text{if } f'(x)  \text{ is odd: }& \qquad = 0 \\
  \\
\text{if } f'(x)  \text{ is even: }& \qquad = \int^{a}_{0}f'(x) \ dx
\end{align}
$$
- in $\int^{b}_{a}f'(x) \ dx$  a and b are range of $f(x)$
- Integration cancels out derivative: $\int \dfrac{d[f(x)]}{dx}dx=f(x)$
>[!question]- $\int^{1}_{0}\dfrac{d}{dx}(\sin ^{-1}(\dfrac{x^{2}}{1+2x}))dx$ 

simply put upper and lower limit: $\sin ^{-1}(\dfrac{(1)^{2}}{1+2(1)})-\sin ^{-1}(\dfrac{(0)^{2}}{1+2(0)})=\sin ^{-1}(\dfrac{1}{3})$ 
  
- if we have 
$$\int \ln[f(x)] f'(x) \ dx \qquad=\qquad f(x)\times[\ln(f(x))-1] + c $$
- if upper limit is a variable $t$ and lower limit is a constant $a$
$$\begin{align}
 \text{if:} \quad \int^{t}_{a}f'(x) \ dx = f(t) \quad \text{then} \\   
\\
 \int^{t}_{0}x \ dx = \left[\dfrac{x^{2}}{2} \right]^{t}_{0} = \dfrac{t^{2}}{2}
\end{align}$$
- order: highest derivative in an equation
- degree: power of the term with the highest **order**
- $\int e^{a\times g(x)}(a\times f(x)\ +\ f'(x)) = e^{a\times g(x)}f(x) + c$
>[!question]- $\int 0 \ dx=$ 
>a)$x+C$$\qquad$**b)**$C$$\qquad$c)$1+C$$\qquad$d)none
  
   $(x \times 0) +C=C$

- $e^{x}$ has same derivative and integral
 - $\int \dfrac{f'(x)}{f(x)}=\ln(f(x))+C$
>[!question]- integral of $\dfrac{e^{x}}{e^{x}+1}$ 
>**a)**$\ln|e^{x}+1|+C$$\qquad$b)$\ln|e^{x}|+C$$\qquad$c)$e^{x}+C$$\qquad$d)none

>[!question]- $\dfrac{6x^{2}+8x+16}{2x^{3}+4x^{2}+16x}$ 

$\ln(2x^{3}+4x^{2}+16x)$

## 4: Analytical Geometry

- To determine the unknown point in a parallelogram ABCD, D is equal to sum of its adjacent sides A and C, subtracted by B: 
  $$D=A+C-B$$
 
  
- a linear equation of two variables represents a line i.e.
$$\begin{align}  \text{general form of eq. of a line:} \quad &
  ax + by + c =0 \\
  \text{slope}=m=-\dfrac{a}{b} \\
 \\
 \text{x-intercept}= -\dfrac{c}{a} \\
 \\
 \text{y-intercept} = -\dfrac{c}{b}
\end{align}
$$
- two lines are coinciding if their slopes and x or y intercept are equal
$$\begin{aligned}

  m_1 = m_2 ; & \quad \text{only parallel} \\
   \text{x or y intercepts are equal}; & \quad  \text{also coinciding}
\end{aligned}$$

| thing                           | formula                                                                                                         | explainations                                                    |                                   |     |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------------- | --- |
| distance                        | $d = \|AB\| = \sqrt{(x_{2}-x_{1})^{2}+ (y_{2}-y_{1})^{2}}$                                                      | distance between two points                                      |                                   |     |
| midpoint                        | $\left( \dfrac{x_{2}+x_{1}}{2},\dfrac{y_{2}+y_{1}}{2} \right)$                                                  | the point in the middle of 2 points                              |                                   |     |
| division of line internally     | $P = \left( \dfrac{k_{2} x_1 + k_{1} x_2}{k_{1} + k_{2}}, \dfrac{k_{2} y_1 + k_{1} y_2}{k_{1} + k_{2}} \right)$ | P is the position vector where of the point                      | ![[dividing line internally.png]] |     |
| division of line externally     | $P = \left( \dfrac{k_{2} x_1 - k_{1} x_2}{k_{1} - k_{2}}, \dfrac{k_{2} y_1 - k_{1} y_2}{k_{1} - k_{2}} \right)$ | P is the position vector where of the point                      |                                   |     |
| distance between point and line | $d = \dfrac{\|ax_{1}+by_{1}+c\|}{\sqrt{a^{2} +b^{2}}}$                                                          | where $ax + by + c$ is the line<br>$P(x_{1},y_{1})$ is the point |                                   |     |
| slope                           | $\tan \theta=m=(\dfrac{y_{2}-y_{1}}{x_{2}-x_{1}})$                                                              | the tangent of inclination(θ)                                    |                                   |     |
| ==Centroid of triangle==        | ==$( \dfrac{x_{1}+x_{2}+x_{3}}{3}, \dfrac{y_{1}+y_{2}+y_{3}}{3})$==                                             |                                                                  | ![[centroid.png]]                 |     |
| in-center of a triangle         | $(\dfrac{a x_1 + b x_2 + c x_3}{a + b + c},\dfrac{a y_1 + b y_2 + c y_3}{a + b + c})$                           | from bisector of the angles                                      | ![[in-circle.png]]                |     |
|                                 |                                                                                                                 |                                                                  |                                   |     |

$$\begin{align}
  \text{Standard: }& \quad Ax + By = C \\
\\
  \text{General: }& \quad Ax + By + C = 0 \\
\\
  \text{Slope-Intercept: }& \quad y = mx + c \\
\\
  \text{Point-Slope: }& \quad y - y_1 = m(x - x_1) \\
\\
  \text{Two-Slope: }& \quad y - y_1 = \dfrac{y_2 - y_1}{x_2 - x_1} (x - x_1) \\
\\
\text{Two-Intercept: }& \quad \dfrac{x}{a} + \dfrac{y}{b} = 1 \\
\\
\end{align}
$$
- slope of horizontal line is $0$ or $tan(0  \text{ or } 180)$ and of vertical line $\infty$ or undefined 
- prependicul
- if two lines are prependicular then $m_{1}\times m_{2} = -1$
  if two lines are parallel then $m_{1}=m_{2}$
- for three collinear points
  $$
\left| \begin{matrix} 
x_1 & y_1 & 1 \\
x_2 & y_2 & 1 \\
x_3 & y_3 & 1
\end{matrix} \right| = 0
$$

- if slope of two lines AB and BC are equal, then A, B and C are co-linear
- in $(x,y)$, x is the distance from y-axis and vice versa
- 
$$
 \text{Area of triangle    }= \Delta = \dfrac{1}{2}\begin{vmatrix}x_{1} & y_{1} & 1 \\ x_{2} & y_{2} & 1 \\ x_{3} & y_{3} & 1 \\ \end{vmatrix}
$$

- if in the equation of two lines co-efficients of $x$, and co-efficients of y are equal then they are parallel  a₁=a₂ and b₁=b₂
- Position of a point $P(x_{1},y_{1})$ relative to a line $ax + by + c = 0$
$$
  \begin{align}
  ax_{1} + by_{1} + c> 0;& \quad \text{lies above line}\\
  ax_{1} + by_{1} + c < 0;& \quad \text{lies below line}\\
  ax_{1} + by_{1} + c = 0;& \quad \text{lies on the line}\\
\end{align}
$$
- similarly position of a line $ax + by + c = 0$ relative to $x \text{ and } y$ axes

$$
\begin{align}
a> 0 ; &   \quad  \text{ above x-axis } \quad | &  \quad b> 0 ;    \quad  \text{ right y-axis } \\ 
a < 0 ; &   \quad  \text{ below x-axis }\quad  |  & \quad b < 0 ;    \quad  \text{ left y-axis }\\
a = 0 ; &   \quad  \text{ on x-axis } \quad \quad   |&  \quad b = 0 ;    \quad  \text{ on y-axis }\\
\end{align}$$
- if axis $(x,y)$ is shifted through $(h,k)$ then new axis   $$\begin{align}
(X,Y) = (x-h,y-k) \\
\\
\text{or} \quad (x,y) = (X+h,y+k)
\end{align}$$
in other words, a point $(x,y)$ shifted through point $(h,k)$, becomes $(X,Y)$
- three lines $ax_{n} + by_{n} + c_{n} =0$ are concurrent if
$$
  \begin{vmatrix} a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\ 
a_3 & b_3 & c_3 \end{vmatrix} = 0
$$
- angle betwezen two lines having slopes $m_{1} \text{ and }m_{2}$, from $l_{1}$ to $l_{2}$ going counter clockwise(arrow strikes $l_{2}$)
$$
\tan \theta =  \dfrac{m_{2} -m_{1}}{1
+m_{1}m_{2}}
$$
- $ax^{2} + 2hxy +by^{2} =0$ represents two lines through origin, they are
$$\begin{align}
 \text{ real and distinct: } & h^{2}> ab \\
 \text{ real and coincident: } & h^{2} = ab \\
 \text{ imaginary: } &  h^{2} < ab\\ \\
\end{align}
$$
- the angle between them is:
$$
  \tan \theta = \dfrac{2\sqrt{ h^{2} -ab}}{a+b}
$$
- pair of lines perpendicular to $ax^2 + 2hxy +by^2 =0$ are given by $bx^2 - 2hxy +ay^2 =0$ 

## 5: Linear Inequalities and Programming
- if an equality  $ax+by>$ or $<  0$ its associated equation ax + bx = 0 which represents the line, if the equations includes $\leq \text{or} \geq$ then this line is included otherwise its shown as dotted
- a function being maximized or minimized is an objective function
- the solution which maximizes or minimizes a function is called an optimal solution
- feasible regions, region restricted to first quadrant
- optimal solution only exists in feasible region
- intersection of two boundary lines is a corner point if its is in feasible region
- four symbols of inequality $<,\>, \ \geq, \ \leq$
- the corner point satisfies both inequalities, and can be obtained by solving the associated equation of both lines
- 
- 
## 6: Conic Section

![[conic section gif.gif|center|400]]
$$
  \text{ Circle: }x^{2}+y^{2}=1 \qquad \text{ Ellipse: }\dfrac{x^{2}}{a^{2}}+\dfrac{y^{2}}{b^{2}}=1 \qquad \text{ Hyperbola: } \dfrac{x^{2}}{a^{2}}-\dfrac{y^{2}}{b^{2}}=1 \qquad  \text{ Parabola: }y^{2}=4ax
$$
$$
 \text{Most General Equation: }Ax^2 + By^2 + 2hxy + 2gx + 2fy + c = 0
$$
- Degenerated conic:
	- a **point** is a degenerated **circle** or **ellipse** (plane parallel or at angle to an angle not equal to angle of cone)
	- a **straight line** is a degenerated **parabola** (plane at angle equal to cone)
	- **two intersecting lines** are a degenerated **hyperbola** (plane is perpendicular to the cone)
- eccentricity; $e=\dfrac{|PF|}{|PL|}$ is a positive constant, ==and if==
$$
\begin{align}
e=1 \qquad \to & \text{ parabola } \\
e=0 \qquad  \to & \text{ circle }\\
e>1 \qquad   \to& \text{ hyperbola }\\
0<e<1 \qquad  \to & \text{ ellipse }
\end{align}
$$
- at maximum, two conic can intersect each other at **4 points**, min at 0 points
- ==determine the conic==
$$\begin{align}
A=B  ;&  \quad \text{ same sign} & \rightarrow \quad &\text{circle} \\
A \neq B ;& \quad \text{ same sign} & \rightarrow \quad &\text{ellipse} \\
A \neq B ;& \quad \text{ opposite sign} & \rightarrow \quad &\text{hyperbola} \\
A = 0  &\text{ or } B = 0  \quad  &\rightarrow  \quad &\text{parabola}\\
\end{align}
$$
if $xy$ term is present ==use the following method:==
$$\begin{align}

h^2 = AB: &  \qquad \to \text{ Parabola } \\
h^2> AB: &  \qquad \to \text{ Hyperbola} \\
h^2 < AB: &  \qquad \to \text{ Circle or Ellipse } \\
h=0; \ \ A=B: & \qquad \to \text{ Circle }
\end{align}
$$

- any point that lies on a line or conic, satisfies its equation, this core concept is used to solve many mcqs by back solving
### circle:
- $$\begin{align}
 &\text{General Equation: \quad }Ax^2 + By^2+ 2gx + 2fy + c = 0
\\
 &\text{Standard Equation: \quad}r^2=(x-h)^2 + (y-k)^2
\end{align}$$
if in general equation $A \text{ and } B$ are equal to 1 then 
$$\begin{align}
 \text{center = } & (-g,-f) \text{ or }(h,k)\\
 \\
 \text{radius = } r=&  \sqrt{g^2+f^2-c}
\end{align}
$$
	if values $c(h,k)$ and $r$ are given, use standard equation to form equation  of circle.

- while solving any MCQ, make sure $A \text{ and }B$ are equal to $1$
- if radius = 0 then its a point circle
- no $xy$ term (product of x an y) is present in equation of circle

- if radius = 0 then its a point circle
- if $g^{2} = c$ then circle touches x-axis
  if $f^{2} = c$ then circle touches y-axis
  if $f^{2}=g^{2} = c$ then circle touches both axes
>[!question]- The circle $x^{2}+y^{2}+4x-2y+4=0$ touches___ 
>a)X-axis$\qquad$b)y-axis$\qquad$c)Both X and Y Axis$\qquad$d)None of the Axis
  
- no $xy$ term (product of x and y) is present in equation of circle
- length of a chord $=2\sqrt{r^2-d^2}$, where d is distance of midpoint of chord from center
- circle is a special form of ellipse when minor and major axes are equal
- Position of a point $P(x_{1},y_{1})$ relative to a circle is done by putting point in equation of circle(standard or general)
$$
  \begin{align}
  r^2=(x_{1}-h)^2 + (y_{1}-k)^2> 0;& \quad \text{lies outside circle}\\
   \\
r^2=(x_{1}-h)^2 + (y_{1}-k)^2 < 0;& \quad \text{lies inside circle}\\
   \\
r^2=(x_{1}-h)^2 + (y_{1}-k)^2= 0;& \quad \text{lies on circle}\\
\end{align}
$$
- to find the quadrants the circle passes though
	  1.) find center, this will give one quadrant
	  2.) find radius, second quadrant will be the one, which is less than radius
	  ![[mcq circle quadrant.png]]
- Circle passes through:
	  all 4 quadrants if $c$ is negative
	  3 quadrants and origin if $c$ is zero
	  

### tangents
- to find tangent to a curve at any point $(x_{1},y_{1})$, replace
$$
\begin{align}
  x^{2} \to x.x_{1} \\
   \\
2x \to x+x_{1}\\
 \\
  y^{2} \to y.y1 \\
 \\
2y \to y+y1
\end{align}
$$
- length of tangent of circle from $(x_{1},y_{1})$ is done by putting $x=x_{1} \text{ and }y=y_{1}$ in equation of circle and taking square root
  **CO-EFFICIENT OF $X^{2}$ AND $Y^{2}$ MUST BE ONE**
$$
 \text{ Length of tangent }=\sqrt{(x_{1}-h)^{2}+(y_{1}-k)^{2}-r^{2} } = \sqrt{ x_{1}^{2}+y_{1}^{2}+2gx_{1}+2fy_{1}+c }
$$
- $x^{2}+y^{2}+4x+2y=0$ from the point P(-1,2)
### Parabola:
$$
\begin{align}

y^{2} =4ax \qquad y^{2} = -4ax \qquad  \text{ are symmetric about x-axis } \\
 \\
x^{2} =4ay \qquad x^{2} = -4ay \qquad  \text{ are symmetric about y-axis }
\end{align}
$$
![[table of parabola.jpg|center|800]]
- the parabola opens where the term with degree 1 points; x-right, -x-left, y-up, -y-down

-   $a$ is called the focal length
- for form  
- line $y=mx +c$ is tangent on parabola if: $c = \dfrac{a}{m}$
-  in any equation: $(y-k)^{2}=4a(x-h)$, the term $(y-k)$ is the axis
- for any equation of form $Ax + By^2 + hxy + 2gx + 2fy + c = 0$ solve it by completing square
- 


### Ellipse:
$$
 \dfrac{x^{2}}{a^{2}}+\dfrac{y^{2}}{b^{2}}=1 \qquad 
$$
- ![[Table of Ellipse.jpg|center|700]]
- $2a$ : length of major axis
- $2b$: length of minor axis
- $c = \sqrt{ a^2-b^2};\qquad$ distance between center and foci:
- $2c$ distance between foci  
	- $c^{2}=a^{2}-b^{2}$
- semi major axis means only $a$, as in half of major axis
	- eq. directrix: x or y = ± a²/c
- distance b/w directrices: d= 2a²/c
- Area: $\pi ab$
 - Perimeter≈ $\pi(a+b)$
- **focal parameter**: distance between focus and directrix: $\dfrac{b^{2}}{c}$
- in standard form of ellipse $Ax + By^2 + hxy + 2gx + 2fy + c = 0$ if certain conditions are met, of A and B, the bigger can be a² and smaller can be b²
  
>[!question]- largest circle inscribed in ellipse $16x^{2}+4y^{2}=64$ 
>

$=\dfrac{x^{2}}{4}+\dfrac{y^{2}}{16}=1;\qquad a=4,b=2$
the largest circle **inside** will have radius equal to semi minor axis = b, $\pi r^{2}=\pi(b)^{2}=\pi 2^{2}$
  

### Hyperbola: 
$$
 \dfrac{(x-h)^{2}}{a^{2}}-\dfrac{(y-k)^{2}}{b^{2}}=1 \qquad 
$$
- product of distances of foci to any perpendicular is $b^{2}$
- hyperbola is along the axis which is positive in the equation
- symmetric on both axes
- if $a=b$ then its a rectangular hyperbola
- Foci: $c^{2}=a^{2}+b^{2}$
- distance between foci: 2c

- $e = \dfrac{c}{a}$
- $c^²=a(1-e)=a-ae$
- Directrices = $x=y=\pm \dfrac{c}{e^{2}}$
- Length of latus-rectum: = $\dfrac{2b^{2}}{a}$
- Length of traverse axis(where vertices lie): 2a
- Length of conjugate axis(where CoVertices lie): 2b
- ![[table of hyoerbola.jpg|center|600]]
>[!question]- $\dfrac{(x-2)^{2}}{9}-\dfrac{(y+1)^{2}}{16}=1$ 
 
 Center = (2,-1)
 Vertices(∓(a+h), k) = (∓(3+2),-1)
Co Vertices(∓(b+h), k) = (∓(4+2),-1)
 Foci (∓(c+h),k) = (∓(5+2),-1)    ; $c=\sqrt{ a^{2}+b^{2} }$

- for asymptotes simply replace the 1 with 0 and solve for y
>[!question]- asymptote of $4x^{2}-y^{2}=1$ 
>a)$y=\pm x$$\qquad$**b)$y=\pm 2x$**$\qquad$c)$y=1$$\qquad$d)none

$4x^{2}-y^{2}=0$
$4x^{2}=y^{2};\qquad y=\pm2x$

- In rectangular hyperbola
	-  $a^{2}=b^{2}$  
	- $xy=c;\qquad c \neq 0;$ where c is a constant
	- its eccentricity is always $\sqrt{ 2 }$
	- their asymptotes are perpendicular
## 7: Vectors
- $PQ = OQ - OP$
- $PQ = -QP$
- sum of vectors forming a closed loop is zero
>[!question]- A(1,1,2), B(2,2,3), C(3,3,4) and D(4,4,5) then $AB+BC+CD+DA=?$
>a)(10,10,10)$\qquad$**b)0**$\qquad$c)(1,1,1)$\qquad$d)none
  
- for a triangle sum of its sides as vectors is zero $$\underline{u} + \underline{v} + \underline{w} = 0$$
  or sum of its any two sides, is equal to the third$$\underline{u} + \underline{v} =  \underline{w} $$
>[!question]- $i+j+k, \ 2i+3j+4k,  \text{ and } 3i+\lambda j+5k$  is a triangle, value of $\lambda$ is:
>**a)4**$\qquad$b)-4$\qquad$c)2$\qquad$d)-2
  
- line segment from origin to point is a position vector
- from point to point is a vector
$$\begin{array}{|c|c|c|c|c|c|}
\hline
\textbf{Operation} & \textbf{Trigonometric Formula} & \textbf{Component Formula} & \textbf{Perpendicular} & \textbf{Parallel}  &  \textbf{Angle}\\
\hline
\text{Dot Product} & \mathbf{A} \cdot \mathbf{B} = |\mathbf{A}| |\mathbf{B}| \cos \theta & \mathbf{A} \cdot \mathbf{B} = A_x B_x + A_y B_y + A_z B_z & 0 \text{ if } \theta = 90^\circ & \text{Max. if } \theta = 0^\circ  & \cos\theta =\dfrac{\vec{A}\vec{B}}{|A||B|}\\
\hline
\text{Cross Product} & \mathbf{A} \times \mathbf{B} = |\mathbf{A}| |\mathbf{B}| \sin \theta \, \hat{n} & \mathbf{A} \times \mathbf{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ A_x & A_y & A_z \\ B_x & B_y & B_z \end{vmatrix} & \text{Max. if } \theta = 0^\circ & 0 \text{ if } \theta = 180^\circ  & \sin\theta =\dfrac{\vec{A}\vec{B}}{|A||B|}\\
\hline
\end{array}
$$

- if two vectors are perpendicular and you need to find one of their coordinates, set their dot product equal to zero and solve
>[!question]- $a=2\alpha i+j-k$ and $b=i+\alpha j+4k$ , are perpendicular then $\alpha=?$
>**a)$\dfrac{4}{3}$**$\qquad$b)4$\qquad$c)3$\qquad$d)$\dfrac{5}{3+}$
  
- 
- projection **of B** *on* **A** where $\theta$ is the angle b/w them is: = component of B along A = $B\cos\theta =\dfrac{\vec{A}\vec{B}}{A} = \vec{B}\hat{A}$
>[!question]- if the projection of $a=3i+j-k$ along $b=\lambda i-j+k$ is $-\dfrac{8}{\sqrt{ 6 }}$ then $\lambda$ is?
>a)-1$\qquad$**b)-2**$\qquad$c)0$\qquad$d)1
 
 

$\dfrac{3\lambda -2}{\sqrt{ \lambda^{2} }+2}=-\dfrac{8}{\sqrt{ 6 }}$; now back solve and chose the one that satisfies the equation

- orthogonal: if two curves are perpendicular
- for any vector, where $\alpha,\beta \text{ and }\gamma$ are its angles with corresponding axes
	- $\cos^{2} \alpha + \cos^{2} \beta + \cos^{2}\gamma =1$
	- $\sin^{2} \alpha + \sin^{2} \beta + \sin^{2}\gamma =2$
- For any two parallel vectors $u=ai+bj$ and $v=ci+dj$, the ratios of coefficient of corresponding components are equal
	i.e. $\dfrac{a}{c}=\dfrac{b}{d}$
>[!question]-  if $u=4i-6j$ and $v=\alpha i-18j$, are parallel then $\alpha$ is:
>a)4$\qquad$b)6$\qquad$c)8$\qquad$**d)12**
 
 - a vector $u=ai+bj+ck$ is
	 - is $\sqrt{ a^{2}+b^{2} }$ units away from z-axis
	 - is $\sqrt{ c^{2}+a^{2} }$ units away from y-axis
	 - is $\sqrt{ c^{2}+b^{2} }$ units away from x-axis

>[!question]- A(3, 4, 9) then distance of A from z-axis is: 
>**a)5**$\qquad$b)6$\qquad$c)3$\qquad$d)8

- Direction cosines of a vector are the components of its unit vector
	- e.g. $u=4i-6j$ has direction cosines of $\cos \alpha=\dfrac{4}{\sqrt{ 52 }}$ and $\cos \dfrac{6}{\sqrt{ 52 }}$

- Scalar Triple Product:
	- its **zero** if the vectors are co planar
	- it gives the **volume of the parallelepiped** formed by the three vectors.
$$\vec{a} \cdot (\vec{b} \times \vec{c}) = 
\begin{vmatrix}
a_x & a_y & a_z \\
b_x & b_y & b_z \\
c_x & c_y & c_z \\
\end{vmatrix}$$
>[!question]- $4i.(2j\times 5k)$ 
>a)30$\qquad$b)20$\qquad$c)11$\qquad$**d)40**
  
	

| Volume of      | formula                        | diagram                                           |     |
| -------------- | ------------------------------ | ------------------------------------------------- | --- |
| Parallelogram  | $A\times B$                    | ![[Cross_product_parallelogram.svg\|center\|200]] |     |
| Tetrahedron    | $\dfrac{1}{6}[A .(B\times C)]$ | ![[Tetrahedron.png\|center\|250]]                 |     |
| Parallelepiped | $A .(B\times C)$               | ![[parallelpiped.png\|center\|500]]               |     |
>[!question]- » Volume of tetrahedron whose vertices are A(0, 0, 0), B(1,1, 0), C(O, 1, 1) and D(1, 0, 1) 
>**a)**$\dfrac{1}{3}$$\qquad$b)$\dfrac{1}{2}$$\qquad$c)$\dfrac{1}{8}$$\qquad$d)$\dfrac{1}{6}$
  
  $AB = i+j;\qquad AC=j+k;\qquad AD=i+k\qquad$ 
$$\dfrac{1}{6}AB.(AC\times AD)= \dfrac{1}{6}
 \begin{vmatrix} 
 {{1}} & {{1}} & {{0}} \\ 
 {{0}} & {{1}} & {{1}} \\ 
 {{1}} & {{0}} & {{1}} 
 \end{vmatrix} = \dfrac{1}{6}\times 2 =\dfrac{1}{3}
 $$
