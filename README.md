### Hi, I'm Dylan 👋

Computer engineering student at **Trinity College Dublin** (MAI). I work on **exact quantum circuit simulation**, on the **classical verification of quantum-advantage claims**, and on **AI systems**. Currently at **Intel**, working on NPU software.

🌐 [dylanneve1.github.io](https://dylanneve1.github.io) · 📫 neved@tcd.ie

---

#### 🔬 Research highlights

- **Classical attacks on peaked quantum circuits.** Structural de-obfuscation plus tensor-network methods recover the hidden peak of BlueQubit's heuristic peaked circuits (HQAP) on ordinary hardware.
  - Solved **all 12 problems** of BlueQubit's Peak Portal (2570/2570), each correct on the first submission.
  - The 56-qubit **P9 in ~3 s on a laptop**, using an MPO with an exact centre block and mirror-partner scheduling. Prior published method: ~1 h on an A100.
  - The 98-qubit P11/P12, submitted to the [Quantum Advantage Tracker](https://github.com/quantum-advantage-tracker/quantum-advantage-tracker.github.io/issues/252), with the negative results written up too.
  - Code and write-ups: [`qsim-lab/research/data/peaked-circuits`](https://github.com/dylanneve1/qsim-lab/tree/main/research/data/peaked-circuits). Preprint in preparation.
- **[qsim-lab](https://github.com/dylanneve1/qsim-lab)**: an exact quantum circuit simulator written from scratch in Rust, with a typed Python API ([docs](https://dylanneve1.github.io/qsim-lab/)). A cost-model planner picks among state-vector, stabilizer, MPS, sparse, hybrid and other engines. Results include gate-level Shor factoring a generic 31-bit semiprime (and 39–43-bit N with small order support), detector sampling 9–12× faster than Stim on large jobs, and new weight-6 qLDPC codes.

#### 🛠️ Projects

| Project | What it is |
|---|---|
| [**Talon**](https://github.com/thefalconry/talon) | Open-source, multi-platform agent harness (Telegram, Discord, Teams, terminal) with pluggable model backends, MCP tools and persistent background agents |
| [**qsim-lab**](https://github.com/dylanneve1/qsim-lab) | Exact quantum circuit simulator (Rust + Python) and the research built on it |
| [**Islet**](https://github.com/dylanneve1/islet) | Material 3 Expressive "dynamic island" for Pixel, with runtime cutout detection and no network permission |
| [**CarDash**](https://github.com/dylanneve1/cardash) | Material 3 launcher for Android car head units; no AndroidX, no Gradle |
| [**TFI Go**](https://github.com/dylanneve1/tfi-go) | Material You redesign of TFI Live, Ireland's public-transport app |
| [**AICoreChat**](https://github.com/dylanneve1/AICoreChat) | On-device Gemini Nano chat via Android AICore |
| [**diy-gpt-pro**](https://github.com/dylanneve1/diy-gpt-pro) | Open-source multi-agent "pro" reasoning orchestrator |

#### 🧰 Tools I use

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog%2FVHDL-555555?style=flat)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat&logo=qiskit&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
