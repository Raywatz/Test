# Physics 1: Mechanics: Lesson Plan

Modeled on the topic list of **AoPS Physics 1: Mechanics**, which is at the level of AP Physics C: Mechanics. It assumes Algebra 2 and trigonometry; a small amount of calculus (derivatives as slopes, integrals as areas) is introduced in Unit 0 and used where it helps. If you're enrolled in the AoPS course, use this as a companion: read the matching unit here before each week's class and use the practice problems as extra drill.

Use g = 9.8 m/s² unless stated otherwise.

**How to solve any physics problem (use it every time):**
1. Draw a picture and choose a coordinate system (which way is +).
2. List the knowns and unknowns, with units.
3. Pick the principle: kinematics, Newton's 2nd law, energy, momentum, or torque/angular momentum.
4. Solve **with symbols first**, then plug in numbers.
5. Check the units, the sign, and whether the size makes sense.

---

## Unit 0: Math Toolkit

### 0.1 Units and Dimensional Analysis
**Learn:** SI base units: meter (m), kilogram (kg), second (s). Derived: newton N = kg·m/s², joule J = N·m, watt W = J/s. Every term in an equation must have the same units, which lets you catch errors and even guess formulas.

**Example:** The period of a pendulum might depend on L (m), g (m/s²) and m (kg). The only combination with units of seconds is √(L/g), so T ∝ √(L/g), independent of mass. (The exact formula is T = 2π√(L/g).)

### 0.2 Vectors
**Learn:** A vector has magnitude and direction. Components: Aₓ = A cos θ, Aᵧ = A sin θ. Magnitude A = √(Aₓ² + Aᵧ²), direction θ = tan⁻¹(Aᵧ/Aₓ) (check the quadrant). Add vectors component by component.
- **Dot product:** A·B = AB cos θ = AₓBₓ + AᵧBᵧ (a scalar; used for work).
- **Cross product:** |A × B| = AB sin θ, direction by the right-hand rule (used for torque and angular momentum).

### 0.3 Calculus Essentials
**Learn:**
- The **derivative** is the instantaneous rate of change (the slope of the tangent line): v = dx/dt, a = dv/dt. Power rule: d/dt(tⁿ) = n tⁿ⁻¹.
- The **integral** is the accumulated area under a curve: Δx = ∫v dt, Δv = ∫a dt.

**Example:** x(t) = 3t² − 2t + 1 → v(t) = 6t − 2 → a = 6. At t = 2: v = 10 m/s.

**Practice:**
1. A force vector is 50 N at 37° above the x-axis. Find its components.
2. Add A = (3, 4) and B = (−5, 2). Find the magnitude and direction of the sum.
3. Use units to decide which is correct for a spring's period: 2π√(m/k) or 2π√(k/m). (k has units of N/m.)
4. x(t) = t³ − 6t. When is the object momentarily at rest?

**Unit 0 answers:** 1) (39.9, 30.1) N 2) (−2, 6): magnitude √40 ≈ 6.32, direction about 108.4° 3) m/k has units kg/(kg/s²) = s², so 2π√(m/k) 4) v = 3t² − 6 = 0 → t = √2 ≈ 1.41 s

---

## Unit 1: Kinematics in One Dimension

### 1.1 Position, Velocity, Acceleration
**Learn:** Displacement Δx (vector) vs. distance (scalar). Average velocity = Δx/Δt. Average acceleration = Δv/Δt. On graphs: the **slope** of x–t is v; the slope of v–t is a; the **area** under v–t is Δx; the area under a–t is Δv.

### 1.2 Constant Acceleration
**The equations** (constant a only):
- v = v₀ + at
- x = x₀ + v₀t + ½at²
- v² = v₀² + 2aΔx
- Δx = ½(v₀ + v)t

**Example:** A car goes from 0 to 27 m/s in 9 s. a = 3 m/s²; distance = ½(3)(9²) = **121.5 m**.

### 1.3 Free Fall
**Learn:** Near Earth, a = −g (taking up as +), whatever the mass (ignoring air resistance). At the top of the path v = 0 but a is still −g.

