34 lectures in TTL
### Lecture 1 <br>

#### REX 2 2022/08/06
#### REX 1

2022/08/06:

3000<->End

- span to the whole 3d space, non singular, invertible
- 3700 mins calculation on row and column way
- Ax is a comb of column of A

2022/08/05:

1500<->3000

- 3 plane intersect at a point, the point is a solution, 3 plane intersect at a point, means 2 plane are parallel, and so on
- row picture is line or plane, column picture is vector

2022/08/04:

0000<->1500

- row picture, column picture, matrix form
- 0430 mins row picture
- 1000 mins column picture
- all the combination fill the whole plane

### Lecture 2 <br>

#### REX 2 2022/08/16
#### REX 1

2022/08/16

3000<->End

- E32, mark it as 32, multiplier is on the 32
- E32E21A=u
- E32E21 is lower triangle matrix
- move the parenthesis, it is called as associated law
- P for permutation, you can't read it in multiplier way
- inverse of E32E21 is L
- A=LU
- use multiplier idea to think about inverse of E32
- E21^-1E32^-1, pay attention to the sign

2022/08/15

1500<->3000

- augmentaed matrix
- elimination, get the final right hand side
- back substitution
- get 3 unknowns
- matrix times a column is a column
- row times a matrix is a row

2022/08/14

0000<->1500

- elimination, software use this method to solve equation
- m n, m>n no solution
- m < n more than one solution
- m=n one solution if independent
- 0430 mins the first pivot
- recursive
- upper triangle, is u
- pivot can't be 0
- if pivot is 0 and no 0 below, then dependent, no solution m > n, not invertible
- augmented column

### Lecture 3 <br>
#### REX 2 2022/08/26
#### REX 1

2022/08/26

3000<->End

- inverse can't exist Ax=0, because x is non 0, Ainverse times A lead to x=0
- invertible, determinant is none 0
- gauss jordan equation, solve 2 equation at once
- a b c d, are 4 unknowns
- augmented matrix
- E times A|I ,  2 ideas thinks of row times a matrix, and times matrix in block way

2022/08/25

1500<->3000

- fourth way of matrix calculation, first column times first row, second column times second row
- matrix block multiplication
- non zero vector x solve Ax=0, means A singular

2022/08/24

0000<->1500
- case study multiplication

### Lecture 4 <br>

#### REX 2 2022/07/28
#### REX 1

2022/07/28:

3000<->End

- multiply, subtract 2 operations counted as one operation
- 100^2
- the count
- 1/3 ncubed
- cost of b, what is b, TBRT
- b, n^2 RHS, elimination and backward substitution
- above are without row exchanges
- then he talks about with row exchanges
- permutation
- how many 3 by 3 row exchange
- inverse is transpose, about permutation matrices
- 4 by 4, how many permutations

2022/07/27:

1500<->3000

- product of inverses is L
- 2000 mins explaination of why reverse order is better
- in the right order, the multiplier just sit on L
- E is product or row elimination
- how many operations, the cost

2022/07/26
0000<->1500

- A first inverse then transpose and reverse order, is this a definition
- A=LU, A=LDU, D stands for diagnol
- general form of A=U

### Lecture 5 <br>
#### REX 2 2022/08/24
#### REX 1

2022/08/24

1500<->End No voice, skip the rest

2022/08/23

0000<->1500

- sometimes it doesn't need to do row exchange
- matlab, solve a system, it would permutation first
- P^-1=P^T
- I lost my mind to the air 0500 mins to 0900 mins

### Lecture 6 <br>
#### REX 2 2022/09/09
#### REX 1

2022/09/09

3000<->End

- solution to Ax=0, in the null space, and think about why null space is a space
- if it is R3 the null space is a line
- match finance and capability
- to [1,2,3,4], right hand side, the solution can't form a subspace, because zero vector is not in the space, it doesn't go through the origin
- sub space have to go through the origin

2022/09/08

1500<->3000

- columns don't fill the whole space
- for equation 3 unknown can't fill the whole space
- b in the column space of A are solutions
- dependent and independent, if it contributes something new or not
- column space is about b, null space is about x

2022/09/07

0000<->1500

