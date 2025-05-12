
| Law                 | Symbolic Representation                              | Definition                                                                                       |
| ------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Commutative Law** | $a \oplus b = b \oplus a$                            | The order of applying the operation does not affect the result.                                  |
| **Associative Law** | $(a \oplus b) \oplus c = a \oplus (b \oplus c)$      | The grouping of operands does not affect the result.                                             |
| **Closure Law**     | $a,b \in S, a \oplus b \in S$ (where $S$ is the set) | The result of applying the operation to two elements from a set is still an element of that set. |

# Part 1
## 1: Number System -+
- $a + bi = (a,b )$
- $i^{2n}= -1$ ; $i^{3n}= -i$ ; $i^{4n}= 1$ 
- Modulus or Absolute value = $r = \sqrt{a^2 + b^2}$
- argument = $\theta = \tan^{-1}\left(\dfrac{b}{a}\right)$
- Euler formula and De-Moivre's theorem for complex numbers also called polar forms are: $a + bi = re^{i\theta} = r(Cos\theta + iSin\theta)$
- $cis\theta = Cos\theta+iSin\theta$
- $\dfrac{cis(x)}{cis(y)} =cis(x-y)$
- $(cis\theta)^x= cis(\theta x)$
- multiplication of complex numbers 
$$(a+b i)(c+d i) = (ac-bd)+ (ad+ bc)i$$
- $C$ is field
- polar co-ordinates of a point $(r,\theta)$
- $\dfrac{1}{i}= -i$

## 2: Sets and Sub-Sets -+
- Power of a Set = No. of subsets = $2^{n}$
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
- if a whole row/column is zero, determinant is zero
  if a two whole rows or columns are equal then determinant is zero
- $A \times B$ if $A_j = B_i$ 
- if A is diagonal matrix,  then its  inverse is reciprocal of its elements i.e 
  $A= \begin{pmatrix} a & 0 & 0 \\ 0 & b & 0 \\ 0 & 0 & c \end{pmatrix}; A^{-1} =\begin{pmatrix} \dfrac{1}{a} & 0 & 0 \\ 0 & \dfrac{1}{b} & 0 \\ 0 & 0 & \dfrac{1}{c} \end{pmatrix}$
- if A is diagonal then its determinant |A| is simple product of diagonal elements.i.e 
$|A|= \begin{vmatrix} a & 0 & 0 \\ 0 & b & 0 \\ 0 & 0 & c \end{vmatrix} = (abc)$
- solve determinant of $4\times4$ or higher using determinant properties


## 4: Quadratic Equations 
- Fourth roots of 16 are: $2i,-2i,2,-2$
- sum of fourth roots is zero
- if $a$ is root of polynomial equation $P(x)$ then $P(a)$ is zero
- $$
\begin{align}
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
- for $ax^2 + bx +c$ whose roots are $\begin{aligned}\alpha \text{ and }  \beta \end{aligned}$ then$$\begin{align*} S = \alpha + \beta &= -\dfrac{b}{a} \\ P = \alpha \times \beta &= \dfrac{c}{a} \\ ax^2 + bx + c &= x^2 - Sx + P \end{align*}$$
  - Quadratic Formula: $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
## 6: Sequences and Series+ 
- $$
\begin{array}{|c|c|c|c|c|}
\hline
\textbf{Type} & \textbf{General Term} & \textbf{Sum} & \textbf{Mean} & \textbf{Example} \\
\hline
\text{A.P.} & a_n = a + (n-1)d & S_n = \dfrac{n}{2}[2a_{1} + (n-1)d] = \dfrac{n}{2}(a_{1} + a_n) & \text{A.M} = \dfrac{a + b}{2} & 2, 5, 8 \\
\hline
\text{G.P.} & a_n = ar^{n-1} & S_n = \dfrac{a_{1}(1 - r^n)}{1 - r} \, \text{for} \, r < 1, \,  \text{or} \, S_n = \dfrac{a_{1}(r^n - 1)}{r - 1} \, \text{for} \, r > 1 & \text{G.M} = \sqrt{ab} & 3, 6, 12 \\
\hline
\text{H.P.} & a_n = \dfrac{1}{a + (n-1)d} & S_n = \dfrac{n}{\dfrac{1}{a_1} + \dfrac{1}{a_2} + \dots + \dfrac{1}{a_n}} & \text{H.M} = \dfrac{2ab}{a+B} & 1, \dfrac{1}{2}, \dfrac{1}{3} \\
\hline
\end{array}
$$
- for an infinite G.P series$$S_{\infty}=\sum_{n=1}^{\infty} a^n = \dfrac{a}{1 - r} , |r| < 1$$
  - x/9 = 0.xxxxx... like if you divide x digit number by 9 with x 9s this repeats that number in decimal .e.g 34/99 = 0.343434... or 234/999= 0.234234....
