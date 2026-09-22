# Hello, I'm Eoghan! 👋

I build things that sit where hardware meets software: circuit boards, the firmware that runs on them, and the tools that check both before anything gets made. Right now that's Hauksbee.

If you're into engineering, entrepreneurship, or building things that matter, give me a shout.

## 🛠️ Technical Skills

[![Skills](https://skillicons.dev/icons?i=rust,cpp,python,ts,go,swift,react,arduino)](https://skillicons.dev)

## ⚡ Currently Building: [Hauksbee](https://github.com/hauksbee-dev/hauksbee)

**CI for hardware.** Hand it a PCB and it tells you what blows up before you order boards.

Hauksbee takes the files you already produce (KiCad, Eagle, Altium, ODB++, IPC-2581, Gerbers, BOM and placement data, and compiled firmware), reconstructs the circuit the copper actually implements, binds device models, solves it, and boots your firmware against the solved board. Every finding comes with the evidence that caused it.

- Given only the Gerbers a fab receives, it recovers the board's nets with 99.7–100% agreement against the native design (over located pads, across seven routed boards).
- Its generic USB-C classifier catches the Raspberry Pi 4's infamous charging fault in a reconstruction of the original board, and passes the repaired version.
- Written in Rust, with a CLI, a local web UI with live 2D copper and probes, and JSON/JUnit/SARIF output for CI.

<a href="https://github.com/hauksbee-dev/hauksbee"><img src="https://raw.githubusercontent.com/hauksbee-dev/hauksbee/main/frontend/screenshots/beauty/2d-live.png" alt="Hauksbee showing a board live in 2D with net activity" width="720"></a>

## 🚀 Favourite Projects

### Hardware and research

- **[Project Tarski](https://github.com/ETM-Code/Project-Tarski):** An analogue neuromorphic spiking neural network accelerator built from discrete components: a 350 mm, 3,442-component board designed to classify MNIST digits in analogue electronics at a fraction of the power of a digital chip. The board is built and spiking; bench bring-up is ongoing. Includes a [hardware-accurate emulator](https://github.com/ETM-Code/Tarski-Emulator) and a [Rust SNN trainer](https://github.com/ETM-Code/Gilgamesh) that trains against the real circuit.
- **[GridAI](https://github.com/ETM-Code/eirgrid):** Policy Gradient Reinforcement Learning to design the future of the Irish power grid. A blazingly fast, custom-built AI in Rust.
- **[ForceField](https://github.com/ETM-Code/forceField)** & **[ESP-Now-Node](https://github.com/ETM-Code/ESP-Now-Node):** Concussion-detecting hurling helmet sensors on an ESP32 mesh network, built in the Patch programme.
- **[Lander-Transmitter](https://github.com/ETM-Code/Lander-Code):** Optimised data transmission from a rocket lander, with a custom serial plotter.

### Apps and tools

- **[Quill](https://github.com/ETM-Code/quill):** A fast, native macOS markdown editor with WYSIWYG, LaTeX math, and syntax highlighting. Just 4.6 MB. Also available [for VS Code](https://github.com/ETM-Code/quill-vscode).
- **[Wiley](https://github.com/ETM-Code/wiley):** A voice-driven AI coworker at a shared Excalidraw whiteboard. It draws, codes, runs, and ships with you.
- **[Refract](https://github.com/ETM-Code/refract):** Apple-style liquid glass for the web as a React kit, refracting the real content behind it. [Live demo](https://etm-code.github.io/refract/).
- **[embed-codelab](https://github.com/ETM-Code/embed-codelab):** An embeddable coding-exercise component that compiles and grades Verilog, C, and Rust against hidden tests. Self-hosted, no Docker.
- **[fileconvert](https://github.com/ETM-Code/fileconvert):** Universal file converter that runs entirely in your browser via WebAssembly. No uploads, no servers.
- **[StudySmith](https://studysmith.app):** An AI learning app built to help people learn more consistently.
- **[modelRunner](https://github.com/ETM-Code/modelRunner):** Agent orchestration for debates, critique loops, and exploratory research between Claude and Codex.

### For fun

- **[Competitive Crafting](https://github.com/ETM-Code/competitive-crafting):** A multiplayer Minecraft crafting race. Share a room code and race your friends to craft the target item. [Play it here](https://competitive-crafting.eoghancollins.com).
- **[snakestral](https://github.com/ETM-Code/snakestral):** Watch Mistral AI play Snake. A demo of spatial reasoning in LLMs.

### Handy CLIs

- **[exam-papers](https://github.com/ETM-Code/exam-papers):** Bulk-download Irish State Exam papers and marking schemes, reverse-engineered from the examinations.ie archive.
- **[canvascli](https://github.com/ETM-Code/canvascli):** Browse Canvas LMS courses and download their content into PDFs.
- **[Music-Platform-Converter](https://github.com/ETM-Code/Music-Platform-Converter):** Convert playlists between Apple Music, Spotify, and YouTube Music.

## 📫 Contact Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Eoghan%20Collins-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/eoghan-timothy-collins/)
[![Website](https://img.shields.io/badge/eoghancollins.com-red?style=flat&logo=google-chrome)](https://eoghancollins.com)
