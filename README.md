# Oluwatosin Abioye Afolabi

**Founder & CEO, Genovo Technologies · NVIDIA Inception Program**
Systems Architect · ML Researcher · Published at AAAI '26

Lagos, Nigeria · [afolabi@genovotech.com](mailto:afolabi@genovotech.com) · [genovotech.com](https://genovotech.com) · [folabi.me](https://folabi.me)

---

## Research

**Temporal Eigenstate Networks: Linear-Complexity Sequence Modeling via Spectral Decomposition**
*Accepted — AAAI-26 AIDD Workshop*
O(T) complexity vs O(T²) transformers · 3–28× speedup · 120× memory reduction
Universal approximation proofs · Lyapunov stability analysis
→ [OpenReview](https://openreview.net/forum?id=DGgt5mCyY3)

**Resonance Neural Networks: Frequency-Domain Information Processing**
*Preprint — OpenReview*
O(n log n) FFT-based architecture · 4–6× parameter efficiency vs transformers
Gradient stability proofs · Holographic memory encoding

**Thermodynamic Manifold Alignment: Physics-Inspired Compositional Reasoning**
*Preprint — OpenReview*
Statistical mechanics foundation · Parameterized manifold energy minimization
SCAN benchmark evaluation

---

## Systems Projects

| Project | Language | What it is |
|---|---|---|
| [Genovo Engine](https://github.com/tafolabi009/genovo-engine) | Rust | AAA-tier game engine. 253K+ lines across 26 modules: PBR/deferred/ray tracing renderer, rigid body + cloth + fluid physics, behavior trees + navmesh AI, custom scripting VM, reliable UDP networking. |
| [TocinLang](https://github.com/tafolabi009/TocinLang) | C++ / LLVM | Systems language targeting LLVM IR. Custom lexer, parser, semantic analyzer. Goroutine-style concurrency, NUMA-aware scheduling, V8 FFI. |
| [TosinOS](https://github.com/tafolabi009/tosin-rtos) | C / x86 ASM | 32-bit protected-mode monolithic kernel. Preemptive scheduler (16 priority levels), custom paging/heap, VFS, IPC. Sub-20KB. |
| [EPOCH VCS](https://github.com/tafolabi009/epoch-vcs) | C++ / Rust | Distributed VCS via Merkle DAGs. SIMD-accelerated diff (10× faster than Git), Ed25519 signatures, Zstd delta compression. |
| [NavierFlow](https://github.com/tafolabi009/navierflow) | Python / Taichi | CFD engine: Navier-Stokes + Lattice Boltzmann solvers. GPU-parallelized. Real-time multi-phase flow visualization. |
| [Hate](https://github.com/tafolabi009/hate) | Rust | Register-based bytecode VM. NaN-boxed values (8-byte), generational GC, async/await, pattern matching, closures. |
| [Code Editor](https://github.com/tafolabi009/Code-editor) | C++17 / x86-64 ASM | SIMD-accelerated editor. AVX2/SSE4.2 search at 10GB/s, gap buffer, ImGui UI, <100ms cold start, <50MB RAM. |
| [Emulator](https://github.com/tafolabi009/genovo-emulator) | C++20 | Cross-platform emulator framework for NES/GB/CHIP-8/x86 BIOS. Micro-op CPU execution, hardware-accelerated video. |

---

## Genovo Technologies

**[Genovo Technologies](https://genovotech.com)** — Delaware C-Corp · NVIDIA Inception Program

| Product | Description |
|---|---|
| **[SynthOS](https://synthos.dev)** | AI training data validation. 90%+ model collapse prediction. Multi-scale cascade validation across 15+ proxy models (1M–500M params). |
| **Autonomous SRE Agent** | LLM-driven infrastructure agent for incident detection, root-cause analysis, and automated remediation. |
| **COBOL Migration Engine** | Transpiles COBOL to idiomatic Go. AST-level transformation with semantic preservation. |

---

## Infrastructure

Production AI inference stack:
- **8× NVIDIA H100 80GB** (GCP `a3-highgpu-8g`, `us-east5-a`)
- vLLM serving **Qwen3-235B-AWQ** on RAID-0 NVMe
- LangGraph-based agentic pipeline

---

## Skills

```
Systems:      Rust · C++ · C · x86 Assembly · LLVM IR · OS Kernels · Compiler Design
ML Research:  PyTorch · CUDA · Novel Architectures · Spectral Methods · Mathematical Proofs
Inference:    vLLM · H100 Cluster Ops · AWQ Quantization · Distributed Serving
Security:     CEH (EC-Council) · Penetration Testing · Threat Detection · Cryptography
Infra:        AWS · GCP · Docker · Kubernetes · CI/CD · Linux
```

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tafolabi009&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tafolabi009&layout=compact&theme=dark&hide_border=true&langs_count=8" height="165" />
</p>

---

**ORCID:** [0009-0001-2852-2885](https://orcid.org/0009-0001-2852-2885)

*Compilers, kernels, novel architectures — not frameworks.*
