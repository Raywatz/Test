# Algebra 2: Full Lesson Plan

Standards covered: N-CN (complex numbers), N-RN (rational exponents), A-SSE, A-APR, A-CED, A-REI (expressions, polynomials, equations), F-IF, F-BF, F-LE (functions, building functions, exponential models), F-TF (trigonometric functions), S-ID, S-IC, S-CP, S-MD (statistics and probability).

Tip: graph every function in this course in Desmos as you study it. Seeing the graph move when you change a number is the fastest way to understand transformations.

---

## Unit 1: Functions, Linear Models, and Systems

### 1.1 Key Features of Functions
**Learn:**
- A **function** assigns each input exactly one output (vertical line test).
- **Domain** = allowed inputs; **range** = outputs.
- Key features: x- and y-intercepts, intervals where the function is increasing or decreasing, positive or negative, relative maximums and minimums, symmetry, and **end behavior** (what f(x) does as x → ±∞).
- **Average rate of change** from a to b = (f(b) − f(a))/(b − a), the slope between the two points.

**Example:** f(x) = x² from x = 1 to 4: (16 − 1)/(4 − 1) = **5**.

### 1.2 Parent Functions and Transformations
**Learn:** Parent functions: linear x, quadratic x², cubic x³, absolute value |x|, square root √x, cube root ∛x, reciprocal 1/x, exponential bˣ.
For g(x) = a·f(b(x − h)) + k:
- **h**: shift right h (left if negative). Note the sign flips inside the parentheses.
- **k**: shift up k.
- **a**: vertical stretch (|a| > 1) or compression (|a| < 1); a < 0 reflects over the x-axis.
- **b**: horizontal compression by a factor of 1/|b|; b < 0 reflects over the y-axis.

**Example:** g(x) = −2|x − 3| + 1 is |x| reflected over the x-axis, stretched by 2, and moved right 3 and up 1. The vertex is **(3, 1)** and it opens down.

### 1.3 Piecewise, Absolute Value, and Step Functions
**Learn:** A **piecewise** function uses different rules on different intervals. Graph each piece only on its interval: a closed dot means included, an open dot means excluded. **Step functions** such as the greatest integer function ⌊x⌋ look like stairs.

**Example:** f(x) = { x + 2 if x < 0; x² if x ≥ 0 }. Then f(−3) = −1 and f(3) = 9.

### 1.4 Arithmetic Sequences
**Learn:** Add the same **common difference d** each time.
- Explicit: aₙ = a₁ + (n − 1)d
- Recursive: a₁ = (start), aₙ = aₙ₋₁ + d
- An arithmetic sequence is a linear function whose domain is the positive integers.

### 1.5 Solving Equations and Inequalities by Graphing
**Learn:** To solve f(x) = g(x), graph y = f(x) and y = g(x); the x-coordinates of the intersections are the solutions (A-REI.11). This works for any function types, which is why it's used all year.

### 1.6 Systems of Equations in Three Variables
**Learn:** Use elimination to remove one variable from two different pairs of equations. Solve the resulting 2×2 system, then back-substitute. Geometrically, each equation is a plane, so a system can have one point, no solution, or infinitely many solutions.

**Example:** x + y + z = 6, 2x − y + z = 3, x + 2y − z = 2.
- (1) + (3): 2x + 3y = 8
- (1) − (2): −x + 2y = 3, so x = 2y − 3
- Substitute: 2(2y − 3) + 3y = 8, so y = 2, x = 1, z = 3. **(1, 2, 3)**

### 1.7 Systems of Inequalities and Linear Programming
**Learn:** Graph each inequality (dashed line for < or >, solid for ≤ or ≥) and shade; the overlap is the **feasible region**. In **linear programming**, the maximum or minimum of an objective such as P = 3x + 2y occurs at a **vertex** of the feasible region, so test each vertex.

**Practice:**
1. Average rate of change of f(x) = x³ from x = 0 to x = 2.
2. Describe g(x) = (x + 4)² − 5 as a transformation of x², and give the vertex.
3. Find a₂₀ for 7, 11, 15, …
4. Solve: x − y + 2z = 5, 2x + y − z = 1, x + y + z = 6.
5. Maximize P = 3x + 2y subject to x ≥ 0, y ≥ 0, x + y ≤ 8, x ≤ 5.

