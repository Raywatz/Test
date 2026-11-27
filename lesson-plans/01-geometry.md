# Geometry: Full Lesson Plan

Standards covered: G-CO (congruence), G-SRT (similarity, right triangles, trig), G-C (circles), G-GPE (coordinate geometry), G-GMD (measurement), G-MG (modeling), S-CP/S-MD (probability).

---

## Unit 1: Foundations of Geometry and Proof

### 1.1 Points, Lines, and Planes
**Goal:** Use the basic vocabulary of geometry.
**Learn:**
- *Undefined terms*: **point** (a location), **line** (extends forever both ways), **plane** (flat surface extending forever).
- **Segment** AB: part of a line with two endpoints. **Ray** AB: starts at A and goes forever through B.
- **Collinear** = on the same line. **Coplanar** = in the same plane.
- Postulates (accepted without proof): two points determine exactly one line; three non-collinear points determine one plane; two lines intersect in at most one point; two planes intersect in a line.

**Example:** How many lines pass through 4 points, no three collinear? Each pair makes a line: 4·3/2 = **6 lines**.

### 1.2 Measuring Segments: Distance and Midpoint
**Goal:** Find lengths and midpoints, including on the coordinate plane.
**Learn:**
- **Segment Addition Postulate**: if B is between A and C, then AB + BC = AC.
- **Distance formula**: d = √((x₂ − x₁)² + (y₂ − y₁)²) (this is the Pythagorean theorem in disguise).
- **Midpoint formula**: M = ((x₁ + x₂)/2, (y₁ + y₂)/2).
- Congruent segments (≅) have equal length.

**Example:** A(−2, 3), B(4, −5). AB = √(6² + (−8)²) = √100 = **10**. Midpoint = ((−2+4)/2, (3−5)/2) = **(1, −1)**.

**Practice:**
1. Find the distance and midpoint for (−1, 4) and (5, −4).
2. M(5, 1) is the midpoint of AB and A = (3, −2). Find B.
3. B is between A and C. AB = 2x + 3, BC = x − 1, AC = 17. Find x.

### 1.3 Measuring Angles and Angle Pairs
**Goal:** Classify angles and use angle-pair relationships.
**Learn:**
- Acute (< 90°), right (= 90°), obtuse (between 90° and 180°), straight (180°).
- **Angle Addition Postulate**: if D is in the interior of ∠ABC, then m∠ABD + m∠DBC = m∠ABC.
- **Complementary**: sum to 90°. **Supplementary**: sum to 180°.
- **Linear pair**: adjacent angles forming a line, so they are supplementary.
- **Vertical angles**: opposite angles formed by two intersecting lines; they are congruent.
- **Angle bisector**: a ray splitting an angle into two congruent angles.

**Example:** Vertical angles measure (5x − 10)° and (3x + 20)°. Then 5x − 10 = 3x + 20, so x = 15 and each angle is **65°**.

**Practice:**
4. ∠A and ∠B are supplementary, m∠A = 3x + 10, m∠B = 2x + 20. Find both angles.
5. The complement of an angle is 4 times the angle. Find the angle.

### 1.4 Basic Constructions (compass and straightedge)
**Goal:** Perform the standard constructions (G-CO.12, 13).
**Learn:** practice each one with a real compass, or in GeoGebra.
1. **Copy a segment**: set the compass to the length, then mark it on a new ray.
2. **Copy an angle**: draw an arc on the original angle, use the same arc on the new ray, then transfer the arc's chord width.
3. **Perpendicular bisector** of a segment: draw arcs from both endpoints with the same radius (more than half the length); connect the two intersection points.
4. **Angle bisector**: draw an arc crossing both sides, then from those two points draw equal arcs; connect the vertex to the intersection.
5. **Perpendicular through a point** (on or off the line): mark two points on the line equidistant from the point, then perpendicular-bisect them.
6. **Parallel line through a point**: copy an angle (corresponding angles).
7. **Equilateral triangle, square, regular hexagon inscribed in a circle**: for the hexagon, keep the compass at radius r and step around the circle 6 times. For the triangle, use every other hexagon point. For the square, draw two perpendicular diameters.

**Why they work:** each relies on congruent triangles (SSS), which you will learn in Unit 4.

### 1.5 Inductive and Deductive Reasoning, Conditional Statements
**Goal:** Analyze logical statements.
**Learn:**
- **Inductive reasoning**: finding a pattern (it can be wrong; one **counterexample** disproves a conjecture).
- **Deductive reasoning**: using facts, definitions and logic to reach certain conclusions.
- **Conditional**: If p, then q (p → q). *p* = hypothesis, *q* = conclusion.
  - **Converse**: q → p
  - **Inverse**: not p → not q
  - **Contrapositive**: not q → not p (always has the same truth value as the original)
  - **Biconditional**: p if and only if q (true only when the conditional and its converse are both true). Good definitions are biconditionals.