* $A>G>H$ if a & b are +ve
  $A<G<H$ if a & b are -ve
  $G^2 = A \times H$
- to find d in AP from $a_{x}=m \text{ to } a_{y}=n$
	  $\dfrac{n-m}{y-x} =d$


## 7: Permutation and Combination +
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

- 1/2 Probability of even and odd sum from one or multiple dice rolls
 - $n! = (n) \times (n-1)!$
 - ***permutation***: different arrangements of ***n*** numbers taken ***r*** at a time
   ***Combination***: selection of ***r*** objects from a total of **n** objects, where the order of selection does not matter.
$$\begin{align*}
   \text{Permutation: \quad} & ^{n}P_{r}= \dfrac{n!}{(n-r)!} \\
   \text{Combination: \quad} & ^{n}C_{r} =\quad \binom{n}{r} = \dfrac{n!}{r!(n-r)!}

   \end{align*}$$
 - if in combination **P*** objects are always included: $^{n-p}C_{r-p}$ if never included $^{n-p}C_{r}$ same for permutation
 - 

| $^{n}C_{0} = ^{n}C_{n} = 1$ | $^{n}C_{r} = ^{n}C_{r-1}$ | $^{n}C_{r}.r! = ^{n}P_{r}$ |
| --------------------------- | ------------------------- | -------------------------- |
| $^{n}P_{n}=n!$              |                           |                            |

 - Diagonals of a n sided polygon: $^{n}C_{2} - n$
 - Probability = $\dfrac{\text{no. favourible outcomes}}{\text{total  outcomes}}$
 - circular permutation  = $(n-1)!$
   circular permutation on a flipable ring = $\dfrac{(n-1)!}{2}$
-  probability can never be greater than 1
$P(A \cup B) = P(A) + P(B) - P(A \cap B)$
- $P(A \cap B)$ is the probability of an event whrre both A and B occur, $P(A \cup B)$ is the probability where in a given set either A or B may occur
- possible outcomes of an experiment with x outcomes performed n times: $x^n$, then probability is $\dfrac{\text{favourable outcomes from } x^n}{x^n}$ like probability of no heads(1 favorable from 2 possible) from a coin (x=2) tossed n times
- probability of an 
- common factorials

| 0!  | 1!  | 2!  | 3!  | 4!  | 5!  | 6!  | 7!   |
| --- | --- | --- | --- | --- | --- | --- | ---- |
| 1   | 1   | 2   | 6   | 24  | 120 | 720 | 5040 |

- in permutation ~={blue}**order** =~of elements matters while in combination it only the ~={yellow}present elements=~ matter
- how to determine wether the question requires permutation or combinations

| Permutation                                                                                                                                  | Combinations                                                                                                            |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Arrangements<br>standing or sitting in row or in a circle<br>problem regarding digits<br>letters(A,B,C...)<br>Formation of words, number,etc | Selection, Choice, Draw,etc<br>Distributation, formation of  a group, commitee, team,etc <br>problem regarding geometry |
|                                                                                                                                              |                                                                                                                         |
## 8: Mathematical Induction and Binomial Theorem
$$
(a+b)^{n}
$$
- number of terms is $n+1$
-  Middle term: 
$$\begin{align}

\text{if n is even:} & \qquad(\dfrac{n+2}{2})^{ \text{ th }} \\
 \\
