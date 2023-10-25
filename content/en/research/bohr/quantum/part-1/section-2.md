---
heading: "Section 2"
title: "Systems of one degree of freedom"
description: "Systems of a single degree of freedom shows the simplest illustration of the principles in section 1"
weight: 10
image: "/covers/quantum.jpg"
contributors: ['Bohr']
---


Systems of a single degree of freedom shows the simplest illustration of the principles in section 1. 

- This lets us establish a general theory of stationary states. 
- This is due to the fact that the motion will be simply periodic, provided the distance between the parts of the system will not increase infinitely with the time. 
  - In such a case, the stationary state will no longer be stationary. 

<!-- ) P. Ehrenfest, Phys. Zeitschr. XV p. 660 (1914).  -->

The above interpretation of this relation is not stated explicitly by Ehrenfest. But it presents itself directly if the quantum theory is taken in the form corresponding to the fundamental assumption I.


On account of this, the discussion of the mechanical transformability of the stationary states can, as pointed out by Ehrenfest,

) for systems of one degree of freedom be based on a mechanical theorem about periodic systems due to Boltzmann and originally applied by this author in a discussion of the bearing of mechanics on the explanation of the laws of thermodynamics. 

For the sake of the considerations in the following sections it will be convenient here to 

I give the proof in a form which differs slightly from that given by Ehrenfest.
- It also takes regard to the modifications in the ordinary laws of mechanics claimed by Relativity.

Consider for the sake of generality a conservative mechanical system of s degrees of freedom, the motion of which
is governed by Hamilton’s equations:
dpk
dt = −
∂E
∂qk
,
dqk
dt =
∂E
∂pk
, (k = 1, . . . , s) (4)


where E is the total energy considered as a function of the generalised positional coordinates q1, . . . , qs and the corresponding canonically conjugated momenta p1, . . . , ps. 

If the  velocities are so small that the variation in the mass of the
particles due to their velocities can be neglected, the p’s are
1
) P. Ehrenfest, loc. cit. Proc. Acad. Amsterdam, XVI, p. 591
(1914).


defined in the usual way by
pk =
∂T
∂qk
, (k = 1, . . . , s)
where T is the kinetic energy of the system considered as a
function of the generalised velocities ˙q1, . . . , ˙qs

q˙k =
dqk
dt 
and of q1, . . . , qs.

If the relativity modifications are taken into account the p’s are defined by a similar set of expressions
in which the kinetic energy is replaced by
T
0 =
Xm0c
2

1 −
p
1 − v
2/c2

,
where the summation is to be extended over all the particles
of the system, and v is the velocity of one of the particles
and m0 its mass for zero velocity, while c is the velocity of
light.
Let us now assume that the system performs a periodic
motion with the period σ, and let us form the expression

```elixir
I = ∫σ0 ∑s1 pkqkdt (5)
```

which is easily seen to be independent of the special choice of coordinates q1, . . . , qs used to describe the motion of the system. 

In fact, if the variation of the mass with the velocity is neglected we get

```elixir
I = 2∫σ0 Tdt
``` 

if the relativity modifications are included, we get a quite analogous expression in which the kinetic energy is replaced by

```elixir
T'' = ∑ 1/2 m0v2 √ 1-v2/c2
```


Consider next some new periodic motion of the system formed by a small variation of the first motion, but which may need the presence of external forces in order to be a mechanically possible motion. For the variation in I we get then

```elixir
δI = ∫σ0 ∑s1 (qkσpk + pkσpk) dt + ∑s1 pkqk δt|δ0
```

where the last term refers to the variation of the limit of the
integral due to the variation in the period σ. By partial integration of the second term in the bracket under the integral
we get next
δI =
Z σ
0
Xs
1
( ˙qk δpk − p˙k δqk) dt +
Xs
1
pk( ˙qk δt + δqk)



σ
0
,
where the last term is seen to be zero, because the term in
the bracket as well as pk will be the same in both limits, since
the varied motion as well as the original motion is assumed
to be periodic. By means of equations (4) we get therefore
δI =
Z σ
0
Xs
1