- linear combination, in the space
- in the space, or sub space means, their linear computing can't escape from the plane
- comlumn space 1420 mins

2022/03/18:💫 Finished this lecture
### Lecture 7 <br>

#### REX 2 2022/09/28
#### REX 1

2022/09/28

3000<->End

- will show up
- transpose the matrix and think about its pivot
- in 4000 mins example, he choose a free variable, while in previous example he also choosed a free variable, not pivot variable

2022/09/27

1500<->3000

- special solution
- Ax=0, Ux=0
- pivot variable, free variable
- n minus r in m by n matrix of free variables
- echelon form
- reduced row echelon form
- identity matrix sitting in the pivot
- u is echelon, r is reduced row echelon
- pivot part, and free part of the matrix
- null space matrix, N
- RN=0
- N=[], block matrix, one calculation get all solutions in the null space

2022/09/26

0000<->1500

- elimination will not change null space, it will change column space
- 0700 mins, rank of A
- pivot columns and free columns
- free is you can assign anything to the columns
- set pivot column to be 1 0
- x is derived at the end of the section

2022/03/20:💫 Finished this lecture
### Lecture 8 <br>

2023/01/14

1100<->2600

- step 1 x particular
- set all free variables to 0
- solve Ax=b for pivot  variables
- x null space
- complete solution = x particular + x null space
- Axp=b, Axn=0, A(xp+xn)=b
- special solution to null space 2000 mins
- xp is a particular guy, xn is a subspace
- x=xp+xn
- x is not in the x null sub space
- r<=m pivot can't more than number of rows, r<=n a column can't have more than one pivot

2023/01/13

0000<->1100

- connect to lecture 13, the answer might be related with F 0 0 F or something in this lecture, the block matrix
- 0557 mins, condition for solvability
- solvable when b is in CA
- if a combinition of rows of A give zero row, then same comb of entries of b must give 0
- then find the complete solution to Ax=b
- starting from finding one peticular solution

2022/03/21:💫 Finished this lecture, and some take away, in the last few minutes, rank tell you everything about number of solutions, if you forgot, watch it again

### Lecture 9 <br>
2022/03/22: 💫 basis, null space, rank, dimension of column space of A <br>
2022/04/28: finished, 0300 mins, m<n means there are free variables, means it has non-zero solutions;
0900 mins, introduce the concept of dependent;
1500 mins, independent AX=0, rank=0, N(A)=0; dependent N(A) non-zero rank<n;
3000 mins, vectors give basis, the matrix is invertible;
3400 mins, basis is square matrix;
3900 mins, how special solution is produced;
4200 mins, rank A = # of pivot columns = dim of C(A);
4643 mins, dim N(A) = n - r = # of free variables;

### Lecture 10 <br>

#### REX 4 2022/11/20
#### REX 3 2022/07/01
#### REX 2 2022/04/26
#### REX 1 2022/03/22

2022/11/20

3400<->End

- R was I, E was A inverse, in independent matrix case
- if the matrix has more than one row that are 0 vectors
- upper trangular, symmetric matrices
- diagnal matrices

2022/11/19

3000<->4500

- take the transpose of ATy=0 then get the reason of left null space
- gauss jordan
- rref
- rref AI->RE
- EA=R
- to invertible matrix, R is I
- E is A-1
- zero row, and last row in the E

2022/11/18

1500<->3000

- dimension of the column space and the dimension of the row space are the same
- dimension of null space, m by n matrix, n-r
- special solutions, free variables, give one free variable one and the rest zero
- dim NAT = m-r
- CR is not CA, R is after row reduction
- basis for row space is first r rows of R
- row reduction changes column space doesn't change row space
- why NAT is left null space

2022/11/17

0000<->1500

- R3
- rows are dependent
- rank, rows tell you something about columns
- C(A)
- N(A)
- rowspace
- row are basis for the row spaces
- all the combinition of the rows of A
- C(AT)
- nullspace of AT, N(AT)=left null space of A
- dim C(A)=rank r
- TBR the last lecture
- pivot columns
- basis is pivot columns
- dimension is r