\text{if n is odd:} & \qquad(\dfrac{n+1}{1})^{ \text{th}}  \text{ and } (\dfrac{n+3}{1})^{ \text{th}}
\end{align}
$$
- Sum of co-efficients: $\qquad 2^{n}$  
- $x^{\text{th}}$ term or $r^{ \text{th}}$ power of b:  
  $$T_{r+1}=\binom{n}{r} \times a^{n-r}\times b^{r}$$ where $x=r+1$, like for 4th term we put r=3
- 
## 9: Fundamentals of Trigonometry

| System      | units                                    | conversion                                           | definition                                                               |
| ----------- | ---------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------ |
| sexagesimal | $\theta^{\circ} M_{inute}' S_{econds}''$ | $\dfrac{M'}{60}=\theta^\circ, \dfrac{S''}{60}=M$<br> | 1 degree is the angle, the 360th part of a circle subtends on the centre |
| circular    | rad.                                     | $2\pi \ rad.= 1 \ rev = 360^\circ$                   | the angle subtended by an arc equal in length to radius                  |
- basic unit of angle is second
![[Pasted image 20250329235536.png]]

| Polygon      | Area                                      | Perimeter      | arc            |
| ------------ | ----------------------------------------- | -------------- | -------------- |
| **Circle**   | $A =\pi r^{2}$                            | $L =2 \pi r$   | $l = \theta r$ |
| **Sector**   | $A =\dfrac{1}{2}r^2\theta = \dfrac{1}{2}rl$ | $l = \theta r$ |                |
| **Triangle** | $A = \dfrac{1}{2}ab$                       |                |                |
![[sign of angles.png]]




|     | Identity                             | addition                                                                                                                                                             | half angle                                                                                 | triple angle                                      | Sum/diff to products |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------- | -------------------- |
| Sin | ==$\sin^2\theta +\cos^2\theta=1$==   | ==$\sin(\alpha + \beta) = \sin(\alpha)\cos(\beta) + \cos(\alpha)\sin(\beta)$==<br>==$\sin(\alpha - \beta) = \sin(\alpha)\cos(\beta) - \cos(\alpha)\sin(\beta)$==<br> | $\sin\left(\dfrac{\theta}{2}\right) = \pm \sqrt{\dfrac{1 - \cos(\theta)}{2}}$                | $\sin(3\theta) = 3\sin(\theta) - 4\sin^3(\theta)$ |                      |
| Cos | ==$\sec^2\theta = \tan^2\theta+1$==  | ==$\cos(\alpha + \beta) = \cos(\alpha)\cos(\beta) - \sin(\alpha)\sin(\beta)$==<br>==$\cos(\alpha - \beta) = \cos(\alpha)\cos(\beta) + \sin(\alpha)\sin(\beta)$==     | $\cos\left(\dfrac{\theta}{2}\right) = \pm \sqrt{\dfrac{1 + \cos(\theta)}{2}}$                | $\cos(3\theta) = 4\cos^3(\theta) - 3\cos(\theta)$ |                      |
| Tan | ==$cosec^2\theta = \cot^2\theta+1$== | irrelevant                                                                                                                                                           | $\tan\left(\dfrac{\theta}{2}\right) = \pm \sqrt{\dfrac{1 - \cos(\theta)}{1 + \cos(\theta)}}$ | irrelevant                                        |                      |
|     |                                      |                                                                                                                                                                      |                                                                                            |                                                   |                      |
|     |                                      |                                                                                                                                                                      |                                                                                            |                                                   |                      |

for a right angled triangle 
$Cos\theta = \dfrac{Base}{Hypotenuse}$
$Sin\theta = \dfrac{Prependicular}{Hypotenuse}$
$\tan\theta = \dfrac{\sin \theta}{cos\theta} = \dfrac{Prependicular}{Base}$


