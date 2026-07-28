```
SYSTEM MEMORY BLOCK
Paper: Physics 1st Paper
Chapter: 5 — Work, Energy and Power (কাজ, শক্তি ও ক্ষমতা)
Status: FULL CHAPTER REVIEW (all 9 micro-topics closed by explicit user confirmation)
Micro-Topics Covered: [1. Work, 2. Work by Variable Force, 3. Work-Energy Theorem, 4. Kinetic Energy, 5. Gravitational PE, 6. Conservation of Mechanical Energy, 7. Power, 8. Elastic/Inelastic Collisions, 9. Coefficient of Restitution]
Next Action: Chapter 6 (Gravitation & Gravity) — awaiting user instruction to begin
```

# Chapter 5 Full Review: Work, Energy and Power (কাজ, শক্তি ও ক্ষমতা)

---

## Master Formula Sheet

| # | Concept | Formula |
|---|---|---|
| 1 | Work (constant force) | W = Fs cosθ |
| 2 | Work (variable force) | W = ∫F(x)dx = area under F-x graph |
| 3 | Spring work | W = ½kx² |
| 4 | Work-Energy Theorem | W_net = ΔKE = ½mv_f² − ½mv_i² |
| 5 | Kinetic Energy | KE = ½mv² = p²/2m |
| 6 | Gravitational PE | U = mgh |
| 7 | Conservation of Mech. Energy | KE₁+U₁ = KE₂+U₂ (no non-conservative forces) |
| 8 | Average Power | P = W/t |
| 9 | Instantaneous Power | P = dW/dt = Fv |
| 10 | Momentum Conservation (any collision) | m₁u₁+m₂u₂ = m₁v₁+m₂v₂ |
| 11 | Elastic Collision (1D) | v₁,v₂ — see Micro-Topic 8 formula |
| 12 | Perfectly Inelastic Collision | v = (m₁u₁+m₂u₂)/(m₁+m₂) |
| 13 | Coefficient of Restitution | e = (v₂−v₁)/(u₁−u₂) = √(h₂/h₁) |

---

## Conceptual Thread — How the Chapter Connects

1. **Work** is defined first as the foundational scalar quantity (F·s cosθ), establishing the sign convention (θ determines positive/negative/zero work) that recurs throughout the chapter.
2. **Variable-force work** extends this to non-constant forces via integration/graph area, with the spring result (W=½kx²) becoming essential later for oscillation and elastic-energy contexts.
3. **Work-Energy Theorem** is derived purely from Newton's 2nd law + work definition — it is *not* a new axiom, but a direct consequence, and it defines kinetic energy's formula in the process.
4. **Kinetic Energy** is isolated as a state function (contrast with work as a process quantity) — this distinction is a recurring conceptual exam target.
5. **Gravitational PE** introduces the idea of energy stored by position, with the critical caveat that only ΔU (not absolute U) has physical meaning.
6. **Conservation of Mechanical Energy** unifies KE and U: total mechanical energy is constant *only* when forces are conservative (no friction/dissipation) — this restriction is the most tested conceptual boundary in the chapter.
7. **Power** shifts focus from "how much" work/energy to "how fast" — introducing the time dimension, culminating in P = Fv linking force, velocity, and rate directly.
8. **Collisions** apply momentum + (conditionally) kinetic energy conservation together, splitting into elastic (both conserved) vs inelastic (only momentum conserved) categories.
9. **Coefficient of Restitution** quantifies the collision spectrum between these two extremes (e=1 elastic, e=0 perfectly inelastic), closing the chapter's logical arc from single-force work all the way to real-world imperfect collisions.

---

## Cross-Cutting Common Traps (Chapter-Wide)

1. **Sign convention drift:** The θ-based sign convention from Micro-Topic 1 (positive/negative/zero work) must be carried consistently through friction (Micro-Topic 3, 6), gravity (Micro-Topic 5), and restitution (Micro-Topic 9) problems — a frequent source of chained errors across multi-part CQs.
2. **Confusing "conserved" scope:** Momentum is *always* conserved in collisions; mechanical energy is conserved *only* without non-conservative forces; kinetic energy is conserved *only* in elastic collisions — these three distinct conservation scopes are commonly conflated.
3. **State vs. process quantities:** Work is path/process-dependent; KE and U are state functions (depend only on current condition). Mixing these up leads to errors in multi-step energy-transformation problems.
4. **Unit fluency:** Joule (J), Watt (W), horsepower (hp), and their interconversions appear throughout — board papers frequently test unit conversion as a standalone skill within larger numerical problems.

---

## Mixed Synthesis Practice Set (Board-Difficulty, 2024–2026 style)

**Q1 (Multi-concept CQ):** A 2 kg block is released from rest at the top of a frictionless 5 m high ramp, slides down, and then collides perfectly inelastically with a stationary 3 kg block at the bottom. Find (a) the speed of the 2 kg block just before collision, (b) the common velocity after collision, and (c) the kinetic energy lost in the collision.

**Answer: (a) v ≈ 9.9 m/s, (b) v_common ≈ 3.96 m/s, (c) KE lost ≈ 58.8 J**

<details><summary>Click for Solution</summary>

**(a)** Using conservation of mechanical energy (frictionless ramp):
mgh = ½mv² → v² = 2gh = 2×9.8×5 = 98 → v = √98 ≈ 9.9 m/s

**(b)** Using conservation of momentum for the perfectly inelastic collision:
v_common = (m₁u₁ + m₂u₂)/(m₁+m₂) = (2×9.9 + 3×0)/(2+3) = 19.8/5 ≈ 3.96 m/s

**(c)** KE before collision = ½(2)(9.9²) ≈ 98 J (equal to the PE lost on the ramp, as expected)
KE after collision = ½(2+3)(3.96²) ≈ ½×5×15.68 ≈ 39.2 J
KE lost = 98 − 39.2 ≈ 58.8 J

This problem chains Micro-Topics 6 (conservation of mechanical energy on the ramp) and 8 (perfectly inelastic collision at the bottom), a typical multi-concept board CQ structure.

</details>

**Q2 (Multi-concept CQ):** A pump lifts water from a well 12 m deep and delivers it at the top with a speed of 3 m/s, pumping 50 kg of water every second. Find the total power output of the pump. (g = 9.8 m/s²)

**Answer: P ≈ 6105 W**

<details><summary>Click for Solution</summary>

Per second, the pump must supply both gravitational PE and kinetic energy to 50 kg of water:

Power for lifting (PE component): P₁ = (mgh)/t = (50×9.8×12)/1 = 5880 W
Power for kinetic energy (KE component): P₂ = (½mv²)/t = (½×50×3²)/1 = 225 W

Total power: P = P₁ + P₂ = 5880 + 225 = 6105 W

This problem chains Micro-Topics 5 (gravitational PE), 4 (kinetic energy), and 7 (power as rate of energy delivery) — a classic multi-concept synthesis question.

</details>

---

## Chapter Status

All 9 micro-topics of Chapter 5 (Work, Energy and Power) are now formally closed and synthesized. Ready to proceed to **Chapter 6: Gravitation and Gravity** whenever you'd like to begin — or, if you'd prefer, I can generate a chapter-end MCQ drill set or a downloadable consolidated PDF/DOCX of all 9 micro-topic files combined.

What would you like next?
