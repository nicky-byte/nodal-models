# Nodal models

Files the Nodal iOS app downloads on demand.

## jev.gguf

The on-device safety classifier Nodal uses to screen chat and image prompts.

- Source: [AlexWortega/openjev](https://huggingface.co/AlexWortega/openjev), `qwen3.5-0.8b-nli-v2s-long` (MIT licence)
- Base model: Qwen3.5 0.8B (Apache License 2.0)
- Converted to GGUF with llama.cpp's `convert_hf_to_gguf.py --no-mtp` and quantised to Q6_K with `llama-quantize`.
- SHA-256: `bb9e7efff0a2ab2c6f2ea83074d1042b0c08f881c3bd0b526574546aaed786d4`

The original model's licences apply to this file.
