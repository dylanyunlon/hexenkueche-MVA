# Hexenküche — Mixed-Precision Vector Quantization across Asymmetric GPU Architectures

> *"Du musst verstehn! Aus Eins mach Zehn, und Zwei lass gehn, und Drei mach gleich..."*
> — Die Hexe, Faust I

Mix FP8 (H100) / FP16 (A6000) / INT8 (CPU) vector representations and
guarantee cross-precision distance equivalence for ANN recall consistency.

## Upstream

| Directory | Origin | Role |
|-----------|--------|------|
| `upstream/bigvectorbench` | [BenchCouncil/BigVectorBench](https://github.com/BenchCouncil/BigVectorBench) | Heterogeneous embedding benchmark |
| `upstream/jhq` | [jiabhan/JHQ](https://github.com/jiabhan/JHQ) | JL-enhanced hierarchical quantization |
| `upstream/fasthnsw` | [cryo-zd/fasthnsw](https://github.com/cryo-zd/fasthnsw) | Optimized HNSW index construction |
