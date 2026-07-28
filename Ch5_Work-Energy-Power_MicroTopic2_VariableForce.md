```
SYSTEM MEMORY BLOCK
Paper: Physics 1st Paper
Chapter: 5 — Work, Energy and Power (কাজ, শক্তি ও ক্ষমতা)
Current Micro-Topic: 2 of N — "Work Done by a Variable Force"
Status: OPEN (not yet closed)
Completed: [1. Work — Definition, Formula, Sign Convention]
Next Micro-Topic: "Work-Energy Theorem"
Chapter Closure: NOT reviewed (pending explicit user confirmation)
```

# Chapter 5: Work, Energy and Power
## Micro-Topic 2: Work Done by a Variable Force (পরিবর্তনশীল বল দ্বারা কৃতকাজ)

---

### 1. Topic Identification & Core Theory (NCTB Standard)

**Micro-Topic Name:** Work Done by a Variable Force via Area Under F–s Graph and Integration (গ্রাফের ক্ষেত্রফল ও ইন্টিগ্রেশনের মাধ্যমে পরিবর্তনশীল বলের কাজ)

**Deep-Dive Explanation:**

The formula W = Fs cosθ only applies when the force is constant throughout the displacement. [W = Fs cosθ সূত্রটি কেবল তখনই প্রযোজ্য যখন সরণের সম্পূর্ণ সময় বলটি ধ্রুবক থাকে।]
In many real situations — a spring being stretched, a rocket losing mass as it burns fuel — the force changes continuously with position. [বাস্তবে অনেক ক্ষেত্রেই — যেমন স্প্রিং টানার সময়, বা জ্বালানি পুড়িয়ে ভর হারানো রকেটে — বল অবস্থানের সাথে সাথে ক্রমাগত পরিবর্তিত হয়।]
To handle this, the total displacement is divided into infinitesimally small segments ds, over each of which the force F(x) can be treated as approximately constant. [এটি সমাধানের জন্য মোট সরণকে অতিক্ষুদ্র ভাগ ds-এ ভাগ করা হয়, যার প্রতিটির মধ্যে বল F(x)-কে প্রায় ধ্রুবক ধরা যায়।]
The small work done over each segment is dW = F(x) dx, and the total work is the sum (integral) of all these small contributions from initial position x₁ to final position x₂. [প্রতিটি ক্ষুদ্র অংশে কৃত কাজ dW = F(x) dx, এবং মোট কাজ হলো x₁ থেকে x₂ পর্যন্ত এই সকল ক্ষুদ্র কাজের সমষ্টি (ইন্টিগ্রাল)।]
Graphically, this total work equals the area enclosed between the F–x curve and the x-axis, between the limits x₁ and x₂. [লেখচিত্রের মাধ্যমে দেখলে, এই মোট কাজ হলো F–x লেখ এবং x-অক্ষের মধ্যবর্তী ক্ষেত্রফল, x₁ থেকে x₂ সীমার মধ্যে।]
If the curve lies above the x-axis, the area (and work) is positive; if below, it is negative. [যদি লেখচিত্রটি x-অক্ষের উপরে থাকে, ক্ষেত্রফল (ও কাজ) ধনাত্মক হয়; নিচে থাকলে ঋণাত্মক হয়।]

**Multi-Book Synthesis:**