**Example:** A ball thrown up at 20 m/s rises for 20/9.8 = 2.04 s and reaches 20²/(2·9.8) = **20.4 m**.

**Practice:**
1. A rock is dropped from 45 m. How long does it fall, and how fast does it hit the ground?
2. A car at 30 m/s brakes at 6 m/s². What is its stopping distance?
3. On a v–t graph, v rises linearly from 0 to 10 m/s over 4 s, then stays constant for 6 s. Find the total displacement.
4. A ball is thrown down at 5 m/s from a 30 m tower. Find its speed at the ground.

**Unit 1 answers:** 1) t = √(2·45/9.8) ≈ 3.03 s; v ≈ 29.7 m/s 2) 30²/(2·6) = 75 m 3) 20 + 60 = 80 m 4) v = √(25 + 2·9.8·30) ≈ 24.8 m/s

---

## Unit 2: Motion in Two Dimensions

### 2.1 Projectile Motion
**Learn:** The horizontal and vertical motions are **independent**. Horizontal: constant velocity (aₓ = 0). Vertical: free fall (aᵧ = −g). They share the same time t.
- Level ground: range R = v₀² sin 2θ / g (maximum at 45°); maximum height H = (v₀ sin θ)²/(2g); time of flight = 2v₀ sin θ / g.

**Example:** Launched at 20 m/s at 30° from level ground: vₓ = 17.32, vᵧ = 10. Time = 2(10)/9.8 = 2.04 s; range = 17.32 × 2.04 ≈ **35.3 m**; max height = 100/19.6 ≈ **5.10 m**.

### 2.2 Relative Velocity
**Learn:** v(A relative to C) = v(A relative to B) + v(B relative to C). Classic cases: a boat crossing a river, a plane in the wind, rain seen from a moving car.

**Example:** A boat heads straight across a 100 m wide river at 4 m/s; the current is 3 m/s. The boat's speed relative to the ground is 5 m/s. Crossing time = 100/4 = 25 s, and it drifts 3 × 25 = **75 m** downstream.

**Practice:**
1. A ball rolls off a 1.25 m table at 3 m/s. How far from the table does it land?
2. A projectile is launched at 30 m/s at 60°. Find its range and maximum height (level ground).
3. A plane flies at 200 km/h heading north; the wind blows east at 50 km/h. Find its ground speed and direction.

**Unit 2 answers:** 1) t = √(2·1.25/9.8) ≈ 0.505 s; x ≈ 1.52 m 2) R = 900 sin 120°/9.8 ≈ 79.5 m; H = (25.98)²/19.6 ≈ 34.4 m 3) √(200² + 50²) ≈ 206 km/h, 14.0° east of north

---

## Unit 3: Newton's Laws

### 3.1 The Three Laws
1. An object keeps its velocity unless a net force acts on it (inertia).
2. **ΣF = ma** (a vector equation; apply it along each axis separately).
3. Forces come in equal and opposite pairs **acting on different objects**.

### 3.2 Free-Body Diagrams and Common Forces
**Learn:** Draw only the forces *on* the object: weight W = mg (down), normal force N (perpendicular to the surface), tension T (along the rope, pulling), friction (along the surface), applied forces. Then write ΣFₓ = maₓ and ΣFᵧ = maᵧ.

**Example (elevator):** A 70 kg person in an elevator accelerating upward at 2 m/s². N − mg = ma → N = 70(9.8 + 2) = **826 N** (the person "feels heavier").

### 3.3 Connected Objects and Pulleys
**Learn:** Treat each object separately, with the same rope tension and linked accelerations. Or treat the whole system as one object to find a quickly.

**Example (Atwood machine):** 3 kg and 5 kg masses hang over an ideal pulley. a = (5 − 3)g/(5 + 3) = **2.45 m/s²**. Tension T = 2m₁m₂g/(m₁ + m₂) = 2(3)(5)(9.8)/8 ≈ **36.8 N**.

**Practice:**
1. A 10 N force pushes a 2 kg block on a frictionless floor. Find a.
2. Two blocks (2 kg and 3 kg) touch on a frictionless floor; 20 N pushes the 2 kg block. Find a and the force between the blocks.
3. A 4 kg block on a frictionless table is tied over a pulley to a hanging 1 kg block. Find a and T.
4. A 5 kg lamp hangs from two cords, each at 30° to the horizontal. Find the tension in each.

