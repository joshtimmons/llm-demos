# Differences between models.

These notebooks accompany the 10/27 presentation on the differences between models.

## 01 - number of parameters.ipynb

Our first demo is to use the same generative prompt against different sizes of the same model. We're using gpt2, an older model, because it is possible to get smaller models with fewer parameters.

### GPT2 (direct ancestor of GPT3, GPT4, and ChatGPT)
* small: 124M parameters
* medium: 355M parameters
* large: 774M parameters
* xl: 1.5M parameters

### OpenLlama 2
* 3B (3 billion parameters)

## 02 - context size.ipynb
Context size is the number of tokens that a model can process at once. Small context sizes means that we can't provide too much information in our prompt and that we won't get a large amount of coherent output.

This notebook starts with OpenLlama 2 7B, which has a 2K token context size. We'll generate a small number of tokens in our first pass then increase that on OpenLlama-2-7B and MPT-7B-Storywriter models.

