# Geometrodynamics in Brief
## The Parable of the Apple
From the route of two ants on an apple, one understands quite illustrative, the geometric theory of gravity.

> **Einstein's local view of gravity contrasts with Newton's action at a distance.**

> **Physics is simple when viewed locally.**

1. Locally geodesics appear straight
2. Over more extended regions of space and time, geodesics receding from each other gather at a rate governed by the curvature of spacetime, and this effect that geometry enforces on matter is what old-fashioned physics calls *Gravitation*
3. Matter in return gives spacetime it's curvature.

> Space acts on matter, telling it how to move. Matter reacts back on back on space, telling it how to curve. Thus the matter here influences the matter there. That's Einstein's explanation for Gravitation.

## Spacetime With and Without Coordinates

> But with all the daring in the world... How is one to drive a nail into spacetime to mark a point?

Nature provides a good help here, as Einstein was first to emphasize the point. Characterize the point by what's happening there!
Give the point of spacetime the name "*event*".

To say that the event marks a collision of such and such a photon with such and such a particle is identification enough. The world lines of that photon and that particle are rooted in the past and stretch into the future. They have connections with other world lines. These nearby world lines are in turn linked in many ways with other world lines (some so remote).

One does not need to have coordinates, just following all the events and world lines would suffice to have a description of what's happening in the universe. Despite that, having coordinates is very logical and convenient (we are used to it!). Otherwise searching for an specific event in the history of cosmos would be redundant.

![[Pasted image 20241123192455.png]]

Introduce Coordinates, these are four indexed numbers per event:

$$
(x^0, x^1, x^2, x^3)
$$
Coordinates do not generally measure length. 

| Concept                       | Description                                                                                                                                                                                                                   | Notation                                                                                                                                |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Events                        | Events are denoted by capital script, one-letter Latin names. Sometimes subscripts are used.                                                                                                                                  | 𝒫, ℒ, 𝒬, ℛ, 𝒫₀, 𝒫₁, etc.                                                                                                            |
| Coordinates of an event 𝒫    |                                                                                                                                                                                                                               | t(𝒫), x(𝒫), y(𝒫), z(𝒫),<br>x⁰(𝒫), x¹(𝒫), x²(𝒫),<br>x³(𝒫),<br>or more abstractly<br>xᵃ(𝒫) or xᵅ(𝒫)<br>(Greek indices: 0,1,2,3) |
| Time coordinate               | When one of the four is picked to play this role                                                                                                                                                                              | x⁰(𝒫)                                                                                                                                  |
| Space coordinates             | Latin indices take values 1, 2, or 3                                                                                                                                                                                          | x¹(𝒫), x²(𝒫), x³(𝒫)<br>x(𝒫), y(𝒫), z(𝒫)                                                                                           |
| Shorthand notation            | One soon tires of writing explicitly the functional dependence of the coordinates. For coordinates of event 𝒫 and space coordinates. Note: x^i depends not only on choice of 𝒫 but also on arbitrary choice of coordinates! | xᵃ<br>xⁱ                                                                                                                                |
| Other coordinates             | For the same event 𝒫 may be denoted                                                                                                                                                                                          | x̄ᵃ(𝒫) or just x̄ᵃ,<br>x̃ᵃ(𝒫) or just x̃ᵃ,<br>x'ᵃ(𝒫) or just x'ᵃ                                                                     |
| Transformation                | From one coordinate system to another is achieved by the four functions                                                                                                                                                       | x̄⁰(x⁰, x¹, x², x³),<br>x̄¹(x⁰, x¹, x², x³),<br>x̄²(x⁰, x¹, x², x³),<br>x̄³(x⁰, x¹, x², x³),<br>or more succinctly<br>x̄ᵃ(x)            |
| Separation vector*            | Little arrow reaching from one event ℒ to neighboring event 𝒫. Can be characterized by coordinate-value differences                                                                                                          | u or v or ξ, or 𝒫 - ℒ<br>ξᵃ ≡ xᵃ(𝒫) - xᵃ(ℒ),<br>ξⁱ ≡ xⁱ(𝒫) - xⁱ(ℒ)                                                                   |
| Transformation of components  | Of a vector from one coordinate system to another is achieved by partial differential equations                                                                                                                               | ξ̄ᵃ = ∂x̄ᵃ/∂xᵇ ξᵇ                                                                                                                       |
| Einstein summation convention | Any index that is repeated in a product is automatically summed on                                                                                                                                                            | ∂x̄ᵃ/∂xᵇ ξᵇ = Σᵇ ∂x̄ᵃ/∂xᵇ ξᵇ                                                                                                            |

