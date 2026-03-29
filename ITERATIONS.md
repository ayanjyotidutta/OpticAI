# 🛠️ Product Iteration Log: OpticAI

**Product Owner:** Ayan Jyoti Dutta  
**Status:** Version 1.0 — Gold Master Release (COMPLETE)  
**Deployment:** [https://opticalgame.vercel.app/]

---

### 📈 The Comprehensive Evolution & Pivot Log

This table documents the strategic journey from a basic color-matching script to a high-fidelity perceptual benchmarking engine.

| Phase | Milestone | Challenge / Friction Point | Strategic Intervention | Result & Product Impact |
| :--- | :--- | :--- | :--- | :--- |
| **Alpha** | **Logic Foundation** | RGB (Red, Green, Blue) matching felt like "math," not "art." | **Architecture Shift:** Replaced RGB with **HSL (Hue, Saturation, Lightness)** logic. | Aligned the engine with human artistic intuition. Matching became a "feeling" rather than a calculation. |
| **Beta** | **The Game Loop** | The tool felt static; there were no stakes, urgency, or "game feel." | **The Timer Engine:** Split the UX into a strict **5s Memory** phase and a **30s Execution** phase. | Transformed a simple utility into a "Pressure Cooker" challenge that tests short-term visual memory. |
| **v0.5** | **UX Stress Testing** | Users lost focus during the 30s window. The stakes didn't feel "visceral." | **Sensory Sync:** Integrated a **1s heartbeat pulse** animation and a stressed timer UI. | Induced visceral urgency and psychological "timer stress," forcing users into a state of deep focus. |
| **v0.7** | **Scoring & Curve** | Scores were too linear/easy; rounds felt random and unrewarding. | **Cubic Decay Algorithm:** Applied a **1.8x exponent** to the Euclidean distance formula. | Elevated the skill ceiling; a "9.0+" became a true badge of honor. It separated the "Apprentices" from "Visionaries." |
| **v0.9** | **The Viral Hook** | Retention was low; users played once and closed the tab without sharing. | **The Viral Loop:** Added adaptive "Beat It" logic + a **Dual-Action Share Console**. | Triggered the *Zeigarnik Effect* (desire to finish/improve) and social competition via "one-tap" result copying. |
| **v1.0** | **Elite Production** | The UI lacked brand authority and a sense of professional "finish." | **Neomorphic Overhaul:** Implemented hardware-style depth, radiant glows, and **/50 benchmarking**. | Positioned as a **Premium Perceptual Audit** tool rather than a casual mobile game. |
| **Final** | **Instructional UX** | Minor cognitive friction; users weren't sure what to do in the heat of the timer. | **Instructional Headers:** Added "Memorise the Colour" and "Guess the Colour" clinical headers. | Zeroed out cognitive load. Users can now focus 100% of their mental energy on color retention. |

---

### 🎨 Version 1.0 Final Technical Specifications

#### **1. High-Intensity "Radiant" Glow UI**
* **The Problem:** The "Start" and "Retry" buttons were getting lost in the minimalist black background.
* **The Intervention:** Created an `@keyframes glow-pulse` with a 35px spread and 0.6 opacity white shadow.
* **The Logic:** This creates a "visual heartbeat." It draws the eye to the primary CTA (Call to Action) without needing loud colors, maintaining the "Old Money" aesthetic.

#### **2. Clinical Benchmarking Engine**
* **The Problem:** A raw score (e.g., 8.44) had no ceiling or context for a new user.
* **The Intervention:** Implemented a definitive **50.00 Point Scale** and the **"Elite Floor"** logic.
* **The Logic:** By adding `/50` to the final score and suggesting a minimum target of **25**, we establish a professional benchmark. It tells the user: "This is a serious test of your vision."

#### **3. Production-Grade UX Stability**
* **The Problem:** Two major technical "flaws" were identified during stress testing: the **Ghost Timer** (auto-jumping rounds) and **Mobile Zoom** (accidental pinching).
* **The Intervention:** * **Ghost Fix:** Added `setResultTimer(-2)` to kill the loop on manual click.
    * **Touch Fix:** Applied `touch-action: none` to the body and `pan-x` to sliders.
* **The Logic:** Ensures the tech is as premium as the design. The app feels "locked-in" and sturdy, especially on high-end mobile devices.

#### **4. Visual Perceptual Audit**
* **The Problem:** Users knew they were "wrong" but didn't know *why* or by how much.
* **The Intervention:** Re-engineered the **Split-View Comparison Cards** in the final summary.
* **The Logic:** By showing the Target vs. the Guess in a 50/50 split, users can visually audit their bias (e.g., "I always guess too bright"). This turns the app into a self-improvement diagnostic tool.

---

### 💼 Product Lead Reflection
> "OpticAI Version 1.0 represents the final evolution of a 'simple idea' into a **High-Fidelity Perceptual Engine**. We stripped away the clutter of traditional mobile gaming to reveal a clinical, tactile experience. By combining **Euclidean Math** with **Neomorphic Design**, we've created a product that is as much a status symbol as it is a vision test."

**Developed & Audited by Ayan Jyoti Dutta 😇**
