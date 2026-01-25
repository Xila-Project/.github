<h1 align="center">
  <img src="https://www.xila.dev/images/logo_dark.svg" alt="Xila Logo" style="height: 1em; vertical-align: middle;"> Xila
</h1>

<p align="center">
  <strong>A modern, memory-safe operating system for embedded systems.</strong><br>
  Rewritten in <b>Rust</b>. Powered by <b>WebAssembly</b>.
</p>

<p align="center">
  <a href="https://xila.dev">🌍 Website</a> •
  <a href="https://documentation.xila.dev/demonstrations/wasm/en/">🎬 Demonstrations</a> •
  <a href="https://www.xila.dev/guide/">📖 Guide</a> •
  <a href="https://www.xila.dev/reference/">📚 Reference</a> •
  <a href="mailto:contact@xila.dev">✉️ Contact</a> •
  <a href="https://matrix.to/#/#xila:anneraud.fr">💬 Matrix</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Rust-orange?style=flat-square&logo=rust" alt="Rust">
  <img src="https://img.shields.io/badge/Runtime-WASM-624de3?style=flat-square&logo=webassembly" alt="WASM">
  <img src="https://img.shields.io/matrix/xila%3Amatrix.org?style=flat-square&logo=matrix&label=matrix" alt="Matrix">
</p>

---

## ⚡ The Evolution

Xila has been completely reimagined. We have moved away from the legacy C++/Berry architecture to a modern stack built on **Rust** for maximum memory safety and **WebAssembly (WASM)** for a high-performance, sandboxed application ecosystem.

### Why the rewrite?

- **Memory Safety:** Leveraging Rust to eliminate common embedded bugs at compile-time.
- **WASM Portability:** Applications are language-agnostic. Develop in any language that targets WebAssembly.
- **Security:** Sandboxed execution of software components.
- **Performance:** Near-native execution speeds on microcontrollers.

## 🏗️ Architecture

Xila acts as a lightweight kernel and abstraction layer for microcontrollers (primarily ESP32-S3), providing:

- **Core:** The Rust-based heartbeat managing hardware abstraction and task scheduling.
- **WASM Runtime:** A portable execution engine for sandboxed binaries.
- **Unified API:** Simplified interfaces for graphics, connectivity, and storage.

## 📂 Repositories

| Repository                                             | Description                                                     |
| :----------------------------------------------------- | :-------------------------------------------------------------- |
| [**Core**](https://github.com/Xila-Project/Core)       | The Rust-based core operating system and WASM execution engine. |
| [**Website**](https://github.com/Xila-Project/Website) | The source for [xila.dev](https://xila.dev).                    |

## 💬 Community & Support

Join us to discuss development, suggest features, or get help:

- **Matrix:** [#xila:matrix.org](https://matrix.to/#/#xila:matrix.org)
- **Email:** [contact@xila.dev](mailto:contact@xila.dev)

> [!IMPORTANT]  
> Xila is currently in a **heavy alpha/rewrite phase**. The legacy C++ repositories have been archived to focus entirely on the new Rust/WASM architecture.

---

<p align="center">
  Built with 🦀 by <strong>Alix ANNERAUD</strong> and contributors. <br>
  Xila is licensed under the <a href="https://alix-anneraud.mit-license.org/">MIT License</a>.
</p>
