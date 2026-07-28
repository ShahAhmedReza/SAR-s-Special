```
SYSTEM MEMORY BLOCK
Paper: Physics 1st Paper
Chapter: 5 — Work, Energy and Power (কাজ, শক্তি ও ক্ষমতা)
Current Micro-Topic: 3 of N — "Work-Energy Theorem"
Status: OPEN (not yet closed)
Completed: [1. Work — Definition/Formula, 2. Work Done by a Variable Force]
Next Micro-Topic: "Kinetic Energy"
Chapter Closure: NOT reviewed (pending explicit user confirmation)
```

# Chapter 5: Work, Energy and Power
## Micro-Topic 3: Work-Energy Theorem (কাজ-শক্তি উপপাদ্য)

---

### 1. Topic Identification & Core Theory (NCTB Standard)

**Micro-Topic Name:** The Work-Energy Theorem — Net Work Equals Change in Kinetic Energy (নিট কাজ ও গতিশক্তির পরিবর্তনের সম্পর্ক)

**Deep-Dive Explanation:**

The work-energy theorem states that the net (total) work done by all forces acting on a body equals the change in its kinetic energy. [কাজ-শক্তি উপপাদ্য অনুসারে, কোনো বস্তুর উপর ক্রিয়াশীল সকল বলের দ্বারা কৃত নিট (মোট) কাজ তার গতিশক্তির পরিবর্তনের সমান।]
Mathematically, this is written as W_net = ΔKE = KE_final − KE_initial. [গাণিতিকভাবে এটি লেখা হয় W_net = ΔKE = KE_শেষ − KE_প্রাথমিক।]
This theorem can be derived directly from Newton's second law combined with the definition of work, without needing any new physical assumption. [এই উপপাদ্যটি নিউটনের দ্বিতীয় সূত্র এবং কাজের সংজ্ঞা একত্রিত করে সরাসরি প্রতিপাদন করা যায়, কোনো নতুন ভৌত অনুকল্প ছাড়াই।]
Starting from F = ma, and using the chain rule v(dv/dx) = a, one can show that F dx = mv dv, and integrating both sides from initial to final velocity gives W = ½mv_f² − ½mv_i². [F = ma থেকে শুরু করে এবং চেইন রুল v(dv/dx) = a ব্যবহার করে দেখানো যায় F dx = mv dv, এবং উভয় পক্ষকে প্রাথমিক থেকে শেষ বেগ পর্যন্ত ইন্টিগ্রেট করলে পাওয়া যায় W = ½mv_f² − ½mv_i²।]
If net work done is positive, the body speeds up; if negative, it slows down; if zero, its speed remains unchanged. [নিট কাজ ধনাত্মক হলে বস্তুর বেগ বৃদ্ধি পায়; ঋণাত্মক হলে হ্রাস পায়; শূন্য হলে বেগ অপরিবর্তিত থাকে।]
This theorem is extremely powerful for solving problems because it connects force/displacement information directly to speed, without requiring detailed knowledge of acceleration as a function of time. [এই উপপাদ্যটি সমস্যা সমাধানে অত্যন্ত শক্তিশালী, কারণ এটি সময়ের সাপেক্ষে ত্বরণ না জেনেই বল/সরণ তথ্যকে সরাসরি বেগের সাথে সংযুক্ত করে।]

**Multi-Book Synthesis:**

- **Tapan Sir (Hasan Book House):** Presents the theorem as a direct logical consequence of the definitions already covered (Work in Micro-Topics 1–2), reinforcing that no new axiom is being introduced — only combination of Newton's 2nd law with the calculus-based definition of work. He is the primary source for the conceptual emphasis that this theorem applies to *net* work (sum of all forces), not the work of any single force alone.
- **Ishaq & Amir Hossain Khan Sir (Ideal Books):** Provide the full step-by-step calculus derivation (F=ma → v dv/dx substitution → integration), and this is the canonical derivation expected to be reproducible in board CQ answers when a "derive the work-energy theorem" question appears.
- **Akkharpatra Physics:** Focuses on application variety — friction-inclusive problems (net work = applied work − friction work), multi-force scenarios, and problems requiring the theorem to find final velocity or stopping distance without directly using kinematics equations, which is a favored problem style in recent (2023–2026) board sets.