**Unit 3 answers:** 1) 5 m/s² 2) a = 4 m/s²; the force on the 3 kg block = 12 N 3) a = 1(9.8)/5 = 1.96 m/s²; T = 4(1.96) = 7.84 N 4) 2T sin 30° = 49, so T = 49 N

---

## Unit 4: Friction, Inclines, and Springs

### 4.1 Friction
**Learn:** Static friction: f_s ≤ μ_s N (it matches whatever is needed, up to a maximum). Kinetic friction: f_k = μ_k N (constant, opposes the sliding). Usually μ_s > μ_k.

### 4.2 Inclines
**Learn:** Tilt your axes so x runs along the slope. The weight's components are mg sin θ (down the slope) and mg cos θ (into the slope), so N = mg cos θ (if nothing else pushes perpendicular to the slope).

**Example:** A block slides down a 30° incline with μ_k = 0.2: a = g(sin 30° − 0.2 cos 30°) = 9.8(0.5 − 0.173) ≈ **3.20 m/s²**.

### 4.3 Springs
**Learn:** Hooke's Law: F = −kx (a restoring force proportional to the stretch).

**Practice:**
1. A 10 kg box on the floor has μ_s = 0.5, μ_k = 0.3. What force starts it moving? What force keeps it moving at constant speed?
2. Find the steepest angle at which a block stays at rest if μ_s = 0.6.
3. A 2 kg mass stretches a hanging spring by 0.1 m. Find k.
4. A 5 kg block is pushed up a 20° incline (μ_k = 0.25) at constant speed by a force parallel to the incline. How large is the force?

**Unit 4 answers:** 1) 49 N; 29.4 N 2) tan θ = 0.6, θ ≈ 31.0° 3) k = 19.6/0.1 = 196 N/m 4) F = mg(sin 20° + 0.25 cos 20°) ≈ 49(0.342 + 0.235) ≈ 28.3 N

---

## Unit 5: Circular Motion

### 5.1 Uniform Circular Motion
**Learn:** Even at constant speed, the velocity's direction changes, so there's a **centripetal acceleration** a_c = v²/r = ω²r, pointing toward the center. Period T = 2πr/v. Centripetal force isn't a new force: it's whatever **net** force points inward (tension, friction, gravity, normal force).

### 5.2 Applications
- **Flat curve:** friction provides the inward force: μ_s mg = mv²/r, so v_max = √(μ_s g r).
- **Banked curve (no friction):** tan θ = v²/(rg).
- **Vertical loop:** at the top, mg + N = mv²/r. The minimum speed to stay on the track is v = √(gr).
- **Conical pendulum:** T cos θ = mg, T sin θ = mv²/r.

**Example:** A car on a flat curve, r = 50 m, μ_s = 0.8: v_max = √(0.8 · 9.8 · 50) ≈ **19.8 m/s**.

**Practice:**
1. A 0.5 kg ball on a 1 m string makes 2 revolutions per second in a horizontal circle (ignore gravity). Find the tension.
2. What banking angle lets cars take a 100 m radius curve at 20 m/s with no friction needed?
3. Find the minimum speed at the top of a loop with radius 10 m.

**Unit 5 answers:** 1) v = 2π(1)(2) ≈ 12.57 m/s; T = mv²/r ≈ 79 N 2) tan θ = 400/980, θ ≈ 22.2° 3) √98 ≈ 9.9 m/s

---

## Unit 6: Work, Energy, and Power

### 6.1 Work
**Learn:** W = F·d = Fd cos θ. Work is positive if the force has a component along the motion and negative if against it. Normal forces and centripetal forces do **zero** work. For a varying force, W = ∫F dx (the area under the F–x graph). Spring: W = ½kx².

### 6.2 Kinetic Energy and the Work-Energy Theorem
**Learn:** KE = ½mv². **W_net = ΔKE.**

**Example:** A 1000 kg car going 20 m/s stops. ΔKE = −½(1000)(400) = −200,000 J, so friction does −200 kJ of work. If the braking force is 8000 N, the stopping distance is **25 m**.

