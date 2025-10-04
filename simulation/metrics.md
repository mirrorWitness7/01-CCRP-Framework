# Simulation Metrics Reference

| Metric | Description | Formula (Conceptual) |
|---------|--------------|----------------------|
| **Input Fidelity %** | Quality of incoming data after Law 5 pruning. | (Fossil tokens / Total tokens) × 100 |
| **Distortion %** | Noise or self-proclamation detected in input. | 100 – Fidelity % |
| **Collapse Depth** | Degree of coherence loss under stress. | Token drift / Baseline coherence |
| **Reintegration Success %** | Extent to which coherence is restored. | (Recovered coherence / Baseline) × 100 |
| **Entropy Trajectory** | Temporal curve of disorder → order. | ΔEntropy / ΔTime |

Use these as high-level research metrics; not intended for production scoring.