- **Law of Detachment**: p → q is true and p is true, so q is true.
- **Law of Syllogism**: p → q and q → r, so p → r.

**Example:** "If a figure is a square, then it has four right angles." True. Converse: "If a figure has four right angles, then it is a square." False; counterexample: a non-square rectangle.

**Practice:**
6. Write the converse, inverse and contrapositive of "If x = 3, then x² = 9." Which are true?
7. "If it rains, the game is canceled. If the game is canceled, we go to the movies." It rains. What can you conclude, and by which law?

### 1.6 Writing Proofs
**Goal:** Write two-column and paragraph proofs.
**Learn:**
- Properties you can cite as reasons: **Reflexive** (AB = AB), **Symmetric** (if a = b then b = a), **Transitive** (a = b and b = c, so a = c), **Substitution**, plus the Addition/Subtraction/Multiplication/Division Properties of Equality, and the **Distributive** property.
- Every statement needs a reason: Given, a definition, a postulate, or a previously proven theorem.

**Example:** Prove that vertical angles are congruent.
| Statement | Reason |
|---|---|
| 1. ∠1 and ∠2 are vertical angles | Given |
| 2. ∠1 and ∠3 form a linear pair; ∠2 and ∠3 form a linear pair | Definition of linear pair |
| 3. m∠1 + m∠3 = 180°, m∠2 + m∠3 = 180° | Linear Pair Postulate |
| 4. m∠1 + m∠3 = m∠2 + m∠3 | Substitution (Transitive) |
| 5. m∠1 = m∠2 | Subtraction Property of Equality |
| 6. ∠1 ≅ ∠2 | Definition of congruent angles |

**Practice:**
8. Given: AB = CD. Prove: AC = BD (A, B, C, D collinear in that order). Hint: add BC to both sides.

**Unit 1 answers:** 1) d = 10, M(2, 0) 2) B(7, 4) 3) x = 5 4) x = 30; 100° and 80° 5) 18° 6) Converse "If x² = 9 then x = 3" is false (x = −3). Inverse "If x ≠ 3 then x² ≠ 9" is false. Contrapositive "If x² ≠ 9 then x ≠ 3" is true. 7) We go to the movies (Law of Syllogism, then Detachment) 8) AB + BC = CD + BC (Addition Property); AB + BC = AC and BC + CD = BD (Segment Addition); so AC = BD (Substitution).

---

## Unit 2: Parallel and Perpendicular Lines

### 2.1 Angles Formed by a Transversal
**Learn:** When a transversal crosses two **parallel** lines:
- **Corresponding angles** are congruent (Postulate).
- **Alternate interior** angles are congruent.
- **Alternate exterior** angles are congruent.
- **Same-side (consecutive) interior** angles are supplementary.

**Example:** Alternate interior angles are (4x + 15)° and (6x − 25)°. Then 4x + 15 = 6x − 25, so x = 20 and each angle is **95°**.

### 2.2 Proving Lines Parallel
**Learn:** The **converses** work: if corresponding angles are congruent (or alternate interior angles are congruent, or same-side interior angles are supplementary), the lines are parallel. Also: two lines perpendicular to the same line are parallel, and two lines parallel to the same line are parallel.

### 2.3 Triangle Angle Sum and Exterior Angles
**Learn:**
- The angles of a triangle sum to **180°**. Proof: draw a line through one vertex parallel to the opposite side and use alternate interior angles.
- **Exterior Angle Theorem**: an exterior angle equals the sum of the two remote interior angles.

**Example:** The remote interior angles are 40° and 75°, so the exterior angle is **115°**.

### 2.4 Slopes of Parallel and Perpendicular Lines
**Learn:**
- Slope m = (y₂ − y₁)/(x₂ − x₁). Point-slope form: y − y₁ = m(x − x₁). Slope-intercept form: y = mx + b.
- **Parallel** lines have equal slopes. **Perpendicular** lines have slopes that are negative reciprocals (m₁·m₂ = −1). Vertical ⟂ horizontal.

**Example:** The line through (2, 3) perpendicular to y = 2x + 1 has slope −½: y − 3 = −½(x − 2), so **y = −½x + 4**.

**Practice:**
1. Same-side interior angles are (2x + 10)° and (3x − 5)°. Find x.
2. A triangle's angles are in the ratio 1:2:3. Find them.
3. Find the lines through (1, 5) that are (a) parallel and (b) perpendicular to y = −3x + 2.
4. Are the lines 2x + 3y = 6 and 3x − 2y = 4 parallel, perpendicular, or neither?

