### `koodoxz` // Systems & Kernel Infrastructure

Focused on low-latency network primitives, kernel-level perimeter defense (eBPF/XDP), zero-allocation memory safety, and autonomous DNS resolution engineered in **Rust** and **Go**.

```
[ Edge Clients ] ──(DoQ)──> [ Ingress Gateway ] ──(UDS)──> [ Recursive Root ]
      ▲                            │                              ▲
      │                            ▼                              │
[ Caraka ]                  [ Kalas (eBPF) ]               [ Runut Engine ]
                                   ▲
                                   │ (Dynamic Threat Sync)
                            [ Tameng WAF ]
```

#### Active Initiative: MECOB Ecosystem
A high-performance, defense-in-depth networking architecture eliminating commercial telemetry and kernel softirq bottlenecks at hardware line-rate:

| Component | Scope | Core Technology | Repository |
| :--- | :--- | :--- | :--- |
| **[Kalas](https://github.com/koodoxz/kalas)** | Layer 3 & 4 | Linux eBPF / AF_XDP Driver Hook | [`koodoxz/kalas`](https://github.com/koodoxz/kalas) |
| **[Tameng](https://github.com/koodoxz/tameng)** | Layer 7 WAF | ML-assisted Behavioral Defense (Go) | [`koodoxz/tameng`](https://github.com/koodoxz/tameng) |
| **[Gapura](https://github.com/koodoxz/gapura)** | Ingress Gateway | DoQ / DoH / DoT Protocol Termination | [`koodoxz/gapura`](https://github.com/koodoxz/gapura) |
| **[Runut](https://github.com/koodoxz/runut)** | DNS Core | Zero-GC Iterative Root Resolver | [`koodoxz/runut`](https://github.com/koodoxz/runut) |
| **[Caraka](https://github.com/koodoxz/caraka)** | Edge Client | 0-RTT DNS over QUIC Proxy Forwarder | [`koodoxz/caraka`](https://github.com/koodoxz/caraka) |

🌐 **Interactive Architecture & Telemetry Portal:** [koodoxz.github.io](https://koodoxz.github.io)

---
<sub>Deterministic Infrastructure &middot; Zero-GC Primitives &middot; AGPL-3.0-or-later</sub>