|     | Sum/diff to product                                                                                                                                                                     | product to sum/diff                                                                                                                          |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| sin | $\sin(A) + \sin(B) = 2 \sin( \dfrac{A+B}{2}) \cos( \dfrac{A-B}{2})$<br>$\sin(A) - \sin(B) = 2 \cos\left( \dfrac{A+B}{2} \right) \sin\left( \dfrac{A-B}{2} \right)$                          | $\cos(A) \cos(B) = \dfrac{1}{2} \left( \cos(A+B) + \cos(A-B) \right)$<br>$\cos(A) \sin(B) = \dfrac{1}{2} \left( \sin(A+B) - \sin(A-B) \right)$ |
| cos | $\cos(A) + \cos(B) = 2 \cos\left( \dfrac{A+B}{2} \right) \cos\left( \dfrac{A-B}{2} \right)$<br>$\cos(A) - \cos(B) = -2 \sin\left( \dfrac{A+B}{2} \right) \sin\left( \dfrac{A-B}{2} \right)$ | $\sin(A) \sin(B) = \dfrac{1}{2} \left( \cos(A-B) - \cos(A+B) \right)$<br>$\sin(A) \cos(B) = \dfrac{1}{2} \left( \sin(A+B) + \sin(A-B) \right)$ |


|                       |                             |
| --------------------- | --------------------------- |
| $sin(-θ) = -sin(θ)$   | $\cos ec(-θ) = -\cos ec(θ)$ |
| $\cos(-θ) = \cos(θ)$  | $\sec(-θ) = \sec(θ)$        |
| $\tan(-θ) = -\tan(θ)$ | $\cot(-θ) = -\cot(θ)$       |

| function | $\theta =0$ | $\theta = 30$        | $\theta = 45$        | $\theta = 60$        | $\theta = 90$ |
| -------- | ----------- | -------------------- | -------------------- | -------------------- | ------------- |
| sin      | 0           | $\dfrac{1}{2}$        | $\dfrac{1}{\sqrt{2}}$ | $\dfrac{\sqrt{3}}{2}$ | 1             |
| cos      | 1           | $\dfrac{\sqrt{3}}{2}$ | $\dfrac{1}{\sqrt{2}}$ | $\dfrac{1}{2}$        | 0             |
| tan      | 0           | $\dfrac{1}{\sqrt{3}}$ | 1                    | $\sqrt{ 3 }$         | undefined     |
## 10: Trigonometric Identities
![[reference angle.png|center|800]]
- Allied Angles
  if in sin,cos,tan θ is being added to an odd multiple of $\dfrac{\pi}{2}$ then they change to cos,sin,cot, if even remains same, if at $\left( n \times\dfrac{\pi}{2} \right) + \theta$ is in a quadrant in which the value of sin,cos,tan is negative the cos,sin,cot also recieve the negative sign
- 

| func    | period formula            |
| ------- | ------------------------- |
| sin(ax) | period = $\dfrac{2\pi}{a}$ |
| cos(ax) | period = $\dfrac{2\pi}{a}$ |
| tan(ax) | period = $\dfrac{\pi}{a}$  |
| h       |                           |
## 12: Applications of trignometry
- 

| Law of Sines                                                       | Law of Cosines                        | Law of tangents |
| ------------------------------------------------------------------ | ------------------------------------- | --------------- |
| $\dfrac{a}{\sin \alpha}=\dfrac{b}{\sin \beta}=\dfrac{c}{\sin \gamma}$ | $\cos \alpha=\dfrac{b^2+c^2-a^2}{2bc}$ |                 |

area
$s = \dfrac{a+b+c}{2}$

| Two sides and included angle        | one side and two angles                                    | three sides are given             |
| ----------------------------------- | ---------------------------------------------------------- | --------------------------------- |
| $\Delta = \dfrac{1}{2}be\sin \alpha$ | $\Delta = \dfrac{a^2 \sin \beta \sin \gamma}{2\sin \alpha}$ | $\Delta= \sqrt{s(s-a)(s-b)(s-c)}$ |
| $\Delta = \dfrac{1}{2}ac\sin \beta$  | $\Delta = \dfrac{b^2 \sin \alpha \sin \gamma}{2\sin \beta}$ |                                   |
| $\Delta = \dfrac{1}{2}ab\sin \gamma$ | $\Delta = \dfrac{c^2 \sin \alpha \sin \beta}{2\sin \gamma}$ |                                   |


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
  and range has a shortcut if numerator and denominator have linear polynomial functions $\dfrac{P(x)}{Q(x)}$ then exclude ratio of coefficients of x from range.e.g $\dfrac{ax+b}{cx+d}$ or $\dfrac{x+1}{x-5}$then Range = $R - \dfrac{a}{c}$ or $R - \{1\}$ or $(-\infty,1)U(1,\infty)$