**Unit 2 answers:** 1) 5x + 5 = 180, x = 35 2) 30°, 60°, 90° 3a) y = −3x + 8 3b) y = ⅓x + 14/3 4) Slopes −⅔ and 3/2 multiply to −1, so perpendicular.

---

## Unit 3: Transformations (Rigid Motions)

### 3.1 Reflections
**Learn:** A reflection flips a figure over a line; each point and its image are equidistant from the line, and the line is the perpendicular bisector of the segment joining them.
- Over the x-axis: (x, y) → (x, −y)
- Over the y-axis: (x, y) → (−x, y)
- Over y = x: (x, y) → (y, x)
- Over y = −x: (x, y) → (−y, −x)

### 3.2 Translations
**Learn:** Slide every point by the same vector ⟨a, b⟩: (x, y) → (x + a, y + b).

### 3.3 Rotations
**Learn:** Turn about a center point by an angle (counterclockwise is positive). About the origin:
- 90°: (x, y) → (−y, x)
- 180°: (x, y) → (−x, −y)
- 270°: (x, y) → (y, −x)

**Example:** Rotate triangle A(1, 2), B(4, 2), C(4, 5) 90° about the origin: A′(−2, 1), B′(−2, 4), C′(−5, 4).

### 3.4 Compositions and Rigid Motions
**Learn:**
- **Rigid motions** (isometries) are reflections, translations and rotations. They preserve distance and angle measure, so the image is congruent to the original.
- A **composition** does one transformation, then another (order matters). Reflecting over two parallel lines gives a translation of twice the distance between them. Reflecting over two intersecting lines gives a rotation of twice the angle between them.
- **Glide reflection**: a translation followed by a reflection over a line parallel to the translation.
- Reflections reverse **orientation** (clockwise becomes counterclockwise); rotations and translations preserve it.

### 3.5 Symmetry
**Learn:**
- **Line symmetry**: a reflection maps the figure onto itself. A regular n-gon has n lines of symmetry.
- **Rotational symmetry**: a rotation of less than 360° maps the figure onto itself. A regular n-gon maps onto itself under rotations by multiples of **360°/n**.

**Practice:**
1. Reflect (2, −5) over y = x.
2. Rotate (3, 4) 90° counterclockwise about the origin.
3. Translate (1, 1) by ⟨−3, 2⟩, then reflect over the x-axis.
4. Describe every rotation that maps a regular pentagon onto itself.
5. How many lines of symmetry does a rectangle (non-square) have?

**Unit 3 answers:** 1) (−5, 2) 2) (−4, 3) 3) (−2, 3) → (−2, −3) 4) 72°, 144°, 216°, 288° (and 360°) 5) 2

---

## Unit 4: Triangle Congruence

### 4.1 Congruence and Rigid Motions
**Learn:** Two figures are **congruent** exactly when a sequence of rigid motions maps one onto the other. In congruent figures, corresponding parts are congruent: **CPCTC** ("corresponding parts of congruent triangles are congruent"). Write congruence statements in matching order: if △ABC ≅ △DEF, then A↔D, B↔E, C↔F.

### 4.2 Congruence Criteria
**Learn:** Triangles are congruent by:
- **SSS**: three pairs of sides.
- **SAS**: two sides and the **included** angle.
- **ASA**: two angles and the **included** side.
- **AAS**: two angles and a non-included side.
- **HL** (right triangles only): hypotenuse and a leg.
- **Not valid**: SSA (the "ambiguous case") and AAA (that only gives similarity).

**Example:** Given AB ≅ DE, ∠B ≅ ∠E, BC ≅ EF. The angle sits between the two sides, so the triangles are congruent by **SAS**.

### 4.3 Isosceles and Equilateral Triangles
**Learn:**
- **Isosceles Triangle Theorem**: if two sides are congruent, the angles opposite them (base angles) are congruent. The converse is also true.
- An equilateral triangle is also equiangular, with each angle 60°.
- The bisector of an isosceles triangle's vertex angle is the perpendicular bisector of the base.

**Example:** The vertex angle is 40°, so the base angles are (180 − 40)/2 = **70°** each.

### 4.4 Congruence Proofs (including overlapping triangles)
**Example:** Given: M is the midpoint of AB, and PM ⟂ AB. Prove: PA ≅ PB.
| Statement | Reason |
|---|---|
| 1. M is the midpoint of AB | Given |
| 2. AM ≅ MB | Definition of midpoint |
| 3. PM ⟂ AB | Given |
| 4. ∠PMA and ∠PMB are right angles, so ∠PMA ≅ ∠PMB | Definition of perpendicular; all right angles are congruent |
| 5. PM ≅ PM | Reflexive Property |
| 6. △PMA ≅ △PMB | SAS |
| 7. PA ≅ PB | CPCTC |

