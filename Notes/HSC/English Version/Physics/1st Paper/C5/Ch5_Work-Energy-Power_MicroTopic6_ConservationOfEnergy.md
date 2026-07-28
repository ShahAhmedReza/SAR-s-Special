```
SYSTEM MEMORY BLOCK
Paper: Physics 1st Paper
Chapter: 5 — Work, Energy and Power (কাজ, শক্তি ও ক্ষমতা)
Current Micro-Topic: 6 of N — "Conservative Forces and Conservation of Mechanical Energy"
Status: OPEN (not yet closed)
Completed: [1. Work, 2. Work by Variable Force, 3. Work-Energy Theorem, 4. Kinetic Energy, 5. Gravitational PE]
Next Micro-Topic: "Power"
Chapter Closure: NOT reviewed (pending explicit user confirmation)
```

# Chapter 5: Work, Energy and Power
## Micro-Topic 6: Conservative Forces and Conservation of Mechanical Energy (সংরক্ষণশীল বল ও যান্ত্রিক শক্তির সংরক্ষণ)

---

### 1. Topic Identification & Core Theory (NCTB Standard)

**Micro-Topic Name:** Conservative vs. Non-Conservative Forces, and the Principle of Conservation of Mechanical Energy (সংরক্ষণশীল ও অসংরক্ষণশীল বল, এবং যান্ত্রিক শক্তির সংরক্ষণ নীতি)

**Deep-Dive Explanation:**

A conservative force is one for which the work done in moving a body between two points is independent of the path taken, and depends only on the initial and final positions. [সংরক্ষণশীল বল হলো এমন বল যার দ্বারা কোনো বস্তুকে দুটি বিন্দুর মধ্যে সরাতে কৃত কাজ গৃহীত পথের উপর নির্ভর করে না, বরং কেবল প্রাথমিক ও শেষ অবস্থানের উপর নির্ভর করে।]
Equivalently, the work done by a conservative force around any closed path (returning to the starting point) is always zero. [সমতুল্যভাবে, একটি সংরক্ষণশীল বল দ্বারা যেকোনো বদ্ধ পথে (শুরুর বিন্দুতে ফিরে আসা) কৃত কাজ সর্বদা শূন্য।]
Gravity and the spring (elastic) force are classic examples of conservative forces, while friction and air resistance are classic examples of non-conservative forces, since the work done by friction depends on the total path length traveled, not just the endpoints. [মহাকর্ষ ও স্প্রিং (স্থিতিস্থাপক) বল সংরক্ষণশীল বলের ধ্রুপদী উদাহরণ, অন্যদিকে ঘর্ষণ ও বায়ু প্রতিরোধ অসংরক্ষণশীল বলের ধ্রুপদী উদাহরণ, কারণ ঘর্ষণের কাজ কেবল প্রান্তবিন্দুর উপর নয়, মোট অতিক্রান্ত পথের দৈর্ঘ্যের উপরও নির্ভর করে।]
Only conservative forces can have an associated potential energy function, because potential energy must be a well-defined single value at each position — which is only possible if work is path-independent. [কেবল সংরক্ষণশীল বলের একটি সংশ্লিষ্ট বিভবশক্তি অপেক্ষক থাকতে পারে, কারণ বিভবশক্তিকে প্রতিটি অবস্থানে একটি সুনির্দিষ্ট একক মান হতে হবে — যা কেবল তখনই সম্ভব যখন কাজ পথ-নিরপেক্ষ হয়।]
The principle of conservation of mechanical energy states that, in a system where only conservative forces do work (no friction, air resistance, or other energy-dissipating forces), the total mechanical energy (KE + U) remains constant at every point along the motion. [যান্ত্রিক শক্তি সংরক্ষণ নীতি অনুসারে, এমন একটি সিস্টেমে যেখানে কেবল সংরক্ষণশীল বল কাজ করে (কোনো ঘর্ষণ, বায়ু প্রতিরোধ বা অন্য শক্তি-ক্ষয়কারী বল নেই), গতিপথের প্রতিটি বিন্দুতে মোট যান্ত্রিক শক্তি (KE + U) ধ্রুবক থাকে।]
This is expressed as KE₁ + U₁ = KE₂ + U₂ for any two points 1 and 2 along the motion. [এটি প্রকাশ করা হয় KE₁ + U₁ = KE₂ + U₂ হিসেবে, গতিপথের যেকোনো দুটি বিন্দু ১ এবং ২-এর জন্য।]

**Multi-Book Synthesis:**

