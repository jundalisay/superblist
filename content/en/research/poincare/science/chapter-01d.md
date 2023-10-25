---
title: Proof By Recurrence
heading: Chapter 1d
weight: 8
description: Science and Hypothesis
image: "/covers/hyp.jpg"
author: "H. Poincare"
icon: /avatars/poincare.png
---

<!-- VI. -->

<!-- The views upon which reasoning by recurrence is based may be exhibited in other forms; we may say, for instance, that -->

In any finite collection of different integers, one is always smaller. 
- This gives us the illusion of having proved that reasoning by recurrence is legitimate. 

But we shall always be brought to a full stop—we shall always come to an indemonstrable axiom, which will at bottom be but the proposition we had to prove translated into another language. 

We cannot therefore escape the conclusion that the rule of reasoning by recurrence is irreducible to the principle of contradiction. 

Nor can the rule come to us from experiment. 

Experiment may teach us that the rule is true for the first 10 or the first 100 numbers, for instance; it will not bring us to the indefinite series of numbers, but only to a more or less long, but always limited, portion of the series.

If that were all that is in question, the principle of contradiction would be sufficient, it would always enable us to develop as many syllogisms as we wished. It is only when it is a question of a single formula to embrace an infinite number of syllogisms that this principle breaks down, and there, too, experiment is powerless to aid. 

This rule, inaccessible to analytical proof and to experiment, is the exact type of the à priori synthetic intuition. 

On the other hand, we cannot see in it a convention as in the case of the postulates of geometry.

Why then is this view imposed upon us with such an irresistible weight of evidence? 

It is because it is only the affirmation of the power of the mind which knows it can conceive of the indefinite repetition of the same act, when the act is once possible. 

The mind has a direct intuition of this power. Experiment can only be for it an opportunity of using it, and thereby of becoming conscious of it.

But if the legitimacy of reasoning by recurrence cannot be established by experiment alone, is it so with experiment aided by induction? 

We see successively that a theorem is true of the number 1, of the number 2, of the number 3, and so on.

The law is manifest and it is so on the same ground that every physical law is true which is based on a very largenature of mathematical reasoning.

but limited number of observations.

It cannot escape our notice that here is a striking analogy with the usual processes of induction. But an essential difference exists. 

Induction applied to the physical sciences is always uncertain. 
- This is because it is based on the belief in a general order of the universe. 
- This order is external to us. 

Mathematical induction, as proof by recurrence, on the contrary, is necessarily imposed on us. 
- This is because it is only the affirmation of a property of the mind itself.


<!-- VII. -->

Mathematicians always try to generalise the propositions that they have obtained. An example is the equality:

```elixir
a + 1 = 1 + a,
```

We use this to establish the equality which is obviously more general.

```elixir
a + b = b + a,
```

Mathematics may, therefore, like the other sciences, proceed from the specific to the general. 

This is a fact which might otherwise have appeared incomprehensible to us at the beginning of this study, but which has no longer anything mysterious about it, since we have ascertained the analogies between proof by recurrence and ordinary induction.

Mathematical recurrent reasoning and physical inductive reasoning are based on different foundations. 

But they move in parallel lines and in the same direction, from the specific to the general.

To prove the equality

```elixir
(1) a + 2 = 2 + a
```

we need only apply the rule below twice

```elixir
a + 1 = 1 + a
```
We then write

```elixir
(2) a + 2 = a + 1 + 1 = 1 + a + 1 = 1 + 1 + a = 2 + a.
```

The equality thus deduced by purely analytical means is not, however, a simple specific case. It is something quite different. 

We may not therefore even say in the really analytical and deductive part of mathematical reasoning that we proceed from the general to the particularnature of mathematical reasoning.

The two sides of the equality (2) are merely more complicated combinations than the two sides of the equality (1), and analysis only
serves to separate the elements which enter into these combinations and to study their relations.

Mathematicians therefore proceed “by construction,” they “construct” more complicated combinations. 

When they analyse these combinations, these aggregates, so to speak, into their primitive elements, they see the relations of the elements and deduce the relations of the aggregates themselves. 

The process is purely analytical, but it is not a passing from the general to the particular, for the aggregates obviously cannot be regarded as more particular than their elements.

Great importance has been rightly attached to this process of “construction,” and some claim to see in it the necessary and sufficient condition of the progress of the exact sciences. 

Necessary, no doubt, but not sufficient!

For a construction to be useful and not mere waste of mental effort, for it to serve as a stepping-stone to higher things, it must first of all possess a kind of unity enabling us to see something more than the juxtaposition of its elements. 

Or more accurately, there must be some advantage in considering the construction rather than thescience and hypothesis elements themselves. What can this advantage be? 

Why reason on a polygon, for instance, which is always decomposable into triangles, and not on elementary triangles?

It is because there are properties of polygons of any number of sides, and they can be immediately applied to any particular kind of polygon. In most cases it is only after long efforts that those properties can be discovered, by directly studying the relations of elementary triangles. If
the quadrilateral is anything more than the juxtaposition of two triangles, it is because it is of the polygon type.

A construction only becomes interesting when it can be placed side by side with other analogous constructions for forming species of the same genus. 

To do this we must necessarily go back from the particular to the general, ascending one or more steps. 

The analytical process “by construction” does not compel us to descend, but it leaves us at the same level. 

We can only ascend by mathematical induction, for from it alone can we learn something new. Without the aid of this induction, which in certain
respects differs from, but is as fruitful as, physical induction, construction would be powerless to create science.

This induction is only possible if the same operation can be repeated indefinitely. 

That is why the theory of chess can never become a science, for the different moves of the same piece are limited and do not resemble each other.