(This proves the **Perpendicular Bisector Theorem**.)

Tips: mark the diagram with everything given; look for shared sides (Reflexive) and vertical angles; for overlapping triangles, redraw them separately.

**Practice:**
1. Which criterion, if any: (a) two angles and the included side (b) two sides and a non-included angle (c) right triangles with congruent hypotenuses and one pair of congruent legs?
2. An isosceles triangle has base angles of (3x + 5)° each and vertex angle (2x)°. Find all angles.
3. Prove: if AC bisects ∠BAD and ∠B ≅ ∠D, then △ABC ≅ △ADC.

**Unit 4 answers:** 1) (a) ASA (b) none, SSA isn't valid (c) HL 2) 2(3x + 5) + 2x = 180, x = 21.25; base angles 68.75°, vertex 42.5° 3) ∠BAC ≅ ∠DAC (definition of angle bisector), ∠B ≅ ∠D (given), AC ≅ AC (Reflexive), so congruent by AAS.

---

## Unit 5: Relationships Within Triangles

### 5.1 Bisector Theorems
**Learn:**
- **Perpendicular Bisector Theorem**: any point on the perpendicular bisector of a segment is equidistant from the endpoints (the converse is also true).
- **Angle Bisector Theorem**: any point on an angle bisector is equidistant from the two sides of the angle (distance measured perpendicularly).

### 5.2 Points of Concurrency
| Point | Formed by | Key fact |
|---|---|---|
| **Circumcenter** | perpendicular bisectors | Equidistant from the **vertices**; center of the circumscribed circle |
| **Incenter** | angle bisectors | Equidistant from the **sides**; center of the inscribed circle; always inside |
| **Centroid** | medians (vertex to midpoint of the opposite side) | Divides each median **2:1** (the longer part is at the vertex); balance point |
| **Orthocenter** | altitudes | Inside for acute, at the right-angle vertex for right, outside for obtuse triangles |

Circumcenter location: inside an acute triangle, at the hypotenuse midpoint of a right triangle, outside an obtuse triangle.

**Example:** A median is 18 long. The centroid is **12** from the vertex and **6** from the midpoint.

### 5.3 Midsegment Theorem
**Learn:** The segment joining the midpoints of two sides of a triangle is **parallel** to the third side and **half** as long.

### 5.4 Triangle Inequalities
**Learn:**
- **Triangle Inequality**: the sum of any two sides is greater than the third. If two sides are a and b, the third side c satisfies |a − b| < c < a + b.
- The longest side is opposite the largest angle (and the shortest side is opposite the smallest angle).
- **Hinge Theorem (SAS Inequality)**: if two triangles have two pairs of congruent sides, the triangle with the larger included angle has the longer third side.

**Practice:**
1. A midsegment is parallel to a side of length 14. How long is it?
2. Two sides of a triangle are 5 and 9. What are the possible lengths of the third side?
3. Can 4, 7 and 12 be the side lengths of a triangle?
4. In △ABC, m∠A = 50°, m∠B = 70°. List the sides from shortest to longest.
5. Which point of concurrency is the best place for a cell tower equidistant from three towns?

**Unit 5 answers:** 1) 7 2) 4 < x < 14 3) No (4 + 7 < 12) 4) m∠C = 60°, so BC (opposite A), AB (opposite C), AC (opposite B) 5) Circumcenter

---

## Unit 6: Quadrilaterals and Other Polygons

### 6.1 Polygon Angle Sums
**Learn:**
- Interior angle sum of an n-gon = **(n − 2)·180°**.
- Exterior angle sum (one at each vertex) = **360°** for any convex polygon.
- Regular n-gon: each interior angle = (n − 2)·180°/n; each exterior angle = 360°/n.

**Example:** A regular polygon has exterior angles of 24°, so n = 360/24 = **15** sides.