2022/03/22: 💫 finished <br>
2022/04/26: finished, 0330 mins, 2 equal row -> singular matrix, means dependent;
0540 mins, rank, double check;
1819 mins, special solutions;
2443 mins, C(R)<>C(A) different column spaces but same row space;
2600 mins, basis for row space, first row of R;
3400 mins, Gauss-Jordan;

2022/06/29:

0000<->1500

- row space
- N(AT) is left null space
- identify the four fundamental spaces
- draw four fundamental space picture
- pivot and basis
- dimension and rank
- dimension of row space and column space are the same

2022/06/30:

1500<->3000 next topic is null space of A transpose

- basis are pivot columns, dimension are rank r, which means the basis is r dimension
- is 2 dimensional
- special solution
- C(R)<>C(A)
- basis for row space is first r rows of R, not A
- but row space of R is the same as row space of A

2022/07/01:

finished,

3000<->End

- why N(AT) is left null space, and its explaination
- combination of columns that gives 0 column, combination fo rows that gives 0 row
- produce dimension, produce basis
- span the space to R n by n

### Lecture 11 <br>

2022/12/08

3000<->End

- if the dimension is 0, the basis is empty
- understand the dimension of the subspace, then understand the basis
- free variable, independent
- all special solutions are basis

2022/12/07

3000<->End

- matrix of all four 1
- dim N A = n-r
- TBRT
- set the free variable as 1 0 0, 0 1 0
- CA is R1
- gives number n and m
- graph = nodes, edges
- graph theory???


2022/12/06

1500<->3000

- find a basis for solution space
- rank 1 matrices is building block for all the matrices, rank 4 can be break down to    4 rank 1 matrices
- subset of rank 4 matrices, form a subspace
- add 2 rank 4 matrices , is the sum rank 4

2022/12/05

1500<->3000

- dim solution space = 2 but cosx and sinx is not the only basis
- you can multiply them by number and you can sum them
- 7 by 17 matrix of rank 4 matrices
- add 2 rank 4 matrices the rank might not be rank 4
- subset of rank 1 matrices is not a subspace
- TBRT

2022/12/04

1500<->3000

- solution to differential equation
- special solution to differential equation
- basis
- dimCA=rank=dimCAT
- pivot column times pivot row gives a matrix
- rank 1 matrix are building block
- subset of rank 1 matrices, not a subspace
- TBRT

2022/12/03

0000<->1500

- matrix space
- sub space of symmetric matrices
- symmetric dimension above then you know 3 below, this is about information
- 6+6=3+9

2022/12/02

0000<->1500

- TBRT
- basis for M = all 3 by 3 s
- dim M is 9, dim S is 6, dim U is 6, dim D is 3
- dim(S intersect U)=3
- sum S+U = all 3 by 3 s

2022/03/23: 💫 finished

### Lecture 12

2022/12/21

3200<->End

- applied math
- ATy=0 Kirchoff's CL
- e=Ax potential differences at nodes
- y=Ce current y1 y2 y3 y4 y5
- ATA ATCA symmetric

2022/12/20

3000<->4500

- when do elimination, the last row become all 0
- satisfies Kirkoff current law
- they are not independent because they come from a loop
- edges
- pivot column doesn't have a loop
- tree: graph with no loop
- number of loops = number of edges minus (number of nodes minus 1)
- Euler's formula
- from dimNAT, derive number of loops equals, derives Euler's formula
- TBRT

2022/12/19

1500<->3000

- basis for the null space
- potential difference can only be determined by constant
- nothing will move if the potential are the same
- potentials
- rank of the matrix is 3
- 5 edges, 4 nodes
- potential differences, c currents y1 to y5 on edges
- x2-x1=y1 ...
- Kirchoff's CL
- ATy=0
- conservation law
- y1 y3 y4
- ATy is about nodes, it has 4 rows, represents 4 nodes

2022/12/18

1500<->3000

- basis of the null space
- from graph theory to linear algebra
- TBRT
- TBR basis
- OHM's LAW
- enable user to use it at its potential strength
- current on node
- current in equal to current out

2022/12/17

0000<->1500

- matrix comes from somewhee
- eletrical network
- incidence matrix
- loop corresponds to dependent row
- real matrix from genuene graph

### Lecture 13

2023/01/13

1000<->1400