- **Tapan Sir (Hasan Book House):** Anchors the conceptual foundation by carefully distinguishing conservative from non-conservative forces using the closed-path (zero net work) test, and stresses that this classification is a *prerequisite* for legitimately applying conservation of mechanical energy — a frequent CQ theme is "explain why mechanical energy is NOT conserved when friction is present."
- **Ishaq & Amir Hossain Khan Sir (Ideal Books):** Formalize the derivation, W_net = ΔKE (from Micro-Topic 3) combined with W_conservative = −ΔU (definition linking force to potential energy), leading to ΔKE + ΔU = 0, i.e., KE + U = constant — this derivation chain is the standard reproducible board proof.
- **Akkharpatra Physics:** Provides extensive application variety — roller coaster/pendulum/free-fall problems using conservation of mechanical energy to find speeds at various heights without kinematics, plus mixed-force problems combining a small friction loss with an otherwise conservative system (energy "lost" to heat), a common recent (2024–2026) board CQ pattern.

---

### 2. Mathematical Framework & Formulas

**Primary Formula (conservation, no non-conservative forces):**

$$KE_1 + U_1 = KE_2 + U_2 \quad \text{(mechanical energy constant)}$$

**Derivation Link:**

$$W_{net} = \Delta KE \quad \text{and} \quad W_{conservative} = -\Delta U \implies \Delta KE + \Delta U = 0$$

**General Case (with non-conservative/dissipative forces present, e.g., friction):**

$$KE_1 + U_1 = KE_2 + U_2 + |W_{friction}|$$

| Symbol | Meaning | SI Unit | Physical Significance |
|---|---|---|---|
| KE₁, KE₂ | Kinetic energy at points 1 and 2 | Joule (J) [জুল] | Motion-energy at each state [প্রতিটি অবস্থায় গতিশক্তি] |
| U₁, U₂ | Potential energy at points 1 and 2 | Joule (J) [জুল] | Position-energy at each state [প্রতিটি অবস্থায় অবস্থানশক্তি] |
| W_friction | Work done by/against friction | Joule (J) [জুল] | Energy dissipated as heat, not recoverable as mechanical energy [তাপ হিসেবে ক্ষয়প্রাপ্ত শক্তি] |

**Common Traps (English Version students):**
1. **Applying conservation of mechanical energy where friction is present:** The single most common conceptual error — students use KE₁+U₁ = KE₂+U₂ even when the problem explicitly mentions a rough surface, ignoring the energy dissipated as heat.
2. **Confusing "conservative force" with "the force being constant":** A conservative force need not have constant magnitude (e.g., spring force F = kx varies with position but is still conservative) — the defining property is path-independence of work, not constant magnitude.
3. **Forgetting that normal force and tension typically do zero work:** In many conservation-of-energy problems, normal force and string tension are perpendicular to motion (or do no net work in ideal constraints) and should not be included as "forces doing work" in the energy balance.
4. **Sign error in the friction-loss equation:** Students forget that |W_friction| is *subtracted* from the initial mechanical energy to get final mechanical energy, sometimes adding it instead.

---

### 3. Chronological Type-Wise Board Questions (2016 – 2026)

⚠️ Same note as previous micro-topics: board-pattern representative problems, not guaranteed verbatim board transcriptions.

**Type A: Free Fall / Direct Conservation (No Friction)**

- **Question (Board-pattern):** A ball of mass 2 kg is dropped from a height of 20 m. Using conservation of mechanical energy, find its speed just before hitting the ground. (g = 9.8 m/s², neglect air resistance)
- **NCTB Standard Solution:**
  1. KE₁ + U₁ = KE₂ + U₂, with KE₁ = 0 (dropped from rest), U₂ = 0 (ground reference) [প্রাথমিক ও শেষ শর্ত বসানো]
  2. U₁ = mgh = 2 × 9.8 × 20 = 392 J = KE₂ = ½mv²
  3. 392 = ½ × 2 × v² → v² = 392 → **v = √392 ≈ 19.8 m/s**
