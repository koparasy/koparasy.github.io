---
layout: default
title: Home
---

# Konstantinos “Dinos” Parasyris

**Computer Scientist · LLNL (CASC)**  
Compilers, runtime systems, GPU performance engineering, and ML/HPC integration.

![Profile photo](assets/pic.png){: style="width:160px;border-radius:14px;float:right;margin-left:18px;margin-top:6px;" }

I work on systems that sit at the intersection of **compilers (Clang/LLVM/MLIR)**, **parallel programming models (OpenMP/CUDA/HIP)**, and **machine-learning tooling (PyTorch)** for HPC workflows. I enjoy understanding systems end-to-end—how they behave, why they’re slow, and how to make them faster and more reliable.

---

## Focus Areas
- Compiler & IR design (LLVM/MLIR, ClangIR/CIR)
- GPU compilation, performance analysis, and autotuning
- Runtime specialization / JIT compilation
- ML-driven performance engineering and surrogate modeling for HPC

---

## Projects

**Mneme**  
[Mneme](https://olympus-hpc.github.io/Mneme/) is a kernel-centric record–replay and autotuning framework designed to collect realistic GPU performance data from large applications. It captures individual kernel executions together with their memory state, allowing replay, specialization, and performance exploration in isolation. Mneme is used to build representative datasets for compiler and runtime research, lowering the barrier to data-driven optimization and ML-based performance modeling.

**Proteus**  
[Proteus](https://olympus-hpc.github.io/proteus/) is an LLVM-based JIT specialization framework that enables IR-level transformations and optimization decisions at runtime. It allows selective specialization of function arguments, dynamic optimization-level selection, and integration of custom LLVM passes without requiring whole-program recompilation. Proteus is designed for incremental adoption in HPC codes and supports both CUDA and HIP toolchains.

**AMS**  
[AMS](https://software.llnl.gov/AMS/) integrates machine-learning surrogate models into scientific simulation codes to accelerate expensive computations while preserving correctness. It provides a runtime interface for model inference, confidence-based fallback to the original computation, and seamless integration with MPI-based ensemble workflows. AMS is designed to support emerging AI-driven workflows in production HPC environments.

**ClangIR (CIR)**  
[ClangIR](https://github.com/llvm/clangir/commits?author=koparasy) I contribute to the design and implementation of ClangIR (CIR), focusing on GPU-related extensions such as address-space semantics, device runtime lowering, fatbinary registration, and split compilation. This work aims to provide a more structured and analyzable IR between Clang and LLVM, improving compiler diagnostics, transformations, and long-term maintainability.

**OpenMP**  
My work on OpenMP offload focuses on compiler and runtime support for GPU targets. I was part of the team that prototyped the llvm/offload project through the [CUDAOMP](https://dl.acm.org/doi/abs/10.1145/3559009.3569687) work.


---

## Selected Publications & Service
- Publications: [Google Scholar](https://scholar.google.gr/citations?user=BVW8btMAAAAJ&hl=el&oi=ao)
- Open-source: [GitHub](https://github.com/koparasy)
- Professional: [LinkedIn](https://www.linkedin.com/in/koparasy/) 

---

## Contact
- **Office:** LLNL-CASC, B451

> Note: This page reflects personal work and views, not official positions of LLNL.