### 6.2 Parallelograms
**Properties** (if it's a parallelogram, then): opposite sides are parallel and congruent; opposite angles are congruent; consecutive angles are supplementary; the diagonals bisect each other.
**Tests** (it IS a parallelogram if): both pairs of opposite sides are congruent; or both pairs of opposite angles are congruent; or the diagonals bisect each other; or **one** pair of opposite sides is both congruent and parallel.

### 6.3 Rectangles, Rhombuses, Squares
- **Rectangle**: a parallelogram with 4 right angles, so its **diagonals are congruent**.
- **Rhombus**: a parallelogram with 4 congruent sides, so its **diagonals are perpendicular** and bisect the angles.
- **Square**: both a rectangle and a rhombus, so it has all of the above.

### 6.4 Trapezoids and Kites
- **Trapezoid**: exactly one pair of parallel sides (the bases).
- **Isosceles trapezoid**: congruent legs, so each pair of base angles is congruent and the diagonals are congruent.
- **Trapezoid Midsegment** = (base₁ + base₂)/2, parallel to the bases.
- **Kite**: two pairs of consecutive congruent sides; diagonals are perpendicular; one pair of opposite angles is congruent.

### 6.5 Coordinate Proofs with Polygons
**Learn:** Use **slope** to test for parallel/perpendicular sides, the **distance formula** for congruent sides, and the **midpoint formula** to check whether diagonals bisect each other.

**Example:** Is A(0, 0), B(4, 1), C(5, 5), D(1, 4) a rhombus? Every side is √17 (for example AB = √(16 + 1)), so all sides are congruent: **yes**. Diagonal slopes: AC = 1, BD = −1, so the diagonals are perpendicular, which confirms it. It is not a square: the slopes of AB and AD are ¼ and 4, which are not negative reciprocals, so there are no right angles.

**Practice:**
1. Find the interior angle sum of a hexagon and the measure of each angle of a regular hexagon.
2. In a parallelogram, consecutive angles are (3x)° and (x + 20)°. Find both angles.
3. A trapezoid has bases 10 and 18. Find its midsegment.
4. A rectangle's diagonals are 2x + 6 and 5x − 9. Find x.
5. Show that P(1, 1), Q(5, 3), R(4, 5), S(0, 3) is a parallelogram. Is it a rectangle?

**Unit 6 answers:** 1) 720°, 120° 2) x = 40; 120° and 60° 3) 14 4) x = 5 5) Slopes: PQ = ½, SR = ½, QR = −2, PS = −2. Opposite sides are parallel, so it's a parallelogram. ½ · (−2) = −1, so adjacent sides are perpendicular and it **is** a rectangle.

---

## Unit 7: Similarity

### 7.1 Dilations
**Learn:** A dilation with center C and **scale factor k** maps each point P to P′ on ray CP with CP′ = k·CP.
- Centered at the origin: (x, y) → (kx, ky).
- k > 1 enlarges; 0 < k < 1 reduces.
- A dilation maps a line not through the center to a **parallel** line, and multiplies every segment length by k. Angles are preserved.

### 7.2 Similarity Transformations
**Learn:** Two figures are **similar** (~) if a dilation plus rigid motions maps one onto the other. Similar polygons have congruent corresponding angles and **proportional** sides. Perimeters scale by k, areas by **k²**, volumes by **k³**.

### 7.3 Proving Triangles Similar
- **AA~**: two pairs of congruent angles.
- **SSS~**: all three side ratios are equal.
- **SAS~**: two side ratios are equal and the included angles are congruent.

**Example:** Triangles with sides 6, 8, 10 and 9, 12, 15: every ratio is 1.5, so they're similar by **SSS~**.

### 7.4 Proportions in Triangles
- **Side-Splitter (Triangle Proportionality) Theorem**: a line parallel to one side of a triangle divides the other two sides proportionally.
- **Triangle Angle Bisector Theorem**: an angle bisector divides the opposite side in the ratio of the adjacent sides.

### 7.5 Similarity in Right Triangles
**Learn:** The altitude to the hypotenuse creates three similar triangles. If the hypotenuse is split into segments x and y:
- altitude h = √(xy) (the **geometric mean**)
- each leg = √(hypotenuse × the adjacent segment)
- The Pythagorean theorem can be proven this way (G-SRT.4).

### 7.6 Partitioning a Segment
**Learn:** The point P that divides AB in the ratio m:n (from A) is P = A + (m/(m + n))·(B − A), applied to each coordinate.

**Example:** A(1, 2), B(7, 11), ratio 1:2. The fraction is ⅓: P = (1 + ⅓·6, 2 + ⅓·9) = **(3, 5)**.

**Practice:**
1. Dilate (4, −6) by k = ½ centered at the origin.
2. Two similar triangles have scale factor 3. The small one has area 10. Find the large one's area.
3. In △ABC, DE ∥ BC with D on AB and E on AC. AD = 6, DB = 4, AE = 9. Find EC.
4. The altitude to the hypotenuse splits it into segments 4 and 9. Find the altitude.
5. Find the point ¾ of the way from A(−2, 0) to B(6, 8).

**Unit 7 answers:** 1) (2, −3) 2) 90 3) 6/4 = 9/EC, EC = 6 4) √36 = 6 5) (−2 + 6, 0 + 6) = (4, 6)