*Note: This definition of a vector is valid only in flat spacetime. The refined definition ("tangent vector") in curved spacetime is not spelled out here (see Chapter 9), but flat-geometry ideas apply with good approximation even in curved geometry, when the two points are sufficiently close.

**Note: These formulas are precisely accurate only when the region of spacetime under consideration is flat and when in addition the coordinates are Cartesian. Otherwise they are approximate—though they become arbitrarily good when the separation between points and the length of the vector become arbitrarily small.


> Coordinate singularities normally unavoidable.

There are many ways that coordinate systems are imperfect. Singularities, where the coordinates cannot be as good differentiating the points (or there might be multiple coordinates to explain one point). Can this be avoided? A theorem states **no**, Two is the minimum number of *coordinate patches* required to cover the two-sphere without singularities.

*This emphasizes our point, where events are primary, coordinates are just the means of bookkeeping.*

> Continuity of Spacetime

In the figure above we have shown a very small number of the possible worldlines. If we were to  put all there is, from such figure one can in imagination step to the idealized limit: an infinitely dense collection of light rays and of worldlines of infinitesimal test particles. 

> The mathematics of manifolds applied to the physics of spacetime

With this idealized physical limit, the mathematical concept of a continuous four-dimensional *Manifold* has a one-to-one correspondence; and in this limit, continuous, differentiable coordinate systems operate.

### Dimensionality of Spacetime: A good test
1. **Initial Point Selection**
   - Start with point $\mathcal{P}$ in n-dimensional manifold
   - Neighborhood is an n-dimensional ball
   - Ball's boundary is a smooth $(n-1)$-dimensional manifold

2. **First Reduction: $(n-1)$ Dimensions**
   - Select point $\mathcal{R}$ on boundary
   - Neighborhood is $(n-1)$-dimensional ball
   - Boundary is smooth $(n-2)$-dimensional manifold

3. **Continue Reduction**
   - Process continues through decreasing dimensions
   - Each step reduces dimension by 1
   - Each boundary is smooth manifold of next lower dimension

4. **Two-Dimensional Stage**
   - Reach point $\mathcal{Q}$ in two-dimensional manifold
   - Neighborhood is two-dimensional ball ("disc")
   - Boundary is smooth one-dimensional manifold (circle)

5. **One-Dimensional Stage**
   - Select point $\mathcal{S}$ on circle
   - Neighborhood is one-dimensional ball (line segment)
   - Boundary consists of two points

6. **Dimensional Counting**
   - Presence of point boundaries confirms one-dimensionality
   - Count backwards to original dimension
   - Total dimension equals number of points used ($\mathcal{P}$, $\mathcal{R}$, $\mathcal{Q}$, $\mathcal{S}$)

7. **Spacetime Application**
   - For spacetime manifold, this process requires 4 points
   - Confirms spacetime is 4-dimensional

This countdown process provides a constructive proof of manifold dimensionality through successive boundary reductions.

This mathematical reasoning about dimensionality makes good sense at all distances (because of the notion of smoothness and infinitesimally close points), but if one judges by the predictions of *Quantum Field Theory*, everything breaks! It predicts violent fluctuations in the geometry at distances on the order of Planck length. 

No one has found any way to escape this prediction. As nearly as one can estimate, these fluctuations give space at small distances a *"multiply connected"* or *"foamlike"* character. This lack of smoothness may well deprive even the concept of dimensionality itself of any meaning at the Plank scale of distances. 

> Difficulty in defining geometry even at classical distances?

If spacetime at small distances is far from mathematical model of a continuous manifold, is there not also at larger distances a wide gap between the mathematical model and physical reality?

> Conclusion

In conclusion, when one deals with spacetime in the context of classical physics, one accepts
1. The notion of "infinitesimal test particle".
2. The idealization that the totality of identifiable events forms a four-dimensional continuous manifold.
Only at the end of this book will a look be taken at some of the limitations placed by the quantum principle on one's way of speaking about and analyzing spacetime.

