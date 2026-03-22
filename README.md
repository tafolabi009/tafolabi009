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
→ [OpenReview](#REPLACE_WITH_LINK)

**Thermodynamic Manifold Alignment: Physics-Inspired Compositional Reasoning**  
*Preprint — OpenReview*  
Statistical mechanics foundation · Parameterized manifold energy minimization  
SCAN benchmark evaluation  
→ [OpenReview](#REPLACE_WITH_LINK)

---

## Infrastructure

Currently operating a production AI inference stack:
- **8× NVIDIA H100 80GB** (GCP `a3-highgpu-8g`, `us-east5-a`)
- vLLM serving **Qwen3-235B-AWQ** on RAID-0 NVMe
- LangGraph-based agentic pipeline in active development

---

## Systems Projects

| Project | Language | Description |
|---|---|---|
| [TocinLang](https://github.com/tafolabi009/TocinLang) | C++ / LLVM | Statically-typed systems language targeting LLVM IR. Custom lexer, parser, semantic analyzer. Goroutine-style concurrency, NUMA-aware scheduling, V8 integration. |
| [TosinOS](https://github.com/tafolabi009/tosin_rtos) | C / x86 Assembly | 32-bit protected-mode monolithic kernel. Preemptive scheduler (16 priority levels), custom paging/heap allocator, VFS abstraction, IPC mechanisms. Sub-20KB footprint. |
| [EPOCH VCS](https://github.com/tafolabi009/epoch_vcs) | C++ / Rust | Distributed VCS via Merkle DAGs. C++ core + Rust backend. SIMD-accelerated diff (10× faster than Git), Ed25519 signatures, Zstd delta compression. |
| [NavierFlow](https://github.com/tafolabi009/NavierFlow) | Python / Taichi | CFD engine: Navier-Stokes + Lattice Boltzmann solvers. GPU-parallelized. Real-time multi-phase flow visualization. |
| [SynthOS](https://github.com/genovotechnologies/synthos_dev) | Python / PyTorch | AI training data validation. 90%+ model collapse prediction. Multi-scale cascade validation across 15+ proxy models (1M–500M params). |

---

## Company

**[Genovo Technologies](https://genovotech.com)** — Delaware C-Corp  
Member, NVIDIA Inception Program · YCombinator Mentorship  
Building SynthOS: synthetic data validation platform with model collapse detection and performance warranties.

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

## Recognition

- **NVIDIA Inception Program** — AI/Data infrastructure startup accelerator  
- **AAAI-26 Workshop Acceptance** — Novel O(T) neural architecture  
- **ORCID:** [0009-0001-2852-2885](https://orcid.org/0009-0001-2852-2885)

---

*Building from first principles. Compilers, kernels, novel architectures — not frameworks.*
