# Creative Question: Work, Energy & Power

**[P1-Ch05: Work, Energy & Power | Micro-topic: Work Done by a Variable Force | Tier 1 | Level: Knowledge(a)/Comprehension(b)/Application(c)/HigherOrder(d) — CQ]**

---

### Stem
A force acting on a particle moving along the x-axis varies as $F = (6x + 2)\text{ N}$, where $x$ is in meters. The particle moves from $x = 1\text{ m}$ to $x = 4\text{ m}$. An engineer claims that treating this variable force as if it were constant (using its value at $x = 1\text{ m}$) to estimate total work would overestimate the true work done.

---

### Questions & Answers

#### (a) State the general expression for work done by a variable force. (1 mark)

For a variable force, work done is **$W = \int F \, dx$, the integral of force with respect to displacement between the initial and final positions**.

---

#### (b) Why can't the simple formula $W = Fs$ be used directly for a variable force? (2 marks)

The formula $W = Fs$ cannot be used directly because **it assumes $F$ stays constant over the entire displacement, but a variable force changes value continuously with position**.

The formula $W = F s \cos \theta$ is valid only for an infinitesimally small displacement $dx$ over which $F$ may be treated as approximately constant, giving $dW = F \, dx$. To find total work over a finite path where $F$ genuinely changes, these infinitesimal contributions must be summed continuously, which is precisely the operation of integration. Using a single constant value of $F$ across the whole path ignores this variation and yields an incorrect result.

---

#### (c) Calculate the work done by the force as the particle moves from $x = 1\text{ m}$ to $x = 4\text{ m}$. (3 marks)

The stem directly relates to **Work Done by a Variable Force via Integration**.

> **Work by Variable Force:** $W = \displaystyle\int_{x_1}^{x_2} F \, dx$, where $F$ is expressed as a function of position $x$.

From the stem:
* Force function, $F = (6x + 2)\text{ N}$
* Initial position, $x_1 = 1\text{ m}$
* Final position, $x_2 = 4\text{ m}$

$$W = \int_{1}^{4} (6x + 2) \, dx = \left[3x^2 + 2x\right]_{1}^{4}$$

$$W = \left(3(4)^2 + 2(4)\right) - \left(3(1)^2 + 2(1)\right)$$

$$W = (48 + 8) - (3 + 2) = 56 - 5 = 51\text{ J}$$

Therefore, the work done by the variable force is **$51\text{ J}$**, found using **Work Done by a Variable Force via Integration**.

---

#### (d) Evaluate the engineer's claim by comparing the true work with the constant-force estimate. (4 marks)

The engineer's claim is **incorrect — using $F$ at $x = 1\text{ m}$ as a constant underestimates the work, it does not overestimate it**.

> **Comparing Constant-Force Estimate with True Variable-Force Work:**  
> If $F$ increases with $x$ over the path, using the smallest value of $F$ (at the start point) as a constant will always give a work estimate lower than the true integrated work, since every subsequent point on the path actually experiences a larger force than the one assumed.

From the stem:
* Force at initial position ($x = 1\text{ m}$):  
  $$F_1 = 6(1) + 2 = 8\text{ N}$$
* Total displacement ($s$):  
  $$s = x_2 - x_1 = 4 - 1 = 3\text{ m}$$

Using this initial force as a constant over the entire distance:

$$W_{\text{estimate}} = F_1 \cdot s = (8)(3) = 24\text{ J}$$

**Comparison:**
* Estimated Work: $W_{\text{estimate}} = 24\text{ J}$
* True Work (from part c): $W_{\text{true}} = 51\text{ J}$

Since $24\text{ J} < 51\text{ J}$, the constant-force method underestimates, rather than overestimates, the true work done.

Therefore, **because $F$ increases from $8\text{ N}$ to $26\text{ N}$ over the path, assuming the initial smaller value throughout gives $24\text{ J}$, well below the true $51\text{ J}$, so the engineer's claim is false**.

---

> 📘 **Bangla Note (বোঝার জন্য — পরীক্ষার খাতায় লিখবে না):**  
> পরিবর্তনশীল বলের কাজ $W = \int F \, dx$ দিয়ে বের করতে হয়। এখানে বল $x$ বাড়ার সাথে বাড়ছে ($8\text{ N} \to 26\text{ N}$), তাই শুরুর মান ধ্রুবক ধরলে প্রকৃত কাজের চেয়ে কম মান পাওয়া যাবে (২৪ J বনাম প্রকৃত ৫১ J) — বেশি নয়।