---

## Unit 8: Right Triangles and Trigonometry

### 8.1 Pythagorean Theorem and Its Converse
**Learn:** a² + b² = c² (c is the hypotenuse). Converse: if c² = a² + b², the triangle is right. If c² < a² + b² it's acute; if c² > a² + b² it's obtuse. Common triples: 3-4-5, 5-12-13, 8-15-17, 7-24-25 (and their multiples).

### 8.2 Special Right Triangles
- **45°-45°-90°**: legs x, x; hypotenuse **x√2**.
- **30°-60°-90°**: short leg x (opposite 30°); long leg **x√3**; hypotenuse **2x**.

### 8.3 Trigonometric Ratios
**Learn (SOH-CAH-TOA):** sin A = opposite/hypotenuse, cos A = adjacent/hypotenuse, tan A = opposite/adjacent.
- Similar right triangles have the same ratios, which is why trig works (G-SRT.6).
- **Cofunctions**: sin A = cos(90° − A) (G-SRT.7). Example: sin 30° = cos 60° = ½.

### 8.4 Solving Right Triangles
**Learn:** Use trig to find missing sides; use inverse trig (sin⁻¹, cos⁻¹, tan⁻¹) to find missing angles. **Angle of elevation** is measured up from horizontal; **angle of depression** is measured down from horizontal (and they are equal by alternate interior angles).

**Example:** A ladder 20 ft long makes a 70° angle with the ground. Height reached = 20 sin 70° ≈ **18.8 ft**.

**Example:** A 6 ft person's shadow is 8 ft. Angle of elevation of the sun = tan⁻¹(6/8) ≈ **36.9°**.

### 8.5 Law of Sines, Law of Cosines, and Triangle Area (any triangle)
- **Area** = ½ab sin C.
- **Law of Sines**: a/sin A = b/sin B = c/sin C. Use it for AAS, ASA, and SSA (SSA may have 0, 1 or 2 triangles: the ambiguous case).
- **Law of Cosines**: c² = a² + b² − 2ab cos C. Use it for SAS and SSS.

**Example:** a = 7, b = 8, C = 60°: c² = 49 + 64 − 2(7)(8)(0.5) = 57, so c ≈ **7.55**. Area = ½(7)(8) sin 60° ≈ **24.25**.

**Practice:**
1. Sides 9, 12, 15: acute, right or obtuse? What about 6, 7, 10?
2. The leg of a 45-45-90 triangle is 7. Find the hypotenuse.
3. The hypotenuse of a 30-60-90 triangle is 10. Find both legs.
4. A right triangle has a 35° angle and hypotenuse 20. Find the side opposite 35°.
5. A plane flying at 5,000 ft sees an airport at an angle of depression of 8°. Horizontal distance?
6. A = 40°, B = 60°, a = 10. Find b.
7. Sides 5, 7, 9. Find the largest angle.

**Unit 8 answers:** 1) Right (81 + 144 = 225); obtuse (100 > 36 + 49) 2) 7√2 ≈ 9.90 3) 5 and 5√3 ≈ 8.66 4) 20 sin 35° ≈ 11.47 5) 5000/tan 8° ≈ 35,577 ft 6) b = 10 sin 60°/sin 40° ≈ 13.47 7) cos C = (25 + 49 − 81)/(70) = −0.1, C ≈ 95.7°

---

## Unit 9: Coordinate Geometry

### 9.1 Polygons on the Coordinate Plane
**Learn:** Use distance for perimeter. For area, use base × height with perpendicular lines, or enclose the shape in a rectangle and subtract the corner triangles.

**Example:** Triangle (0, 0), (6, 0), (2, 5): base 6, height 5, area **15**.

### 9.2 Equation of a Circle
**Learn:** A circle with center (h, k) and radius r: **(x − h)² + (y − k)² = r²** (derived from the distance formula). To find the center and radius from expanded form, **complete the square**.

**Example:** x² + y² − 6x + 4y − 12 = 0
→ (x² − 6x + 9) + (y² + 4y + 4) = 12 + 9 + 4
→ (x − 3)² + (y + 2)² = 25. Center **(3, −2)**, radius **5**.

### 9.3 Parabolas from Focus and Directrix
**Learn:** A parabola is all points equidistant from a **focus** point and a **directrix** line. With vertex (h, k) and p = the distance from vertex to focus:
- Opens up/down: (x − h)² = 4p(y − k)
- Opens left/right: (y − k)² = 4p(x − h)

**Example:** Focus (0, 2) and directrix y = −2 give vertex (0, 0), p = 2: x² = 8y, i.e. **y = x²/8**.

