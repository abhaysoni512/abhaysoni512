<div align="center">

```
latency: [████████████████████] <1μs
```

# Abhay Soni
### Systems Engineer · Low-Latency C++ · HFT Infrastructure

*Building software where microseconds are money*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/abhaysoni512)
[![Twitter](https://img.shields.io/badge/X-000000?style=flat-square&logo=x)](https://x.com/abhaysoni512)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abhaysoni512@gmail.com)

</div>

---

## What I work on

C/C++ systems engineer focused on the intersection of **low-latency software** and **quantitative finance**.  
I work at the level of sockets, packets, kernel I/O — now optimizing for nanosecond-sensitive trading infrastructure.

```cpp
// My current obsession
auto t0 = rdtsc();
order_book.insert(order);          // sub-microsecond target
auto latency_ns = to_ns(rdtsc() - t0);
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

**Low-latency C++**
- C++17/20 — move semantics, templates, concepts, constexpr
- Lock-free data structures (SPSC/MPMC), `std::atomic` memory ordering
- Custom allocators (pool, arena), cache-line-aligned layouts, SIMD basics

**Linux performance**
- `epoll` / `io_uring`, `perf` / `vtune` profiling, CPU affinity & isolation
- Kernel bypass concepts (DPDK), hugepages, `rdtsc` cycle-accurate benchmarking

**Networking**
- TCP/UDP stacks, raw sockets, packet capture
- Multicast (market data delivery), FIX / ITCH protocol parsing

**Quant tooling**
- Python (NumPy, pandas) for research, backtesting, and data analysis
- Market microstructure: order book mechanics, bid-ask spread, market making

---

## 🛠 Stack

![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cpp&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📈 Stats

<div align="center">

_![Stats](https://github-readme-stats.vercel.app/api?username=abhaysoni512&show_icons=true&hide_border=true&theme=default&count_private=true)
![Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=abhaysoni512&layout=compact&hide_border=true&theme=default)___

</div>

---

## 📬 Open to

HFT / prop trading / quant finance roles in India — SDE / Systems Engineer profiles where **latency is a first-class requirement**.

> *"The bottleneck is always somewhere you haven't looked yet."*