### 6.3 Power
**Learn:** P = W/t = Fv. 1 horsepower ≈ 746 W.

**Practice:**
1. A 20 N force at 60° above horizontal pulls a box 5 m. How much work does it do?
2. A 2 kg block at 3 m/s slides 1.5 m on a rough floor and stops. Find the friction force.
3. A 60 kg person climbs 3 m of stairs in 4 s. Find their power.

**Unit 6 answers:** 1) 50 J 2) KE = 9 J, so f = 9/1.5 = 6 N 3) 60(9.8)(3)/4 = 441 W

---

## Unit 7: Potential Energy and Conservation of Energy

### 7.1 Potential Energy
**Learn:** Gravitational: U = mgh. Spring: U = ½kx². These exist only for **conservative** forces (where the work done doesn't depend on the path). The force is the negative slope of U: F = −dU/dx.

### 7.2 Conservation of Mechanical Energy
**Learn:** With no friction: KE₁ + U₁ = KE₂ + U₂. With friction: KE₁ + U₁ = KE₂ + U₂ + (heat), where heat = f_k·d.

**Example:** A roller coaster starts at rest 20 m high. At the bottom, v = √(2gh) = √392 ≈ **19.8 m/s** (independent of mass and track shape).

**Example:** A spring with k = 200 N/m compressed 0.1 m launches a 0.5 kg block: ½(200)(0.01) = ½(0.5)v², so **v = 2 m/s**.

### 7.3 Energy Diagrams
**Learn:** On a graph of U(x), an object with total energy E can only be where U ≤ E. Turning points are where U = E. Minima are stable equilibria; maxima are unstable.

**Practice:**
1. A pendulum is released from 0.5 m above its lowest point. Find its speed at the bottom.
2. A 2 kg block slides down a 5 m frictionless ramp (height drop 3 m), then onto a rough floor (μ_k = 0.4). How far does it slide on the floor?
3. A ball must make it around a vertical loop of radius R. From what minimum height must it start (frictionless, sliding)?

**Unit 7 answers:** 1) √(2 · 9.8 · 0.5) ≈ 3.13 m/s 2) mgh = μmg d → d = 3/0.4 = 7.5 m 3) At the top, v² = gR; energy: mgh = mg(2R) + ½mgR, so h = 2.5R

---

## Unit 8: Momentum and Impulse

### 8.1 Momentum and Impulse
**Learn:** Momentum p = mv (a vector). Impulse J = FΔt = ∫F dt = Δp. A longer impact time means a smaller force (airbags, bending your knees when you land).

**Example:** A 0.15 kg baseball arrives at 40 m/s and leaves at 30 m/s in the opposite direction. Δp = 0.15(30 − (−40)) = **10.5 N·s**. If contact lasts 0.002 s, F_avg = **5,250 N**.

### 8.2 Conservation of Momentum
**Learn:** If no external net force acts, the total momentum of a system is constant. This applies to collisions and explosions (and recoil).

**Example:** A 60 kg skater throws a 2 kg ball forward at 15 m/s. Recoil: 60v = 2(15), so **v = 0.5 m/s** backward.

**Practice:**
1. A 0.06 kg tennis ball hits a wall at 20 m/s and bounces back at 15 m/s. Find the impulse.
2. A 1,000 kg cannon fires a 10 kg shell at 300 m/s. Find the recoil speed.

**Unit 8 answers:** 1) 0.06 × 35 = 2.1 N·s (away from the wall) 2) 3 m/s

---

## Unit 9: Collisions and Center of Mass

### 9.1 Types of Collisions
- **Elastic**: both momentum and kinetic energy are conserved.
- **Inelastic**: momentum is conserved, but some kinetic energy is lost.
- **Perfectly inelastic**: the objects stick together, losing the most KE.

**1D elastic collision with m₂ initially at rest:**
v₁′ = (m₁ − m₂)/(m₁ + m₂) · v₁, v₂′ = 2m₁/(m₁ + m₂) · v₁.
Equal masses simply swap velocities.