- x is complete solution
- special solution + general solution
- x is complete solution
- the clue is within the complete solution
- TBR complete solution

2023/01/12

1000<->1535

- complete solution
- why x = vector + c times vector + d times vector, gives the conclusion that c times vector and d times vector forms the null space, how did he know what are the elements within A1535 mins, TBR null space

2023/01/11

0000<->1500

- 3 vectors in R 7, what the dimension it would be
- you want me to do an instant decision but I am lacking of needed information, can you describe more about this, or what you just said is everything
- echelon form
- reduced echelon form, u 0 0 u
- why dim NA=2
- TBRT from 1000 mins

### Lecture 14 <br>
2022/03/24: 💫 finished why when m>n, which means by which m equations and n unknown there is no solution?

### Lecture 15 <br>

#### REX 2 2022/04/30
#### REX 1 2022/03/25

2022/10/13

3300<->End

- invertible square matrix can span the whole Rn, or column space is the whole Rn
- least square example
- no solution equation, after you muply it by AT, you get a solution

2022/10/12

3000<->4500

- e in NAT, e is perpendicular to CA
- A might not be a square matrix
- when A is square invertible matrix, its columns space is the whole Rn
- the projection matrix is I when A is square invertible matrix
- application of OLS

2022/10/11

1500<->3000

- why projection
- Ax=b may have no solution
- solve the closet solution
- then solve Axhat=P
- plan is column space of a matrix consists of 2 vectors
- think transpose of matrix in vector way
- think in linear system way
- e is in null space of A transpose

2022/10/10
0000<->1500

- double b will double the projection, by looking at the formula
- projection matrix, act on b
- column space of the projection matrix is the line through a
- rank is 1
- TBR rank
- PT=P
- P2=P

2022/03/25:  finished why when m>n, which means by which m equations and n unknown there is no solution? because: it might have a situation like 0=1, or x1=1 in the same time x1=2 <br>
2022/04/30: finished, 0428 mins, projection matrix of OLS;
0830 mins, uppercase of P projection matrix, lowercase p is projected vector, aTa is length square;
1200 mins, C(P) line through A in the example, rank(P) = 1 in the example;
P^2=P, P^T=P symmetric;
1800 mins, m>n, Ax=b no solution, solve Axhat=P;
3742 mins, A is not square matrix;A is square matrix, P = I, which means column space of A is the whole R^n, P is I, notice sigular cases;
4621 mins, m>n case, unknown are paprameters vector

2022/06/17:

REW

0000<->1300

- p is on the same direction as a, so p = xa
- aT(b-xa)=0 is a fundamental formula
- you can derive x and p through above formula
- notice p and P
- consider if b becomes 2b, what happen on projection
- if a becomes 2a it will not affect projection, so there is a projection matrix P and we have Pb
- put parenthesis on different place then you create p and P
- C(P) = line through a, and rank(P)
- P is symm
- 

2529<->3100

- the same formula, [vector](b-Axvector)
- what does sub space that e in
- N(AT) orthorgnal to C(A)
- multi dimension, x and little p
- then P

3400<->3920

- look at the P, if A is invertible square matrix, then the C(A) is the whole Rn, then projection matrix is I


### Lecture 16 <br>

2022/11/02

3000<->End

- error vector is perpendicular to the space
- if A has indep columns, then ATA is invertible
- length of Ax and length of Ax square
- unit vector, perpendicular if dot product is 0
- ortho normal vectors

2022/11/01

1500<->3000

- over compensate for outlier
- given b1, given b2 the same as p1 p2, and e1 e2
- ATA symmetric, invertible
- back substitution, get e1 e2 e3

2022/10/31

0000<->1500

- projection matrix kills perpendicular part, leaves the part that b is in the column space of matrix
- the basic four space
- intepret the above claims based in formula
- columns space means Ax
- p(Pb)+e
- (I-P)b=e
- minimize determinant of Ax-b square
- e1 square + e2 square + e3 square
- fitting a straight line

2022/03/27: finished, it is worth of a review, if A has independent column, ATA must be invertible

2022/06/04:

0000<->2000

0000 mins

