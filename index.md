# FEEC

We collect a range of applications of FEEC, highlighting the importance of structure-preserving discretizations.



## Contents

- [Whitney Form](#Whitney Form)

- [Maxwell Eigenvalues](#Maxwell Eigenvalues)
- 



## Whitney Form

**Reference**: D.N. Arnold. [Fifty years of Whitney elements](https://www-users.cse.umn.edu/~arnold//talks/whitney-print.pdf), Colloquium on the 50*th* anniversary of the journal Numerische Mathematik, Munich, June 16, 2009.

<img src="/Users/longchen1/Library/CloudStorage/Dropbox/Math/Research/feec/figures/whitney.png" alt="whitney" style="zoom:120%;" />

### The Ray–Singer conjecture

Hoping to prove it, in 1976 Dodziuk and Patodi proved the convergence of the approximation of the eigenvalues of the Hodge Laplacian obtained using Whitney forms.

In 1978 Muller completed the program using Dodziuk and Patodi’s convergence results to prove the Ray–Singer conjecture.

<img src="/Users/longchen1/Library/CloudStorage/Dropbox/Math/Research/feec/figures/RaySingerconjecture.png" alt="RaySingerconjecture" style="zoom:120%;" />



## Maxwell Eigenvalues

**Reference**: D.N. Arnold. [Ten Lectures on Finite Element Exterior Calculus](https://www-users.cse.umn.edu/~arnold//feec-cbms/index.html), NSF/CBMS course, ICERM, June 11-15, 2012.

When Lagrange elements are used, the Maxwell operator exhibits spurious eigenvalues and an incorrect spectrum due to the lack of $H(\mathrm{curl})$-conformity. Using Nédélec edge elements, which are $H(\mathrm{curl})$-conforming, yields the correct spectrum.

<img src="/Users/longchen1/Library/CloudStorage/Dropbox/Math/Research/feec/figures/Maxwelleig.png" alt="Maxwelleig" style="zoom:60%;" />