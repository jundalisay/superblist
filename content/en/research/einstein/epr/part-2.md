---
title: "Two Systems"
heading: "Part 2"
weight: 6
# date: 2022-04-10
# linkTitle: "EPR Paradox"
# date: 2022-08-08
description: "Einstein Ether is a impotent something"
icon: "/icons/einbla.png"
image: "/covers/epr.png"
---


Two systems, `I` and `II` interact from the time `t=0` to `t=T`. Afterwards, they stop interacting. Their states before `t=0` were known.

<!-- We can then calculate with the help of  -->

Schrodinger's equation gets the state of the combined system `I+II` at any subsequent time. <!-- ; in particular, for any t>T.  -->

Let us designate the corresponding wave function by .. 

But we cannot calculate the state in which either one of the two systems is left after the interaction.       

This, according to quantum mechanics, can be done only through further measurements, by a process known as "the reduction of the wave packet". 


Let `a1`, `a2`, `a3` be the eigenvalues of some physical quantity A pertaining to system I and `u1(x1)`, `u2(x1)`, `u3(x1)`, the corresponding eigenfunctions, where `x1` stands for the variables used to describe the ﬁrst system. 

Then `Ψ`, considered as a function of `x1`, can be expressed as= 
           
```elixir
Ψ(x1, x2) = ∑n=1 Ψn(x2)un(x1) (7)    
```

where `x2` stands for the variables of the second system. 

Here Ψn(x2) are to be regarded merely as the coefﬁcients of the expansion of Ψ into a series of orthogonal functions un(x1). 

Suppose that `A` is measured and is found to have the value `ak`. 



It means that, after the measurement= 
- `I` is left in the state given by the wave function uk(x1)
- `II` is left in the state given by the wave function pk(x2)

This is the process of reduction of the wave packet; the wave packet given by the infinite series (7) is reduced to a single term= 

```elixir
Ψk(x2)uk(x1)
```

The set of functions `un(x1)` is determined by the choice of the physical quantity `A`. 

If, instead of this, we had chosen another quantity `B`, having the eigenvalues `b1`, `b2`, `b3`, ... and eigen~functions `v1(x1)`, `v2(x1)`, `v3(x1)`, we should have obtained, instead of Eq. (7), the expansion= 


```elixir
Ψ(x1, x2) = ∑s=1 φs(x2)vs(x1)
```

where φs’s are the new coefﬁcients. 

If now the quantity `B` is measured and is found to have the value `br`, then after the measurement= 
- `I` is left in the state vr(x1)
- `II`  is left in the state given by φr(x2)


Thus, as a consequence of two different measurements performed on `I`, `II`may be left in states with two different wave functions. 

On the other hand, since at the time of measurement, the two systems no longer interact, no real change can take place in `II` in consequence of anything done to `I`.

But this is only because of the absence of interaction between the two systems. Thus, it is possible to assign two diﬂerent wave functions, `Ψk` and `φr`, to the same reality (`II` after the interaction with `I`). 

These two wave functions, `Ψk` and `φr` might be eigenfunctions of two non-commuting operators corresponding to some physical quantities `P` and `Q` respectively. 

This is shown by an example. 

Let us suppose that the two systems are two particles, and that

```elixir  
Ψ(x1, x2) = ∫e(2πi/h)(x1-x2+x0) (9)
```

where x0 is some constant. 

Let `A` be the momentum of the Particle 1. As in Eq. (4), its eigenfunctions will be

```elixir  
up(x1) = e(2πi/h)px1            (10)
```

corresponding to the eigenvalue `p`. Since we have here the case of a continuous spectrum, Equation 7 will now be written:

```elixir  
Ψ(x1, x2) = ∫ Ψp(x2)up (x1) dp  (11)    
```

where

```elixir
Ψp(x2) = e—(2πi/h)(x2-x0)p (12) 
```


This `Ψp`, however is the eigenfunction of the operator                                                 

```elixir
P = (h / 2πi) d/dx2,  (13)    
```

corresponding to the eigenvalue `— p` of the momentum of Particle 2. 

On the other hand, if `B` is the coordinate of Particle 1, it has the eigenfunctions                                

```elixir            
vx(x1) = d (x1—x),   (14)   
```

corresponding to the eigenvalue `x`, where `6(x1—x)` is the well-known Dirac delta-function. Eq. (8) in this case becomes                             
                                                         
```elixir
Ψp(x1, x2) = ∫ φx(x2) vx(x1) dx, (15) 
```

where                                                    
                                                         
```elixir
φx(x2) = ∫ e(2πi/h) (x-x2+x0) pdp = hd (x—x2+x0) (16)                    
```

This φx, however, is the eigenfunction of the operator

```elixir                     
Q = x2               (17)    
```

corresponding to the eigenvalue `x+x0` of the coordinate of Particle 2. Since                 

```elixir
PQ — QP = h/2πi,               (18)    
```

then it is possible for Ψk and φr to be eigenfunctions of two noncommuting operators, corresponding to physical quantities.

In Equations 7 and 8, we assume that `Ψk` and `φr` are eigenfunctions of some noncommuting operators `P` and `Q`, corresponding to the eigenvalues `pk` and `qr`, respectively. Thus, by measuring either `A` or `B` we can predict with certainty, without  disturbing Particle 2, either the value of= 
- `P` (that is `pk`) or
- `Q` (that is `qr`). 

Thus, `P` and `Q` are elements of reality. But both wave functions `Ψk` and φr belong to the same reality. 


Previously we proved that either:

1. quantum—mechanics given by the wave function is not complete or
2. when the operators corresponding to two physical quantities do not commute, the two quantities cannot have simultaneous reality


If the wave function does completely describes physical reality, then 2 physical quantities, with noncommuting operators, can have a simultaneous reality. <!-- Thus the negation of (1) leads to the negation of the only other alternative (2). --> Therefore, quantum mechanics is <!-- We are thus forced to conclude that the quantum-mechanical description of physical reality given by wave functions is --> not complete.

The main objection to this conclusion is that our criterion of reality is not sufﬁciently restrictive. 

Our conclusion could not be reached if physical quantities are regarded as simultaneous elements of reality *only when they can be simultaneously measured or predicted*. This means that since either one or the other `P` and `Q`, but not both simultaneously, can be predicted, then they are not simultaneously real.

This makes the reality of `P` and `Q` depend on the process of measurement done on Particle 1 which does not disturb Particle 2 in any way.

{{< c v="red" >}}
We answer that this is not a reasonable deﬁnition of reality. Therefore, the wave function does not provide a complete description of physical reality. Yet such a theory is possible.
{{< /c >}}

![Lol](/icons/einbla.png)
