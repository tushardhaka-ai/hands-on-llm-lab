# Hands-on LLM: Transformers, Attention & Fine-tuning

An interactive companion notebook for learning the mechanics behind modern language models: vectors, cosine similarity, queries/keys/values, scaled dot-product attention, a tiny trainable PyTorch model, and an optional FLAN-T5 inspection.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tushardhaka-ai/hands-on-llm-lab/blob/main/hands-on-llm-lab.ipynb)

## Run it

1. Select **Open in Colab** above.
2. Choose **Runtime → Run all** for the lightweight NumPy and PyTorch sections.
3. The optional FLAN-T5 cell is disabled by default because it downloads a larger model. Set `RUN_FLAN_T5 = True` only when you want to run it.

The notebook is educational and intentionally uses small toy values so every attention calculation stays inspectable.