- b perpendicular to column space, b is in the null space of A transpose
- Ax column space of A
- p + e = b
- (I-P)b=e
- m time n matrix, m>n no solution
- minimize ||Ax-b||^2 = ||e||^2=e1^2+e2^2+e3^2
- put p1 p2 p3 in the equation, the equation will be solvable
- 

1500 mins

2022/06/05:

1500<->3500

1500 mins

- over compensate
- 2 picture, one is perpendicular 2 space, another is scatter plot
- invertible means have solution
- TBR positive definite
- back substitution
- 

3000 mins

- b = p + e, and p is perpendicuar to e
- 2 pictures, in one picture, C and D didn't show up, in another picture, C and D showed up

4500 mins

2022/06/06:

finished
3500<->End

- if A has indep columns then ATA is invertible
- invertible matrix null space only has 0 vector
- vTv is the length of the vector, if vTv=0 means v is 0
- if columns are perpendicular to each other, columns are independent
- perp unit vector = ortho normal vector
- TBR lecture 17

### Lecture 17 <br>

#### REX 2 2022/06/18
#### REX 1 2022/03/28

2022/03/28: finished, A=QR, a projection R is right upper triangle matrix, R links A and Q, Q is a orthonormal matrix; vector in the column space of A, projection of A is I

2022/06/13

finished,
0000<->1500

- orthognal and orthonormal
- QTQ=I
- qTq
- when it is square matrix, then QT is the inverse of Q
- we call it orthognal
- perm Q
- understand what is orthonormal Q
- Q has triangle vector element
- Q has 1 or minus 1 as its elements
- 4 d Q construction
- practice to construct some Qs
- 3 times 2 form of "Q" TBRT what was the purpose of this

1500<->3400

- previous Q are 2 by 2, 4 by 4
- this Q is 3 by 3
- Gram schmidt TBR
- projection to a Q
- TBRT
- A=a and error vector B construct a orthonormal basis
- TBR check definition of Q in the book, if it can be a 2 by 3 rectangular matrix
- check the result of ATB

2022/06/16:

finished,
3400<->End

- get 3 vector, make them to be orthonormal
- Gram-Schemid formula
- 3857 mins, a example
- 4409 mins, A basis and Q basis
- A=LU elimination
- A=QR an expression of Gram Schemid
- 4817 mins TBRT
- look at the book to see how to complete QR

### Lecture 18 <br>
2022/03/29: finished, property of determinant 9-10, |AB|=|A||B|, |AT|=|A|, they are at the end of the lecture, need to practice

### Lecture 19
2022/03/30: finished, cofactor and determenent

### Lecture 20
2022/03/30: finished, area of triangle, area of parallel 4 sides, cramer rules x=detB/detA, where B = b|Rest of A

### Lecture 21
2022/03/30: finished, shortage of eigen vector; asymatric matrix leads to complex eigen value

2022/05/26:


0000<->1500

0000 mins

- eigen vector with eiven value 0, null space
- A is singular, lambda=0 is evalue
- if A is not singular, only 0 vector can turn Ax=0
- if A is singular, null space vector can turn Ax=0
- n*n matrix will have n eigen values
- sum of the eigen values, equal to sum of traces

1500 mins

2022/05/27:

1500<->3625

1500 mins

- charastistic equation
- how to solve x, elimination, find pivot, give free variable a value, like 1,0 0,1
- symmetric matrix, real eigen value
- eigen vector perpendicular to each other
- trace linear coefficient, constant term is determinant
- set free variable to be 1, so pivot variable is -1

3000 mins

- eigen value will be added by a constant number, eigen vector will be unchanged
- 

4500 mins

2022/05/28:

finished,
3625<->End

3000 mins

- Q rotation matrix
- end up with imagine number
- anti symmetric, -Q=Q
- triangle matrix, diagnal tells you the eigen value
- no second indep x
- 

End mins

### Lecture 22
2022/03/31: finished, the application of eigen value and eigen vector, difference equation, eigen value can describe how fast a series like fabonacci series evolves<br>
2022/04/01: ② reviewed, 0412 minutes, how to derive A=S LAMBDA S^-1

2022/05/13:

0000<->1733, which matrix is not diagnolizable;