### 9.4 Coordinate Proofs
**Learn:** Place the figure conveniently (a vertex at the origin, a side on the x-axis) and use variables, such as (0, 0), (2a, 0), (2b, 2c) for a general triangle (using 2's keeps midpoints clean). Then prove with slope, distance and midpoint.

**Example:** Prove the midsegment theorem. Midpoints of the sides from (0, 0) and (2a, 0) to (2b, 2c) are (b, c) and (a + b, c). The midsegment has slope 0 (parallel to the base, which has slope 0) and length a, which is half the base 2a. ✓

**Practice:**
1. Write the equation of the circle with center (−1, 4) and radius 3.
2. Find the center and radius: x² + y² + 8x − 2y − 8 = 0.
3. Does (4, 5) lie on (x − 1)² + (y − 1)² = 25?
4. Write the equation of the parabola with focus (2, 3) and directrix y = −1.

**Unit 9 answers:** 1) (x + 1)² + (y − 4)² = 9 2) (x + 4)² + (y − 1)² = 25; center (−4, 1), r = 5 3) 9 + 16 = 25, yes 4) Vertex (2, 1), p = 2: (x − 2)² = 8(y − 1)

---

## Unit 10: Circles

### 10.1 Arcs, Arc Length, Sectors, Radians
**Learn:**
- **Central angle** = the measure of its intercepted arc. Minor arc < 180°, major arc > 180°, semicircle = 180°.
- **Arc length** = (θ/360°)·2πr. **Sector area** = (θ/360°)·πr².
- **Radian measure** = arc length ÷ radius (s = rθ with θ in radians). 180° = π radians.
- **All circles are similar** (any circle can be dilated onto any other).

**Example:** r = 6, θ = 120°: arc length = ⅓·12π = **4π ≈ 12.57**; sector area = ⅓·36π = **12π ≈ 37.70**.

### 10.2 Tangents
**Learn:** A tangent is **perpendicular** to the radius at the point of tangency. Two tangent segments from the same outside point are **congruent**.

**Example:** A tangent segment from P touches the circle at T. The radius is 5 and the distance from P to the center is 13. Then PT = √(169 − 25) = **12**.

### 10.3 Chords
**Learn:** Congruent chords ⇔ congruent arcs ⇔ equidistant from the center. A diameter (or radius) perpendicular to a chord **bisects** the chord and its arc.

### 10.4 Inscribed Angles
**Learn:**
- **Inscribed angle = ½ its intercepted arc.**
- An angle inscribed in a semicircle is a **right angle**.
- Inscribed angles that intercept the same arc are congruent.
- Opposite angles of an **inscribed quadrilateral** are **supplementary**.
- The angle between a tangent and a chord = ½ the intercepted arc.

### 10.5 Other Angles and Segment Lengths
**Angles:**
- Vertex **inside** the circle (two chords): angle = ½(sum of the intercepted arcs).
- Vertex **outside** (secants/tangents): angle = ½(far arc − near arc).

**Segments:**
- Two chords intersecting: (part)(part) = (part)(part), so a·b = c·d.
- Two secants from an outside point: (outside)(whole) = (outside)(whole).
- Tangent and secant: tangent² = (outside)(whole).

**Practice:**
1. Convert 120° to radians and 3π/4 to degrees.
2. An inscribed angle intercepts a 110° arc. Find the angle.
3. ABCD is inscribed in a circle and m∠A = 75°. Find m∠C.
4. Two chords intersect. One is split into 3 and 8; the other into 4 and x. Find x.
5. From an outside point, a tangent has length t; a secant has an outside part of 4 and a whole length of 9. Find t.
6. Two secants from an outside point intercept arcs of 130° and 50°. Find the angle.
7. A chord of length 16 is 6 units from the center. Find the radius.

**Unit 10 answers:** 1) 2π/3; 135° 2) 55° 3) 105° 4) 3·8 = 4x, x = 6 5) t² = 36, t = 6 6) ½(130 − 50) = 40° 7) √(8² + 6²) = 10

---

## Unit 11: Area, Surface Area, and Volume

### 11.1 Area Review
Rectangle bh; parallelogram bh; triangle ½bh; trapezoid ½(b₁ + b₂)h; rhombus/kite ½d₁d₂; circle πr²; regular polygon ½·apothem·perimeter.

### 11.2 Cross Sections and Solids of Revolution
**Learn:** A **cross section** is the 2D shape you get when you slice a solid with a plane (slicing a cube can give a square, rectangle, triangle, or even a hexagon). Rotating a 2D shape around a line makes a **solid of revolution**: a rectangle makes a cylinder, a right triangle makes a cone, a semicircle makes a sphere.