---

### 2. Mathematical Framework & Formulas

**Primary Formula:**

$$W_{net} = \Delta KE = \frac{1}{2}mv_f^2 - \frac{1}{2}mv_i^2$$

**Derivation core step:**

$$F = ma = m\frac{dv}{dt} = m v\frac{dv}{dx} \implies F\,dx = mv\,dv \implies \int F\,dx = \int mv\,dv$$

| Symbol | Meaning | SI Unit | Physical Significance |
|---|---|---|---|
| W_net | Net (total) work done by all forces | Joule (J) [জুল] | Sum of work from every force acting on the body [বস্তুর উপর ক্রিয়াশীল সকল বলের কাজের সমষ্টি] |
| m | Mass of the body | Kilogram (kg) [কিলোগ্রাম] | Inertial resistance to change in motion [গতি পরিবর্তনে জড়তার বাধা] |
| v_i, v_f | Initial and final speed | m/s [মিটার/সেকেন্ড] | Speed before and after the net work is done [কাজ সম্পন্ন হওয়ার আগে ও পরের বেগ] |
| ΔKE | Change in kinetic energy | Joule (J) [জুল] | Net energy gained/lost due to motion change [গতির পরিবর্তনজনিত নিট শক্তি লাভ/ক্ষয়] |

**Common Traps (English Version students):**
1. **Using work of a single force instead of net work:** A very frequent board error — students plug in only the applied force's work and forget to subtract friction/opposing work before equating to ΔKE.
2. **Sign of ΔKE when decelerating:** Forgetting that ΔKE is negative when a body slows down, which correctly matches negative net work (e.g., due to friction) — sign mismatches lose marks.
3. **Confusing this theorem with conservation of mechanical energy:** The work-energy theorem uses *net* work (including non-conservative forces like friction); it is NOT the same as conservation of mechanical energy, which specifically excludes non-conservative forces. This distinction is a very common conceptual confusion tested in board CQs.
4. **Forgetting v_i ≠ 0 in "starts from rest" wording:** Some students misread "brought to rest" vs "starts from rest" and swap v_i and v_f, flipping the sign of the answer.

---

### 3. Chronological Type-Wise Board Questions (2016 – 2026)

⚠️ Same note as previous micro-topics: board-pattern representative problems, not guaranteed verbatim board transcriptions.

**Type A: Direct Substitution (Find final velocity from net work)**

- **Question (Board-pattern):** A 4 kg block starts from rest and a net force does 72 J of work on it. Find its final speed.
- **NCTB Standard Solution:**
  1. W_net = ΔKE = ½mv_f² − ½mv_i², with v_i = 0 [প্রাথমিক বেগ শূন্য]
  2. 72 = ½ × 4 × v_f² − 0 → 72 = 2v_f²
  3. v_f² = 36 → **v_f = 6 m/s**
- **Line-by-Line Breakdown:** Step 1 sets v_i = 0 explicitly because the body "starts from rest," a keyword directly translating to a numerical condition. [ধাপ ১ এ v_i = 0 বসানো হয়েছে কারণ "স্থির অবস্থা থেকে শুরু" শব্দগুচ্ছটি সরাসরি একটি সাংখ্যিক শর্তে রূপান্তরিত হয়।]

**Type B: Friction-Inclusive (Net Work = Applied − Friction)**

- **Question (Board-pattern):** A 10 kg crate initially moving at 4 m/s is pushed with a force doing 150 J of work over a distance where friction does −50 J of work. Find the final speed.
- **NCTB Standard Solution:**
  1. W_net = W_applied + W_friction = 150 + (−50) = 100 J [নিট কাজ নির্ণয়]
  2. W_net = ½mv_f² − ½mv_i² → 100 = ½(10)v_f² − ½(10)(4²)
  3. 100 = 5v_f² − 80 → 5v_f² = 180 → v_f² = 36 → **v_f = 6 m/s**