**Unit 1 answers:** 1) (8 − 0)/2 = 4 2) Left 4, down 5; vertex (−4, −5) 3) 7 + 19·4 = 83 4) (1, 2, 3) 5) Vertices (0,0), (5,0), (5,3), (0,8): P = 0, 15, 21, 16, so the maximum is 21 at (5, 3).

---

## Unit 2: Quadratic Functions, Equations, and Complex Numbers

### 2.1 Forms of a Quadratic Function
| Form | Equation | Shows |
|---|---|---|
| Vertex | y = a(x − h)² + k | Vertex (h, k); axis x = h |
| Standard | y = ax² + bx + c | y-intercept c; vertex at x = −b/(2a) |
| Factored (intercept) | y = a(x − p)(x − q) | x-intercepts p, q; axis halfway between them |

a > 0 opens up (has a minimum); a < 0 opens down (has a maximum).

**Example:** y = 2x² − 8x + 3. Vertex x = 8/4 = 2, y = 8 − 16 + 3 = −5, so the vertex is **(2, −5)**, a minimum.

### 2.2 Modeling with Quadratics
**Learn:** Projectile motion: h(t) = −16t² + v₀t + h₀ (feet) or −4.9t² + v₀t + h₀ (meters). The maximum height is at the vertex; the ball lands where h = 0. You can also fit a quadratic through 3 points by solving a 3×3 system, or with regression on a calculator.

**Example:** h(t) = −16t² + 64t + 5. Maximum at t = 64/32 = 2 s, height = −64 + 128 + 5 = **69 ft**.

### 2.3 Solving by Factoring
**Learn:** GCF first, then trinomials, **difference of squares** a² − b² = (a − b)(a + b), and **perfect squares** a² ± 2ab + b² = (a ± b)². Use the **Zero Product Property**: if AB = 0, then A = 0 or B = 0.

### 2.4 Complex Numbers
**Learn:**
- i = √−1, so i² = −1. Powers cycle in fours: i, −1, −i, 1. To find iⁿ, use the remainder of n ÷ 4.
- A complex number is a + bi. Add and subtract like terms. Multiply with FOIL and replace i² with −1.
- The **conjugate** of a + bi is a − bi, and (a + bi)(a − bi) = a² + b². Divide by multiplying the top and bottom by the conjugate of the denominator.

**Example:** (3 + 2i)(1 − 4i) = 3 − 12i + 2i − 8i² = **11 − 10i**.
**Example:** (2 + i)/(1 − i) = (2 + i)(1 + i)/2 = (2 + 3i + i²)/2 = **(1 + 3i)/2**.

### 2.5 Completing the Square
**Learn:** For x² + bx, add (b/2)² to make (x + b/2)². Use it to solve equations and to convert to vertex form.

**Example:** x² + 6x − 7 = 0 → x² + 6x + 9 = 16 → (x + 3)² = 16 → x + 3 = ±4 → **x = 1 or −7**.

### 2.6 Quadratic Formula and the Discriminant
**Learn:** x = (−b ± √(b² − 4ac))/(2a). The **discriminant** b² − 4ac tells you the kind of solutions:
- positive: two real solutions (2 x-intercepts)
- zero: one real (double) solution (touches the x-axis)
- negative: two complex conjugate solutions (no x-intercepts)

**Example:** x² − 4x + 13 = 0: x = (4 ± √(16 − 52))/2 = (4 ± 6i)/2 = **2 ± 3i**.

### 2.7 Linear-Quadratic Systems
**Learn:** Substitute the linear equation into the quadratic. A line can meet a parabola (or circle) in 0, 1 or 2 points.

**Example:** y = x² and y = x + 2 → x² − x − 2 = 0 → x = 2 or −1 → **(2, 4) and (−1, 1)**.

**Practice:**
1. Write y = x² − 10x + 21 in vertex form and factored form.
2. Factor: 3x² + 10x − 8.
3. Simplify i²³ and (4 − 3i) − (−2 + 5i).
4. Divide: (3 + 4i)/(2 − i).
5. Solve by completing the square: x² − 8x + 5 = 0.
6. Use the discriminant to classify the roots of 2x² + 3x + 5 = 0, then solve.
7. Solve the system x² + y² = 25 and y = x + 1.

