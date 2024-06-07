

## Non-Abelian Coulomb Force

<!-- C(
)=
and C(adj) = N
(N -->

Let’s now apply this to the force between quarks. The group theory machinations above tell us that the operator T a (R1 )T a (R2 ) decomposes into a block diagonal matrix, with entries labelled by the irreducible representations R ⇢ R1 ⌦ R2 and given by

<!-- 1
T a (R1 )T a (R2 ) = [C(R) C(R1 ) C(R2 )]
2
R -->

The quark and anti-quark can sit in two different irreducible representations: the singlet and the adjoint (2.65). For the singlet, we have

<!-- ⇤
1⇥
N2 1
C(1) C(N) C(N̄) =
2
2N -->

The minus sign ensures that the force between the quark and anti-quark in the singlet channel is attractive. This is what we would have expected from our classical intuition.

However, when the quarks sit in the adjoint channel, we have

<!-- ⇤
1⇥
1
C(adj) C(N) C(N̄) =
2
2N -->

Perhaps surprisingly, this is a repulsive force.
The group theory analysis above makes it simple to compute the classical force
between quarks in any representation. Suppose, for example, we have two quarks, both
in the fundamental representation. They decompose as


<!-- N⌦N=
where dim(
) = 12 N (N + 1) and dim(
1
[C (
2
)
C(N)
) = 12 N (N
C(N)] =
and
1). We then have
N 1
2N
i
1h ⇣ ⌘
N +1
C
C(N) C(N) =
2
2N -->


and the force is repulsive between quarks in the symmetric channel, but attractive in
the anti-symmetric channel.


Even classically, Yang-Mills theory provides a somewhat richer structure to the forces between particles. 

However, at the classical level, Yang-Mills retains the familiar 1/r fall-off from Maxwell theory. This is the signature of a force due to the exchange of massless particles in d = 3+1 dimensions, whether photons or gravitons or, in this case, gluons. As we now explain, at the quantum level things are very different. 

## The Confining Force

In the previous section, we stated (but didn’t prove!) that Yang-Mills has a mass gap. 

This means that, at distances 1/⇤QCD , the force will be due to the exchange of massive particles rather than massless particles. 

In many situations, the exchange of massive particles results in an exponentially suppressed Yukawa force, of the form V (r) ⇠ e mr /r, and you might have reasonably thought this would be the case for Yang-Mills. 

You would have been wrong.

Let’s again consider a quark and an anti-quark, in the N and N̄ representations respectively. The energy between the two turns out to grow linearly with distance

<!-- V (r) = r -->

(2.67)
for some value that has dimensions of energy per length. 

It is often referred to as the string tension. 

On dimensional grounds, we must have ⇠ ⇤2QCD since there is no other scale in the game.

For 2 quarks, the result is even more dramatic. Now the tensor product of the 2 representations does not include a singlet (at least this is true for SU (N ) with N 3).

The energy between the two quarks turns out to be infinite. This is a general property of quantum Yang-Mills: the only finite energy states are gauge singlets. 

The theory is confining: an individual quark cannot survive on its own, but is forced to
enjoy the company of friends.

There is a possibility for confusion in the the claim that only singlet states survive in a confining gauge theory. 

In any gauge theory, one should only talk about gauge invariant states and a single quark is not a gauge invariant object. 

However, we can render the quark gauge invariant by attaching a Wilson line (2.14) which stretches
from the position of the quark to infinity. 

When we blithely talk about a single quark, we should really be thinking of this composite object. This is not directly related to the issue of confinement.

The statements above hold equally well for electrons in QED: these too are only gauge invariant when  attached to a Wilson line. 

Instead, the issue of confinement is a dynamical statement, rather than a kinematical one.
Confinement means that the quark + Wilson line costs infinite energy in Yang-Mills,
while the electron + Wilson line (suitably regulated) costs finite energy in QED.
– 77 –There are situations where it’s not possible to form a singlet from a pair of particles,
but it is possible if enough particles are added. The baryon provides a good example,
in which N quarks, each in the fundamental representation of SU (N ), combine to form
a singlet B = ✏i1 ...iN qi1 . . . qiN . These too are finite energy states.
Confinement in Yang-Mills is, like the mass gap, a challenging problem. There is no
analytic demonstration of this phenomenon. Instead, we will focus on building some
intuition for why this might occur and understanding the right language to describe it.
2.5.2 An Analogy: Flux Lines in a Superconductor
There is a simple system which provides a useful analogy for confinement. This is a
superconductor.
One of the wonders of the superconducting vacuum is its ability to expel magnetic
fields. If you attempt to pass a magnetic field through a superconductor, it resits. This
is known as the Meissner effect. If you insist, by cranking up the magnetic field, the
superconductor will relent, but it will not do so uniformly. Instead, the magnetic field
will form string-like filaments known as vortices.
We can model this using the Abelian Higgs model. This is a U (1) gauge field, coupled
to a complex scalar
Z
1
S = d4 x
Fμ⌫ F μ⌫ + |Dμ |2
(| |2 v 2 )2
4e2
with Dμ = @μ
iAμ . (As an aside: in an actual superconductor, the complex scalar
field describes the cooper pair of electrons, and should have a non-relativistic kinetic
term rather than the relativistic kinetic terms we use here.)
In the vacuum, the scalar has an expectation value, h| |i = v, spontaneously breaking
the U (1) gauge symmetry and giving the photon a mass, m2 = 2e2 v 2 . This is, of course,
is the Higgs mechanism. In this vacuum, the scalar also has a mass given by m2 = 4 v 2 .
Let’s start by seeing how this explains the Meissner effect. We’ll look for time
dependent solutions, with A0 = 0 and a magnetic field B i = 12 ✏ijk Fjk . If we assume
that the Higgs field doesn’t deviate from = v then the equation of motion for the
gauge field is
r⇥B=
m2 A
)
r2 B = m 2 B
This is known as the London equation. It tells us that magnetic fields are exponentially
damped in the Higgs phase, with solutions of the form B(x) = B0 e m x . In the context
– 78 –of superconductors, the length scale L = 1/m is known as the penetration depth. Later
another length scale, ⇠ ⇠ 1/m , will also be important; this is called the correlation
length.
Of course, the assumption that = v is not justified:
is a dynamical field and
is determined by its equation of motion. This is where we will find the vortices. We
decompose the complex scalar as
= ⇢eiff
All finite energy, classical configurations must have ⇢ ! v as x ! 1. But the phase
is arbitrary. This opens up an interesting topological possibility. Consider a classical
configuration which is invariant in the x3 direction, but is localised in the (x1 , x2 ) plane.
The translational invariance x3 reflects the fact that we will be constructing an infinite
string solution, aligned along x3 . We parameterise the plane by radial coordinates
x1 + ix2 = rei✓ . Then all configurations whose energy is finite when integrated over the
(x1 , x2 ) plane involve a map
ff(✓) : S11 7! S1
(2.68)
These maps fall into disjoint classes, labelled by the number of times that winds as
we move around the asymptotic circle S11 . This is the same kind of idea that we met
when discussing theta vacua and instantons in Sections 2.2 and 2.3. In that case we
were dealing with the homotopy group ⇧3 (S3 ); here we have a simpler situation, with
maps of the form (2.68) classified by
⇧1 (S1 ) = Z
In this case, it is simple to write down an expression for the integer n 2 Z which
classifies the map. It is the winding number,
1
n=
2⇡
Z
d✓
S11
@ff
2 Z
@✓
(2.69)
In this way, the space of field configurations decompose into sectors, labelled by n 2 Z.
The vacuum sits in the sector n = 0. A particularly simple way to find classical solutions
is to minimize the energy in a sector n 6= 0. These solutions, which are stabilised by
their winding at infinity, and are often referred to as topological solitons. In the present
context, these solitons will the vortices that we are looking for.
– 79 –B
φ
v
r
L
r
ξ
Figure 13: The profile for the magnetic field and Higgs field in a vortex.
We’ll consider radially symmetric scalar profiles of the form
(r, ✓) = ⇢(r)ein✓
(2.70)
We will first see why any configuration with n 6= 0 necessarily comes with a magnetic
field. Because our configurations are invariant under x3 translations, they will always
have a linearly diverging energy corresponding to the fact that we have an infinite
string. But the energy density in the (x1 , x2 ) plane should integrate to a finite number.
We denote the energy per unit length of the vortex string by . The kinetic term for
the scalar gives a contribution to the energy that includes
⇠
Z
drd✓ r
✓
1 @
r @✓
iA✓
◆
2
=
Z
in⇢
drd✓ r
r
2
iA✓ ⇢
If we try to set A✓ = 0, the energy has a logarithmic divergence from the integral over
the (x1 , x2 ) plane. To compensate we must turn on A✓ ! n/r as r ! 1. But this
means that the configuration (2.70) is accompanied by a magnetic flux
Z
I
2
= d x B3 = d✓ rA✓ = 2⇡n
(2.71)
We see that the flux is quantised. This is the same quantisation condition that we saw
for magnetic monopoles in Section 1.1 (albeit with a rescaled convention for the gauge
field because we chose to put the coupling e2 in front of the action). Note, however, that
here we haven’t invoked any quantum mechanics; in the Higgs phase, the quantisation
of flux happens for topological reasons, rather than quantum reasons.
So far we have talked about configurations with winding, but not yet discussed
whether they are solutions to the equations of motion. It is not hard to find solutions
for a single vortex with n = 1 (or, equivalently, an anti-vortex with n = 1). We write
– 80 –an ansatz for the gauge field as A✓ = f (r)/r and require f (r) ! 1 as r ! 1. The
equations of motion then reduce to ordinary differential equations for ⇢(r) and f (r).
Although no analytic solutions are known, it is simple to solve them numerically. These
solutions are often referred to as Nielsen-Olesen vortices.
Here we will build some intuition for what these look like without doing any hard
work. The key feature is that winds asymptotically, as in (2.70), which means that
by the time we get to the origin it has something of an identity crisis and does not
know which way to point. The only way in which the configuration can remain smooth
is if = 0 at the origin. But it costs energy for to deviate from the vacuum, so it
must do so over as small a scale as possible. This scale is ⇠ ⇠ 1/m .
Similarly, we know that the flux (2.71) must be non-zero. It is energetically preferable
for this flux to sit at the origin, since this is where the Higgs field vanishes. This flux
spreads over a region associated to the penetration length L ⇠ 1/m . The resulting
profiles for the Higgs and magnetic fields are sketched in the figures.
Type I, Type II and Bogomonlyi
Before we explain why these vortices provide a good analogy for confinement, we first
make a small aside. As described above, there are two length scales at play in the
vortex solutions. The Higgs field drops to zero over a region of size ⇠ ⇠ while the
magnetic field is spread over a region of size ⇠ L.
The ratio of these two scales determines the force between two parallel vortices. For
far separated vortices, the force is exponentially suppressed, reflecting the fact that the
theory is gapped. As they come closer, either their magnetic flux will begin to overlap
(if L > ⇠), or their scalar profiles will begin to overlap (if ⇠ > L). The magnetic flux is
repulsive, while the scalar field is attractive. Based on this distinction, superconductors
are divided into two classes:
Type I: ⇠ > L. In this case, the overlap of the scalar profiles of vortices provide the
dominant, attractive force. If one applies a uniform magnetic field to a superconductor,
it turns into one big vortex. But a big vortex is effectively the same as turning the
system back into the normal phase. This means that the superconductor resists an
applied magnetic field until it reaches a critical value, at which point the system exits
the Higgs phase. This means that no vortices are seen in Type I superconductors.
Type II: ⇠ < L. Now the magnetic flux of the vortices overlap are they approach,
resulting in a repulsive force. This means that when a uniform magnetic field is applied
to a Type II superconductor, it will form many vortices, each of which wants to be as
– 81 –Figure 14: An Abrikosov lattice in a Type II superconductor.
far from the others as possible. The result is a periodic array of vortices known as an
Abrikosov lattice. An example is shown in the figure4 .
At the boundary between Type I and Type II superconductors, the heuristic ar-
guments above suggest that there are no forces between vortices. Mathematically,
something rather pretty happens at this point. We have m2 = m2 or, equivalently,
= e2 /2. At this special value, we can write the tension of the vortex string as the
sum of squares,
Z
1 2 X
e2
2
2
=
d x 2 B3 +
|Di | + (| |2 v 2 )2
2e
2
i=1,2
Z
=
d2 x |D1
iD2 |2 + iD1 † D2
iD2 † D1
=
=
Z
Z
+
d2 x |D1
1
B3 + e2 (| |2
2e2
iD2 |2
d2 x |D1 + iD2 |2 +
v2)
2
i † [D1 , D2 ] +
B3 (| |2
v2)
1
B32 + e2 (| |2
2e2
1
B3 + e2 (| |2
2e2
v2)
2
v2)
2
B3 (| |2
v2)
+ v 2 B3
where, in going to the last line, we used the fact that [D1 , D2 ] = iF12 = +iB3 . This
“completing the square” trick is the same kind of Bogomolnyi argument that we used in
Section 2.3 when discussing instantons. Since the two squares are necessarily positive,
the energy can be bounded by
Z
E
d2 x v 2 B3 = 2⇡v 2 n
4
This picture is taken from P. Goa et al, Supercond. Sci. Technol. 14, 729 (2001). A nice gallery
of vortex lattices can be found here.
– 82 –Figure 15: The flux lines for a monopole
and anti-monopole in vacuum.
Figure 16: The same flux lines in a su-
perconductor.
where we have related the flux to the winding using (2.71). This is nice. In a sector
with winding n > 0, there is a minimum energy bound. Moreover, we can saturate this
bound by requiring that the quantities in the squares vanish,
D1 = iD2
and B3 =
e2 (| |2
v2)
(2.72)
These are the Bogomolnyi vortex equations. For n < 0, one can play a similar game
with some minus signs shu✏ed around to derive Bogomolnyi equations for anti-vortices.
The vortex equations (2.72) have a number of remarkable properties. In particular,
it can be shown that the general solution has 2n parameters which, at least for far sep-
arated vortices, can be thought of as the position of n vortices on the plane. Physically,
this arises because there is no force between the vortices. You can read more about
this in the lecture notes on Solitons.
The Confinement of Monopoles
So far we’ve reviewed some basic physics of the Higgs phase of electromagnetism. But
what does this have to do with confinement? To see the connection, we need to think
about what would happen if we place a Dirac monopole inside a superconductor.
To get some grounding, let’s first consider a monopole and anti-monopole in vacuum.
Their magnetic field lines spread out in a pattern that is familiar from the games we
played with iron filings and magnets when we were kids. This is sketched in the left-
hand figure. These field lines result in a Coulomb-like force between the two particles,
V (r) ⇠ 1/r.
Now what happens when we place these particles inside a superconductor? The
magnetic flux lines can no longer spread out, but instead must form collimated tubes.
This is sketched in the right-hand figure. This tube of flux is the vortex that we
– 83 –Figure 17: A simulation of a separated
quark anti-quark pair in QCD.
Figure 18: A simulation a separated
baryon state in QCD.
described above As we have seen, happily the magnetic flux carried by a single vortex
coincides with the magnetic flux emitted by a single Dirac monopole. The energy cost
in separating the monopole and anti-monopole by a distance r is now
V (r) = r
where is the energy per unit length of the vortex string. In other words, inside a
superconductor, magnetic monopoles are confined!
What lesson for Yang-Mills can we take away from this? First, it seems very plausible
that the confinement of quarks in Yang-Mills is again due to the emergence of flux lines,
this time (chromo)electric rather than magnetic flux lines. However, in contrast to the
Abelian Higgs model, the Yang-Mills flux tube is not expected to arise as a semi-
classical solution of the Yang-Mills equations. Instead, the flux tube should emerge in
the strongly coupled quantum theory where one sums over many field configurations.
Indeed, such flux tubes are seen in lattice simulations where they provide dominant
contributions to the path integral. An example is shown in the figure5 .
It is less obvious how these flux tubes form between N well separated quarks which
form a baryon. Simulations suggest that the flux tubes emitted by each quarks can
join together at an N -string vertex. The picture for a well separated baryon in QCD,
with G = SU (3) gauge group, is shown in the figure.
We might also wish to take away another lesson from the superconducting story. In
the Abelian Higgs model, the electrically charged field condenses, resulting in the
confinement of monopoles. Duality then suggests that to confine electrically charged
5
These simulations were created by Derek Leinweber. You can find a host of beautiful QCD
animations on his webpage.
– 84 –objects, such as quarks, we should look to condense magnetic monopoles. This idea
smells plausible, but there has been scant progress in making it more rigorous in the
context of Yang-Mills theory. (For what it’s worth, the idea can be shown to work in
certain supersymmetric theories.) Nonetheless, it encourages us to look for magnetic
objects in non-Abelian gauge theories. We will describe these in Sections 2.6 and 2.8.
Regge Trajectories
The idea that quark anti-quark pairs are held together by flux tubes has experimental
support. Here we’ll provide a rather simplistic model of this set up. Ignoring the overall
translational motion, the energy of two, massless relativistic quarks, joined together by
a string, is given by
E =p+ r
with p = p1 p2 the relative momentum. We’ll embrace the spirit of Bohr, and require
that the angular momentum is quantised: J = pr 2 Z. We can then write the energy
as
J
E= + r
r
p
For a fixed J, this is minimized at r = J/ , which gives us the relationship between
the energy and angular momentum of the states,
E2 ⇠ J
We can now compare this to the data for hadrons.
A plot of the mass2 vs spin is known as a Chew-
Frautschi plot. It is shown on the right for light vec-
tor mesons6 . We see that families of meson and their
resonances do indeed sit on nice straight lines, re-
ferred to as Regge trajectories. The slope of the lines
is determined by the QCD string tension, which
turns out to be around
⇠ 1.2 GeV 2 . Perhaps
more surprisingly, the data also reveals nice straight
Regge trajectories in the baryon sector.
Figure 19:
2.5.3 Wilson Loops Revisited
Above we identified two different possible phases of Yang-Mills theory: the Coulomb
phase and the confining phase. The difference between them lies in the forces experi-
enced by two well-separated probe particles.
6
This plot was taken from the paper by D. Ebert, R. Faustov and V. Galkin, arXiv:0903.5183.
– 85 –• Coulomb: V (r) ⇠ 1/r
• Confining: V (r) ⇠ r
To this, we could add a third possibility that occurs when the gauge field is Higgsed,
so that electric charges are completely screened. In this case we have
• Higgs: V (r) ⇠ constant
We’ll discuss this phase more in Section 2.7.3.
Usually in a quantum field theory (or in a statistical field theory) we identify the
phase by computing the expectation value of some order parameter. The question that
we would like to ask here is: what is the order parameter for confinement?
To answer this, we can rephrase our earlier discussion in terms of the path integral.
To orient ourselves, let’s first return to Maxwell theory. If we want to compute the path
integral in the presence of an electrically charged probe particle, we simply introduce
the particle by its associated current J μ , which now acts as a source. We then add to
the action the term Aμ J μ . Moreover, for a probe particle which moves along a worldline
C, the current J is a delta-function
localised on C. We then compute the partition
H
i CA
function with the insertion e
,
✓ I ◆E Z
✓ I ◆
D
exp i A
= DA exp i A eiSMaxwell
(2.73)
C
C
where we’re being a little sloppy on the right-hand-side, omitting both gauge fixing
terms and the normalisation factor coming from the denominator.
In Yang-Mills, there is a similar story. The only difference is that we can’t just
stipulate a fixed current J μ because the term Aμ J μ is not gauge invariant. Instead, we
must introduce some internal colour degrees of freedom for the quark, as we described
previously in Section 2.1.3. As we saw, integrating over these colour degrees of freedom
leaves us with the Wilson loop W [C], which we take in the fundamental representation
✓ I ◆
W [C] = tr P exp i A
Performing the further path integral over the gauge fields A leaves us with the expec-
tation value of this Wilson loop
✓ I ◆
D
E Z
W [C] = DA tr P exp i A eiSY M
(2.74)
C
– 86 –Now consider the specific closed loop C shown in the figure. We again take this to sit in
the fundamental representation. It has the interpretation that we create a quark anti-
quark pair, separated by a distance r, at some time in the past. These then propagate
forward for time T , before they annihilate back to the vacuum.
What behaviour would we expect from the expectation value
hW [C]i? We’ll work in Euclidean space. Recall from our earlier lec-
tures on quantum field theory that, for long times, the path integral
projects the system onto the lowest energy state. Before the quarks
appear, and after they’ve gone, this is the ground state of the system
which we can take to have energy zero. (Actually, you can take it
to have any energy you like; its contribution will disappear from our
analysis when we divide by the normalisation factor that missing on
the right-hand-side of (2.73) and (2.74).) However, in the presence
of the sources, the ground state of the system has energy V (r). This
means that we expect the Euclidean path integral to give
D
E
lim W [C] ⇠ e V (r)T
r
T
Figure 20:
r,T !1
This now gives us a way to test for the existence of the confining the phase directly in
Yang-Mills theory. If the theory lies in the confining phase, we should find
D
E
lim W [C] ⇠ e A[C]
(2.75)
r,T !1
where A[C] is the area of the the loop C. This is known as the area law criterion for
confinement. We won’t be able to prove that Wilson loops in Yang-Mills exhibit an
area law, although we’ll offer an attempt in Section 4.2 when we discuss the strong
coupling expansion of lattice gauge theory. We will have more success in Section 7 and
8 when we demonstrate confinement in lower dimensional gauge theories.
If a theory does not lie in the confining phase, we get different behaviour for the
Wilson loop. For example, we could add scalar fields which condense and completely
break the gauge symmetry. This is the Higgs phase, and we will discuss it in more
detail in Section 2.7 where we first introduce dynamical matter fields. In the Higgs
phase, we have
D
E
lim W [C] ⇠ e μL
r,T !1
where L = 2(r + T ) is the perimeter of the loop and μ is some mass scale associated
to the energy in the fields that screen the particle. This kind of perimeter law is
characteristic of the screening phase of a theory.
– 87 –Wilson Loops as Operators
There is a slightly different perspective on Wilson loops that will also prove useful: we
can view them as operators on the Hilbert space of states. Since we are now dealing
with Hilbert spaces and states, it’s important that we are back in Lorentzian signature.
In quantum field theory, states are defined as living on a spacelike slice of the system.
For this reason, we should first rotate our Wilson loop so that C is a spacelike, closed
curve, sitting at a fixed point in time. The interpretation of the operator W [C] is
that it adds to the state a loop of electric flux along C. To see this, we can again
revert to the canonical formalism that we introduced in Section 2.2. The electric field
is E i = i / Ai (x), so we have
i
E W [C] = tr P
✓
Ai (x)
I
A W [C]
C
◆
which indeed has support only on C.
The expectation value hW [C]i is now interpreted as the amplitude for a loop of
electric flux W [C]|0i to annihilate to the vacuum h0|. In the confining phase, this is
unlikely because the flux tube is locally stable. The flux tube can, of course, shrink
over time and disappear, but that’s not what hW [C]i is measuring. Instead, it’s looking
for the amplitude that the flux tube instantaneously disappears. This can happen only
through a tunnelling effect which, in Euclidean space, involves a string stretched across
the flux tube acting. This Euclidean action of this string is proportional to its area,
again giving hW [C]i ⇠ e A with A[C] the minimal area bounding the curve.
In contrast, in the Higgs phase the string is locally unstable. Each part of the
string can split into pieces and dissolve away. This is still unlikely: after all, it has to
happen at all parts of the string simultaneously. Nonetheless, it is more likely than the
corresponding process in the confining phase, and this is reflected in the perimeter law
hW [C]i ⇠ e μL .
2.6 Magnetic Probes
Much of our modern understanding of gauge theories comes from the interplay between
electric and magnetic degrees of freedom. In the previous section we explored how Yang-
Mills fields respond to electric probes. In this section, we will ask how they respond to
magnetic probes.
– 88 –A warning: the material in this section is a little more advanced than what we covered
until now and won’t be required for much of what follows. (An exception is Section 3.6
which discusses discrete anomalies and builds on the machinery we develop here.) In
particular, sections 2.7 and 2.8 can both be read without reference to this section.
2.6.1 ’t Hooft Lines
Our first task is to understand how to construct an operator that corresponds to the
insertion of a magnetic monopole. These are referred to as ’t Hooft lines. For electric
probes, we could build the corresponding Wilson line out of local fields Aμ . But there
are no such fields that couple to magnetic charges. This means that we need to find a
different way to describe the magnetic probes.
We will achieve this by insisting that the fields of the theory have a prescribed singular
behaviour on a given locus which, in our case, will be a line C in spacetime. Because
such operators disrupt the other fields in the theory, they are sometimes referred to as
disorder operators.
’t Hooft Lines in Electromagnetism
To illustrate this idea, we first describe ’t Hooft lines in U (1) electromagnetism. We
have already encountered magnetic monopoles in Section 1.1. Suppose that a monopole
of charge m traces out a worldline C in R3,1 . (We referred to magnetic charge as g in
Section 1.1, but this is now reserved for the Yang-Mills coupling so we have to change
notation.) For any S2 that surrounds C, we then have
Z
B · dS = m
(2.76)
S2
We normalise the U (1) gauge field to have integer electric charges. As explained in
Section 1.1, the requirement that the monopole is compatible with these charges gives
the Dirac quantisation condition (1.3), which now reads
eim = 1
)
m 2 2⇡Z
(2.77)
For the magnetic field to carry flux (2.76), we must impose singular boundary conditions
on the gauge field. As an example, suppose that we take the line C to sit at the spatial
origin x = 0 and extend in the temporal direction t. Then, as explained in Section 1.1
we can cover the S2 by two charts. Working in polar coordinates with Ar = 0 gauge,
in the northern hemisphere, we take the gauge field to have the singular behaviour
A !
m(1 cos ✓)
2r sin ✓
– 89 –
as r ! 0There is a similar condition (1.7) in the southern hemisphere, related by a gauge trans-
formation.
We now define the ’t Hooft line T [C] by requiring that we take the path integral only
over fields subject to the requirement that they satisfy (2.76) on C. This is a rather
unusual definition of an “operator” in quantum field theory. Nonetheless, despite its
unfamiliarity, , we can – at least in principle – use to compute correlation functions of
T [C] with other, more traditional operators.
’t Hooft Lines in Yang-Mills
What’s the analogous object in Yang-Mills theory with gauge group G. To explain the
generalisation of Dirac quantisation to an arbitrary, semi-simple Lie group we need to
invoke a little bit of Lie algebra-ology that was covered in the Symmetries and Particles
course.
We work with a Lie algebra g. We denote the Cartan sub-algebra as H ⇢ g. Recall
that this is a set of r mutually commuting generators, where r is the rank of the Lie
algebra. Throughout the rest of this section, bold (and not silly gothic) font will denote
an r-dimensional vector.
We again define a ’t Hooft line for a timelike curve C sitting at the origin. We will
require that the magnetic field B i , i = 1, 2, 3, takes the form
Bi !
xi
Q(x) as r ! 0
4⇡r3
where Q(x) is a Lie algebra valued object which specifies the magnetic charge of the
’t Hooft line. Spherical symmetry requires that Q(x) be covariantly constant. We can
again cover the S2 with two charts, and in each pick Q(x) to be a constant which, by
a suitable gauge transformation, we take to sit in the Cartan subalgebra. We write
Q=m·H
for some r-dimensional vector m which determines the magnetic charge. We can think
of this as r Dirac monopoles, embedded in the Cartan subalgebra.
The requirement that the ’t Hooft lines are consistent in the presence of Wilson lines
gives the generalised Dirac quantisation condition,
exp (im · H) = 1
(2.78)
The twist is that this must hold for all representations of the Lie algebra. To see why
this requirement affects the allowed magnetic charges, consider the case of G = SU (2).
– 90 –We can pick a U (1) ⇢ SU (2) in which we embed a Dirac monopole of charge m. The
W-bosons have electric charge q = ±1 and are consistent with a ’t Hooft line of charge
m = 2⇡. However, our ’t Hooft line should also be consistent with the insertion of a
Wilson line in the fundamental representation, and this carries charge q = ±1/2. This
means that, for G = SU (2), the ’t Hooft line must carry m = 2, twice the charge of
the simplest Dirac monopole.
To extend this to a general group and representation, we need the concept of weights.
Given a d dimensional representation, |μa i with a = 1, . . . , d of g, we may introduce a
set of weights, which are the eigenvalues
H|μa i = μa |μa i
(2.79)
All such weights span the weight lattice ⇤w (g).
The weights of the adjoint representation are special and are referred to as roots.
Recall that these roots ff can be used to label the other generators of the Lie algebra,
which are denoted as Eff . In the adjoint representation, the eigenvalue condition (2.79)
becomes the commutation relation [H, Eff ] = ffEff . Importantly, the roots also span
a lattice
⇤root (g) ⇢ ⇤w (g)
The weights and roots have the property that
ff·μ 1
2 Z
ff2
2
for all μ 2 ⇤w (g) and ff 2 ⇤root (g). This is exactly what we need to solve the Dirac
quantisation condition (2.78), which becomes m · μ 2 2⇡Z for all μ 2 ⇤w (g). We define
the co-root
2ff
ff_ = 2
ff
These co-roots also span a lattice, which we call ⇤co root (g). Clearly, we have ff_ ·μ 2 Z
for all ff_ 2 ⇤co root (g) and μ 2 ⇤w (g). If the magnetic charge vector sits in the co-root
lattice, then the Dirac quantisation condition is obeyed. More generally, it turns out
that for simply connected groups we have
m 2 2⇡ ⇤co root (g)
(2.80)
This is sometimes referred to as the Goddard-Nuyts-Olive (or GNO) quantisation con-
dition. We will look at the possible magnetic charges for non-simply connected groups
shortly.
– 91 –There is one last part of this story. The co-root lattice can be viewed as the root
lattice for a Lie algebra g_ , so that ⇤co root (g) = ⇤root (g_ ) For simply laced algebras
(these are the ADE series, and so includes su(N )), all roots have the same length and
are normalised to ff2 = 2. In this case, the roots and co-roots are the same and g_ = g.
For non-simply laced groups, the long and short roots get exchanged. This means that,
for example, so(2N + 1)_ = sp(N ) and sp(N )_ = so(2n + 1).
2.6.2 SU (N ) vs SU (N )/ZN
There seems to be something of an imbalance between the Wilson line operators and
the ’t Hooft line operators. Of course, these electric and magnetic probes are defined
in rather different ways, but that’s not our concern. Instead, it’s slightly disconcerting
that there are more Wilson line operators than ’t Hooft line operators. This is because
Wilson line operators are labelled by representations R which, in turn, are associated to
elements of the weight lattice ⇤w (g). In contrast, ’t Hooft lines are labelled by elements
of ⇤root (g_ ) which is a subset of ⇤w (g_ ). Roughly speaking, this means that Wilson
lines can sit in any representation, including the fundamental, while ’t Hooft lines can
only sit in representations that arise from tensor products of the adjoint. Why?
To better understand the allowed magnetic probes, we need to look more closely
at the global topology of the gauge group. We will focus on pure Yang-Mills with
G = SU (N ). Because the gauge bosons live in the adjoint representation, they are
blind to any transformation which sits in the centre ZN ⇢ SU (N ),
n
o
ZN = e2⇡ikN , k = 0, 1, . . . , N 1
The gauge bosons do not transform under this centre ZN subgroup. In the older
literature, it is sometimes claimed that the correct gauge group of Yang-Mills is actually
SU (N )/ZN . But this is a bit too fast. In fact, the right way to proceed is to understand
that there are two different Yang-Mills theories, defined by the choice of gauge group
G = SU (N ) or G = SU (N )/ZN
Indeed, more generally we have a different theory with gauge group G = SU (N )/Zp
for any Zp subgroup of ZN . The difference between these theories is rather subtle. We
can’t distinguish them by looking at the action, since this depends only on the shared
su(N ) Lie algebra. Moreover, this means that the correlation functions of all local
operators are the same in the two theories so you don’t get to tell the difference by
doing any local experiments. Nonetheless, different they are. The first place this shows
up is in the kinds of operators that we can use to probe the theory.
– 92 –Zm
Zm
Ze
Ze
Figure 21: The figure on the left shows that allowed Wilson and ’t Hooft lines (in green)
for the gauge group SU (3). The figure on the right shows the allowed lines for gauge group
SU (3)/Z3 .
Let’s start with the Wilson lines. As we saw in Section 2.5, these are labelled by
a representation of the group. The representations of G = SU (N )/ZN are a subset
of those of G = SU (N ); any representation that transforms non-trivially under ZN
is prohibited. This limits the allowed Wilson lines. In particular, the theory with
G = SU (N )/ZN does not admit the Wilson line in the fundamental representation,
but Wilson lines in the adjoint representation are allowed. Similarly, the theory with
gauge group G = SU (N )/ZN cannot be coupled to fundamental matter; it can be
coupled to adjoint matter.
This has a nice description in terms of the lattices that we introduced. For G =
SU (N ), the representations are labelled by the weight lattice ⇤w (g). (The precise
statement is that there is a one-to-one correspondence between representations and
⇤w (g)/W where W is the Weyl group.) However, for G = SU (N )/ZN , the representa-
tions are labelled by the root lattice ⇤root (g). Indeed, the difference between the weight
and root lattice for g = su(N ) is precisely the centre,
⇤w (g)/⇤root (g) = ZN
Now we come to the ’t Hooft lines. When we introduced ’t Hooft lines in the previous
section, we were implicitly working with the universal cover of the gauge group, so
that all possible Wilson lines were allowed. The requirement that magnetic charges are
compatible with all representations and, in particular, the fundamental representation,
resulted in the GNO condition (2.80) in which ’t Hooft lines are labelled by ⇤root (g).
But what if we work with G = SU (N )/ZN ? Now we have fewer Wilson lines, and so
the demands of Dirac quantisation are less onerous. Correspondingly, in this theory
the ’t Hooft lines are labelled by ⇤w (g).
– 93 –We can summarise the situation by labelling any line operator by a pair of integers
(z e , z m ) 2 ZeN ⇥ Zm
N
(2.81)
These describe how a given line operator transforms under the electric and magnetic
centres of the group. If we have two line operators, labelled by (z e , z m ) and (z 0 e , z 0 m )
then Dirac quantisation requires z e z 0 m z m z 0 e = 0 mod N . Note the similarity with
the quantisation condition on dyons (1.4) that we met earlier.
For gauge group G = SU (N ), the line operators are labelled by (z e , 0) with z e =
0, . . . , N 1. Note that this doesn’t mean that there are no magnetically charged ’t
Hooft lines: just that these lines sit in the root lattice and so have z m = 0 mod N .
In contrast, for G = SU (N )/ZN the line operators are labelled by (0, z m ) with
z m = 0, . . . , N 1. This time the Wilson lines must transform trivially under the
centre of the group, so z e = 0 mod N . The resulting line operators for G = SU (3) and
G = SU (3)/Z3 are shown in Figure 21. Yang-Mills with G = SU (N ) has more Wilson
lines; Yang-Mills with G = SU (N )/ZN has more ’t Hooft lines.
There is a slightly more sophisticated way of describing these different line operators
using the idea of generalised symmetries. We postpone this discussion until Section 3.6
where we will find an application in discrete anomalies.
The Theta Angle and the Witten Effect
The Witten effect gives rise to an interesting interplay between ’t Hooft lines and the
theta angle of Yang-Mills. Recall from Section 1.2.3, that a Dirac monopole of charge
m in Maxwell theory picks up an electric charge proportional to the ✓ angle, given by
q=
✓m
2⇡
This analysis carries over to ’t Hooft lines in both Maxwell and Yang-Mills theories.
In the latter case, a shift of ✓ ! ✓ + 2⇡ changes the electric charge carried by a line
operator,
✓ ! ✓ + 2⇡
)
(z e , z m ) ! (z e + z m , z m )
For G = SU (N ), this maps the spectrum of line operators back to itself. However,
for G = SU (N )/ZN there is something of a surprise, because after a shift by 2⇡, the
spectrum of line operators changes. This is shown in Figure 22 for G = SU (3)/ZN . We
learn that the theory is not invariant under a shift of ✓ ! ✓ + 2⇡. Instead, to return to
– 94 –Zm
Zm
Zm
Ze
Ze
Ze
Figure 22: The spectrum of dyonic line operators in gauge group SU (3)/Z3 , shown for ✓ = 0
(on the left), ✓ = 2⇡ (in the middle) and ✓ = 4⇡ (on the right).
our original theory, with the same line operators, we must send ✓ ! ✓ + 2⇡N . In other
words,
G = SU (N ) has ✓ 2 [0, 2⇡)
G = SU (N )/ZN has ✓ 2 [0, 2⇡N )
,
We’ll explore some consequences of this in Section 3.6 when we discuss anomalies in
discrete symmetries.
One of the arguments we gave in Section 2.2 for the periodicity ✓ 2 [0, 2⇡) was the
R
appropriate quantisation of the topological charge d4 x tr ?F μ⌫ Fμ⌫ . Instantons provide
solutions to the equations of motion with non-vanishing topological charge. For Yang-
Mills with G = SU (N )/ZN , the enlarged range of ✓ suggests that there might be
“fractional instantons”, configurations that carry 1/N th the charge of an instanton.
In fact, there are no such non-singular configurations on R4 . But these fractional
instantons do arise on manifolds with non-trivial topology. For example, if we take
Euclidean spacetime to be T4 , we can impose twisted boundary conditions in which,
upon going around any circle, gauge fields come back to themselves up to a gauge
transformation which lies in the centre ZN . Such boundary conditions are allowed for
gauge group G = SU (N )/ZN , but not for G = SU (N ). One can show that these
classes of configurations carry the requisite fractional topological charge.
’t Hooft Lines as Order Parameters
One of the primary motivations for introducing line operators is to find order parameters
that will distinguish between different phases of the theory. When G = SU (N ) we
have the full compliment of Wilson lines. As we saw in Section 2.5, an area law for the
fundamental Wilson loop signals that the theory lies in the confining phase, which is
– 95 –the expected behaviour for pure Yang-Mills. If we also add scalar fields to the theory,
these could condense so that we sit in the Higgs phase; in this case the Wilson loop
exhibits a perimeter law.
If the gauge group is G = SU (N )/ZN , we no longer have the fundamental Wilson
line at our disposal. Instead, we have the fundamental ’t Hooft line with z m = 1,
and this now acts as our order parameter. Since the local dynamics is independent of
the global topology of the gauge group, pure Yang-Mills theory is again expected to
confine. But, as in our discussion of superconductors in Section 2.5.2, the confinement
of electric charge is equivalent to the screening of magnetic charge. This means that
the signature of electric confinement is now a perimeter law for the ’t Hooft line.
We can also consider G = SU (N )/ZN Yang-Mills in the Higgs phase. The theory
does not admit scalar fields in the fundamental representation, so we introduce adjoint
scalars which subsequently condense. A single adjoint scalar will break the gauge
group to its maximal torus, U (1)N 1 , but with two misaligned adjoint Higgs fields we
can break the gauge symmetry completely. This is the Higgs phase. As described in
Section 2.5.2, the Higgs phase can be thought of as confinement of magnetic charges.
Correspondingly, the ’t Hooft line now exhibits an area law.
That’s All Well and Good, but...
The difference between Yang-Mills with G = SU (N ) and G = SU (N )/ZN seems rather
formal. As we mentioned above, all correlation functions of local operators in the two
theories coincide, which means that any local experiment that we can perform will
agree. The theories only differ in the kinds of non-local probes that we can introduce.
You might wonder whether this is some pointless intellectual exercise.
If we consider Yang-Mills on flat R3,1 , then there is some justification in ignoring
these subtleties: the physics of the two theories is the same, and we’re just changing
the way we choose to describe it. However, even in this case these subtleties will help
us say something non-trivial about the dynamics as we will see in Section 3.6 when we
discuss discrete anomalies.
The real differences between the two theories arise when we study them on back-
ground manifolds with non-trivial topology. Here the two theories can have genuinely
different dynamics. Perhaps the most straightforward case arises for Yang-Mills coupled
to a single, massless adjoint Weyl fermion. This theory turns out to have supersym-
metry and goes by the name of N = 1 super Yang-Mills. Although supersymmetry is
beyond the scope of these lectures, it turns out that it provides enough of a handle for
– 96 –us to make quantitative statements about their dynamics. If we consider these theories
on spacetime R2,1 ⇥ S1 , the low energy dynamics, specifically the number of ground
states, does depend on the global topology of the gauge group.
2.6.3 What is the Gauge Group of the Standard Model?
We all know the answer to the question in the heading. The gauge group of the Standard
Model is
G = U (1)Y ⇥ SU (2) ⇥ SU (3)
Or is it?
The fermions in a single generation sit in the following representations of G,
Leptons: lL : (2, 1) 3
eR : (1, 1) 6
Quarks:
qL : (2, 3)+1
uR : (1, 3)+4
dR : (1, 3) 2
)(z2e , z3e )Y = (1, 0) 3
)(z2e , z3e )Y = (1, 1)+1
)(z2e , z3e )Y = (0, 1) 2
)(z2e , z3e )Y = (0, 0) 6
)(z2e , z3e )Y = (0, 1)+4
where the subscript denotes U (1)Y hypercharge Y , normalised so that Y 2 Z. We could
add to this the right-handed neutrino ⌫R which is a gauge singlet. In the table above,
we have also written the charges z2e and z3e under the Z2 ⇥ Z3 centre of SU (2) ⇥ SU (3).
Finally, the Higgs boson sits in the representation (2, 1)3 ) (z2e , z3e )Y = (1, 0)3 .
Each of these representations has the property that
Y = 3z2e
2z3e mod 6
This means that there is a Z6 subgroup of G = U (1)Y ⇥ SU (2) ⇥ SU (3) under which
all the fields are invariant: we must simultaneously act with the Z6 = Z2 ⇥ Z3 centre
of SU (2) ⇥ SU (3), together with a Z6 ⇢ U (1)Y . Because nothing transforms under
this Z6 subgroup, you can sometimes read in the literature that the true gauge group
of the Standard Model is
U (1)Y ⇥ SU (2) ⇥ SU (3)
G=
(2.82)
where = Z6 . But this is also too fast. The correct statement is that there is a fourfold
ambiguity in the gauge group of the Standard Model: it takes the form (2.82), where
is a subgroup of Z6 , i.e.
= 1, Z2 , Z3 , or Z6
We note in passing that we can embed the Standard Model in a grand unified group,
such as SU (5) or Spin(10), only if = Z6 .
– 97 –As we mentioned above, the choice of does not affect any local correlations functions
and, in particular, does not affect physics at the LHC. Nonetheless, each choice of
defines a different theory and, in principle, the distinction could have observable
consequences. One place that the difference in shows up is in the magnetic sector.
Previously we discussed the allowed ’t Hooft lines. However, there is a folk theorem that
when a quantum field theory is coupled to gravity then any allowed electric or magnetic
charge has a realisation as a physical state. In other words, particles (or groups of
particles) should exist with each of the allowed electric and magnetic charges.We’ll
see in Section 2.8 how magnetic monopoles can arise as dynamical particles in a non-
Abelian gauge theory.
The arguments for this are far from rigorous and, for magnetic charges, boil down to
the fact that an attempt to define an infinitely thin ’t Hooft line in a theory coupled
to gravity will result in a black hole. If we now let this black hole evaporate, and insist
that there are no remnants, then it should spit out a particle with the desired magnetic
charge.
So what magnetic monopoles are allowed for each choice of ? First, let’s recall how
electromagnetism arises from the Standard Model. The electromagnetic charge q of
any particle is related to the hypercharge Y and the SU (2) charge ⌧ 3 by
q=
Y
+ ⌧3
6
This gives us the familiar electric charges: for the electron q =
q = +2/3; and for the down quark q = 1/3.
1; for the up quark
We denote the magnetic charge under U (1)Y as mY . As we explained in Section 2.5.2,
when a Higgs field condenses, many of the magnetically charged states are confined. In
the Standard Model, those that survive must have
6mY
= z2m mod 2
2⇡
The magnetic charge under U (1)Y and SU (2) then conspires so that these states are
blind to the Higgs field. For such states, the resulting magnetic charge under electro-
magnetism is
m = 6mY
Now we’re in a position to see the how the global structure of the gauge group affects
the allowed monopole charge. Suppose that we take = 1. Here, the monopoles must
– 98 –obey the Dirac quantisation condition with respect to each gauge group individually.
This means that mY 2 2⇡Z, and so the magnetic charge of any particle is quantised
as m 2 12⇡Z. This is six times greater than the magnetic charge envisaged by Dirac.
Of course, Dirac only knew about the existence of the electron with charge q = 1. The
quarks, together with the structure of the electroweak force, impose a more stringent
constraint.
In contrast, if = Z6 , more magnetic charges are allowed. This is entirely analogous
to the situation that we saw in the previous section. The Dirac quantisation condition
now imposes a single constraint on the combined gauge charges from each factor of the
gauge group,
6Y mY
3z2e z2m + 2z3e z3m
2 6Z
2⇡
But this gives us more flexibility. Now we are allowed a magnetic monopole with
mY = 16 ⇥ 2⇡ provided that it also carries a magnetic charge under the other groups,
z2m = 1 and z3m = 1. In other words, the Standard Model with
= Z6 admits
the kind of magnetic monopole that Dirac would have expected, with m = 2⇡. Of
course, this obeys Dirac quantisation with respect to the electron. But it also obeys
Dirac quantisation with respect to the fractionally charged quarks because it carries a
compensating non-Abelian magnetic charge.
2.7 Dynamical Matter
Until now, we have (mostly) focussed on pure Yang-Mills, without any additional,
dynamical matter fields. It’s time to remedy this. We will consider coupling either
scalar fields, , or Dirac spinors to Yang-Mills.
Each matter field must transform in a representation R of the gauge group G. In
the Lagrangian, the information about our chosen representation is often buried in the
covariant derivative, which reads
Dμ = @ μ
iAaμ T a (R)
where T a (R) are the generators of the Lie algebra in the representation R. For scalar
fields, the action is
Z
Sscalar = d4 x Dμ † Dμ
V( )
where V ( ) can include both mass terms and 4 interactions. For spinors, the action
is
Z
/
Sfermion = d4 x i  ̄D
m ̄
– 99 –If we have both scalars and fermions then we can also include Yukawa interactions
between them.
Our ultimate goal is to understand the physics described by non-Abelian gauge the-
ories coupled to matter. What is the spectrum of excitations of these theories? How do
these excitations interact with other? How does the system respond to various probes
and sources? In this section, we will start to explore this physics.
2.7.1 The Beta Function Revisited
The first question we will ask is: how does the presence of these matter degrees of
freedom affect the running of the gauge coupling g 2 (μ)? This is simplest to answer for
massless scalars and fermions. Suppose that we have Ns scalars in a representation
Rs and Nf Dirac fermions in a representation Rf . The 1-loop running of the gauge
coupling is