0000 mins, A=SLAMBDAS-1, how to get this formula;

0725 mins, S-1AS=LAMBDA; if S is invertible, invertible if all the column are independent, and determinant <>0;

0936 mins, A^2's eigen value and eigen vectors; eigen values turn to be squared, eigen vectors are still the same;

TBR foure series, because it is a method that I am not that familiar with;

1523 mins, if all the |lambda| < 1, wil make A^k as k->infinity;

2022/05/19

finished,
1730<->End

1730 mins:

- set the determinant=0 to get eigen value, A-lambda null space is eigen vector;
- in this case there is no 2 different eigen vector;
- TBR strengthen eiven value and eigen vector;

2800 mins:

- he mentioned difference equation;
- You should build your study system, it is interesting and it will benefit yourself;
- why he can split u0 to the combination of eigen vector, the relation between eigen vector and basis? QSN;
- eigen vector is normalized to unit vector;
- one step equation;
- symetric metric good properties TBR;
- a quick way of getting eigen vector;

End mins:

### Lecture 23
2022/03/31: 1653/5103, why resolve a differential equation has something to do with e^lambda t? <br>
2022/04/01: finished

### Lecture 24
#### REX 1 2022/04/04
2022/04/01: 0454/5111, markov matrix, has lambda= 1, and its steady state: lamnbda = 1, what is steady state? <br>
2022/04/04: finished, 300 mins, steady state;
424 mins, Markov has a lambda eigen value;
525 mins, other lambda < 1;
700 mins, steady state again;
1758 mins, eigen value of A = eigen value of A^T;
2600 mins, steady state;
4800 mins, Forier series;
3655 mins, projection eigen vector matrix;
3900 mins, Q-1=QT

### Lecture 25
2022/04/05: finished, 0126 mins, symetric A=AT, has real lambda; eigenvector can be chosen to be perpendicular, A=QlambdaQ-1 = QlambdaQT;
820 mins, spetrum;
2300 mins, good matrices, independence x's, A=QT, A=A^-T;
2820 mins, every symatric matrices is combination of perpendicular matrices;
3551 mins; postive definite matrix, all lambda are +, all pivots are +, all subset determinants are positive

### Lecture 26
2022/04/07: finished, 150 mins, fast fourier transform;
600 mins, inner product lead to distance square;
720 mins, example make life easier;
1341 mins, perpendicular in complex;
2206 mins, fourier series, euler formula;
3400 mins, why FFT need to review;
4550 mins, example of applying FFT <br>

2022/05/06:
0300 mins, FFT make n^2 mults to nlog2n
0500 mins, good ATA is positive, so ZTZ is no good, Z-TZ is good and the formula is equivalent as ZHZ
0921 mins, inner product of complex is yHX 
1557 mins, unitary = orthognoal but in complex space, hermitian = symmetry in complex space
1727 mins, TBR basis, orthognal;
fourier series, Fnij = w^ij
2102 mins, w is a special number, w^n =  1, euler formula, eix= cos+sin , and by this, w = i 
2735 mins, F4 column are orthognal or ?unitary?, deal with inner product of compex number you have to take hermitation, or conjugate
3133 mins, orthognal and orthonrmal-unit,
3200 mins, cols orthonormal matrix has property, FHF=I, inverse is easy to find
3400 mins, w64^2=w32
3700 mins, permutation matrix is change location of rows
3900 mins, diagnal matrix in this case, how it is looked like
4108 mins, you can keep performing FT, TBR diagnal matrix, TBRT
 

### Lecture 27
#### REX 2 2022/07/14
#### REX 1 2022/04/08
2022/04/08: finished, ellipsoid=football, hyperbloic=double curve line, parabola=x^2;
0356 mins, definition for positive, lambda test, det test, pivot test, XTAX>0 test;
0555 mins, positive semidefinite;
1030 mins, quadratic form;
3348 mins, A=LU;
2638 mins, 2nd derivative positive definite min point; this is a core class bring things together;
3959 mins, special matrix;
4811 mins, radius eigen value = Qlambda QT=A, Q eigen vector matrix is direction of radius of elliposoid, eigen value is the size of the vector;
3612 mins, 2nd derivative matrix, has to be 0, which will determine min point

