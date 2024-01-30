# Discrete Optimization Notes - Lecture 4 - Chapter 1

## Matrix Operations

### Transposition
A' = transpose of A

(AB)′ = B′A′

### Matrix Vector Multiplication
Ax =
[
a′1x
.
.
.
a′m x
]

### Idenity Matrix
Identity matrix I is a square matrix whose diagonal entries are equal to one and its
off-diagnol entries equal to zero

IA = A and BI = B for any matrix A or B

A>=0 and A>0 means that every component of matrix A is nonnegative or
positive, respectively

### Matrix Inversion
Square matrix A and square matrix B of same dimension

AB = BA = I, then matrix A is invertible or nonsingular - B is called inverse of A with is A^-1

(A′)^−1 = (A^−1)′

If A and B are invertible matrices of the same dimension, then AB is also and given by (AB)^-1 = B^-1 A^-1

### Linear Independence

Given a finite collection of vectors x1 , . . . , xK ∈ ℜ n -

we say that they are linearly dependent if there exist real numbers

a1 , . . . , aK (not all zero) such that ∑Kk=1 ak x^k = 0


In other words, linear independence requires none of the vectors x1 , . . . , xK ∈ ℜ n to be a linear
combination of the remaining vectors.
- Hence, if one of the vectors is a linear combination of the others, then the set of vectors S is linearly
dependent

### Determinant
Notation det(A)) is used to denote the determinant of square matrix A

Example:

![image1](https://github.com/mayjspencer/CS4433-notes/blob/main/Screen%20Shot%202024-01-30%20at%2010.40.45%20AM.png?raw=true)