### 11.3 Volume
**Learn:**
- **Cavalieri's Principle**: solids with the same height and equal cross-sectional areas at every level have equal volumes (so oblique solids use the same formulas).
- Prism and cylinder: V = Bh (B = base area), so a cylinder is V = πr²h.
- Pyramid and cone: V = ⅓Bh, so a cone is V = ⅓πr²h.
- Sphere: V = (4/3)πr³.

### 11.4 Surface Area
- Prism: 2B + (perimeter)h. Cylinder: 2πr² + 2πrh.
- Pyramid: B + ½(perimeter)(slant height ℓ). Cone: πr² + πrℓ.
- Sphere: 4πr².

### 11.5 Modeling with Geometry (G-MG)
**Learn:** **Density** = mass/volume (or people/area for population density). Design problems: minimize cost or material subject to a constraint.

**Example:** A town of 12,000 people covers a 3 mi × 4 mi rectangle. Population density = 12,000/12 = **1,000 people/mi²**.

**Practice:**
1. Volume of a cylinder with r = 3, h = 10.
2. Volume of a cone with the same r and h.
3. Volume and surface area of a sphere with r = 6.
4. Volume of a square pyramid with base side 6 and height 10.
5. A metal block of 200 cm³ has a mass of 500 g. Find its density.
6. If every dimension of a solid is doubled, what happens to its volume?

**Unit 11 answers:** 1) 90π ≈ 282.7 2) 30π ≈ 94.2 3) V = 288π ≈ 904.8; SA = 144π ≈ 452.4 4) 120 5) 2.5 g/cm³ 6) It is multiplied by 8.

---

## Unit 12: Probability

### 12.1 Sample Spaces and Events
**Learn:** The **sample space** is all possible outcomes. An **event** is a subset. For equally likely outcomes, P(A) = (favorable)/(total). **Complement**: P(not A) = 1 − P(A). **Union** A ∪ B = "A or B". **Intersection** A ∩ B = "A and B".

### 12.2 Addition Rule
**Learn:** P(A or B) = P(A) + P(B) − P(A and B). If A and B are **mutually exclusive** (can't happen together), P(A or B) = P(A) + P(B).

**Example:** Drawing a card: P(heart or king) = 13/52 + 4/52 − 1/52 = **16/52 = 4/13**.

### 12.3 Conditional Probability and Independence
**Learn:**
- **Conditional**: P(B | A) = P(A and B)/P(A), "the probability of B given A."
- **Independent** events: P(A and B) = P(A)·P(B), equivalently P(B | A) = P(B).
- Multiplication rule (general): P(A and B) = P(A)·P(B | A).

### 12.4 Two-Way Tables
**Example:** 100 students: 60 play a sport; of those, 40 also play music. 30 of the 40 non-athletes play music.
| | Music | No music | Total |
|---|---|---|---|
| Sport | 40 | 20 | 60 |
| No sport | 30 | 10 | 40 |
| Total | 70 | 30 | 100 |

P(music | sport) = 40/60 = **2/3**. P(music) = 0.70. Because 2/3 ≠ 0.70, playing a sport and playing music are **not independent** (though they're close).

### 12.5 Counting: Permutations and Combinations
**Learn:**
- **Fundamental Counting Principle**: multiply the number of choices at each stage.
- **Permutations** (order matters): ₙPᵣ = n!/(n − r)!
- **Combinations** (order doesn't matter): ₙCᵣ = n!/(r!(n − r)!)
- Probability with counting: P = (number of favorable selections)/(total selections).

**Example:** Choose a president, VP and secretary from 10 people: ₁₀P₃ = **720**. Choose a 3-person committee: ₁₀C₃ = **120**.

### 12.6 Expected Value and Fair Decisions
**Learn:** Expected value E = Σ(value × probability). A game is **fair** when E = 0.

**Example:** Pay $3 to play; win $10 with probability 0.2. E = 0.2(10) − 3 = **−$1** per game (unfair).

**Practice:**
1. A die is rolled. P(even or greater than 4)?
2. P(A) = 0.5, P(B) = 0.4, independent. Find P(A and B) and P(A or B).
3. Two cards are drawn without replacement. P(both aces)?
4. How many 5-card hands come from 52 cards?
5. In the two-way table above, find P(sport | music).
6. A raffle sells 500 tickets at $2. One prize of $300. Expected value of one ticket?

**Unit 12 answers:** 1) Outcomes {2, 4, 5, 6} → 4/6 = 2/3 2) 0.2; 0.7 3) (4/52)(3/51) = 1/221 4) ₅₂C₅ = 2,598,960 5) 40/70 = 4/7 6) 300/500 − 2 = −$1.40