**Example:** 2 kg at 3 m/s hits 1 kg at rest.
- Perfectly inelastic: v = 6/3 = **2 m/s**; KE goes from 9 J to 6 J (3 J lost).
- Elastic: v₁′ = (1/3)(3) = **1 m/s**, v₂′ = (4/3)(3) = **4 m/s**. Check: momentum 2 + 4 = 6 ✓; KE 1 + 8 = 9 J ✓.

### 9.2 2D Collisions
**Learn:** Conserve momentum separately in x and y.

### 9.3 Center of Mass
**Learn:** x_cm = Σmᵢxᵢ / Σmᵢ (same for y). For continuous objects, x_cm = (1/M)∫x dm. The center of mass moves as if all the mass and all the external forces were concentrated there, so a fireworks shell's CM keeps following the parabola after it explodes.

**Practice:**
1. A 1,500 kg car at 20 m/s rear-ends a 1,000 kg car at rest; they stick. Find their speed and the KE lost.
2. Masses of 2 kg at x = 0, 3 kg at x = 4 m and 5 kg at x = 6 m. Find x_cm.
3. A 0.2 kg puck at 4 m/s (+x) collides with an identical puck at rest. Afterward, the first moves at 2 m/s at 60° from the x-axis. Find the second puck's velocity.

**Unit 9 answers:** 1) v = 30,000/2,500 = 12 m/s; KE 300,000 J → 180,000 J, so 120 kJ lost 2) (0 + 12 + 30)/10 = 4.2 m 3) x: 4 = 2cos 60° + vₓ → vₓ = 3; y: 0 = 2sin 60° + vᵧ → vᵧ = −1.73. So |v| ≈ 3.46 m/s at 30° below the x-axis.

---

## Unit 10: Rotational Kinematics

**Learn:** Angle θ (radians), angular velocity ω = dθ/dt (rad/s), angular acceleration α = dω/dt. Links to linear motion for a point at radius r: s = rθ, v = rω, a_t = rα, a_c = ω²r. The constant-α equations mirror Unit 1:
- ω = ω₀ + αt
- θ = ω₀t + ½αt²
- ω² = ω₀² + 2αθ

Conversions: 1 rev = 2π rad; rpm × 2π/60 = rad/s.

**Example:** A wheel goes from rest to 10 rad/s in 5 s: α = 2 rad/s², θ = ½(2)(25) = **25 rad** ≈ 4 revolutions.

**Practice:**
1. A fan at 300 rpm stops in 10 s. Find α and the number of revolutions it makes while stopping.
2. A 0.3 m radius wheel spins at 20 rad/s. Find the rim speed and centripetal acceleration.

**Unit 10 answers:** 1) ω₀ = 31.4 rad/s; α = −3.14 rad/s²; θ = 157 rad = 25 rev 2) 6 m/s; 120 m/s²

---

## Unit 11: Torque and Rotational Dynamics

### 11.1 Torque
**Learn:** τ = r × F, with |τ| = rF sin θ (lever arm × force). Counterclockwise is usually +.

### 11.2 Moment of Inertia
**Learn:** I = Σmr² (rotational "mass"). Common values:
| Object (axis) | I |
|---|---|
| Point mass at radius r | mr² |
| Hoop or thin ring (center) | MR² |
| Solid disk or cylinder (center) | ½MR² |
| Solid sphere (center) | (2/5)MR² |
| Thin spherical shell | (2/3)MR² |
| Rod (center) | (1/12)ML² |
| Rod (end) | (1/3)ML² |

**Parallel-axis theorem:** I = I_cm + Md².

### 11.3 Newton's 2nd Law for Rotation
**Learn:** **Στ = Iα.**

**Example:** A 2 kg disk (R = 0.5 m) with a rope wrapped around it, pulled with 4 N. I = ½(2)(0.25) = 0.25 kg·m²; τ = 4(0.5) = 2 N·m; α = **8 rad/s²**.

**Example (pulley with mass):** A mass m hangs from a rope wrapped on a disk pulley (M, R): a = mg/(m + M/2).

**Practice:**
1. A 3 kg, 2 m rod pivots at one end and is released horizontally. Find the initial α.
2. A 1 kg mass hangs from a rope around a 4 kg solid disk pulley. Find a.
3. Use the parallel-axis theorem to find I for a rod about its end from I_cm = (1/12)ML².