# Weightlessness
Free fall is synonymous with weightlessness: *absence of any force to drive the object away from its normal track through space-time.*  Travel abroad a spaceship in that state of steady fall toward earth that marks a circular orbit. Then you experience weightlessness, and a natural track through spacetime.

> Free fall is the natural state of motion.

The traveler has one chemical composition, so different than what the spaceship has; yet they travel with each other. Objects of such different nuclear constitution as aluminum and gold fall with acceleration that agree to better than one part in $10^{11}$.  This has been found by Roll, Krotkov, and Dicke in 1964, one of the most important null experiments in all physics. 

> All objects fall with the same acceleration.

Individual molecules fall in step, too, with macroscopic objects \[Estermann, Simpson and Stern 1938\]. And so does neutrons \[Dabbs, Harvey, Paya and Horstmann 1965\]. Even individual electrons, or mu mesons. 

> Eliminate the acceleration by use of a local inertial frame!

Physics looks as complicated to the jet-driven observer as it does to the man on the ground. Rule out both observers to make physics look simple. Instead, travel abroad the freely moving spaceship. Nothing could be more natural than what one sees: every free object moves in a straight line with uniform velocity. 

> Work in a very special coordinate system: a coordinate frame in whihc one is weightless; *a local inertial frame of reference.*

Newton spoke differently: "Absolute space, in its own nature, without relation to anything external, remains always similar and immovable." But how does one give meaning to Newton's absolute space, and mark out its straight lines? In the real world of gravitation, no particle ever follows these straightlines. ==The "*ideal straight line*" is a myth. **It never happened, and it never will**==
---

1. Physics is always and everywhere *locally Lorentzian*.
2. This simplicity shows most clearly in a local Lorentz frame of reference (*inertial frame of reference*)
3. ==To test for a local Lorentz frame, test for weightlessness!==

# Local Lorentz Geometry, With and Without Coordinates

> Local Lorentz geometry is the spacetime analog of local Euclidean geometry.

## Local Euclidean Geometry
What does it mean to say that the geometry of a tiny thumbprint on the apple is Euclidean?
- *Coordinate-free Language (Euclid):* Given a line $AC$. Extend it by an equal distance $CZ$. Let $B$ be a point not on $AZ$ but equidistant from $A$ and $Z$. Then:
	$$
	S_{AB}^2 = S_{AC}^2 + S_{BC}^2
	$$
	![[Pasted image 20241129223545.png]]
- *Language of Coordinates (Descartes):* From any point $A$ to any other point $B$ there's a distance $s$ given in suitable coordinates by:
	$$
	S_{AB}^2 =[x^1(B) - x^1(A)]^2 + [x^2(B)-x^2(A)]^2
	$$
	if one succeeds in finding any coordinate system where this is true for all points $A$ and $B$ in the thumbprint, then one is guaranteed that 
	1. This coordinate system is locally Euclidean
	2. The geometry of the apple's surface is locally Euclidean.
	![[Pasted image 20241129223600.png]]
## Local Lorentz Geometry
What does it mean to say that the geometry of a sufficiently limited region of spacetime in the real physical world is Lorentzian?
- *Coordinate-free Language (Robb 1936)*:
  Let $AZ$ be the world line of a free particle. 
  Let $B$ be an event not on this world-line. 
  Let a light ray from $B$ strike $AZ$ at the event $Q$.
  Let a light ray take off from such an earlier event $P$ along $AZ$ that it reaches $B$. Then the proper distance $S_{AB}$ (spacelike separation) or propertime $\tau_{AB}$ (timelike separation) is given by:
  $$
  S_{AB}^2 \equiv -\tau^2_{AB} = -\tau_{AQ}\tau_{AP}
  $$
  ![[Pasted image 20241129223608.png]]
	Proof of above criterion for local Lorentz geometry, using coordinate methods in the local Lorentz frame where particles remains at rest:
	$$
	\tau^2_{AB} = t^2 - x^2 = (t-x)(t+x) = \tau_{AP}\tau_{AQ} 
	$$
	![[Pasted image 20241129224029.png]]
