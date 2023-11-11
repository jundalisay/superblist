---
title: "How to Fix Math"
subtitle: "Decon Notation to Make Math Fun Again"
date: 2020-09-21
image: /photos/psych/bore.jpg
description : "We propose Decon Notation to make math easier to understand"
contributors: ['Juan']
icon: /icons/sp.png
draft: true
---


A major turn-off in math is the use of arbitrary variables in equations, usually written in Greek characters. This burdens the mind which has to know what those variables mean just to make sense of of the whole equation. An error in one character will nullify the understanding of the whole equation and makes its output wrong.

To make math fun again, we can create a method called decon notation, which deconstructs those arbitrary Greek variables back into plain English. For example, John Maynard Keynes’ uses `ΣQrdr` to define the “marginal efficiency of capital”:


{{< q a="John-Maynard-Keynes" c="General Theory of of Employment, Interest and Money" >}}
If `Qr` is the prospective yield from an asset at time `r`, and `dr` is the present value of £1 deferred `r` years at the current rate of interest, `ΣQrdr`, is the demand price of the investment.
{{< /q >}}


Instead of `ΣQrdr``, we can use its decon version:

`Demand price of investment = Σ [ the Prospective yield from an asset at given timespan * the Present value of £1 deferred at that timespan at the current rate of interest ]`

Which is itself a shortening of plain English:

> The demand price of investment is the summation of the prospective yield from an asset at given timespan multiplied by the Present value of £1 deferred at that timespan at the current rate of interest

This would then make it easy to trace the logic to be coded:

`investment_demand_price = sum([a*b for a,b in zip(prospective_yield_in_time,interest_rate_in_time)])`

Creating the above code is easier if the basis is in Decon Notation instead of ΣQrdr