**Unit 2 answers:** 1) (x − 5)² − 4; (x − 3)(x − 7) 2) (3x − 2)(x + 4) 3) i²³ = i³ = −i; 6 − 8i 4) (3 + 4i)(2 + i)/5 = (2 + 11i)/5 5) x = 4 ± √11 6) D = −31: two complex roots, x = (−3 ± i√31)/4 7) x² + (x + 1)² = 25 → x² + x − 12 = 0 → (3, 4) and (−4, −3)

---

## Unit 3: Polynomial Functions

### 3.1 Graphs of Polynomial Functions
**Learn:**
- **Degree** n and **leading coefficient** determine end behavior:
  - even degree, positive leading coefficient: up on both ends; even, negative: down on both ends
  - odd degree, positive: down on the left, up on the right; odd, negative: up on the left, down on the right
- At most n real zeros and at most n − 1 turning points.
- **Multiplicity**: a zero from (x − r)ᵏ crosses the x-axis if k is odd and **touches and turns** if k is even.

**Example:** f(x) = (x − 1)²(x + 3) has degree 3 with positive leading coefficient. It crosses at −3, touches at 1, falls to the left and rises to the right.

### 3.2 Polynomial Operations and Identities
**Learn:** Add, subtract and multiply polynomials. Key identities (A-APR.4):
- (a + b)² = a² + 2ab + b²
- a³ + b³ = (a + b)(a² − ab + b²) and a³ − b³ = (a − b)(a² + ab + b²)
- **Binomial Theorem**: the coefficients of (a + b)ⁿ come from row n of **Pascal's Triangle** (or ₙCₖ).
  - (x + 2)⁴ = x⁴ + 4x³(2) + 6x²(4) + 4x(8) + 16 = x⁴ + 8x³ + 24x² + 32x + 16
- Polynomial identities can generate things like Pythagorean triples: (x² − y²)² + (2xy)² = (x² + y²)².

### 3.3 Dividing Polynomials
**Learn:** **Long division** works for any divisor. **Synthetic division** works for divisors of the form (x − a).
- **Remainder Theorem**: dividing P(x) by (x − a) leaves remainder P(a).
- **Factor Theorem**: (x − a) is a factor ⇔ P(a) = 0.

**Example:** Divide x³ + 2x² − 5x − 6 by (x − 2). Synthetic division with 2 on the coefficients 1, 2, −5, −6:
bring down 1 → 1·2 = 2, 2 + 2 = 4 → 4·2 = 8, −5 + 8 = 3 → 3·2 = 6, −6 + 6 = **0**.
Quotient x² + 4x + 3 = (x + 1)(x + 3). The zeros are **2, −1, −3**.

### 3.4 Finding All Zeros
**Learn:**
- **Rational Root Theorem**: possible rational roots = ±(factors of the constant)/(factors of the leading coefficient).
- **Fundamental Theorem of Algebra**: a degree-n polynomial has exactly **n** complex roots, counting multiplicity.
- **Conjugate Root Theorem**: with real coefficients, complex roots come in pairs a ± bi; with rational coefficients, irrational roots come in pairs a ± √b.
- Strategy: list the candidates, test them with synthetic division, factor down to a quadratic, then use the quadratic formula.

**Example:** Write a polynomial with roots 2 and 3i. Then −3i is also a root: (x − 2)(x² + 9) = **x³ − 2x² + 9x − 18**.

### 3.5 Solving Polynomial Equations
**Learn:** Factor by grouping or recognize patterns, including **quadratic form**: x⁴ − 5x² + 4 = (x² − 1)(x² − 4), so x = ±1, ±2.

**Practice:**
1. Describe the end behavior of f(x) = −2x⁵ + 3x² − 1.
2. Find the zeros and multiplicities of f(x) = x²(x − 4)³(x + 1). Where does the graph touch, and where does it cross?
3. Use the Remainder Theorem: P(x) = x³ − 4x + 1, find the remainder when dividing by (x − 3).
4. List the possible rational roots of 2x³ − 3x² − 11x + 6, then find all roots.
5. Factor x³ − 27.
6. Expand (2x − 1)³.
7. Solve x³ + x² − 4x − 4 = 0 by grouping.

**Unit 3 answers:** 1) Rises to the left (→ +∞ as x → −∞), falls to the right 2) 0 (multiplicity 2, touches), 4 (mult. 3, crosses), −1 (mult. 1, crosses) 3) 27 − 12 + 1 = 16 4) ±1, ±2, ±3, ±6, ±½, ±3/2; roots 3, −2, ½ 5) (x − 3)(x² + 3x + 9) 6) 8x³ − 12x² + 6x − 1 7) x²(x + 1) − 4(x + 1) = (x + 1)(x − 2)(x + 2), so x = −1, 2, −2

