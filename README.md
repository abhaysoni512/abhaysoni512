<div align="center">


![latency](https://img.shields.io/badge/latency-%3C1μs-success?style=flat-square)


# Abhay Soni

**Systems Engineer · Low-Latency C++ · HFT Infrastructure**

*Building software where microseconds are money*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/abhaysoni512)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/abhaysoni512)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/abhaysoni512/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abhaysoni512@gmail.com)

</div>

---

## About

C/C++ systems engineer with **2 years of production experience** in low-latency software —
working at the level of sockets, packets, and kernel I/O.

Focused on **HFT infrastructure**: nanosecond-scale execution, lock-free concurrency, and
market data systems. I care about performance that's measured, not assumed.

```cpp
// what I think about
auto t0 = rdtsc();
order_book.insert(order);                // sub-microsecond target
auto latency_ns = cycles_to_ns(rdtsc() - t0);
assert(latency_ns < 1000);              // or go back to the drawing board
```

---

## Projects

| Project | Description | Stack | Highlight |
|---|---|---|---|
| [**limit-order-book**](https://github.com/abhaysoni512/limit-order-book) | Price-time priority matching engine | C++20 | `rdtsc` benchmarks · lock-free inserts |
| [**market-data-feed-handler**](https://github.com/abhaysoni512/market-data-feed-handler) | Zero-copy ITCH / FIX parser + UDP multicast receiver | C++ · Rust | Zero heap alloc on hot path |
| [**low-latency-epoll-server**](https://github.com/abhaysoni512/low-latency-epoll-server) | `epoll`-based event loop, CPU-pinned, 1M+ events/sec | C++ | Tuned with `perf` + cache profiling |
| [**backtesting-engine**](https://github.com/abhaysoni512/backtesting-engine) | Tick-level strategy simulation with fill & slippage models | Python · C++ | Pluggable signal API |
| [**tcp-udp-toolkit**](https://github.com/abhaysoni512/tcp-udp-toolkit) | Raw socket experiments · protocol dissection | C | Built for learning, documented for others |

---

## Technical Depth

**Low-latency C++**
- C++17/20 — move semantics, perfect forwarding, concepts, `constexpr`, coroutines
- Lock-free data structures: SPSC / MPMC ring buffers, `std::atomic` with all memory orderings
- Custom allocators (pool, arena), cache-line-aligned structs, SIMD (SSE4 / AVX2 basics)
- Profiling: `perf`, `vtune`, `valgrind`, `rdtsc`-based cycle-accurate benchmarking

**Linux & kernel I/O**
- `epoll` / `io_uring`, CPU affinity & isolation (`isolcpus`, `taskset`), IRQ pinning
- Kernel bypass concepts: DPDK, hugepages, `mlock`
- Tooling: `perf stat`, `perf record`, flamegraphs, `strace`, `tcpdump`

**Networking**
- TCP/UDP socket programming, raw sockets, packet capture
- Multicast (market data delivery), FIX / ITCH protocol parsing
- Zero-copy I/O patterns, scatter-gather, `sendmmsg` / `recvmmsg`

**Quant & market basics**
- Order book structure: price levels, bid-ask, market making, L1/L2/L3 data
- Python (NumPy, pandas) for research, backtesting, and tick data analysis
- FIX protocol, VWAP / TWAP, basic market microstructure

---

## Stack

![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-CE6737?style=flat-square&logo=rust&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Stats

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=abhaysoni512&theme=github-dark-blue&hide_border=true)

<img height="155" src="https://github-readme-stats.vercel.app/api?username=abhaysoni512&show_icons=true&hide_border=true&theme=github_dark&count_private=true&include_all_commits=true&rank_icon=github" />
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhaysoni512&layout=compact&hide_border=true&theme=github_dark&langs_count=6&hide=jupyter%20notebook" />

</div>

---

## Open to

HFT · prop trading · quant finance roles in India — Graviton, Tower Research, Quadeye, Optiver and similar.

SDE / Systems Engineer profiles where **latency is a first-class constraint**, not an afterthought.

> *"The bottleneck is always somewhere you haven't looked yet."*