✓ 2 ◆
1
1
1
11
1
4
⇤U V
= 2
I(adj)
Ns I(Rs )
Nf I(Rf ) log
(2.83)
2
2
g (μ)
g0 (4⇡)
3
3
3
μ2
This generalises the Yang-Mills beta function (2.56). Recall that the Dynkin indices
I(R) are group theoretic factors defined by the trace normalisations,
tr T a (R)T b (R) = I(R) ab
and we are working in the convention in which I(F ) = 12 for the fundamental (or
minimal) representation of any group.
When a field has mass m, it contributes the running of the coupling only at scales
μ > m, and decouples when μ < m. There is a smooth crossover from one behaviour to
the other at scales μ ⇠ m, but the details of this will not be needed in these lectures.
Here we will briefly sketch the derivation of the running of the coupling, following
Section 2.4.2. We will then look at some of the consequences of this result.
The Beta Function for Scalars
If we integrate out a massless, complex scalar field, we get a contribution to the effective
action for the gauge field given by
Z
1
Seff [A] = 2 d4 x trFμ⌫ F μ⌫ + Tr log( D2 )
2g
But this is something we’ve computed before, since it is the same as the ghost contri-
bution to the effective action. The only differences are that we get a plus sign instead
– 100 –of a minus sign, because our scalars are the sensible kind that obey spin statistics,
and that we pick up the relevant trace coefficient I(R), as opposed to I(adj) for the
ghosts. We can then immediately import our results from Section 2.4.2 to get the scalar
contribution in (2.83)
The Beta Function for Fermions
If we integrate out a massless Dirac fermion, we get a contribution to the effective
action for the gauge field given by
Z
1
/
Seff [A] = 2 d4 x trFμ⌫ F μ⌫ log det(iD)
2g
To compute the determinant, it’s useful to expand as
/ = det 1/2 ( μ ⌫ Dμ D⌫ )
det(iD)
⇣
1 μ
1/2 1
= det
{ μ , ⌫ }Dμ D⌫
[ ,
2
2
⇣
⌘
i μ ⌫
1/2
2
= det
D + [ , ]Fμ⌫
4
⌫
]Dμ D⌫
⌘
where, to go to the final line, we have used both the Clifford algebra { μ , ⌫ } = 2 μ⌫ ,
as well as the fact that [Dμ , D⌫ ] = iFμ⌫ . The contribution to the effective action is
then
⇣
⌘
1
i
/ =
log det(iD)
Tr log
D2 14 + [ μ , ⌫ ]Fμ⌫
2
4
2
μ
= 2Tr log( D ) + [ , ⌫ ]Fμ⌫ terms
Here the 12 has changed into a 2 after tracing over the spinor indices. We’re left
having to compute the contribution from the [ μ , ⌫ ]Fμ⌫ terms. This is very similar in
spirit to the extra term that we had to compute for the gauge fluctuations in Section
2.4.2. However, the difference in spin structure means that it differs from the gauge
contribution by a factor of 1/2. The upshot is that we have