---

## Unit 4: Rational Functions

### 4.1 Inverse and Joint Variation
**Learn:** Direct variation y = kx. **Inverse** variation y = k/x (xy = k). **Joint** variation y = kxz. Find k from one data point, then use it.

**Example:** y varies inversely with x, and y = 6 when x = 4. Then k = 24, so when x = 8, **y = 3**.

### 4.2 Graphing Rational Functions
**Learn:** For f(x) = P(x)/Q(x), factor first.
- **Hole**: a factor cancels from the top and bottom (plug x into the simplified form to find the hole's y-value).
- **Vertical asymptote**: a zero of the denominator that does **not** cancel.
- **Horizontal asymptote** (compare degrees):
  - top degree < bottom degree: y = 0
  - degrees equal: y = (leading coefficient on top)/(leading coefficient on bottom)
  - top degree > bottom degree: no horizontal asymptote (if exactly one more, there's a **slant** asymptote, found by division)
- Translated reciprocal: f(x) = a/(x − h) + k has asymptotes x = h and y = k.

**Example:** f(x) = (x + 1)/(x² − 1) = (x + 1)/((x − 1)(x + 1)) = 1/(x − 1) for x ≠ −1. Hole at **(−1, −½)**, vertical asymptote **x = 1**, horizontal asymptote **y = 0**.

### 4.3 Operations with Rational Expressions
**Learn:** Treat them like fractions. Factor everything first.
- Multiply: multiply across and cancel common factors. Divide: multiply by the reciprocal.
- Add/subtract: find the LCD, rewrite each fraction, combine the numerators.
- State excluded values (anything making an original denominator 0).
- Complex fractions: multiply the top and bottom by the LCD of all the little fractions.

**Example:** 1/x + 2/(x + 1) = ((x + 1) + 2x)/(x(x + 1)) = **(3x + 1)/(x(x + 1))**.

### 4.4 Solving Rational Equations
**Learn:** Multiply both sides by the LCD, solve, and **check for extraneous solutions** (any answer that makes a denominator 0 is rejected).

**Example:** x/(x − 3) = 3/(x − 3) + 2. Multiply by (x − 3): x = 3 + 2(x − 3), so x = 3. But x = 3 makes a denominator 0, so there is **no solution**.

**Practice:**
1. z varies jointly with x and y. z = 24 when x = 2, y = 3. Find z when x = 5, y = 4.
2. Find the asymptotes and holes of f(x) = (3x² + 1)/(x² − 4).
3. Simplify (x² − 9)/(x² + 5x + 6).
4. Simplify (x² − 4)/(x + 3) ÷ (x − 2)/(x² + 3x).
5. Solve 2/x + 1/3 = 1.
6. Work problem: pipe A fills a pool in 6 h and pipe B in 3 h. How long together?

**Unit 4 answers:** 1) k = 4, z = 80 2) Vertical asymptotes x = ±2, horizontal y = 3, no holes 3) (x − 3)/(x + 2), x ≠ −3, −2 4) x(x + 2), x ≠ −3, 0, 2 5) x = 3 6) 1/6 + 1/3 = 1/t, so t = 2 h

---

## Unit 5: Rational Exponents and Radical Functions

### 5.1 nth Roots and Rational Exponents
**Learn:** ⁿ√a is the number whose nth power is a. **a^(m/n) = (ⁿ√a)^m = ⁿ√(a^m)**. Negative exponent: a^(−n) = 1/aⁿ. Even roots of negative numbers aren't real; odd roots of negative numbers are fine (∛−8 = −2).

**Example:** 27^(2/3) = (∛27)² = **9**. 16^(−3/4) = 1/(⁴√16)³ = **1/8**.

### 5.2 Properties of Exponents and Radicals
**Learn:** aᵐ·aⁿ = aᵐ⁺ⁿ; aᵐ/aⁿ = aᵐ⁻ⁿ; (aᵐ)ⁿ = aᵐⁿ; (ab)ⁿ = aⁿbⁿ.
- Simplify radicals by pulling out perfect powers: √50 = 5√2; ∛54 = 3∛2.
- Combine only *like* radicals: 3√2 + 5√2 = 8√2.
- **Rationalize** denominators: 6/√3 = 6√3/3 = 2√3; for 1/(2 + √3), multiply by the conjugate (2 − √3) to get 2 − √3.

