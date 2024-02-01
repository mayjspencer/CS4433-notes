# Optimization Notes - Lecture 5 - Chapter 1
# 02/01/24

## Review of Vector Spaces

Vector Space: 
- A set V is called a vector space over a field F (usually the real numbers R or complex numbers C) if it satisfies the following properties:

Addition Operation: 
- There exists an operation called vector addition, denoted by u+v, for every pair of vectors u and v in V, such that the result is also in V.

Scalar Multiplication: 
- There exists an operation called scalar multiplication, denoted by c * v for every scalar c in F and every vector v in V, such that the result is also in V.

Additive Identity: 
- There exists a vector 0 (called the additive identity or zero vector) such that v+0=v for every v in V.

Additive Inverses: 
- For every vector v in V, there exists a vector −v such that v+(−v)=0.

Associativity: 
- Vector addition and scalar multiplication must satisfy the associative property.

Distributivity: 
- Scalar multiplication must distribute over vector addition, both on the left and on the right.


## Subspaces and Bases

Non empty subset of Real numbers is called subspace of Rn if ax + by ∈ S for every x, y ∈ S and every a, b ∈ R

S is a subspace of Rn if it is a subset of Rn and it itself is a vector space

If in addition S != Rn, S is proper subspace

Every subspace must contain the zero vecotr

To test a nonempty set of vectors V is a subspace - only need these tests:

Zero Property: there exists an element 0 ∈ V such that v ∈ V and v + 0 = v

Closure for Addition: For any u,v ∈ V , u + v ∈ V

Closure for Scalar Multiplication: For any v ∈ V and any scaler k, kv ∈ V

## Continue on Subspace and Bases

The span of a finite numbers of vectors x1 , . . . , x^k in Rn is the subspace of Rn defined as the set of all vectors y of the form y = summation from 1 to k of ak * x^k

Any such vector y is a linear combination of x1 , . . . , x^k

A basis of S is a collection of vectors that are linearly independent and whose span is equal to S - there linea combination gives you S

The amount of vectors in a basis (all the same number) is the dimension of the subspace

In particular, the dimension of R is n and a very proper subspace of R has dimension smaller than n

1 dimensional subspaces are lines, 2 dimensional subspaces are planes - both going through the origin

Set{0} is a subspace and its dimension is defined to be zero


## Column and Row Spaces

The column space of A is subspace of R spanned by columns of A - linear combinations of columns

The row space of A is subspace of R spanned by rows of A - linear combinations of rows

Dimension of Column Space always equals the dimension of the Row Space and its number is called the rank of A
 - the rank of a matrix can be thought of as the maximum number of linearly independent row vectors

The rank of m x n matrix can't be higher than m or n
 - max number of L.I. planes you can have in 3d space is 3

The matrix A is said to have full rank if rank A = the smaller of m and n

The set {x ∈ ℜn | Ax = 0} is called the null space, subspace of Rn where dimension = n - rank(A)


## Algorithms