- **Line-by-Line Breakdown:** Step 1 is the most conceptually tested part of this micro-topic — students must recognize that *net* work requires algebraic summation (with correct signs) of every force's individual work, not just the applied force. [ধাপ ১ এই মাইক্রো-টপিকের সবচেয়ে বেশি পরীক্ষিত ধারণা — শিক্ষার্থীদের বুঝতে হবে যে নিট কাজ নির্ণয়ে প্রতিটি বলের পৃথক কাজ সঠিক চিহ্নসহ যোগ করতে হয়।]

**Type C: Stopping Distance (Reverse application)**

- **Question (Board-pattern):** A 1200 kg car moving at 20 m/s is brought to rest by a braking force of 6000 N. Find the stopping distance using the work-energy theorem.
- **NCTB Standard Solution:**
  1. W_net = ΔKE = 0 − ½(1200)(20²) = −240000 J [গতিশক্তির পরিবর্তন]
  2. W_net = −F·s (braking force opposes motion) → −240000 = −6000 × s
  3. **s = 40 m**
- **Line-by-Line Breakdown:** Step 2 assigns a negative sign to the braking force's work because it opposes the direction of motion (θ = 180°), directly linking back to the sign convention established in Micro-Topic 1. [ধাপ ২ এ ব্রেকিং বলের কাজে ঋণাত্মক চিহ্ন বসানো হয়েছে কারণ এটি গতির বিপরীতে কাজ করে (θ = 180°), যা মাইক্রো-টপিক ১-এ প্রতিষ্ঠিত চিহ্ন নিয়মের সাথে সরাসরি সম্পর্কিত।]

---

### 4. Micro-Topic Formative Exercise

**Q1 (Conceptual CQ style):** A student solves a problem by setting "work done by the applied force" equal to ΔKE, ignoring a frictional force that is explicitly mentioned in the problem. Explain the conceptual error and its consequence on the numerical answer.

**Answer: Ignoring friction means only using partial (not net) work, which will overestimate the final kinetic energy/speed since friction always removes energy (negative work) from the system.**

<details><summary>Click for Solution</summary>

The work-energy theorem requires the *net* work — the algebraic sum of work done by every force acting on the body, including non-conservative forces like friction. By equating only the applied force's work to ΔKE, the student effectively assumes friction does zero work, which is physically incorrect whenever the body is in contact with a surface exerting resistance. Since friction always does negative work (opposing motion), omitting it makes the calculated ΔKE too large, leading to an overestimated final speed. The correct method requires: W_net = W_applied + W_friction (with W_friction carrying a negative sign), then equating this net value to ΔKE.

</details>

**Q2 (Mathematical):** A 0.5 kg ball moving at 8 m/s is acted upon by a resistive force that brings it to rest over a distance of 4 m. Find the average resistive force.

**Answer: F ≈ 4 N**

<details><summary>Click for Solution</summary>

W_net = ΔKE = 0 − ½(0.5)(8²) = −16 J
W_net = −F·s (force opposes motion) → −16 = −F(4) → F = 4 N

</details>

**Q3 (Mathematical, board-difficulty 2024–2026 style):** A 2 kg object moving at 3 m/s on a horizontal surface is pushed by a constant force of 10 N over a distance of 5 m in the direction of motion, while friction (coefficient μ = 0.2) acts throughout. Take g = 9.8 m/s². Find the final speed of the object using the work-energy theorem.

**Answer: v_f ≈ 6.28 m/s**

<details><summary>Click for Solution</summary>

Friction force: f = μmg = 0.2 × 2 × 9.8 = 3.92 N
W_applied = 10 × 5 = 50 J
W_friction = −f × s = −3.92 × 5 = −19.6 J
W_net = 50 − 19.6 = 30.4 J

W_net = ½mv_f² − ½mv_i²
30.4 = ½(2)v_f² − ½(2)(3²)
30.4 = v_f² − 9
v_f² = 39.4
v_f = √39.4 ≈ 6.28 m/s

</details>

---

**Next Micro-Topic:** "Kinetic Energy" (formal definition, derivation from work-energy theorem, and its distinct treatment as a state function vs. work as a process quantity).

Proceed to this next micro-topic?