∂E
∂pk
δpk +
∂E
∂qk
δqk

dt =
Z σ
0
δE dt. (6)
Let us now assume that the small variation of the motion
is produced by a small external field established at a uniform
18
rate during a time interval ϑ, long compared with σ, so that
the comparative increase during a period is very small. In
this case δE is at any moment equal to the total work done
by the external forces on the particles of the system since the
beginning of the establishment of the field. Let this moment
be t = −ϑ and let the potential of the external field at t ≥ 0
be given by Ω, expressed as a function of the q’s. At any
given moment t > 0 we have then
δE = −
Z 0
−ϑ
ϑ + t
ϑ
Xs
1
∂Ω
∂qk
q˙k dt −
Z t
0
Xs
1
∂Ω
∂qk
q˙k dt,
which gives by partial integration
δE =
1
ϑ
Z 0
−ϑ
Ω dt − Ωt
,
where the values for the q’s to be introduced in Ω in the
first term are those corresponding to the motion under the
influence of the increasing external field, and the values to be
introduced in the second term are those corresponding to the
configuration at the time t. Neglecting small quantities of
the same order as the square of the external force, however,
we may in this expression for δE instead of the values for the
q’s corresponding to the perturbed motion take those corresponding to the original motion of the system. With this
approximation the first term is equal to the mean value of
the second taken over a period σ, and we have consequently
Z σ
0
δE dt = 0. (7)
19
From (6) and (7) it follows that I will remain constant
during the slow establishment of the small external field, if
the motion corresponding to a constant value of the field is
periodic. If next the external field corresponding to Ω is considered as an inherent part of the system, it will be seen in the
same way that I will remain unaltered during the establishment of a new small external field, and so on. Consequently
I will be invariant for any finite transformation of the system
which is sufficiently slowly performed, provided the motion
at any moment during the process is periodic and the effect
of the variation is calculated on ordinary mechanics.
Before we proceed to the applications of this result we
shall mention a simple consequence of (6) for systems for
which every orbit is periodic independent of the initial conditions. In that case we may for the varied motion take an
undisturbed motion of the system corresponding to slightly
different initial conditions. This gives δE constant, and
from (6) we get therefore
δE = ω δI, (8)
where ω =
1
σ
is the frequency of the motion. This equation
forms a simple relation between the variations in E and I for
periodic systems, which will be often used in the following.
Returning now to systems of one degree of freedom, we
shall take our starting point from Planck’s original theory
of a linear harmonic vibrator. According to this theory the
stationary states of a system, consisting of a particle execut-
20
ing linear harmonic vibrations with a constant frequency ω0
independent of the energy, are given by the well known relation
E = nhω0, (9)
where n is a positive entire number, h Planck’s constant,
and E the total energy which is supposed to be zero if the
particle is at rest.
From (8) it follows at once that (9) is equivalent to
I =
Z σ
0
pq dt ˙ =
Z
p dq = nh, (10)
where the latter integral is to be taken over a complete oscillation of q between its limits. On the principle of the
mechanical transformability of the stationary states we shall
therefore assume, following Ehrenfest, that (10) holds not
only for a Planck’s vibrator but for any periodic system
of one degree of freedom which can be formed in a continuous manner from a linear harmonic vibrator by a gradual
variation of the field of force in which the particle moves.
This condition is immediately seen to be fulfilled by all such
systems in which the motion is of oscillating type i. e. where
the moving particle during a period passes twice through
any point of its orbit once in each direction. If, however,
we confine ourselves to systems of one degree of freedom, it
will be seen that systems in which the motion is of rotating type, i. e. where the particle during a period passes only
once through every point of its orbit, cannot be formed in a

continuous manner from a linear harmonic vibrator without passing through singular states in which the period becomes
infinite long and the result becomes ambiguous. 

We shall not here enter more closely on this difficulty which has been pointed out by Ehrenfest, because it disappears when we
consider systems of several degrees of freedom, where we shall see that a simple generalisation of (10) holds for any
system for which every motion is periodic. 

