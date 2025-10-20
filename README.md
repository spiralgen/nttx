# NTTX

[**NTTX**](https://www.spiral.net/software/nttx.html) is a [SPIRAL](https://www.spiral.net/index.html) package for high-performance cryptographic kernels, focusing on **number theoretic transforms (NTTs)** and **basic linear algebra subprograms (BLAS)** operations.

---

This repository serves as an umbrella project that hosts multiple components:

```
NTTX — A code generation framework for cryptographic kernels
│
├── MoMA (https://github.com/Naifeng/moma)
│   │   Builds upon NTTX
│   │   Implements rewrite rules for large integer arithmetic
│   │   Current target: GPUs
│
├── benchNTT (https://github.com/Naifeng/benchntt)
│   │   Planned integration with NTTX
│   │   Scalar and SIMD implementations
│   │   Current target: CPUs
│
└── ASIC backend (internal)
```

> The long-term goal is to develop a unified code generation framework that targets CPUs, GPUs, and emerging computing platforms to accelerate a wide range of cryptographic workloads.