- *Language of Coordinates (Lorentz, Poincare, Minkowski, Einstein)*: From any event $A$ to any other nearby event $B$, there is a proper distance or proper time, given in suitable coordinates by:
$$
S_{AB}^2 = -\tau_{AB}^2 = -[x^0(B) - x^0(A)]^2 + \sum_{i=1}^3[x^i(B)-x(A)^i]
$$
![[Pasted image 20241129224040.png]]

## Statement of Fact
The geometry of an apple's surface is locally Euclidean everywhere. The geometry of spacetime is locally Lorentzian everywhere.

## Local Geometry in the Language of Modern Mathematics
### Metric for any Manifold
At each point on the apple, at each event of spacetime, indeed, at each point of any "Riemannian Manifold", there exists a geometrical object called the *metric tensor* $g$.

It is a machine with two input slots for the insertion of two vectors:
$$
g( \text{slot 1}, \text{slot 2} )
$$
If one inserts the same vector into both slots, one gets out the square of the length of that vector:
$$
g(\vec u, \vec u) = u^2
$$
If one inserts two different vectors, $u$ and $v$, one gets out a number called the *"scalar product of $u$ on $v$"* 
$$
g(u,v)= g(v,u) = u\cdot v = v\cdot u
$$
The metric is a linear machine, which means
$$
\begin{align}
g(2u + 3w, v) &= 2g(u,v) + 3g(w,v)\\
g(u,av + bw) &= ag(u,v) + bg(u,w)
\end{align}
$$
Consequently, in a given (arbitrary) coordinate system, its operation on two vectors can be written in terms of their components as a bi-linear expression:
$$
g(u,v) = g_{\alpha\beta}u^\alpha v^\beta
$$
The quantities $g_{\alpha\beta}$ are the components of the metric in a given coordinate system.
Since we already investigated what should the product look like in local Euclidean and local Lorentzian, we can see that on the apple the metric is:

$$
g_{\alpha\beta} = \delta_{\beta}^\alpha
$$
and with flat spacetime:
$$
g_{00} = -1, \ g_{ij} = \delta_{ij}
$$
This flat metric if often denoted as $\eta_{\alpha\beta}$.

# Time
> Time is defined so that motion looks simple.

![[Pasted image 20241130175734.png]]

We say that "*Relative to a local Lorentz frame, a free particle*  moves in a straight line with uniform velocity". We now know what straight would mean in a local lorentz frame but what about "uniform velocity"? 

A more fully developed model of a Lorentz reference frame will have holes and clock-activated shutters over each hole. The projectile can reach its target only if.

1. It travels through the correct region in space.
2. Gets through that hole in the correct interval of time.

> Good clock make spacetime trajectories of free particles look straight. 


> Our choice of unit for measuring time: the geometrodynamic centimeter.

The principle of uniformity, taken by itself, leaves free the scale of the time variable. The history of timekeeping discloses many choices of the unit and origin of time. Each one required some human action to give it sanction. 

Space-like intervals and time-like intervals are measured in terms of one and the same geometric unit: the centimeter. Any other decision would complicate in analysis what is simple in nature.

No other choice would live up to Minkowski's word, 
> *"Henceforth space by itself, and time by itself, are doomed to fade away into mere shadows, and only a kind of union of the two will preserve an independent reality"*

**Definition of the centimeter: *The Geometric standard centimeter is the fraction $1/(9.460546 \times 10^{17})$ of the interval between the two "effective equinoxes" that bound the topical year 1900.0.***

![[Pasted image 20241130180021.png]]

# Curvature
Where's geometry in a world of Local Lorentzian spaces? Gravitation seems to have disappeared. Everywhere the geometry of spacetime is locally Lorentzian. Note the apple again, the re-convergence of two nearby geodesics that were divergence from a common point. Consider two test particles in a spaceship around the earth. What gravitational physics is to be seen here? 

Nothing (because we already said that this is an inertial reference frame), Relative to the spaceship and therefore relative to each other, the two test particles move in a straight line with uniform velocity. Increase the precision of measurement until one begins to discern the gradual acceleration the test particles away from each other. This is in Newtonian language, the tide-producing action of the Earth. 

To the observer in the spaceship, however, no Earth is to be seen.
![[Pasted image 20241130181027.png]]