✓ 2 ◆
Z
⇥
⇤ μ ⌫
1 4
T (R)
d4 k
⇤U V
2 μ⌫
/ =
log det(iD)
4
tr Āμ (k)Ā⌫ ( k) (k k
k
) log
2
4
2 3
(4⇡)
(2⇡)
k2
which gives the fermionic contribution to the running of the gauge coupling in (2.83).
Note that, once again, contributions from the extra spin term (the 4) overwhelm
the contribution from the kinetic term (the +4/3). But, because we are dealing with
fermions, there is an overall minus sign. This means that fermions, like scalars, give a
positive contribution to the beta function.
– 101 –2.7.2 The Infra-Red Phases of QCD-like Theories
We will start by ignoring the scalars and considering non-Abelian gauge theories coupled
to fermions. In many ways, this is the most subtle and interesting class of quantum field
theories and we will devote Sections 3 and 5 to elucidating some of their properties.
Here we start by giving a brief tour of what is expected from these theories.
Obviously, there are many gauge groups and representations that we could pick. We
will restrict ourselves to gauge group SU (Nc ), where Nc is referred to as the number
of colours. We will couple to this gauge field Nf Dirac fermions, each transforming
in the fundamental representation of the gauge group. Here Nf is referred to as the
number of flavours. We will further take the fermions to be massless, although we
will comment briefly on what happens as they are given masses. This class of theories
will be sufficient to exhibit many of the interesting phenomena that we care about.
Moreover, this class of theories boasts QCD as one of its members (admittedly you
should relax the massless nature of the quarks just a little bit.)
At one-loop, the running of the gauge coupling can be read off from (2.83)

