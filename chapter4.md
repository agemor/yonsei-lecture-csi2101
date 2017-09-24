# Methods of Proof and Prime Numbers

## 1. Methods of Proof



### 1. 1. Direct Proofs
> Show that the square of an even number is an even number.

Prove
```
p → q
```

### 1. 2. Indirect Proofs
> If n^2 is an odd integer then n is an odd integer

Given
```
p → q 
```
Using contrapositives, prove
```
~q → ~p
```

### 1. 3. Proof by Contradiction
> There are infinitely many prime numbers.

> Prove that if n is an integer and n^3+5 is odd, then n is even

Given
```
p → q 
```
Prove
```
~q = f (when p)
```
### 1. 4. Vacuous Proofs
Given
```
p → q 
```
Prove
```
p = f
```
### 1. 5. Proof by Cases
Given
```
(p1 ∨ p2 ∨ p3) → q
```
Prove
```
(p1 → q) ∧ (p2 → q) ∧ (p2 → q)
```
### 1. 6. Proofs of Equivalences
> Show that m^2=n^2 if and only if m=n or m=-n

Given
```
p if and only if q
```
Prove
```
(p → q) ∧ (q → p)
```

### 1. 7. Existence Proofs
Given
```
∃x P(x)
```
#### 1. 7. 1. Constructive
Find a specific value of c for
which P(c) exists.

#### 1. 7. 2. Non-constructive
Show that such a c exists, but don’t actually find it. (Or assume it does not exist, and show a contradiction)


## 2. Prime Numbers

### Divides Operator
```
(3 | 12) equals (12 mod 3 is 0)
```

### Prime Number
A positive integer p is prime if the only positive factors of p are 1 and p.

### Composite Number
An integer n is composite if and only if there exists an integer a such that a | n and 1 < a < n.

### Greatest Common Divisor
```
GCD(A, B) = GCD(B, A mod B) = ... = GCD(G, 0) = G
```