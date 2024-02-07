---
title: LLMs Compression | Literature Overview | Our work
date: "2024-01-25"
draft: false
tags: ['Papers', 'State-of-The-Art', 'LLMs']
categories: ['research']
---

__*TL;DR*__ I'm currently working on a research project on LLMs Compression. Making these models smaller and more efficient. This includes techniques like Pruning, Quantization, and Distillation. The paper will be published mid-2024.

During our research, we gathered over 150 research papers related to state-of-the-art LLMs Compression methods and Optimization. I think this collection is pretty valuable. So here's this massive pile of research for you.

## Our work
In our research, we address the challenging task of compressing large language models (LLMs) using advanced compression techniques. The essence of our study is to demonstrate the practicality and real-world applicability of this challenge. While existing literature suggests remarkable success in LLM compression, our study is grounded in real-world applications, seeking to determine the true value of these methods in practical settings.

Memory usage is a critical issue in LLMs. When a model requires more memory, it leads to increased data movement. This, in turn, results in higher energy consumption. The more a system has to access memory, the more energy it uses. Therefore, reducing the memory footprint of LLMs is not just about saving space; it's also about energy efficiency and faster processing.

The core contributions of our study are:

#### Innovative Combinations
 We have innovatively combined state-of-the-art compression techniques in a way that, as far as we know, hasn't been attempted before.

#### Practical Measures
 We have evaluated our models in the context of real-world applicability. Beyond theoretical measures such as perplexity, we use LLM-Kick, a practical application for LLMs, to measure performance in a real production environment.

Our focus isn't just on theoretical advancements but on the tangible impact of compression in deployment and development. Through this approach, we aim to provide a straightforward analysis of LLM compression, cutting through the hype to reveal its true value in everyday use.

### Techniques:
#### Quantization
- Quantization reduces the number of bits required to represent each weight in the model, thus decreasing its overall size.
#### Knowledge Distillation
- Knowledge Distillation effectively condensing the knowledge by training a smaller model (student) to replicate the performance of a larger one (teacher).
#### Pruning
- Pruning involves removing less important parts of the model to  
make it more efficient without significant loss in performance.

---

Right now, the collection is organized as a Notion webpage that I've made accessible. I'm still considering other platforms like Zotero or GitHub to host this library, but I haven't settled on one yet. If you have any suggestions or preferences, *let me know*. Update, I will do a HF-Collection.

#### Hugging-Face Collection (in progress)
> https://huggingface.co/collections/TheRealM4rtin/llms-compression-65c368e270ee73487f38b45d
#### Notion Collection
> https://therealmartin.notion.site/LLM-Compression-A-state-of-the-art-6a920ba022c54f0ab4e47b0654e7b738?pvs=4

Note that if you see a green check emoji ✅ next to a paper on the Notion page, it means there's a brief report available for that paper right there on the page.

---
## Some themes covered 
| |
| ---- | ---- |
| Quantization | Pruning |
| Distillation | Low-Rank Factorization |
| Compression | Finetuning |
| Hyperparameters | Encoding |
| Prompt | Benchmarks |
| Open Source Models | Agents |
| Memory |

