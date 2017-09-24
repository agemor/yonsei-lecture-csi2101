# Predicates and Quantified Statements



## Predicate
A predicate is a sentence that contains a finite number of variables and becomes a statement when specific values are substituted for the variables.
```
P: X → {true, false}
```

## Quantifier

### Universal Quantifier: ∀
```
∀x ∈ D, Q(x)
```
Read as, for all x in D, Q(x) is true


### Existential Quantifier: ∃
```
∃x ∈ D, Q(x)
```
Read as, there exists an x for which Q(x) is true

## Predicate Translation
```
A student of mine is wearing a blue shirt.

B(x): "x is wearing a blue shirt"
S(x): "x is my student"
∃x ∈ P such that B(x) ∧ S(x)
```

```
All good students are in class.

C(x): "x is in class"
G(x): “x is a good student"
∀x ∈ P such that G(x) → C(x)
```

## Negation of Quantified Statements
```
~(∃x ∈ D, Q(x)) = ∀x ∈ D, ~Q(x)
~(∀x ∈ D, Q(x)) = ∃x ∈ D, ~Q(x)
```

## Variants of Quantified Statements
Same applies to existential quantifiers.

### Statement
```
(∀x ∈ D) [P(x) → Q(x)]
```
### Converse
```
(∀x ∈ D) [Q(x) → P(x)]
```
### Contrapositive
```
(∀x ∈ D) [~Q(x) → ~P(x)]
```
### Inverse
```
(∀x ∈ D) [~P(x) → ~Q(x)]
```

## Multiple Quantification
```
Let C = {all chairs} and P = {all people}, and S(c,p) represent “person p is sitting in
chair c"

(∀p ∈ P) (∀c ∈ C) [S(c,p)]
(∀c ∈ C) (∀p ∈ P) [S(c,p)]
(∃p ∈ P) (∃c ∈ C) [S(c,p)]
(∃c ∈ C) (∃p ∈ P) [S(c,p)]
```

### Quantification Order
```
The below two are diffrent.

(∀x) (∃y) [y > x]
(∃x) (∀y) [y > x]
```

### Negation of Multiply Quantified Statements
```
~((∃p ∈ P) (∀c ∈ C) [L(c,p)]) = ~((∀p ∈ P) (∃c ∈ C) [~L(c,p)])
```