As regards the application of (9) to statistical problems it was assumed in Planck’s theory that the different states
of the vibrator corresponding to different values of n are a-priori equally probable, and this assumption was strongly
supported by the agreement obtained on this basis with the measurements of the specific heat of solids at low temperatures.

It follows from the considerations of Ehrenfest, mentioned in the former section, that the a-priori probability
of a given stationary state is not changed by a continuous transformation, and we shall therefore expect that for any
system of one degree of freedom the different states corresponding to different entire values of n in (10) are a-priori
equally probable.

As pointed out by Planck in connection with the application of (9), it is simply seen that statistical considerations, based on the assumption of equal probability for the
different states given by (10), will show the necessary relation to considerations of ordinary statistical mechanics in
the limit where the latter theory has been found to give results in agreement with experiments. 

Let the configuration and motion of a mechanical system be characterised by s independent variables q1, . . . , qs and corresponding momenta
p1, . . . , ps and let the state of the system be represented
in a 2s-dimensional phase-space by a point with coordinates
q1, . . . , qs, p1, . . . , ps. Then, according to ordinary statistical mechanics, the probability for this point to lie within a
small element in the phase-space is independent of the position and shape of this element and simply proportional to
its volume, defined in the usual way by
δW = Z
dq1 . . . dqs dp1 . . . dps. (11)

In the quantum theory, however, these considerations cannot be directly applied, since the point representing the state of a system cannot be displaced continuously in the 2sdimensional phase-space, but can lie only on certain surfaces of lower dimensions in this space. 

