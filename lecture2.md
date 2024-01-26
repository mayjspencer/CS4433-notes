# Optimization Notes Lecture 2

## Sets + Notations
x ∈ S  ,  x is an element of S

S = {x | x satsifies P} P , set of all elements having property P

| S | 

S ∪ T 

S ∩ T 

S\T , all elements of S not in T

S ⊂ T  , subset

S ≠ T  , proper subset

∅ , empty set

∀ , for all

∃ , there exists

ℜ , all real numbers

[a, b] = {x ∈ ℜ | a ≤ x ≤ b} , closed interval

(a, b) = {x ∈ ℜ | a < x < b} , open interval

## Vectors and Matrices
A is a m × n dimension matrix

ai,j or [A]i,j   , the (i, j)th entry of A

a′ , Row vector  matrix with m = 1 - BOLD FONT

a  ,  Column vector  matrix with n = 1 - BOLD FONT

A m × n j Aj = (a1j , a2j, . . . , amj)

ai i ai = (ai1, . . . , ain)

ℜn , set of all n-dimensional vectors

x1, . . . , xn components of vecotr x

ith unit vector = ei is the vector with all components equal to zero except ith 

## Linear Programming
Choose values of decision variables such that they minimize the linear cost function
subject to a set of linear equality and inequality constraints

![Image 1]([[https://github.com/mayjspencer/CS4433-notes/blob/main/Screen%20Shot%202024-01-26%20at%202.44.41%20PM.png?raw=true]])

2x1 − x2 + 4x3 is the cost function 

can be written as ∑4-i=1 ci xi, where c = (2, − 1,4,0) and x = (x1 , x2 , x3 , x4 )

c = cost vector, x is decision vector

x2 and x4 are free variables cause they don't have sign constraints

## General Form
all linear programming problems are a case of these forms

min c′x

subj a′i x ≥ bi, i ∈ M1

a′i x ≤ bi, i ∈ M2

a′i x = bi, i ∈ M3

xj ≥ 0, j ∈ N1

xj ≤ 0, j ∈ N2

### Optimal Solution
Optimal Solutionis a feasible solution that minimizes the objective function such that
c′x* ≤ c′xfor every feasible x( ∀x ).
#### Possible Cases for Optimal Solution
unique
multiple
none
- infeasible: X = ∅
- unbounded meaning ∀K ∈ ℜ, ∃x feasible with c′x ≤ K, where
the optimal cost is c′x* = − ∞.
    - basically infinite

## Simple Form
Convert any constrain into this form. 
a′i x ≥ bi

## Compact Form
min c′x
subj Ax ≥ b

## Standard Form
min c′x
subj Ax = b
x ≥ 0

## Summary
• General Form: No restrictions on the type of constraints.

• Simple Form: All the constraints are in a′i x ≥ bi format.

• Compact (Matrix) Form: All elements of the objective functions and constraints are
vectors and matrices.

• Standard Form: All the variables are positive and all the constraints are equality
constraints.