**Unit 11 answers:** 1) τ = mg(L/2) = 29.4 N·m; I = (1/3)(3)(4) = 4; α = 7.35 rad/s² 2) a = 9.8/(1 + 2) ≈ 3.27 m/s² 3) (1/12)ML² + M(L/2)² = (1/3)ML² ✓

---

## Unit 12: Rotational Energy, Rolling, and Angular Momentum

### 12.1 Rotational Kinetic Energy and Rolling
**Learn:** KE_rot = ½Iω². Rolling without slipping: v = ωR, so KE_total = ½mv² + ½Iω².

Rolling down a height h from rest: mgh = ½mv²(1 + I/(mR²)).
- Solid sphere: v = √(10gh/7)
- Solid cylinder: v = √(4gh/3)
- Hoop: v = √(gh)

The object with the smaller I/(mR²) wins a race down a ramp: sphere > cylinder > hoop, regardless of mass or size.

### 12.2 Angular Momentum
**Learn:** L = Iω (rigid body), or L = r × p (point particle). Στ = dL/dt. **If the external torque is zero, L is conserved.**

**Example:** A spinning skater pulls her arms in, so I drops from 4 to 1.6 kg·m². If ω was 2 rev/s, it becomes 4(2)/1.6 = **5 rev/s**. (KE increases; the extra energy comes from her muscles.)

**Practice:**
1. A solid sphere rolls from rest down a 2 m high ramp. Find its speed at the bottom.
2. A 2 kg disk (R = 0.5 m) spinning at 10 rad/s has a 1 kg ring of the same radius dropped onto it. Find the new ω.
3. Why does a figure skater's KE increase when she pulls her arms in, even though L stays constant?

**Unit 12 answers:** 1) √(10 · 9.8 · 2/7) ≈ 5.29 m/s 2) I₁ = 0.25, I₂ = 0.25 + 0.25 = 0.5, so ω = 5 rad/s 3) KE = L²/(2I); smaller I means larger KE, and the work comes from her muscles pulling her arms inward.

---

## Unit 13: Static Equilibrium

**Learn:** Equilibrium means **ΣF = 0 and Στ = 0** about **any** point. Trick: choose the pivot where an unknown force acts, which removes it from the torque equation.

**Example (seesaw):** A 30 kg child sits 2 m from the pivot. Where should a 40 kg child sit? 30(2) = 40x, so **x = 1.5 m**.

**Example (beam):** A 4 m, 10 kg uniform beam is supported at both ends, with a 20 kg load 1 m from the left end. Torques about the left end: R(4) = 10g(2) + 20g(1), so R = 10g = 98 N (right support). Left support = 30g − 10g = 20g = **196 N**.

**Practice:**
1. A uniform 6 m, 20 kg plank rests on supports at x = 0 and x = 4 m. How far past the right support can a 50 kg person walk before the plank tips?
2. A 5 m ladder (weight 200 N) leans against a frictionless wall at 60° to the ground. Find the friction force needed at the floor.

**Unit 13 answers:** 1) Tipping about x = 4: the plank's weight acts at x = 3 (1 m inside); 20(1) = 50d, so d = 0.4 m past the support (x = 4.4 m) 2) Torques about the base: N_wall(5 sin 60°) = 200(2.5 cos 60°), so N_wall = 250/4.33 ≈ 57.7 N = the friction needed.

---

## Unit 14: Gravitation and Orbits

### 14.1 Newton's Law of Gravitation
**Learn:** F = Gm₁m₂/r², with G = 6.67 × 10⁻¹¹ N·m²/kg². Surface gravity g = GM/R². Gravitational PE: U = −GMm/r (zero at infinity).

### 14.2 Orbits
**Learn:** For a circular orbit, gravity provides the centripetal force: v = √(GM/r), T² = (4π²/GM) r³.
- **Kepler's laws:** (1) orbits are ellipses with the sun at one focus; (2) a line from the sun sweeps equal areas in equal times (conservation of angular momentum); (3) T² ∝ a³.
- **Escape speed:** v_esc = √(2GM/R).
- Total energy of a circular orbit: E = −GMm/(2r).

