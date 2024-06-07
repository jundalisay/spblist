---
title: "The Path Integral over the Colour Degrees of Freedom"
description: "The algebra g has many di↵erent representations R"
image: "/covers/yang.png"
# icon: /icons/xeno.png
weight: 2
---


## A Single Instanton in SU (2)

We will focus on gauge group G = SU (2) and solve the self-dual equations Fμ⌫ = ? Fμ⌫
with winding number ⌫ = 1. As we’ve seen, asymptotically the gauge field must be
pure gauge, and so takes the form Aμ ! i⌦@μ ⌦ 1 . An example of a map ⌦(x) 2 SU (2)
with winding ⌫ = 1 is given by

<!-- xμ μ
⌦(x) = p
x2
where
μ
= (1, i~ ) -->

with this choice, the asymptotic form of the gauge field is given by3

<!-- Aμ ! i⌦@μ ⌦ 1 =
1 i ⌫ i
⌘ x
x2 μ⌫
3
as x ! 1 -->

In the lecture notes on Solitons, the instanton solution was presented in singular gauge, where it takes a similar, but noticeably different form.

Here the ⌘μ⌫ are usually referred to as ’t Hooft matrices. They are three 4 ⇥ 4 matrices
which provide an irreducible representation of the su(2) Lie algebra. They are given by

<!-- 0
1
0
1
0
1
0 1 0 0
0 0 1 0
0
B 1 0 0 0C
B 0 0 0 1C
B 0
1
2
3
⌘μ⌫
= @ 0 0 0 1 A , ⌘μ⌫
= @ 1 0 0 0 A , ⌘μ⌫
=@ 0
0 0
1 0
0 1 0 0
0 0 1
0 1 0C
1 0 0
1 0 0 0
A
i -->

These matrices are self-dual: they obey 12 ✏μ⌫⇢ ⌘⇢i = ⌘μ⌫
. This will prove important.

(Note that we’re not being careful about indices up vs down as we are in Euclidean space with no troublesome minus signs.) 

The full gauge potential should now be of
the form Aμ = if (x)⌦@μ ⌦ 1 for some function f (x) ! 1 as x ! 1. 

The right choice turns out to be f (x) = x2 /(x2 + ⇢2 ) where ⇢ is a parameter whose role will be clarified
shortly. We then have the gauge field

<!-- Aμ =
1
x 2 + ⇢2
i
⌘μ⌫
x⌫ i
(2.51) -->

You can check that the associated field strength is

<!-- Fμ⌫ =
2⇢2
⌘i i
(x2 + ⇢2 )2 μ⌫ -->

This inherits its self-duality from the ’t Hooft matrices and therefore solves the Yang-Mills equations of motion.

The instanton solution (2.51) is not unique. By acting on this solution with various symmetries, we can easily generate more solutions. 

The most general solution with winding ⌫ = 1 depends on 8 parameters which, in this context, are referred to as
collective coordinates. Each of them is has a simple explanation: 

• The instanton solution above is localised at the origin. But we can always generate
a new solution localised at any point X 2 R4 simply by replacing xμ ! xμ X μ
in (2.51). 

This gives 4 collective coordinates.

• We’ve kept one parameter ⇢ explicit in the solution (2.51). 

This is the scale size of the instanton, an interpretation which is clear from looking at the field
strength which is localised in a ball of radius ⇢. The existence of this collective
coordinate reflects the fact that the classical Yang-Mills theory is scale invariant:
if a solution exists with one size, it should exist with any size. 

This property is broken in the quantum theory by the running of the coupling constant, and this
has implications for instantons that we will describe below.

The final three collective coordinates arise from the global part of the gauge
group. These are gauge transformations which do not die off asymptotically, and
correspond to three physical symmetries of the theory, rather than redundancies.

For our purposes, we can consider a constant V 2 SU (2) , and act as Aμ !
V Aμ V 1 .

It is straightforward to write down a
corresponding anti-self-dual instanton with winding ⌫ = 1. We simply replace the ’t
Hooft matrices with their anti-self dual counterparts,

<!-- 0
1
0
1
0
1
0
1 0 0
B1 0
1
⌘ ̄μ⌫
= @0 0
0 0
0 0C
0 0
1 0
B0 0 0
2
A , ⌘ ̄μ⌫ = @ 1 0 0
0 1
1 0
0 1 0
1C
0 0 0
1
B0 0 1 0 C
3
A , ⌘ ̄μ⌫ = @ 0 1 0 0 A
0
0
1 0 0 0
i -->

They obey 12 ✏μ⌫⇢ ⌘⇢i = ⌘μ⌫ , and one can use these to build a gauge potential (2.51) with ⌫ = 1. These too form an irreducible representation of su(2), and obey [⌘ i , ⌘ ̄j ] = 0. 

The fact that we can find two commuting su(2) algebras hiding in a 4 ⇥ 4 matrix reflects the fact that Spin(4) ⇠
= SU (2) ⇥ SU (2) and, correspondingly, the Lie algebras
are so(4) = su(2) su(2).