### 5.3 Graphing Radical Functions
**Learn:** y = a√(x − h) + k starts at (h, k); the domain is x ≥ h. y = ∛x has all real numbers as its domain and range, with an inflection point at the origin.

### 5.4 Solving Radical Equations
**Learn:** Isolate the radical, raise both sides to the power of the index, solve, and **always check**, because squaring can introduce extraneous solutions.

**Example:** √(x + 3) = x − 3 → x + 3 = x² − 6x + 9 → x² − 7x + 6 = 0 → x = 1 or 6.
Check x = 1: √4 = 2 but 1 − 3 = −2 ✗. Check x = 6: 3 = 3 ✓. **x = 6**.

### 5.5 Function Operations and Composition
**Learn:** (f + g)(x), (f − g)(x), (fg)(x), (f/g)(x) (exclude g = 0). **Composition**: (f ∘ g)(x) = f(g(x)); work from the inside out. Usually f(g(x)) ≠ g(f(x)).

**Example:** f(x) = 2x + 1, g(x) = x². f(g(2)) = f(4) = **9**; g(f(2)) = g(5) = **25**.

### 5.6 Inverse Functions
**Learn:**
- To find f⁻¹: write y = f(x), **swap x and y**, and solve for y.
- The graph of f⁻¹ is the reflection of f over **y = x**.
- f has an inverse function ⇔ it passes the **horizontal line test** (one-to-one). Otherwise, restrict the domain (for example, x² with x ≥ 0 has inverse √x).
- Verify: f(f⁻¹(x)) = x and f⁻¹(f(x)) = x.

**Example:** f(x) = x³ + 2 → x = y³ + 2 → **f⁻¹(x) = ∛(x − 2)**.

**Practice:**
1. Evaluate 32^(3/5) and 8^(−2/3).
2. Simplify √(75x³y⁴) (assume all variables ≥ 0).
3. Rationalize 4/(3 − √5).
4. Solve √(2x − 1) = x − 2.
5. Solve (x + 1)^(2/3) = 4.
6. f(x) = 3x − 4. Find f⁻¹(x) and verify.
7. f(x) = x² − 1, g(x) = √x. Find f(g(x)) and its domain.

**Unit 5 answers:** 1) 8; 1/4 2) 5xy²√(3x) 3) 4(3 + √5)/4 = 3 + √5 4) x = 5 (x = 1 is extraneous) 5) x + 1 = ±8, so x = 7 or −9 6) f⁻¹(x) = (x + 4)/3; f(f⁻¹(x)) = 3·(x + 4)/3 − 4 = x ✓ 7) x − 1, domain x ≥ 0

---

## Unit 6: Exponential and Logarithmic Functions; Sequences and Series

### 6.1 Exponential Growth and Decay
**Learn:** f(x) = a·bˣ, where a is the initial value and b is the growth factor (b > 1 grows, 0 < b < 1 decays). The horizontal asymptote is y = 0, unless the function is shifted.
- Percent rate r: growth a(1 + r)ᵗ, decay a(1 − r)ᵗ.
- **Compound interest**: A = P(1 + r/n)ⁿᵗ. **Continuous**: A = Pe^(rt).
- Exponential functions change by equal **factors** over equal intervals; linear functions change by equal **differences** (F-LE.1).

**Example:** $1,000 at 5% compounded monthly for 10 years: 1000(1 + 0.05/12)¹²⁰ ≈ **$1,647.01**. Continuous: 1000e^0.5 ≈ **$1,648.72**.

### 6.2 The Number e
**Learn:** e ≈ 2.71828 is the limit of (1 + 1/n)ⁿ as n grows. It's the base of natural growth, and ln x = log base e.

### 6.3 Logarithms
**Learn:** **log_b x = y ⇔ bʸ = x**. "A log is an exponent." Common log: log x = log₁₀ x. Natural log: ln x = log_e x. Basic facts: log_b 1 = 0, log_b b = 1, log_b bˣ = x, b^(log_b x) = x.

**Example:** log₂ 32 = 5 because 2⁵ = 32. log₃(1/9) = −2.