1
11Nc
2
(4⇡)
3
1
1
= 2
2
g (μ)
g0
2Nf
log
3
✓
⇤2U V
μ2
◆
(2.84)
These theories exhibit different dynamics depending on the ratio Nf /Nc .
The Infra-Red Free Phase
Life is simplest when Nf > 11Nc /2. In this case, the contribution to the beta function
from the matter overwhelms the contribution from the gauge bosons, and the coupling
g 2 becomes weaker as we flow towards the infra-red. Such theories are said to be
infra-red free. This means that, for once, we can trust the classical description at low
energies, where we have weakly coupled massless gauge bosons and fermions.
The force between external, probe electric charges takes the form
Velectric (r) ⇠
1
r log(r⇤U V )
which is Coulombesque, but dressed with the extra log term which comes from the
running of the gauge coupling. This is the same kind of behaviour that we would get
in (massless) QED. Meanwhile, the potential between two external magnetic charges
takes the form
Vmagnetic ⇠
log(r⇤U V )
r
– 102 –The log in the numerator reflects the fact that magnetic charges experience a force
proportional to 1/g 2 rather than g 2 .
When Nf = 11Nc /2, the one-loop beta function vanishes. To see the fate of the
theory, we must turn to the two-loop beta function which we discuss below. It will
turn out that the theory is again infra-red free.
These theories are ill-defined in the UV, where there is a Landau pole. However, it’s
quite possible that theories of these types arise as the low-energy limit of other theories.
The Conformal Window
Next, consider Nf just below 11Nc /2. To understand the behaviour of the theory, we
can look at the two-loop contribution to the beta function,
(g) = μ
dg
=
dμ
0g
3
+
1g
5
+ ...
with the one-loop beta function extracted from (2.84)
✓
◆
1
11Nc 2Nf
+
0 =
(4⇡)2
3
3
We won’t compute the two-loop beta function here, but just state the result:
✓
◆
1
34Nc2 Nf (Nc2 1) 10Nf Nc
+
+
1 =
(16⇡ 2 )2
3
Nc
3
Note that 1 > 0 as long as the number of flavours sits in the range Nf < 34Nc3 /(13Nc2
3). But 0 < 0 provided Nf < 11Nc /2 and so we can play the one-loop beta function
against the two-loop beta function, to find a non-trivial fixed point of the RG flow, at
which (g? ) = 0. This is given by
g?2 =
0
1
Importantly, for Nf /Nc = 11/2 ✏, with ✏ small, we have g?2 ⌧ 1 and the analysis above
can be trusted. We learn that the low-energy physics is described by a weakly coupled
field theory which, as a fixed point of RG, is invariant under scale transformations.
This is known as the Banks-Zaks fixed point. There is a general expectation (although
not yet a complete proof) that relativistic theories in d = 3+1 which are scale invariant
are also invariant under a larger conformal symmetry.
– 103 –At any such fixed point, the scale invariance is enough to ensure that both external
magnetic and electric probes experience a Coulomb force
V (r) ⇠
1
r
Such a phase could be described as a non-Abelian Coulomb phase, comprised of massless
gluons and fermions.
What happens if we now lower Nf with fixed Nc ? The formal result above says
that the fixed point remains (at least until Nf ⇡ 34Nc3 /(13Nc2 3) but the value of
the coupling g?2 gets larger so that we can no longer trust the analysis. In general, we
expect there to be a conformal fixed point for
N? < Nf <
11Nc
2
(2.85)
for some critical value N? . This range of Nf is referred to as the conformal window.
The obvious question is: what is the value of N? ?
We don’t currently know the answer to this question. At the lower end of the
conformal window, the theory is necessarily strongly coupled which makes it difficult
to get a handle on the physics. There is evidence from numerical work that when
Nc = 3 (which is the case for QCD) then the lower end of the conformal window sits
somewhere in the window N? 2 [8, 12], and probably closer to the middle than the
edges. One would also expect the conformal to scale with Nc , so one could guess that
N? ⇡ 3Nc to 4Nc . There are various arguments that give values of N? in this range,
but none of them are particularly trustworthy.
We’ve seen that there are a set of conformal fixed point, labelled by Nc and Nf in
the range (2.85). We met such fixed points before in the course on Statistical Field
Theory. In that context, we came across the powerful idea of universality: many
different ultra-violet theories all flow to the same fixed point. This is responsible for
the observation that all gases, regardless of their microscopic make-up, have exactly
the same divergence in the heat capacity at their critical point. We could ask: is there
a form of universality in gauge theories? In other words, can we write down two gauge
theories which look very different in the ultra-violet, but nonetheless flow to the same
infra-red fixed point?
We don’t yet know of any examples of such universality in the QCD-like gauge theo-
ries that we discuss in these lectures, although this is most likely due to our ignorance.
However, such examples are known in supersymmetric theories, which consist of gauge
– 104 –fields, scalars and fermions interacting with specific couplings. In that context, it is
known that supersymmetric SU (Nc ) gauge theories coupled to Nf fundamental flavours
flows to the same fixed point as SU (Nf Nc ) gauge theory coupled to Nf flavours.
(The latter flavours should also be a coupled to a bunch of gauge neutral fields.) Fur-
thermore, the two descriptions can be identified as electric and magnetic variables for
the system. This phenomenon is known as Seiberg duality. However, it is a topic for a
different course.
Confinement and Chiral Symmetry Breaking
What happens when Nf  N? and we are no longer in the conformal window? The
expectation is that for Nf < N? the coupling is once again strong enough to lead to
confinement, in the sense that all finite energy excitations are gauge singlets.
Most of the degrees of freedom will become gapped, with a mass that is set paramet-
2
rically by ⇤QCD = μe1/2 0 g (μ) . However, there do remain some massless modes. These
occur because of the formation of a vacuum condensate
h  ̄i j i ⇠
i, j = 1, . . . , Nf
ij
This spontaneously breaks the global symmetry of the model, known as the chiral
symmetry. The result is once again a gapless phase, but now with the massless fields
arising as Goldstone bosons. We will have a lot to say about this phase. We will say it
in Section 5.
H
For pure Yang-Mills, we saw in Section 2.5 that a Wilson line, W [C] = tr P exp i A
in the fundamental representation provides an order parameter for the confining phase,
with the area law, hW [C]i ⇠ e A , the signature of confinement. However, in the pres-
ence of dynamical, charged fundamental matter – whether fermions or scalars – this
criterion is no longer useful. The problem is that, for a sufficiently long flux tube, it
is energetically preferable to break the string by producing a particle-anti-particle pair
from the vacuum. If the flux tube has tension and the particles have mass m, this
will occur when the length exceeds L > 2m/ . For large loops, we therefore expect
hW [C]i ⇠ e μL . This is the same behaviour that we previously argued for in the Higgs
phase. To see how they are related, we next turn to theories with scalars.
2.7.3 The Higgs vs Confining Phase
We now consider scalars. These can do something novel: they can condense and spon-
taneously break the gauge symmetry. This is the Higgs phase.
– 105 –Consider an SU (Nc ) gauge theory with Ns scalar fields transforming in the funda-
mental representation. If the scalars are massless, then the gauge coupling runs as

✓ 2 ◆
1
1
1
11Nc Ns
⇤U V
= 2
log
2
2
g (μ)
g0 (4⇡)
3
6
μ2
and, correspondingly, the coefficient of the one-loop beta function is
✓
◆
1
11Nc Ns
+
0 =
(4⇡)2
3
6
2
For Ns < 22Nc , the coupling becomes strong at an infra-red scale, ⇤QCD = ⇤U V e1/2 0 g0 .
It is thought that the theory confines and develops a gap at this scale. We expect no
massless excitations to survive.
What now happens if we give a mass m2 to the scalars? For m2 > 0, we expect these
to shift the spectrum of the theory, but not qualitatively change the physics. Indeed,
for m2
⇤2QCD , we can essentially ignore the scalars at low-energies and where we
revert to pure Yang-Mills. The real interest comes when we have m2 < 0 so that the
scalar condense. What happens then?
Suppose that we take m2 ⌧ ⇤2QCD . This means that the scalars condense at a
scale where the theory is still weakly coupled, g 2 (|m|) ⌧ 1, and we can trust our
semi-classical analysis. If we have enough scalars to fully Higgs the gauge symmetry
(Ns
Nc 1 will do the trick), then all the gauge bosons and scalars again become
massive.
It would seem that the Higgs mechanism and confinement are two rather differ-
ent ways to give a mass to the gauge bosons. In particular, the Higgs mechanism is
something that we can understand in a straightforward way at weak coupling while
confinement is shrouded in strongly coupled mystery. Intuitively, we may feel that the
Higgs phase is not the same as the confining phase. But are they really different?
The sharp way to ask this question is: does the theory undergo a phase transition
as we vary m2 from positive to negative? We usually argue for the existence of a
phase transition by exhibiting an order parameter which has different behaviour in the
two phases. For pure Yang-Mills, the signature for confinement is the area law for
the Wilson loop. But, as we argued above, in the presence of dynamical fundamental
matter the confining string can break, and the area law goes over to a perimeter law.
But this is the expected behaviour in the Higgs phase. In the absence of an order
parameter to distinguish between the confining and Higgs phases, it seems plausible
that they are actually the same, and one can vary smoothly from one phase to another.

For example: SU (2) with Fundamental Matter

Consider SU (2) gauge theory with a single scalar in the fundamental representation.

For good measure, we’ll also throw in a single fermion , also in the fundamental representation. We take the action to be

<!-- Z
1
/ +m ̄
S = d4 x
tr F μ⌫ Fμ⌫ + |Dμ |2
( †
v 2 )2 + i  ̄ D
2g 2
4 -->

Note that it’s not possible to build a gauge invariant Yukawa interaction with the matter content available. We will look at how the spectrum changes as we vary from
v 2 from positive to negative.

Higgs Phase, v 2 > 0: When v 2

QCD we can treat the action semi-classically. To read off the spectrum in the Higgs phase, it is simplest to work in unitary gauge in which the vacuum expectation value takes the form h i = (v, 0). 

We can further use the gauge symmetry to focus on fluctuations of the form = (v +  ̃, 0) with  ̃ 2 R.
You can think of the other components of as being eaten by the Higgs mechanism to
give mass to the gauge bosons. 

The upshot is that we have particles of spin 0,1/2 and
1, given by
• A single, massive, real scalar  ̃.
• Two Dirac fermions i = ( 1 , 2 ). Since the SU (2) gauge symmetry is broken, these no longer should be thought of as living in a doublet. As we vary the mass m 2 R, there is a point at which the fermions become massless. (Classically, this
happen at m = 0 of course.)

• Three massive spin 1 W-bosons Aaμ , with a = 1, 2, 3 labelling the generators of
su(2).

Confining Phase, v 2 < 0: When v 2 < 0, the scalar has mass m2 > 0 and does not condense. 

Now we expect to be in the confining phase, in the sense that only gauge singlets have finite energy. We can list the simplest such states: we will see that they are in one-to-one correspondence with the spectrum in the Higgs phase

• A single, real scalar † . This is expected to be a massive excitation. If we were to evaluate this in the Higgs phase then, in unitary gauge, we have † = v 2 +v  ̃+. . . and so the quadratic operator corresponds to the single particle excitation  ̃, plus
corrections.

There are further scalar operators that we can construct, including tr Fμ⌫ F μ⌫ and
 ̄ . 

These have the same quantum numbers as † and are expected to mix with it. In the confining phase, the lightest spin 0 excitation is presumably created by
some combination of these.

• Two Dirac fermions. The first is 1 = † . The second comes from using the ✏ij invariant tensor of SU (2), which allows us to build 2 = ✏ij i j . If we expand
these operators in unitary gauge in the Higgs phase, we have 1 = v 1 + . . . and
2 = v 2 + . . ..

It’s now less obvious that each of these fermions becomes massless for some value of m 2 R, but it remains plausible. Indeed, one can show that this does occur. 

(A modern perspective is that the fermionic excitation is in a different topological phase for m 0 and m ⌧ 0, ensuring a gapless mode as we vary the mass between the two.)

• Finally, we come to the spectrum of spin 1 excitations. Since we want these to be associated to gauge fields, we might be tempted to consider gauge invariant operators such as tr F μ⌫ Fμ⌫ , but this corresponds to a scalar glueball. 

Instead, we can construct three gauge invariant, spin 1 operators. We have the real operator i † Dμ , and the complex operator ✏ij i (Dμ j ). In unitary gauge, these become v 2 A3μ and v 2 (A1μ + iA2μ ) respectively.

This is a strongly coupled theory, so there may well be a slew of further bound states and these presumably differ between the Higgs and confining phases.

Nonetheless, the matching of the spectrum suggests that we can smoothy continue from one phase to the other without any discontinuity. 

We conclude that, for this example, the Higgs and confining phases are actually the same phase.

Another Example: SU (2) with an Adjoint Scalar It’s worth comparing what happened above with a slightly different theory in which we can distinguish between the two phases. 

We’ll again take SU (2), but this time with an adjoint scalar field . We’ll also throw in a fermion , but we’ll keep this in the fundamental representation. The action is now

<!-- ✓
◆2
Z
1
v2
4
μ⌫
2
2
/ + 0 ̄ +m ̄
S= dx
tr F Fμ⌫ + (Dμ )
tr
+ i  ̄D
2g 2
4
2 -->

where we’ve now also included a Yukawa coupling between the scalar and fermion.

Once again, we can look at whether there is a phase transition as we vary v 2 . 

For v 2 < 0, the scalar field is massive and we expect the theory to be gapped and confine. 

Importantly, in this phase the spectrum contains only bosonic excitations. 

There are no fermions because it’s not possible to construct a gauge invariant fermionic operator. 

In contrast, when v 2 > 0 the scalar field will get an expectation value, breaking the gauge group SU (2) ! U (1), resulting in a gapless photon. 

There are also now 2 fermionic excitations which carry charge ± 12 . The spectrum now looks very different from the confining phase.

Clearly in this case the Higgs and confining phases are different. 

Yet, because we have fermions in the fundamental representation, we will still have dynamical breaking of the flux tube and so fundamental Wilson loop W [C] does not provide an order parameter for confinement. 

Nonetheless, the existence of finite energy states which transform under the Z2 centre of SU (2) – which here coincides with ( 1)F , with F the fermion number – provides a diagnostic for the phase.