**Example (ISS):** r = 6.77 × 10⁶ m, GM_Earth = 3.986 × 10¹⁴: v = √(3.986 × 10¹⁴ / 6.77 × 10⁶) ≈ **7.67 km/s**. T = 2πr/v ≈ 5,540 s ≈ **92 min**.

**Practice:**
1. How does gravity change if you double your distance from Earth's center?
2. Escape speed from Earth (M = 5.97 × 10²⁴ kg, R = 6.37 × 10⁶ m)?
3. A planet orbits at 4 times Earth's distance from the sun. Find its period.
4. What orbital radius gives a geostationary orbit (T = 24 h)?

**Unit 14 answers:** 1) It becomes ¼ as strong 2) √(2 · 3.986 × 10¹⁴ / 6.37 × 10⁶) ≈ 11.2 km/s 3) T = 4^1.5 = 8 years 4) r = (GMT²/4π²)^(1/3) ≈ 4.22 × 10⁷ m (about 35,800 km above the surface)

---

## Unit 15: Simple Harmonic Motion (Oscillations)

**Learn:** SHM happens whenever the restoring force is proportional to the displacement: F = −kx, so a = −ω²x.
- Solution: x(t) = A cos(ωt + φ). Then v_max = Aω and a_max = Aω².
- Mass on a spring: ω = √(k/m), T = 2π√(m/k) (independent of amplitude).
- Simple pendulum (small angles): T = 2π√(L/g) (independent of mass).
- Physical pendulum: T = 2π√(I/(mgd)).
- Energy: E = ½kA², shared between KE and PE.

**Example:** m = 0.5 kg, k = 50 N/m: ω = 10 rad/s, T = 2π/10 ≈ **0.628 s**. With A = 0.1 m: v_max = **1 m/s**.

**Example:** A 1 m pendulum: T = 2π√(1/9.8) ≈ **2.0 s**.

**Practice:**
1. A 2 kg mass on a spring (k = 200 N/m) has amplitude 0.05 m. Find T, v_max and the total energy.
2. How long must a pendulum be to have a period of 1 s?
3. Where in the motion is the speed greatest? The acceleration?
4. A pendulum clock is taken to the Moon (g = 1.62 m/s²). Does it run fast or slow?

**Unit 15 answers:** 1) ω = 10, T ≈ 0.628 s; v_max = 0.5 m/s; E = ½(200)(0.0025) = 0.25 J 2) L = g(T/2π)² ≈ 0.248 m 3) Speed is greatest at equilibrium (x = 0); acceleration is greatest at the ends (x = ±A) 4) Slow: the period is longer because g is smaller.

---

## Optional Unit 16: Fluids (if your course includes it)
- Density ρ = m/V; pressure P = F/A; pressure at depth: P = P₀ + ρgh.
- **Archimedes:** buoyant force = weight of the fluid displaced = ρ_fluid V_sub g. Fraction of a floating object submerged = ρ_object/ρ_fluid.
- **Continuity:** A₁v₁ = A₂v₂. **Bernoulli:** P + ½ρv² + ρgh = constant.

---

## Suggested Pacing (about 24 weeks)

| Weeks | Units |
|---|---|
| 1 | 0 Math toolkit |
| 2–3 | 1–2 Kinematics |
| 4–6 | 3–5 Newton's laws, friction, circular motion |
| 7–9 | 6–7 Work and energy |
| 10–12 | 8–9 Momentum, collisions, center of mass |
| 13–17 | 10–13 Rotation and equilibrium |
| 18–19 | 14 Gravitation |
| 20–21 | 15 Oscillations (16 optional) |
| 22–24 | Mixed review: hard problems that combine multiple units |

## Resources
- **AoPS Physics 1** course materials and its Alcumus-style problem sets, if you're enrolled.
- **Khan Academy Physics** and **AP Physics C: Mechanics** videos for a second explanation of any topic.
- *Physics* by Halliday, Resnick & Krane, or the free **OpenStax University Physics Vol. 1** for more practice problems.
- **PhET simulations** (phet.colorado.edu): interactive projectile, spring and orbit models.