### 6.4 Graphing Logarithmic Functions
**Learn:** y = log_b x is the inverse of y = bˣ (a reflection over y = x). The domain is x > 0, there's a vertical asymptote at x = 0, and it passes through (1, 0) and (b, 1). Transformations work as in Unit 1.

### 6.5 Properties of Logarithms
- Product: log_b(MN) = log_b M + log_b N
- Quotient: log_b(M/N) = log_b M − log_b N
- Power: log_b(Mᵖ) = p·log_b M
- **Change of base**: log_b a = (log a)/(log b) = (ln a)/(ln b)

**Example:** Expand log(x²y/z) = 2 log x + log y − log z.

### 6.6 Solving Exponential and Logarithmic Equations
**Learn:**
- Same base: set the exponents equal. 2^(x+1) = 32 = 2⁵, so x = 4.
- Different bases: take the log of both sides. 5ˣ = 20 → x = ln 20/ln 5 ≈ **1.861**.
- Log equations: condense to a single log, rewrite in exponential form, and **check** (you can't take the log of 0 or a negative number).

**Example:** log₂ x + log₂(x − 2) = 3 → log₂(x(x − 2)) = 3 → x² − 2x = 8 → x = 4 or −2. Reject −2. **x = 4**.

**Example (doubling time):** How long for money to double at 6% compounded continuously? 2 = e^(0.06t), so t = ln 2/0.06 ≈ **11.6 years**.

### 6.7 Geometric Sequences
**Learn:** Multiply by the same **common ratio r** each time. Explicit: aₙ = a₁·rⁿ⁻¹. Recursive: aₙ = r·aₙ₋₁. A geometric sequence is an exponential function on the integers.

### 6.8 Series and Sigma Notation
**Learn:**
- Σ (sigma) notation: Σₖ₌₁⁵ (2k + 1) = 3 + 5 + 7 + 9 + 11 = 35.
- **Arithmetic series**: Sₙ = n(a₁ + aₙ)/2.
- **Finite geometric series**: Sₙ = a₁(1 − rⁿ)/(1 − r) (A-SSE.4). Used for mortgage and loan payments.
- **Infinite geometric series**: if |r| < 1, S = a₁/(1 − r); otherwise there is no sum.

**Example:** 3 + 6 + 12 + … (8 terms): 3(1 − 2⁸)/(1 − 2) = **765**.

### 6.9 Modeling with Exponential Functions
**Learn:** Write a model from two points (y = abˣ: divide the equations to eliminate a), or use exponential regression on a calculator. Interpret a and b in context.

**Practice:**
1. A $20,000 car loses 15% of its value per year. Value after 3 years?
2. Evaluate log 1000, ln e⁴, log₄ 2.
3. Condense: 3 log x − ½ log y + log 5.
4. Solve e^(2x) = 10.
5. Solve log₃(x + 1) = 2.
6. Solve 4^(x) = 3^(x+1).
7. Find a₈ for 3, 6, 12, …
8. Sum the infinite series 8 + 4 + 2 + …
9. Sum 1 + 2 + 3 + … + 100.
10. A culture doubles every 5 hours, starting at 200. Write a model and find the count at 12 hours.

**Unit 6 answers:** 1) 20000(0.85)³ = $12,282.50 2) 3; 4; ½ 3) log(5x³/√y) 4) x = ln 10/2 ≈ 1.151 5) x = 8 6) x ln 4 = (x + 1) ln 3, so x = ln 3/(ln 4 − ln 3) ≈ 3.819 7) 3·2⁷ = 384 8) 8/(1 − ½) = 16 9) 100(1 + 100)/2 = 5050 10) N = 200·2^(t/5); N(12) = 200·2^2.4 ≈ 1,056

---

## Unit 7: Trigonometric Functions

### 7.1 Angles and Radian Measure
**Learn:** Angles are in **standard position** (vertex at the origin, starting along the positive x-axis, counterclockwise is positive). **Coterminal** angles differ by multiples of 360° (2π). Convert with **180° = π radians**: multiply degrees by π/180, or radians by 180/π. A radian is the angle whose arc length equals the radius.

**Example:** 150° = 150π/180 = **5π/6**. 3π/4 = **135°**. 400° is coterminal with **40°**.