For systems of one degree of freedom the phase-space is a two-dimensional surface, and the points representing the states of some system
given by (10) will be situated on closed curves on this surface. Now, in general, the motion will differ considerably
for any two states corresponding to successive entire values
of n in (10), and a simple general connection between the
quantum theory and ordinary statistical mechanics is therefore out of question. In the limit, however, where n is large,
the motions in successive states will only differ very little
from each other, and it would therefore make little difference
whether the points representing the systems are distributed continuously on the phase-surface or situated only on the
curves corresponding to (10), provided the number of systems which in the first case are situated between two such
curves is equal to the number which in the second case lies on
one of these curves. But it will be seen that this condition is
just fulfilled in consequence of the above hypothesis of equal
a-priori probability of the different stationary states, because
the element of phase-surface limited by two successive curves
corresponding to (10) is equal to
δW =
Z
dp dq =
Z
p dq
n
−
Z
p dq
n−1
= In − In−1 = h,
(12)
so that on ordinary statistical mechanics the probabilities for
the point to lie within any two such elements is the same. We
see consequently that the hypothesis of equal probability of
the different states given by (10) gives the same result as ordinary statistical mechanics in all such applications in which
the states of the great majority of the systems correspond
to large values of n. Considerations of this kind have led
Debye1
) to point out that condition (10) might have a general validity for systems of one degree of freedom, already
before Ehrenfest, on the basis of his theory of the mechanical transformability of the stationary states, had shown
that this condition forms the only rational generalisation of
Planck’s condition (9).
1
) P. Debye, Wolfskehl-Vortrag. G¨ottingen 1913.
24
We shall now discuss the relation between the theory of
spectra of atomic systems of one degree of freedom, based on
(1) and (10), and the ordinary theory of radiation, and we
shall see that this relation in several respects shows a close
analogy to the relation, just considered, between the statistical applications of (10) and considerations based on ordinary
statistical mechanics. Since the values for the frequency ω
in two states corresponding to different values of n in (10)
in general are different, we see at once that we cannot expect a simple connection between the frequency calculated
by (1) of the radiation corresponding to a transition between
two stationary states and the motions of the system in these
states, except in the limit where n is very large, and where
the ratio between the frequencies of the motion in successive
stationary states differs very little from unity. Consider now
a transition between the state corresponding to n = n
0 and
the state corresponding to n = n
00, and let us assume that
n
0 and n
00 are large numbers and that n
0 − n
00 is small compared with n
0 and n
00. In that case we may in (8) for δE put
E
0 − E
00 and for δI put I
0 − I
00, and we get therefore from
(1) and (10) for the frequency of the radiation emitted or
absorbed during the transition between the two states
ν =
1
h
(E
0 − E
00) = ω
h
(I
0 − I
00) = (n
0 − n
00)ω. (13)
Now in a stationary state of a periodic system the displacement of the particles in any given direction may always
be expressed by means of a Fourier-series as a sum of har-
25
monic vibrations:
ξ =
XCτ cos 2π(τωt + cτ ), (14)
where the C’s and c’s are constants and the summation is
to be extended over all positive entire values of τ . On the
ordinary theory of radiation we should therefore expect the
system to emit a spectrum consisting of a series of lines of
frequencies equal to τω, but, as it is seen, this is just equal
to the series of frequencies which we obtain from (13) by introducing different values for n
0 − n
00. As far as the frequencies are concerned we see therefore that in the limit where
n is large there exists a close relation between the ordinary
theory of radiation and the theory of spectra based on (1)
and (10). It may be noticed, however, that, while on the first
theory radiations of the different frequencies τω corresponding to different values of τ are emitted or absorbed at the
same time, these frequencies will on the present theory, based
on the fundamental assumption I and II, be connected with
entirely different processes of emission or absorption, corresponding to the transition of the system from a given state
to different neighbouring stationary states.
In order to obtain the necessary connection, mentioned
in the former section, to the ordinary theory of radiation in
the limit of slow vibrations, we must further claim that a
relation, as that just proved for the frequencies, will, in the
limit of large n, hold also for the intensities of the different
lines in the spectrum. Since now on ordinary electrodynamics the intensities of the radiations corresponding to different
26
values of τ are directly determined from the coefficients C|tau
in (14), we must therefore expect that for large values of n
these coefficients will on the quantum theory determine the
probability of spontaneous transition from a given stationary
state for which n = n
0
to a neighbouring state for which
n = n
00 = n
0 − τ . Now this connection between the amplitudes of the different harmonic vibrations into which the motion can be resolved, characterised by different values of τ ,
and the probabilities of transition from a given stationary
state to the different neighbouring stationary states, characterised by different values of n
0 − n
00, may clearly be expected to be of a general nature. Although, of course, we cannot without a detailed theory of the mechanism of transition obtain an exact calculation of the latter probabilities, unless n is large, we may expect that also for small values
of n the amplitude of the harmonic vibrations corresponding to a given value of τ will in some way give a measure for
the probability of a transition between two states for which 
n
0 − n
00 is equal to τ . Thus in general there will be a certain
probability of an atomic system in a stationary state to pass
spontaneously to any other state of smaller energy, but if
for all motions of a given system the coefficients C in (14)
are zero for certain values of τ , we are led to expect that no
transition will be possible, for which n
0 − n
00 is equal to one
of these values.

A simple illustration of these considerations is offered by the linear harmonic vibrator mentioned above in connection
with Planck’s theory. Since in this case Cτ is equal to zero for any τ different from 1, we shall expect that for this system only such transitions are possible in which n alters by one unit. 

From (1) and (9) we obtain therefore the simple result that the frequency of any radiation emitted or absorbed
by a linear harmonic vibrator is equal to the constant frequency ω0.

This result seems to be supported by observations on the absorption-spectra of diatomic gases, showing that certain strong absorption-lines, which according to general evidence may be ascribed to vibrations of the two atoms in the molecule relative to each other, are not accompanied by lines of the same order of intensity and corresponding to entire multipla of the frequency, such as it should be expected from (1) if the system had any considerable tendency to pass between non-successive states. In this connection it may be noted that the fact, that in the absorption spectra of some diatomic gases faint lines occur corresponding to the double frequency of the main lines,1) obtains a natural explanation by assuming that for finite amplitudes the vibrations are not
exactly harmonic and that therefore the molecules possess a small probability of passing also between non-successive states.

