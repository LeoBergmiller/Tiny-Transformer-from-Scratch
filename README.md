# Tiny Transformer from Scratch (PyTorch)

A minimal Transformer language model trained on the Tiny Shakespeare corpus for next-token prediction.

## Features
- Byte-level BPE tokenizer (vocab ≤ 500)
- Causal multi-head self-attention (no future attention)
- Residual connections + RMSNorm
- Training/validation loss curves + perplexity
- Attention heatmaps
- Optional text generation (temperature + top-k)

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```

## Notes 
- Includes a `FAST_DEV_RUN` toggle for fast runs vs longer training.