##  2: Differentiation

- $\begin{array}{|c|c|} \hline\textbf{Mathematician} & \textbf{Notation} \\ \hline \text{Leibniz} & \dfrac{dy}{dx} or \dfrac{df}{dx} \\ \hline \text{Newton} & \dot{f(x)} \\ \hline \text{Lagrange} & f'(x) \\ \hline \text{Cauchy} & Df(x) \\ \hline \end{array}$
- $f(x) = aSin(x) + bCos(x)$ has
  max. value = $\sqrt{a^2+b^2}$
  min. value = $-\sqrt{a^2+b^2}$ 
- order of derivative is highest derivative in the equation
  $$\dfrac{d^3y}{dx^3} + \left( \dfrac{xd^2y}{dx^2} \right)^2 + \dfrac{dy}{dx }$$
  has highest order of 3,
  degree is the highest power of x, which in this case is 2

| name            |                                                                                           |     |
| --------------- | ----------------------------------------------------------------------------------------- | --- |
| product rule    | $\dfrac{d}{dx}(f(x).g(x)) = f'(x).g(x) + f(x).g'(x)$                                       |     |
| quotience rule  | $\dfrac{d}{dx}\left[ \dfrac{f(x)}{g(x)} \right] = \dfrac{g(x)f'(x). - f(x).g'(x)}{(g(x))^2}$ |     |
| reciprocal rule | $\dfrac{d}{dx}\left( \dfrac{1}{f(x)} \right) = - \dfrac{f'(x)}{[f(x)]^2}$                    |     |
| power rule      | $\dfrac{d}{dx}(x^n) = nx^{n-1}$                                                            |     |
|                 |                                                                                           |     |

|       | simple                                         | hyperbolic                                        | inverse                                                |
| ----- | ---------------------------------------------- | ------------------------------------------------- | ------------------------------------------------------ |
| Sin   | $\dfrac{d}{dx}\sin x = \cos x$                  | $\dfrac{d}{dx}\sinh x = \cosh x$                   | $\dfrac{d}{dx}\sin^{-1} = \dfrac{1}{\sqrt{1-x^2 }}$      |
| Cos   | $\dfrac{d}{dx}\cos x = -\sin x$                 | $\dfrac{d}{dx}\cosh x =\sinh x$                    | $\dfrac{d}{dx}\cos^{-1} = \dfrac{-1}{\sqrt{1-x^2 }}$     |
| Tan   | $\dfrac{d}{dx}\tan x = \sec^2 x$                | $\dfrac{d}{dx}\tanh x = \sec h^2 x$                | $\dfrac{d}{dx}\tan^{1} = \dfrac{1}{1+x^2 }$              |
| Cot   | $\dfrac{d}{dx}\cot x = -\cos ec^2 x$            | $\dfrac{d}{dx}\coth x = -cos ech^2 x$              | $\dfrac{d}{dx}\cot^{-1} = \dfrac{1}{1+x^2 }$             |
| Cosec | $\dfrac{d}{dx}\cos ec x = -\cos ec\ (x).\cot x$ | $\dfrac{d}{dx}\cosh ec x = -\cosh ec\ (x).\coth x$ | $\dfrac{d}{dx}\cos ec^{-1} = \dfrac{-1}{x\sqrt{1-x^2 }}$ |
| Sec   | $\dfrac{d}{dx}\sec x = \sec x\tan x$            | $\dfrac{d}{dx}\sec h x = -\sec  h x\tan h x$       | $\dfrac{d}{dx}\sec^{-1} = \dfrac{1}{x\sqrt{1-x^2 }}$     |

|                                              |                                                          |
| -------------------------------------------- | -------------------------------------------------------- |
| $\dfrac{d}{dx}e^x=e^x$                        |                                                          |
| $\dfrac{d}{dx}e^{f(x)}=e^{f(x)} \times f'(x)$ | $\dfrac{d}{dx}a^{f(x)}=a^{f(x)} \times \ln a\times f'(x)$ |
|                                              |                                                          |
|                                              |                                                          |

- LOOK FOR RELATOON BETWEEN MACLAURAN AND GEOMETRIC SERIES AAAAAAAAAAAAAAAAAAH
## 3: Integeration
- for any integeral limit of form $\int^{a}_{-a}f'(x) \ dx$
$$
\begin{align}
 \text{if } f'(x)  \text{ is odd: }& \qquad = 0 \\
  \\
\text{if } f'(x)  \text{ is even: }& \qquad = \int^{a}_{0}f'(x) \ dx
\end{align}
$$
$$
\begin{align}
 \text{If } f'(x) \text{ is odd: } & \quad f'(x) = 0 \\
 \text{If } f'(x) \text{ is even: } & \quad \int_{0}^{a} f'(x) \, dx
\end{align}

$$
- in $\int^{b}_{a}f'(x) \ dx$  a and b are range of f(x)
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
## 4: Analytical Geometry
- a linear equation of two variables represents a line .i.e
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

| thing                           | formula                                                                                                         | explainations                                                    |                                      |     |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------------------------ | --- |
| distance                        | $d = \|AB\| = \sqrt{(x_{2}-x_{1})^{2}+ (y_{2}-y_{1})^{2}}$                                                      | distance between two points                                      |                                      |     |
| midpoint                        | $\left( \dfrac{x_{2}+x_{1}}{2},\dfrac{y_{2}+y_{1}}{2} \right)$                                                  | the point in the middle of 2 points                              |                                      |     |
| division of line internally     | $P = \left( \dfrac{k_{2} x_1 + k_{1} x_2}{k_{1} + k_{2}}, \dfrac{k_{2} y_1 + k_{1} y_2}{k_{1} + k_{2}} \right)$ | P is the position vector where of the point                      | ![[dividing line internally.png]]    |     |
| division of line externally     | $P = \left( \dfrac{k_{2} x_1 - k_{1} x_2}{k_{1} - k_{2}}, \dfrac{k_{2} y_1 - k_{1} y_2}{k_{1} - k_{2}} \right)$ | P is the position vector where of the point                      |                                      |     |
| distance between point and line | $d = \dfrac{\|ax_{1}+by_{1}+c\|}{\sqrt{a^{2} +b^{2}}}$                                                          | where $ax + by + c$ is the line<br>$P(x_{1},y_{1})$ is the point |                                      |     |
| slope                           | $\tan \theta=m=(\dfrac{y_{2}-y_{1}}{x_{2}-x_{1}})$                                                              | the tangent of inclination(θ)                                    |                                      |     |
| ==Centroid of triangle==        | ==$( \dfrac{x_{1}+x_{2}+x_{3}}{3}, \dfrac{y_{1}+y_{2}+y_{3}}{3})$==                                             |                                                                  | ![[centroid.png]]                    |     |
| in-center of a triangle         | $(\dfrac{a x_1 + b x_2 + c x_3}{a + b + c},\dfrac{a y_1 + b y_2 + c y_3}{a + b + c})$                           | from bisector of the angles                                      | ![[Pasted image 20250308144439.png]] |     |
|                                 |                                                                                                                 |                                                                  |                                      |     |

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
- slope of horizontal line is $0$ or $(tan(0  \text{ or } 180))$ and of vertical line $\infty$ or undefined 
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
  ax_{1} + by_{1} + c > 0;& \quad \text{lies above line}\\
  ax_{1} + by_{1} + c < 0;& \quad \text{lies below line}\\
  ax_{1} + by_{1} + c = 0;& \quad \text{lies on the line}\\
\end{align}
$$
- similarly position of a line $ax + by + c = 0$ relative to $x \text{ and } y$ axes

$$
\begin{align}
a > 0 ; &   \quad  \text{ above x-axis } \quad | &  \quad b > 0 ;    \quad  \text{ right y-axis } \\ 
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
 \text{ real and distinct: } & h^{2} > ab \\
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
- if an equality  $ax+by >$ or $<  0$ its associated equation ax + bx = 0 which represents the line, if the equations includes $\leq \text{or} \geq$ then this line is included otherwise its shown as dotted
- a function being maximized or minimized is an objective function
- the solution which maximizes or minimizes a function is called an optimal solution
- feasible regions, region restricted to first quadrant
- optimal solution only exists in feasible region
- intersection of two boundary lines is a corner point if its is in feasible region
- four symbols of inequality $<,\  >, \ \geq, \ \leq$
- the corner point satisfies both inequalities, and can be obtained by solving the associated equation of both lines
- 
- 
## 6: Conic Section
![[conics 1.svg|center|600]]

$$
  \text{ Circle: }x^{2}+y^{2}=1 \qquad \text{ Ellipse: }\dfrac{x^{2}}{a^{2}}+\dfrac{y^{2}}{b^{2}}=1 \qquad \text{ Hyperbola: } \dfrac{x^{2}}{a^{2}}-\dfrac{y^{2}}{b^{2}}=1 \qquad  \text{ Parabola: }y^{2}=4ax
$$
$$
 \text{Most General Equation: }Ax^2 + By^2 + 2hxy + 2gx + 2fy + c = 0
$$
- Degenerated conic:
	- a ~={blue}point=~ is a degenerated ~={yellow}circle=~ or ~={yellow}elipse=~ (plane parallel or at angle to an angle not equal to angle of cone)
	- a ~={blue}straight line=~ is a degenerated ~={yellow}parabola=~ (plane at angle equal to cone)
	- ~={blue}two intersecting lines=~ are a degenerated ~={yellow}hyperbola=~ (plane is prependicular to the cone)
- ecentricity is a positive constant, and if
$$
\begin{align}
e=1 \qquad \to & \text{ parabola } \\
e=0 \qquad  \to & \text{ circle }\\
e>1 \qquad   \to& \text{ hyperbola }\\
0<e<1 \qquad  \to & \text{ ellipse }
\end{align}
$$
- at maximum, two conic can intersect each other at ~={yellow}4 points=~, min at 0 points
- ==determine the conic==
$$\begin{align}
A=B  ;&  \quad \text{ same sign} & \rightarrow \quad &\text{circle} \\
A \neq B ;& \quad \text{ same sign} & \rightarrow \quad &\text{ellipse} \\
A \neq B ;& \quad \text{ opposite sign} & \rightarrow \quad &\text{hyperbola} \\
A = 0  &\text{ or } B = 0  \quad  &\rightarrow  \quad &\text{parabola}\\
\end{align}
$$
if $xy$ term is present use the following method:
$$\begin{align}

h^2 = AB: &  \qquad \text{ Parabola } \\
 \\
h^2 > AB: &  \qquad \text{ Hyperbola} \\
 \\
h^2 < AB: &  \qquad \text{ Circle or Ellipse } \\
h=0; \ \ A=B: & \qquad \text{ Circle }
\end{align}
$$

- any point that lies on a line or conic, satisfies its equation, this core concept is used to solve many mcqs
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
  ![[mcq touches axis.png]]
- no $xy$ term (product of x and y) is present in equation of circle
- length of a chord $=2\sqrt{r^2-d^2}$, where d is distance of midpoint of chord from center
- circle is a special form of ellipse when minor and major axes are equal
- Position of a point $P(x_{1},y_{1})$ relative to a circle is done by putting point in equation of circle(standard or general)
$$
  \begin{align}
  r^2=(x_{1}-h)^2 + (y_{1}-k)^2 > 0;& \quad \text{lies outside circle}\\
   \\
r^2=(x_{1}-h)^2 + (y_{1}-k)^2 < 0;& \quad \text{lies inside circle}\\
   \\
r^2=(x_{1}-h)^2 + (y_{1}-k)^2= 0;& \quad \text{lies on circle}\\
\end{align}
$$
- to find the quadrants the circle passes trhough
	  1.) find centre, this will give one quadrant
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
$$
 \text{ Length of tangent }=\sqrt{(x_{1}-h)^{2}+(y_{1}-k)^{2}-r^{2} } = \sqrt{ x_{1}^{2}+y_{1}^{2}+2gx_{1}+2fy_{1}+c }