- **Tapan Sir (Hasan Book House):** Introduces the graphical/area-under-curve method first, before calculus, so students build geometric intuition (triangle, trapezium area formulas for common spring/ramp graphs) prior to symbolic integration. He treats this as the conceptual bridge to the spring force topic (Hooke's Law) later in the chapter.
- **Ishaq & Amir Hossain Khan Sir (Ideal Books):** Formalize it immediately with the calculus definition, W = ∫ from x₁ to x₂ of F(x) dx, and provide the fully worked spring-force derivation W = ½kx² as the flagship example, since this exact result reappears in elastic potential energy problems in later chapters.
- **Akkharpatra Physics:** Emphasizes graph-reading skill — non-standard/irregular F–x graphs (piecewise linear, curved) where students must estimate area by counting grid squares or splitting into geometric shapes, a common MCQ/CQ trick in recent board sets.

---

### 2. Mathematical Framework & Formulas

**Primary Formula (Integral form):**

$$W = \int_{x_1}^{x_2} F(x)\,dx$$

**Graphical form:**

$$W = \text{Area under the } F\text{–}x \text{ graph between } x_1 \text{ and } x_2$$

**Flagship Special Case — Spring Force (Hooke's Law, F = kx):**

$$W = \int_0^{x} kx\,dx = \frac{1}{2}kx^2$$

| Symbol | Meaning | SI Unit | Physical Significance |
|---|---|---|---|
| F(x) | Position-dependent force | Newton (N) [নিউটন] | Force magnitude as a function of position [অবস্থানের অপেক্ষক হিসেবে বলের মান] |
| x₁, x₂ | Initial and final positions | Metre (m) [মিটার] | Integration limits along the path [পথ বরাবর সীমা] |
| k | Spring constant (force constant) | N/m [নিউটন/মিটার] | Stiffness of the spring [স্প্রিং-এর দৃঢ়তার পরিমাপ] |
| W | Work done | Joule (J) [জুল] | Total energy transferred over the variable-force path [সম্পূর্ণ পথে স্থানান্তরিত মোট শক্তি] |

**Common Traps (English Version students):**
1. **Forgetting the negative sign in restoring force:** For a spring, the restoring force is F = −kx, but the work done *by the applied external force* (stretching it) is still positive, W = +½kx² — students often flip this sign incorrectly.
2. **Treating average force incorrectly:** Some students wrongly use F_avg = F(x₁) + F(x₂) (sum) instead of the correct arithmetic mean (F₁+F₂)/2 for linear F–x graphs, or apply an average-force shortcut to non-linear graphs where it's invalid.
3. **Integration limit swap:** Reversing x₁ and x₂ flips the sign of W — always match the limits to the direction of actual displacement.
4. **Units inside integration:** Forgetting to keep k in N/m and x in m consistently before squaring — a frequent numerical slip that produces answers off by factors of 10, 100, etc.

---

### 3. Chronological Type-Wise Board Questions (2016 – 2026)

⚠️ Same note as Micro-Topic 1: questions below are board-pattern representative, not guaranteed verbatim transcriptions. Upload actual board PDFs for exact-wording re-solving.

**Type A: Graphical (Area under F–x graph, piecewise linear)**

- **Question (Board-pattern):** An F–x graph shows force increasing linearly from 0 N to 20 N as x goes from 0 to 4 m, then remaining constant at 20 N from x = 4 m to x = 6 m. Find total work done from x = 0 to x = 6 m.
- **NCTB Standard Solution:**
  1. Split into two regions: triangle (0 to 4 m) and rectangle (4 to 6 m). [দুটি অংশে ভাগ: ত্রিভুজ ও আয়তক্ষেত্র]
  2. Triangle area = ½ × base × height = ½ × 4 × 20 = 40 J
  3. Rectangle area = base × height = 2 × 20 = 40 J
  4. Total W = 40 + 40 = **80 J**
- **Line-by-Line Breakdown:** Step 1 recognizes that irregular graphs must be decomposed into standard geometric shapes whose area formulas are already known — a core NCTB graph-reading skill. [ধাপ ১ এ অনিয়মিত লেখকে পরিচিত জ্যামিতিক আকারে ভাগ করার দক্ষতা প্রদর্শিত হয়, যা NCTB-এর একটি মূল দক্ষতা।]

**Type B: Spring Force (Direct Integration)**

- **Question (Board-pattern):** A spring with force constant k = 200 N/m is stretched from its natural length by 0.15 m. Find the work done in stretching it.
- **NCTB Standard Solution:**
  1. Formula: W = ½kx² [সূত্র প্রয়োগ]
  2. W = ½ × 200 × (0.15)² = 100 × 0.0225 = **2.25 J**
- **Line-by-Line Breakdown:** Squaring x before multiplying is essential — a linear-in-x mistake (forgetting the square) is one of the most common board errors on this exact question type. [x-কে বর্গ করার পূর্বে গুণ করলে ভুল হয় — বর্গ করা ভুলে যাওয়া এই প্রশ্নের ধরনে সবচেয়ে সাধারণ ভুল।]

**Type C: Ratio-Based (Two Springs)**

- **Question (Board-pattern):** Spring A (k₁ = 150 N/m) and Spring B (k₂ = 300 N/m) are stretched by the same distance x. Find the ratio of work done on A to work done on B.
- **NCTB Standard Solution:**
  1. W ∝ k (since x is common and squared identically) [x সমান হওয়ায় W ∝ k]
  2. W₁/W₂ = k₁/k₂ = 150/300 = **1:2**
- **Line-by-Line Breakdown:** Because x² is identical in both cases, it cancels, reducing the problem to a direct spring-constant ratio — this shortcut is frequently tested to check conceptual (not just computational) understanding. [x² উভয় ক্ষেত্রে সমান হওয়ায় বাতিল হয়ে যায়, ফলে সমস্যাটি সরাসরি স্প্রিং ধ্রুবকের অনুপাতে পরিণত হয়।]

---

### 4. Micro-Topic Formative Exercise

**Q1 (Conceptual CQ style):** A student claims that since force is not constant while stretching a spring, the formula W = Fs cosθ can still be used by simply plugging in the final force value F = kx. Explain why this reasoning is physically incorrect, and describe the correct approach.

**Answer: Using the final force value overestimates the work; the correct method requires integrating F(x) over the path, giving W = ½kx², exactly half of what the (incorrect) F_final × x calculation would give.**

<details><summary>Click for Solution</summary>

The formula W = Fs cosθ assumes F is constant over the entire displacement. In a spring, F grows linearly from 0 (at natural length) to kx (at maximum stretch), so using the final value F = kx for the entire displacement s = x would give W = (kx)(x) = kx² — this overcounts the work by a factor of 2, because it assumes the force was at its maximum value throughout the stretch, when in fact it started at zero. The correct approach accounts for the continuously increasing force via integration (or equivalently, the triangular area under the F–x graph), yielding the correct result W = ½kx².

</details>

**Q2 (Mathematical):** The force on a particle varies as F(x) = (3x² + 2x) N, where x is in metres. Find the work done in moving the particle from x = 1 m to x = 3 m.

**Answer: W = 34 J**

<details><summary>Click for Solution</summary>

W = ∫ from 1 to 3 of (3x² + 2x) dx = [x³ + x²] from 1 to 3
= (27 + 9) − (1 + 1) = 36 − 2 = 34 J

</details>

**Q3 (Mathematical, board-difficulty 2024–2026 style):** A variable force acting on a 2 kg block is given by F(x) = (10 − 2x) N for 0 ≤ x ≤ 5 m (force decreases linearly and becomes negative beyond x = 5 m). Find the work done as the block moves from x = 0 to x = 5 m, and interpret the physical meaning of the force becoming zero at x = 5 m.

**Answer: W = 25 J; at x = 5 m the net applied force vanishes (equilibrium point along the path).**

<details><summary>Click for Solution</summary>

W = ∫ from 0 to 5 of (10 − 2x) dx = [10x − x²] from 0 to 5
= (50 − 25) − (0 − 0) = 25 J

At x = 5 m, F(x) = 10 − 2(5) = 0, meaning the applied force has decreased to zero at that position — physically, this could represent a spring returning to natural tension, or a decelerating pushing force reaching the point where it no longer contributes further to motion. Beyond x = 5 m, F(x) becomes negative, meaning the force would begin acting opposite to the direction of motion (decelerating/retarding effect).

</details>

---

**Next Micro-Topic:** "Work-Energy Theorem" (relating net work done to the change in kinetic energy, W_net = ΔKE).

Proceed to this next micro-topic?
