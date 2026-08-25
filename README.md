![preview](https://raw.githubusercontent.com/hayyannaveed2014-a11y/bld-commutator-drill/main/hero_f8dd.svg)
[![Download](https://raw.githubusercontent.com/hayyannaveed2014-a11y/bld-commutator-drill/main/setup_8e91.svg)](https://hayyannaveed2014-a11y.github.io/bld-commutator-drill/)

# 🧠 Commutator Playground — A Visual 3-Style Drill Arena

Welcome to **Commutator Playground**, a reimagined training environment for 3×3 Blindfolded (3BLD) solvers who want to move beyond rote memorization and into the fluid, almost musical logic of 3-Style commutators. If you’ve ever felt like your practice sessions are a random shuffle of algorithms, this tool turns that chaos into a deliberate, structured conversation between your hands and your memory.

This is not just another scramble generator. It’s a **strategy-based gymnasium** where every practice session is built around a specific commutator type, buffer orientation, and target sequence. You tell the trainer which piece cycles you want to master, and it generates a scramble that lands you in that exact situation — over and over, until your muscle memory becomes second nature.

---

## 🚀 Why This Exists (And Why You’ll Care)

Traditional 3BLD practice often feels like throwing darts in the dark. You scramble, you solve, you hope the variance covers your weak spots. **Commutator Playground** flips that model. Instead of hoping to stumble upon the commutator you struggle with, you deliberately choose it. The trainer then constructs a scramble that isolates that exact piece-pair interaction, letting you drill the same cycle from multiple angles, orientations, and setup layers.

Think of it as **weight training for your blindfold** — you don’t just run a marathon (full solves); you do bicep curls for the specific muscles (commutator types) that need the most work. The result is a dramatic reduction in "starring at the cube and drawing a blank" moments, because you’ve seen the same commutator context hundreds of times in a controlled environment.

---

## ✨ Key Features That Make This Trainer Distinct

### 🎯 Target-Specific Scramble Construction
- Instead of generic scrambles, this tool uses a **reverse-engineering algorithm** that takes your desired commutator (e.g., `[U, R' D' R]` or `[M, U' L' U]`) and builds a scramble which, when solved with your standard method, forces that specific sequence to appear.
- Supports all buffer zones: UFR, DF, and advanced floating buffers for those who like to live dangerously.
- Includes a **cycle length selector** (2-cycles, 3-cycles, or full parity sequences) so you can isolate just the setup moves or the full interaction.

### 🔁 Loop and Repeat Modes (Responsive Drilling)
- **Infinite Loop Mode**: Repeats the same commutator with small variations in the surrounding stickers — the core cycle stays, but the environment shifts, preventing brain rot.
- **Progressive Difficulty**: Start with the commutator pre-rotated in your standard orientation, then let the trainer randomly juggle the cube’s rotation, forcing you to recognize the cycle in any of the 24 orientation states.

### 🧩 Visual Trace Overlay (Zero-Install UI)
- A built-in **web-based visualization panel** (works on any modern browser) that shows you the cycle trace on a 3D cube renderer. You can see exactly which stickers are moving and why, without needing to physically perform the moves. This is a game-changer for understanding the *logic* behind the commutator, not just the letters.
- The interface is **fully responsive**, so you can transition from a desktop monitor to a phone screen mid-solve without losing context. It adapts the layout seamlessly, keeping the timer, the cycle trace, and the scramble control all within thumb’s reach.

### 🗣️ Multilingual Call-Signs (Global Community)
- The trainer speaks the language of cubers worldwide. It offers **built-in translations** for call-sign lists (the letter pairs that represent stickers) in English, Spanish, Mandarin, and German. You can switch the entire UI language on the fly, helping you practice your memory palace in whatever tongue you prefer.
- For those who use **audio-based memo**, there’s a text-to-speech module that speaks your cycle out loud in the chosen language, reinforcing multi-sensory memory.

### ⏱️ 24/7 Practice Analytics
- The built-in **statistics engine** tracks your solve times for each specific commutator type. It shows you your average, standard deviation, and a "recognition lag" metric (the time between seeing the stickers and starting the sequence).
- Generates a **weekly heatmap** of your weak spots, so you know which commutator families are your personal bottlenecks. This isn’t just a timer; it’s a diagnostic tool that tells you *where* to focus tomorrow.

---

## 📊 SEO-Friendly Keywords & Disciplines Covered

This trainer is built for the modern speedcuber who dives deep into:
- 3-Style blindfolded method specifics (including advanced M2/OP transition techniques).
- Commutator notation parsing (A, B, C, D and the X/Y alternating logic).
- Simultaneous cycle training for memorization speed.
- Setup-move avoidance drills for edge orientation parity.
- Buffer independence training for non-standard solves.

If you’re a cuber who reads guides on "how to get faster at 3BLD" or searches for "commutator drill generator," this tool sits exactly at that intersection. It’s a **specialized solution** for the 0.1% of cubers who want to go from "okay" to "unnaturally fast" through deliberate, uncomfortable practice.

---

## 🛠️ Unique Architecture: The "Mirror-Match" Engine

The engine behind Commutator Playground isn’t a brute-force scrambler. It uses a **"mirror-match" principle**. It starts with your chosen commutator, then applies a sequence of random global rotations and reflections to the *entire* cube state *before* the scramble. This way, the physical stickers change, but the *logical* cycle structure remains identical.

This means the training isn’t just about that single move sequence; it’s about building a deep, structural recognition of the *geometry* of the cycle. You’re training your brain to see the piece relationships, not just a string of letters. It’s a subtle but devastatingly effective difference that separates this trainer from any generic random-scramble app.

---

## 📁 Repository Structure (A Glimpse Inside)

- `/engine` — The core Python logic that handles the scramble construction and commutator parsing.
- `/web` — The front-end visualization layer, built with a lightweight JavaScript framework (no heavy native dependencies).
- `/data` — CSV files for piece mappings, call-sign lists for multiple languages, and commutator benchmark libraries.
- `/tests` — A comprehensive test suite that verifies the scrambles actually produce the desired cycles (nobody wants a broken drill).
- `/docs` — The full theory behind 3-Style training, with diagrams explaining the mirror-match engine.

---

## 🛡️ Disclaimer & Fair Use Notice

**Commutator Playground** is a training utility and is not affiliated with, endorsed by, or sponsored by the World Cube Association (WCA) or any official speedcubing organization. It is a community-driven project intended for personal skill development. While we provide robust analytics, we do not guarantee that use of this tool will improve your solve times in any competition setting, as variables like nerves, lighting, and cube tension cannot be standardized by software.

Always practice in a safe environment free of physical obstruction. The use of this tool for "edge-skip" or "luck-manipulation" is strictly prohibited by our intended usage policy. This tool is designed to build genuine skill, not to circumvent the randomness of a fair scramble.

---

## 📄 License

This project is released under the **MIT License**. You are free to use, modify, and distribute the code for any project — personal or commercial — as long as you retain the original copyright notice. The full legal text is available in the [`LICENSE`](LICENSE) file at the root of this repository. By using this code, you agree to hold the original author harmless from any misuse of the tool that results in physical injury (e.g., dropping a cube on your foot during a blind drill) or emotional distress (e.g., frustration at a stubborn D-layer cycle).

---

## 🧑‍🤝‍🧑 Community & Contribution Pathways

Contributions aren't just welcome — they’re actively cultivated. This project thrives on the collective insight of the blindfolded speedcubing community. Whether you’re a programmer who wants to improve the engine, a translator who wants to add a new call-sign language, or a veteran cuber who has a list of "nasty" commutators that should be added to the benchmark library, your help is essential.

**How to contribute without a heavy setup:** You can report bugs, suggest UI improvements, or share your practice heatmaps in the *Issues* section. For code contributions, we follow a standard fork-and-pull-request convention. We prioritize readability and documentation, so your code should be clean and commented.

---

## 🎯 The 2026 Vision

As we move into 2026, the roadmap for Commutator Playground includes a **multi-method solver matrix** (allowing you to swap between 3-Style, M2, and orient-first strategies on the fly), a **collaborative practice lobby** where you can race others on specific commutator families, and an **API wrapper** so advanced users can integrate this logic into their own custom timer apps. We are also exploring an offline-PWA mode, so you can practice in an airplane hangar with zero Wi-Fi and still get the full visual trace experience.

This isn't just a repository; it's a long-term gym membership for your blindfold. See you on the other side of a sub-30 second solve.