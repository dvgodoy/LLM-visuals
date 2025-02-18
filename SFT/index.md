# Supervised Fine-Tuning (SFT)

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

These images were originally published in the book ["A Hands-On Guide to Fine-Tuning LLMs with PyTorch and Hugging Face"](https://pytorchstepbystep.com/llms).

They are also available at the book's official repository: [https://github.com/dvgodoy/FineTuningLLMs](https://github.com/dvgodoy/FineTuningLLMs).

## Index

- [Back](https://github.com/dvgodoy/LLM-visuals)
- [Training Loop](#training-loop)
- [Attention](#attention)
- [Memory](#memory)
- [Stochastic Rounding](#stochastic-rounding)

### **** CLICK ON THE IMAGES FOR FULL SIZE ****

## Training Loop

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/forward_pass.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/forward_pass.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/backward_pass.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/backward_pass.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/training_loop.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/training_loop.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.5.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.5.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.6.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.6.png)

## Attention

### Without LoRA

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-no_lora.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-no_lora.png)

### Quantized Optimizer

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-8bit_adam.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-8bit_adam.png)

### LoRA

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-lora.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-lora.png)

### Activations

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-lora_s.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-lora_s.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-lora_short_s.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/gpu_ram-lora_short_s.png)

### Formulas

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.10.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.10.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.11.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.11.png)

## Memory

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eager_attn.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eager_attn.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.1.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.1.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.2.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.2.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.3.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.3.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.4.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.4.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.7.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.7.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.8.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.8.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.9a.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.9a.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.9b.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/eq05.9b.png)

## Stochastic Rounding

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/stochastic_10k.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/stochastic_10k.png)

[![](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/stochastic_100k.png)](https://raw.githubusercontent.com/dvgodoy/LLM-visuals/main/Quantization/stochastic_100k.png)


This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
