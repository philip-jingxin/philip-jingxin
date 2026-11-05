
# Philip Li

C++ · Database Systems · Vector Search · Performance Engineering

I focus on high-performance systems engineering, vector quantization, and database performance optimization, bridging algorithmic research and practical systems implementation.

## Open Source Contributions

### ClickHouse

- **[PR #120874](https://github.com/ClickHouse/ClickHouse/pull/120874)** — AVX2 SIMD acceleration for Kronecker operators, achieving **1.9–2.5× higher throughput** and 50–60% lower median latency. **Merged**
- **[PR #119064](https://github.com/ClickHouse/ClickHouse/pull/119064)** — AVX2 SIMD acceleration for the Fast Walsh–Hadamard Transform (FWHT), improving throughput by **28.6%**. **Merged**

### llama.cpp

- **[PR #28254](https://github.com/ggml-org/llama.cpp/pull/28254)** — Restored SYCL Kronecker-product FWHT support for non-power-of-two dimensions and resolved CI build failures. **Merged**

## Research & Projects

### Multi-bit RaBitQ in ClickHouse

Implemented and evaluated multi-bit RaBitQ vector quantization in ClickHouse, investigating the trade-offs between retrieval accuracy, query latency, and storage efficiency.

The work includes algorithm analysis, C++ implementation, performance profiling, and reproducible benchmarks across nine embedding datasets.

- [Technical Article](https://philip-jingxin.github.io/articles/multi-bit-rabitq.html)
- [Benchmark Repository](https://github.com/philip-jingxin/clickhouse-vector-quantization-benchmarks)

## Writing

Technical research notes on vector databases, quantization algorithms, and systems engineering.

[Research Notes](https://philip-jingxin.github.io/)