2022/07/10:

0000<->1500

- positive definite matrix
- elliposoid
- eigen value test, determinant test
- boarder line, positive semi definite
- singular matrix, 2 by 2, so one eigen value has to be 0
- if XTAX is positive, the matrix is positive definite
- TBRT


2022/07/11:

0000<->1500

- 2 tests that can decide if it is a positive definite
- test 3 is derived from test 2
- xTAx is a more important test
- for every x1 and x2, is it always postive
- but x1 x2 equals 0 would make it 0, should we count that
- 2 6 6 18 threshold

2022/07/12:

1500<->3000

- going up in some directions, going down in other directions
- lambda 1 times lambda is the determinant
- sum of diagnal is trace is lambda 1 plus lambda 2
- positive definite and bowl
- 见微知著
- rewrite it to square form, tell you it is positive

2022/07/13:

3000<->4500

- completing the square has something to do with elimination
- A = LU
- number outside of the square are pivots
- second derivative
- 3 by 3 example, pivot, determinant, eigen values
- 2, minus one, 0; minus one 2, minus one; 0, minus one 2
- calculate xTAx
- TBR positive definite in previous lecture, it is not too much but there are some
- cut a 3 by 3 will give you a something like a football
- eigen vector and eigen value, diagnolization, QLAMBDAQT and the eposolloid

2022/07/13:

3500<->End

- diagnal fxx and fyy has to bigger enough to counter fxy and fyx on the off diagnal
- to make the matrix to be postive definite
- ellipse, ellipsoid
- TBRT, why eigen vector tells you the axis and eigen value tells you the length, TBR A=QLAMBDAQT

### Lecture 28
2022/04/09: finished, 240 mins, a symetry has inverse;
XTAX>0 XTBX>0 XT(A+B)X>0;
0859 mins, ATAX=||AX||^2>=0;
1344 mins, similar matrix;B=M-1AM;
2046 mins, similar matrix has same lambda's;
2400 mins, proof of 2046 mins THM;
2711 mins, bad case lambda1=lambda2=4;
3100 mins, non diagnolizble? has something to do with inverse, Jordan form;
4100 mins, Jordan block; number of blocks = number of eigen vectors;

### Lecture 29
2022/04/10: finished,0036 mins SVD is a way of factorization, SLAMBDAS-1 -> QLAMBDAQT if A is symm;
diagnoal matrices sigma, SVD orthognal times diagnal times orthognal;
0400 mins, gran smith; ||ATA|| positive semi definite;
1600 mins, ATA = V SIGMA^2 VT;
3420 mins, a good example;
Think for yourself, it can make you easy to make decision without regret and have your mood better;
I am limiting myself a lot, totally accept failism idea; They will not save you out of charity,;
3048 mins, singular example;

### Lecture 30
2022/04/11: finished, 0700 mins, transformation Ex2;
1700 mins, T(v)=AX;
2600 mins, coordiate and basis;
3730 mins, eigenvector basis, lambda coordiates are the best T;
4300 mins, A and a12 a22, lower case a is the element of A;
4600 mins, take derivative can be expressed as matrix multiplication, as well as linear transformation

### Lecture 31
2022/04/12: finished, 0500 mins, JPEG;
1100 mins, Fourier basis;
2206 mins, wavelets;
2900 mins, good basis & FFT,FWT;
3200 mins, vector orthonormal, AT=A-1;
4900 mins, eigen vector, basis is compressed the most, but slow

### Lecture 33
2022/04/12: finished, 0000 mins, pseudo inverse;
0353 mins, 2 sided inverse full rank, r=m=n;
0421 mins, left inverse, A, r=n full column rank, null space={0}
0 or 1 solution to Ax=b;
ATA invertable;
0930 mins, (ATA)-1AT left inverse;
1349 mins, right inverse, too many solutions;
r=m<n;
n(AT)={0};
AT(AAT)-1;
1730 mins, classical picture;
1900 mins, projection matrix;
3100 mins, stastician;
3429 mins, SVD can be rectangle matrix? psedo inverse
SIGMA SIGMA+ = (1100);
A=uSIGMAVT
A+=VSIGMA+uT, book sec7.4