### 7.2 The Unit Circle
**Learn:** On a circle of radius 1, the point at angle θ is **(cos θ, sin θ)**, and tan θ = sin θ/cos θ. Memorize the first quadrant:
| θ | 0 | π/6 (30°) | π/4 (45°) | π/3 (60°) | π/2 (90°) |
|---|---|---|---|---|---|
| cos | 1 | √3/2 | √2/2 | ½ | 0 |
| sin | 0 | ½ | √2/2 | √3/2 | 1 |

For other quadrants, use the **reference angle** (the acute angle to the x-axis) and the signs: QI all positive, QII sin positive, QIII tan positive, QIV cos positive ("All Students Take Calculus").

**Example:** cos(4π/3): reference angle π/3 in QIII, so **−½**. sin(5π/6) = **½**.

### 7.3 Graphs of Sine and Cosine
**Learn:** y = a sin(b(x − h)) + k (same for cosine):
- **Amplitude** = |a|; **period** = 2π/|b|; **phase shift** = h; **midline** y = k.
- Max = k + |a|, min = k − |a|.
- sin starts at the midline going up; cos starts at its maximum.
- To graph, divide one period into 4 equal parts and plot the 5 key points.

**Example:** y = 3 sin(2x) − 1: amplitude 3, period π, midline y = −1, max 2, min −4.

### 7.4 Graph of Tangent
**Learn:** y = tan x has period π, vertical asymptotes at x = π/2 + nπ, and zeros at nπ. For y = a tan(bx), the period is π/|b|.

### 7.5 Modeling Periodic Phenomena
**Learn:** Find the midline (average of max and min), amplitude (half the difference), period (from the context), and choose sin or cos based on where the cycle starts.

**Example:** A Ferris wheel has radius 20 ft, its center is 25 ft high, it makes one rotation every 4 minutes, and you board at the bottom: h(t) = 25 − 20 cos(πt/2).

### 7.6 Pythagorean Identity
**Learn:** **sin²θ + cos²θ = 1** (from the unit circle and the Pythagorean theorem). Use it to find one ratio from another, using the quadrant to choose the sign.

**Example:** sin θ = 3/5 in QII: cos θ = −√(1 − 9/25) = **−4/5**, tan θ = **−3/4**.

### 7.7 Reciprocal Functions, Trig Equations, and Identities
**Learn:**
- csc θ = 1/sin θ, sec θ = 1/cos θ, cot θ = 1/tan θ.
- Solving: isolate the trig function, find the reference angle, then all angles in the interval (usually two per period). For a general solution, add + 2πn (+ πn for tangent).
- Sum/difference formulas (often included in this topic):
  - sin(A ± B) = sin A cos B ± cos A sin B
  - cos(A ± B) = cos A cos B ∓ sin A sin B
- Double angle: sin 2A = 2 sin A cos A; cos 2A = cos²A − sin²A.

**Example:** 2 cos x − 1 = 0 on [0, 2π): cos x = ½, so **x = π/3, 5π/3**.
**Example:** sin 75° = sin(45° + 30°) = (√2/2)(√3/2) + (√2/2)(½) = **(√6 + √2)/4**.

**Practice:**
1. Convert 225° to radians and 7π/6 to degrees.
2. Find sin, cos and tan of 7π/4.
3. Find the amplitude, period, midline and max/min of y = −2 cos(πx) + 5.
4. Write a sine function with amplitude 4, period 6, and midline y = 1.
5. cos θ = −5/13 and θ is in QIII. Find sin θ and tan θ.
6. Solve 2 sin x + √3 = 0 on [0, 2π).
7. Find the exact value of cos 15°.
8. An arc on a circle of radius 10 has central angle 2.5 radians. Find the arc length.

**Unit 7 answers:** 1) 5π/4; 210° 2) sin = −√2/2, cos = √2/2, tan = −1 3) Amplitude 2, period 2, midline y = 5, max 7, min 3 4) y = 4 sin(πx/3) + 1 5) sin θ = −12/13, tan θ = 12/5 6) sin x = −√3/2, so x = 4π/3, 5π/3 7) cos(45° − 30°) = (√6 + √2)/4 8) 25

---

## Unit 8: Statistics and Probability

### 8.1 Describing Data
**Learn:** Center: **mean** (average) and **median** (middle). Spread: range, IQR, **standard deviation** (σ, the typical distance from the mean). **Skewed** data: the mean is pulled toward the tail, so report the median and IQR. **Symmetric** data: report the mean and standard deviation.

