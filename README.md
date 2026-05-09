<div align="center">

![latency](https://img.shields.io/badge/latency-%3C1μs-success?style=flat-square)

# Abhay Soni
### Systems Engineer · HPC & Computational Systems · 2 Years | Performance-Critical Infrastructure

*Building software where every nanosecond of compute matters*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/abhaysoni512)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=flat&logo=x&logoColor=white)](https://x.com/abhaysoni512)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/abhaysoni512/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:abhaysoni512@gmail.com)

</div>

---

## What I work on

C/C++ systems engineer with 2 years of focused experience in **performance-critical infrastructure** and **systems optimization**. Building expertise in low-latency networking, distributed systems, and kernel-level optimization for compute-intensive workloads.

```cpp
// My current obsession: compute efficiency
auto t0 = rdtsc();
computational_kernel<<<blocks, threads>>>();  // GPU kernels
mpi_collective_operation();                    // Distributed memory
auto latency_ns = to_ns(rdtsc() - t0);        // sub-microsecond targets
```

---

## 🔨 Active builds

| Project | What it does | Stack | Status |
|---|---|---|---|
| [`limit-order-book`](https://github.com/abhaysoni512/limit-order-book) | Price-time priority matching engine with `rdtsc` benchmarks | C++20 | 🚧 Building |
| [`market-data-feed-handler`](https://github.com/abhaysoni512/market-data-feed-handler) | Zero-copy ITCH/FIX parser, UDP multicast receiver | C++/Rust | 🚧 Building |
| [`low-latency-epoll-server`](https://github.com/abhaysoni512/low-latency-epoll-server) | `epoll`-based event loop, 1M+ events/sec, CPU-pinned | C++ | 🚧 Building |
| [`backtesting-engine`](https://github.com/abhaysoni512/backtesting-engine) | Tick-level strategy simulation, fills & slippage modelling | Python/C++ | 🚧 Building |
| [`tcp-udp-toolkit`](https://github.com/abhaysoni512/tcp-udp-toolkit) | Raw socket experiments, custom protocol stacks | C | 🚧 Building |

---

## ⚙️ Technical depth

**Parallel & Distributed Computing**
- MPI (point-to-point, collectives), OpenMP task & loop parallelism, CUDA/HIP GPU kernels
- Lock-free algorithms (SPSC/MPMC queues), `std::atomic` memory ordering, memory fence optimization
- Domain decomposition, data layout optimization (AoS vs SoA), cache-line awareness

**C++ Systems Programming**
- C++17/20 — move semantics, variadic templates, concepts, constexpr metaprogramming
- Custom allocators (pool, arena, aligned), RAII patterns, performance-critical code paths
- Template specialization, SIMD intrinsics (AVX2/AVX-512), compiler-driven optimization

**Performance Engineering**
- Profiling & benchmarking (`perf`, `likwid`, NVIDIA profilers, flame graphs)
- Roofline analysis, bandwidth/latency characterization, micro-benchmarking
- CPU affinity, NUMA awareness, kernel bypass techniques (io_uring), hugepages
- `rdtsc` cycle-level timing, cache behavior analysis

**HPC Infrastructure**
- Linux kernel tuning, process scheduling, interrupt affinity
- Network optimization (TCP/UDP, multicast, RDMA concepts), zero-copy patterns
- Build systems (CMake), continuous performance regression testing
- Containerization & reproducible compute environments

---

## 🛠 Stack

![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cpp&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MPI](https://img.shields.io/badge/MPI-0051BA?style=flat-square&logo=data:image/svg%2bxml,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%20100%20100%22%3E%3Ctext%20x=%2250%22%20y=%2270%22%20font-size=%2270%22%20text-anchor=%22middle%22%3EMPI%3C/text%3E%3C/svg%3E&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-0051BA?style=flat-square&logo=data:image/svg%2bxml,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%20100%20100%22%3E%3Ctext%20x=%2250%22%20y=%2270%22%20font-size=%2260%22%20text-anchor=%22middle%22%3EOMP%3C/text%3E%3C/svg%3E&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📈 Stats

<div align="center">

![Abhay's GitHub Stats](https://github-readme-stats.vercel.app/api?username=abhaysoni512&show_icons=true&theme=github_dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abhaysoni512&theme=github_dark)

</div>

---

## 📬 Open to

HPC systems engineer roles in India — CSIR labs, IITs, cloud platforms, or performance-focused tech companies. Seeking mid-level SDE/Systems Engineer positions in computational systems, performance engineering, or scientific computing where **optimization and system-level thinking are valued**.

> *"Performance is a feature. Measure it. Optimize it. Own it."*
