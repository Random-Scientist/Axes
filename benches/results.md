Benchmarks (Taffy 0.9.2 from crates.io vs Axes 0.2.0)

Runned on a Ryzen 5 5625U

| Benchmark | Axes | Taffy | Difference |
| --- | --- | --- | --- |
| Tree: 1,000 Nodes | 15.889 µs | 89.114 µs | 460.853% |
| Tree: 10,000 Nodes | 1.1744 ms | 1.0698 ms | -8.90668% |
| Tree: 100,000 Nodes | 8.7379 ms | 33.083 ms | 278.615% |
| Compute: 1,000 Nodes | 17.423 µs | 39.317 µs | 125.661% |
| Compute: 10,000 Nodes | 176.51 µs | 446.35 µs | 152.875% |
| Compute: 100,000 Nodes | 1.7988 ms | 14.976 ms | 732.555% |

Axes is about 3x faster than Taffy