### 8.2 The Normal Distribution
**Learn:** A bell-shaped, symmetric curve with mean μ and standard deviation σ.
- **Empirical Rule**: about 68% of data falls within 1σ of the mean, 95% within 2σ, and 99.7% within 3σ.
- **z-score**: z = (x − μ)/σ, the number of standard deviations from the mean. Use a z-table or calculator (normalcdf) for exact areas.

**Example:** Scores with μ = 70 and σ = 5. 65 to 75 is ±1σ, so about **68%**. Above 80 (z = 2) is about **2.5%**.

### 8.3 Sampling and Bias
**Learn:**
- A **population** is everyone; a **sample** is a subset. A **parameter** describes a population; a **statistic** describes a sample.
- Random sampling methods: simple random, stratified (random within groups), cluster (random whole groups), systematic (every kth).
- Sources of bias: convenience samples, voluntary response, leading questions, undercoverage, nonresponse.

### 8.4 Study Types
**Learn:**
- **Survey**: asks questions.
- **Observational study**: observes without intervening; can show association, not cause.
- **Experiment**: randomly assigns treatments; this is the only type that can show **cause and effect**. Good designs use a control group, randomization, replication, and blinding.

### 8.5 Margin of Error and Simulation
**Learn:** For a sample proportion p̂ from a sample of size n, the margin of error ≈ 2√(p̂(1 − p̂)/n) (≈ 1/√n as a quick estimate) at about 95% confidence. Simulations of many random samples show how much a statistic naturally varies. To compare two treatments, a **randomization test** reshuffles the group labels to see whether the observed difference is unusual.

**Example:** In a poll of 400 people, 55% favor a measure. MOE ≈ 2√(0.55·0.45/400) ≈ 0.05, so the true proportion is about **50% to 60%**.

### 8.6 Probability (continued from Geometry Unit 12)
Review: addition rule, conditional probability, independence, two-way tables, permutations/combinations, and expected value. Algebra 2 adds **using probability to make decisions** (S-MD.6, 7), such as comparing strategies by their expected values.

**Practice:**
1. Heights: μ = 64 in, σ = 3 in. What percent are between 58 and 70 in? What is the z-score of 68.5 in?
2. Identify the bias: a website asks visitors to vote on whether the website is useful.
3. A study finds that people who drink coffee live longer. Can we conclude coffee causes longer life? Why?
4. A sample of 900 voters: find the approximate margin of error (quick estimate).
5. Design an experiment to test whether a new fertilizer increases tomato yield.

**Unit 8 answers:** 1) ±2σ, so about 95%; z = 1.5 2) Voluntary response bias (likely users who already like the site) 3) No. It's observational, so there may be confounding variables (like income or other habits). 4) 1/√900 ≈ 3.3% 5) Randomly assign plants to fertilizer and control groups, keep everything else the same, use many plants per group, compare mean yields.

---

## Extras (Topics Some Algebra 2 Books Include)

### E.1 Conic Sections
- Circle: (x − h)² + (y − k)² = r²
- Parabola: (x − h)² = 4p(y − k)
- Ellipse: (x − h)²/a² + (y − k)²/b² = 1, with c² = |a² − b²| (distance from center to foci)
- Hyperbola: (x − h)²/a² − (y − k)²/b² = 1, with c² = a² + b²; asymptotes y − k = ±(b/a)(x − h)

### E.2 Matrices
- Add or subtract same-size matrices entry by entry. Multiply (m×n)(n×p): row × column.
- 2×2 determinant: |a b; c d| = ad − bc. Inverse = (1/det)·[d −b; −c a] (exists only if det ≠ 0).
- Solve the system AX = B with X = A⁻¹B.

### E.3 Final Review Checklist
You're ready for the final if you can, without notes:
- [ ] Describe any transformation of a parent function and sketch it
- [ ] Solve any quadratic (factoring, completing the square, formula) and handle complex answers
- [ ] Find all zeros of a cubic or quartic and sketch it from its zeros and end behavior
- [ ] Find asymptotes and holes and solve rational equations (checking extraneous solutions)
- [ ] Solve radical equations and find inverse functions
- [ ] Solve exponential and log equations; model growth, decay and interest
- [ ] Sum arithmetic and geometric series
- [ ] Use the unit circle from memory; graph and model with sin and cos
- [ ] Use the normal distribution, identify study types and bias, and interpret margin of error