- **Line-by-Line Breakdown:** Step 1 sets up the conservation equation with correctly identified boundary conditions (KE=0 at top since "dropped," U=0 at ground since that's the reference), a setup pattern tested in nearly every board year for this question type. [ধাপ ১ সঠিকভাবে চিহ্নিত সীমান্ত শর্তসহ সংরক্ষণ সমীকরণ স্থাপন করে।]

**Type B: Pendulum / Height-to-Speed Conversion**

- **Question (Board-pattern):** A pendulum of length 1.5 m is released from a horizontal position (90° from vertical). Find the speed of the bob at the lowest point of the swing. (g = 9.8 m/s², neglect air resistance)
- **NCTB Standard Solution:**
  1. Height dropped h = L(1 − cos90°) = L(1 − 0) = 1.5 m [জ্যামিতি থেকে উচ্চতা নির্ণয়]
  2. KE = U (top) → ½mv² = mgh → v² = 2gh = 2 × 9.8 × 1.5 = 29.4
  3. **v = √29.4 ≈ 5.42 m/s**
- **Line-by-Line Breakdown:** Step 1 requires geometric reasoning to convert the pendulum's angular displacement into a vertical height drop — this geometry-to-energy conversion is a recurring higher-order skill tested in 2023–2026 board CQs. [ধাপ ১ এ কৌণিক সরণকে উল্লম্ব উচ্চতায় রূপান্তরের জ্যামিতিক যুক্তি প্রয়োজন।]

**Type C: With Friction (Non-Conservative Force Present)**

- **Question (Board-pattern):** A 1 kg block slides down a frictionless section then across a rough horizontal section from a height of 5 m, coming to rest after traveling 8 m on the rough section. Find the average friction force. (g = 9.8 m/s²)
- **NCTB Standard Solution:**
  1. Initial mechanical energy (at height 5 m, at rest) = mgh = 1 × 9.8 × 5 = 49 J [প্রাথমিক যান্ত্রিক শক্তি]
  2. Final mechanical energy (at rest on ground) = 0 J [শেষ যান্ত্রিক শক্তি]
  3. Energy lost to friction = 49 − 0 = 49 J = f × s → 49 = f × 8 → **f ≈ 6.125 N**
- **Line-by-Line Breakdown:** Step 3 applies the modified (non-conservative) energy balance, explicitly crediting the "missing" mechanical energy to friction's dissipative work — the core conceptual test of this question type, directly building on the Common Trap #1 warning above. [ধাপ ৩ পরিবর্তিত (অসংরক্ষণশীল) শক্তি ভারসাম্য প্রয়োগ করে, "হারানো" যান্ত্রিক শক্তিকে ঘর্ষণের ক্ষয়কারী কাজের জন্য দায়ী করে।]

---

### 4. Micro-Topic Formative Exercise

**Q1 (Conceptual CQ style):** A student argues that since gravity always does zero net work over a complete round trip (e.g., a ball thrown up that returns to the same height), gravity therefore "does nothing" and can be ignored in energy analysis. Explain why this reasoning is flawed, distinguishing between net work over a closed path and the moment-to-moment work done during the motion.

**Answer: Gravity's zero work over a closed path only means the *net* effect cancels out over the full round trip — it does not mean gravity performs no work during individual segments of the motion; gravity does substantial negative work on the way up (decelerating the ball) and equal positive work on the way down (accelerating it), and this is precisely what makes it a conservative force with a well-defined, recoverable potential energy.**

<details><summary>Click for Solution</summary>

The defining test for a conservative force is that work over a *closed path* sums to zero — this is a statement about the total, not about each instant. During the ball's ascent, gravity acts opposite to the velocity, doing negative work and converting kinetic energy into potential energy (U increases as KE decreases). During descent, gravity acts along the velocity, doing positive work and converting that stored potential energy back into kinetic energy. The magnitudes of positive and negative work exactly cancel over the round trip, which is precisely why the energy is "recoverable" — this recoverability, not the absence of work, is what makes gravity conservative and permits the definition of a potential energy function.

</details>

**Q2 (Mathematical):** A 3 kg object slides down a frictionless curved ramp from a height of 4 m and reaches the bottom. Find its speed at the bottom using conservation of mechanical energy. (g = 9.8 m/s²)

**Answer: v ≈ 8.85 m/s**

<details><summary>Click for Solution</summary>

mgh = ½mv² → v² = 2gh = 2 × 9.8 × 4 = 78.4
v = √78.4 ≈ 8.85 m/s

</details>

**Q3 (Mathematical, board-difficulty 2024–2026 style):** A 2 kg block starts from rest at the top of a 6 m high frictionless ramp, then slides across a rough horizontal floor (μ = 0.25) before coming to rest. Find the distance traveled on the rough floor. (g = 9.8 m/s²)

**Answer: s = 24 m**

<details><summary>Click for Solution</summary>

Mechanical energy at top (all potential, since starts from rest): U = mgh = 2 × 9.8 × 6 = 117.6 J
This entire energy must be dissipated by friction on the rough floor to bring the block to rest (ramp is frictionless, so full energy reaches the bottom as KE, then is consumed by friction):

Friction force: f = μmg = 0.25 × 2 × 9.8 = 4.9 N
Energy dissipated by friction = f × s
117.6 = 4.9 × s
s = 117.6 / 4.9 = 24 m

</details>

---

**Next Micro-Topic:** "Power" — definition as the rate of doing work, formula P = W/t and P = Fv, and distinction between average and instantaneous power.

Proceed to this next micro-topic?
