---
title: The Nature Of Mathematical Reasoning
heading: Chapter 1b
weight: 4
description: Science and Hypothesis
image: "/covers/hyp.jpg"
author: "H. Poincare"
icon: /avatars/poincare.png
---


## 3. Geometry

<!-- Let us now see the geometer at work, and try to surprise some of his methods. The task is not without difficulty; it is not enough to open a book at random and to anal-science and hypothesis

yse any proof we may come across.  -->

Geometry must be excluded, or the question becomes complicated by difficult problems relating to:
- the rôle of the postulates
- the nature and origin of the idea of space. 

For analogous reasons, we cannot avail ourselves of the infinitesimal calculus. 

We must seek mathematical thought where it has remained pure—i.e., in Arithmetic. 

But we still have to choose; in the higher parts of the theory of numbers the primitive mathematical ideas have already undergone
so profound an elaboration that it becomes difficult to analyse them.

Therefore, it is at the beginning of Arithmetic where we can find the answers. 
- It is precisely in the proofs of the most elementary theorems that the authors of classic treatises have shown the least precision and rigour.

Beginners are not prepared for real mathematical rigour. They would see in it nothing but empty,
<!-- tedious subtleties.  -->

It would be waste of time to try to make them more exacting. They have to pass rapidly and without stopping over the road which was trodden slowly
by the founders of the science.

Why is so long a preparation necessary to habituate <!-- nature of mathematical reasoning. --> oneself to this perfect rigour, which it would seem should naturally be imposed on all minds?

This is a logical and psychological problem which is well worthy of study. 
- But we shall not dwell on it as it is foreign to our subject. 

We shall fail in our purpose unless we reconstruct the proofs of the elementary theorems, and give them, not the rough form in which they are left
so as not to weary the beginner, but the form which will satisfy the skilled geometer.


## Definition of Addition

I define<!--  assume that --> the operation `x + 1` as <!--  has been defined. --> adding the number `1` to a given number `x`. 

<!-- Whatever may be said of this definition, it does not enter 
into the subsequent reasoning. -->

I define the operation `x + a` as adding the number `a` to any given number `x`.

Suppose that we have defined the operation: `x + (a − 1)`

the operation x + a will be defined by the equality

```
(1) x + a = x + (a − 1) + 1
```

We shall know what `x+a` is when we know what `x+(a−1)` is. 

We know what x + 1 is, and so we can define successively and “by recurrence” the operations x + 2, x + 3, etc. 

This definition deserves a moment’s attention as its nature distinguishes it even at this stage from the purely logical definition. 

The equality (1), in fact, contains an infinite number of distinct definitions, each having only one meaning when we know the meaning of its predecessor.


Associative

I say that

```bash
a + (b + c) = (a + b) + c
```

In fact, the theorem is true for `c = 1`. It may then be written:

```bash
a + (b + 1) = (a + b) + 1
```

<!-- which, remembering the difference of notation, is nothing but the equality (1) by which I have just defined addition. -->

Assume the theorem true for `c = γ`. It will be true for `c = γ + 1`. Let `(a + b) + γ = a + (b + γ)`

It follows that:

```bash
(a + b) + γ + 1 = a + (b + γ) + 1;
```

or by def. (1),

```bash
(a + b) + (γ + 1) = a + (b + γ + 1) = a + b + (γ + 1)
```

This shows by a series of purely analytical deductions that the theorem is true for `γ + 1`. 

Being true for `c = 1`, we see that it is successively true for c = 2, c = 3, etc.


### Commutative

```bash
a + 1 = 1 + a.
```

The theorem is evidently true for `a = 1`. 

We can verify by purely analytical reasoning that if it is true for `a = γ`.

It will be true for a = γ + 1. 1 Now, it is true for a = 1, and therefore is true for a = 2, a = 3, and so on. This is
what is meant by saying that the proof is demonstrated “by recurrence.”


```bash
a + b = b + a.
```

For (γ + 1) + 1 = (1 + γ) + 1 = 1 + (γ + 1).—[Tr.]

The theorem has just been shown to hold good for b = 1, and it may be verified analytically that if it is true for b = β, it will be true for b = β + 1. 

The proposition is thus established by recurrence.


## Definition of Multiplication

We shall define multiplication by the equalities

(1) a × 1 = a;
(2) a × b = a × (b − 1) + a.

Both of these include an infinite number of definitions;

having defined a × 1, it enables us to define in succession

a × 2, a × 3, and so on.



### Distributive


```bash
(a + b) × c = (a × c) + (b × c).
```

We can verify analytically that the theorem is true for c = 1; then if it is true for c = γ, it will be true for

c = γ + 1. 

The proposition is then proved by recurrence.

### Commutative

```bash
a × 1 = 1 × a.
```

The theorem is obvious for a = 1. We can verify analytically that if it is true for a = α, it will be true for
a = α + 1.


```bash
a × b = b × a
```

The theorem has just been proved for `b = 1`. We can verify analytically that if it be true for b = β it will be true for `b = β + 1`.