$$
- 
### Parabola:
$$
\begin{align}

y^{2} =4ax \qquad y^{2} = -4ax \qquad  \text{ are symmetric about x-axis } \\
 \\
x^{2} =4ay \qquad x^{2} = -4ay \qquad  \text{ are symmetric about y-axis }
\end{align}
$$
![[table of parabola.jpg|center|1000]]

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
- ![[Table of Ellipse.jpg]]
- 2a : length of major axis
- 2b: length of minor axis
- distance brtween centre and foci: $c = \sqrt{ a^2-b^2}$
- 2c distance between foci
- semi major axis means only a, as in half of major axis
- eq. directrix: x or y = ± a²/c
- distance b/w directrixes: d= 2a²/c
- Area: $\pi ab$
- Perimeter≈ $\pi(a+b)$
- focal parameter: distance between focus and directrix: b²/c
- in standard form of ellipse $Ax + By^2 + hxy + 2gx + 2fy + c = 0$ if certain conditions are met, of A and B, the bigger can be a² and smaller can be b²

### Hyperbola: 
$$
 \dfrac{x^{2}}{a^{2}}-\dfrac{y^{2}}{b^{2}}=1 \qquad 
$$
- product of distances of foci to any perpendicular is $b^{2}$
- symmetric on both axes
- if $a=b$ then its a rectangular hyperbola
- $a^{2}+b^{2}=c^{2} \to e = \dfrac{c}{a}$
- $cwjsjcndsyuwiqjnandh^²=a(1-e)$
- ![[table of hyoerbola.jpg]]
## 7: Vectors
- $PQ = OQ - OP$
- $PQ = -QP$
- sum of vectors forming a closed loop is zero
- ^ so for a triangle sum of its sides as vectors is zero
$$
\underline{u} + \underline{v} + \underline{w} = 0
$$
- line segment for  origin to point is a position vector
- from point to point is a vector
$$\begin{array}{|c|c|c|c|c|}
\hline
\textbf{OperationC} & \textbf{Trigonometric Formula} & \textbf{Component Formula} & \textbf{Perpendicular} & \textbf{Parallel} \\
\hline
\text{Dot Product} & \mathbf{A} \cdot \mathbf{B} = |\mathbf{A}| |\mathbf{B}| \cos \theta & \mathbf{A} \cdot \mathbf{B} = A_x B_x + A_y B_y + A_z B_z & 0 \text{ if } \theta = 90^\circ & \text{Max. if } \theta = 0^\circ \\
\hline
\text{Cross Product} & \mathbf{A} \times \mathbf{B} = |\mathbf{A}| |\mathbf{B}| \sin \theta \, \hat{n} & \mathbf{A} \times \mathbf{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ A_x & A_y & A_z \\ B_x & B_y & B_z \end{vmatrix} & \text{Max. if } \theta = 0^\circ & 0 \text{ if } \theta = 180^\circ \\
\hline
\end{array}
$$

- to two vectors are prependicular afnd you need to find one of its coodinates, set their dot product equal to zero and solve
- $\cos \theta = \dfrac{\bar{A.B}}{|\bar{A}||\bar{B}|}$
- projection **of B** *on* **A** where $\theta$ is the angle b/w them is: = component of B along A = $B\cos\theta$ = $\dfrac{\vec{A}\vec{B}}{A} = \vec{B}\hat{A}$
- orthogonal: if two curves are prependicular
- $\cos^{2} \alpha + \cos^{2} \beta + \cos^{2}\gamma =1$
  $\sin^{2} \alpha + \sin^{2} \beta + \sin^{2}\gamma =2$
-  