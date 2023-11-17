---
title: "The Lorentz Transformation"
heading: "Section 11"
weight: 19
# date: 2022-04-10
description: "Einstein implements his c constant, relativity of time and space and moving viewpoints together as the Lorentz Transformation"
image: "/covers/rel.jpg"
icon: "/icons/einbla.png"
author: Albert Einstein
---


Sections 8-10 show that the apparent incompatibility of the law of propagation of light with the principle of relativity (Section 7) arises from two unjustifiable hypotheses from classical mechanics:

1. The time-interval (time) between two events is independent of <!-- the condition of motion of --> the body of reference

2. The space-interval (distance) between two points of a rigid body is independent of <!-- the condition of motion of --> the body of reference

If we drop those two, then the dilemma of Section 7 disappears, because the addition of velocities (Section 6) becomes invalid*. This then makes the law of the propagation of light in vacuum compatible with the principle of relativity.



> *Superphysics Note: Here, Einstein "solves" the inconsistencies in his Theory of Relativity by creating the idea of a spacetime unity that is different from the separated Newtonian spacetime. In reality, his spacetime is merely Galilean spacetime of the material layer glued together by the light of the Electromagnetic layer. Galilean transformation allows the addition of velocities through the standard of matter, while the Lorentz transformation allows a relativistic 'addition' through the standard of light. In a nutshell, the Lorentz transformation 


<!--  spacetime of electromagnetism is different from the spacetime of matter.  
 -->

How can we modify Section 6 [addition of velocities] to unify space and time<!-- remove the disagreement between these two fundamental results of experience -->

<!-- This question leads to a general one. In the discussion of Section 6 we have to do with places and times
relative both to the train and to the embankment. 

How are we to find the place and time of an event in relation to the train, when we know the place and time of the event with respect to the railway embankment? Is there a thinkable answer to this question of such a nature that the law of transmission of light in vacuo does not contradict the principle of relativity? 

In other words=   -->

Referring to my example of an event viewed from a moving train and an embankment=  How should we think of the place and time of individual events relative to both reference-bodies [train and embankment], so that light has the velocity `c` relative to the embankment and to the train? 

![Train](/graphics/train.png)

This is answered by a perfectly definite transformation law for the space-time magnitudes of an event when changing over from one viewpoint to <!--  body of reference to --> another.  <!-- Before we deal with this, we shall introduce the following incidental consideration.  --> <!-- Up to now, we have only considered events taking place along the embankment, which had mathematically to assume the function of a straight line. --> The horizontal embankment is a viewpoint supplemented horizontally and vertically through a framework of rods as mentioned in Section 2. In this way, an event anywhere can be localised through such rods. 

The train travelling with velocity `v` continues across the whole of space. Every event, no matter how far off it may be, could also be localised from the viewpoint of the train.

We can ignore the continual interference of these two viewpoints with each other arising from the impenetrability of solid bodies. In every such framework, we imagine a coordinate system of 3 surfaces perpendicular to each other. 
- non-moving `K` is the embankment
- moving `K'` is the train.

![Moving train relativity](/graphics/physics/trans.png)

Relative to the non-moving `K`, an event would be:
- fixed in space with respect to non-moving `K` by the three perpendiculars `x, y, z` showing its coordinates
- fixed in time by a time-value `t`

Relative to moving `K'`, the same event would be:
- fixed in space and time by corresponding values `x', y', z', t'`. These are different from `x, y, z, t`.

<!-- These magnitudes are results of physical measurements.  -->

What are the values `x', y', z', t'` of an event with respect to the moving `K'` when the magnitudes `x, y, z, t` of the same event with respect to the non-moving `K` are given? 


## Lorentz Transformation

The relations must be so chosen that the law of the transmission of light in a vacuum is satisfied for lightrays with respect to `K` and `K'`. <!-- For the relative orientation in space of the co-ordinate systems indicated in the diagram (Fig. 2), this problem --> This is solved by equations known as the “Lorentz transformation.*”:


``` elixir
x' = (x - vt) / √(1-(v2/c2))

y' = y

z' = z

t' = (t-(v/c2))x) / √(1-v2/c2
```



> *Einstein Note: This is explained in Appendix 1



## Galileo Transformation

If we used instead the Classical mechanics [Section 9?] wherein space and time were absolute, then the equations would be:

<!--  in place of the law of transmission of light we had taken as our basis the tacit assumptions of the older mechanics as to the absolute character of times and lengths, then instead of the above we should have obtained the following equations=  -->

``` elixir
x' = x − vt
y' = y
z' = z
t' = t
```



These are called the “Galilei transformation.” These can be obtained from the Lorentz transformation by substituting an infinitely large value for the velocity of light `c` in the Lorentz transformation.<!-- Aided by the following illustration, we can readily see that, in accordance with the Lorentz transformation,  --> Thus, the law of the transmission of light in vacuum is satisfied both for the non-moving `K` and the moving `K'`. 

A light signal is sent along the positive x-axis. It advances accordaning with the equation (with the velocity `c`)= 

``` elixir
x = ct
```



According to the equations of the Lorentz transformation, this simple relation between `x` and `t` involves a relation between `x'` and `t'`. If we substitute for `x` the value `ct` in the 1st and 4th equations of the Lorentz transformation, we obtain= 

``` elixir
x' = ( c − v ) t / √(1-(v2/c2)

t' = ( 1 − (v/c) ) t / √ (1 − (v2/c2)
```



from which, by division, the expression follows= 

``` elixir
x' = ct'
```



If referred to the system `K'`, the speed of light takes place according to this equation. We thus see that the velocity of transmission relative to the moving `K'` is also equal to `c`.  The same result is obtained for rays of light advancing in any other direction. <!-- This is because the equations of the Lorentz transformation 
were derived conformably to this point of view. -->

