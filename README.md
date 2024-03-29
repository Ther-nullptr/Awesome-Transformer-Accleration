## Software Algorithms -- Quantization

### ViT

* :star:[Post-Training Quantization for Vision Transformer](https://arxiv.org/abs/2106.14156) - *PKU & Huawei Noah’s Ark Lab*, `NIPS 2021`

* :star:[PTQ4ViT: Post-Training Quantization Framework for Vision Transformers](https://arxiv.org/pdf/2111.12293v2) - *Houmo AI & PKU*, `ECCV 2021`

* :star:[FQ-ViT: Post-Training Quantization for Fully Quantized Vision Transformer](https://arxiv.org/pdf/2111.13824) - *MEGVII Technology*, `IJCAI 2022`

* [Q-ViT: Fully Differentiable Quantization for Vision Transformer](https://arxiv.org/pdf/2201.07703) - *Megvii Technology & CASIA*, `arxiv 2022`

* [TerViT: An Efficient Ternary Vision Transformer](https://arxiv.org/pdf/2201.08050v2) - *Beihang University & Shanghai Artificial Intelligence Laboratory*, `arxiv 2022`

* [Patch Similarity Aware Data-Free Quantization for Vision Transformers](https://arxiv.org/abs/2203.02250) - *CASIA*, `ECCV 2022`

* [PSAQ-ViT V2: Towards Accurate and General Data-Free Quantization for Vision Transformers](https://arxiv.org/abs/2209.05687) - *CASIA*, `arxiv 2022`

* [NoisyQuant: Noisy Bias-Enhanced Post-Training Activation Quantization for Vision Transformers](https://arxiv.org/abs/2211.16056) - *NJU & UCB & PKU*, `arxiv 2022`

### BERT

* [Q8BERT: Quantized 8Bit BERT](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9463531) - *Intel AI Lab*, `NIPS Workshop 2019`

* [Ternarybert: Distillation-aware ultra-low bit bert](https://arxiv.org/pdf/2009.12812.pdf) - *Huawei Noah’s Ark Lab*, `EMNLP 2020`

* :star:[I-BERT: Integer-only BERT Quantization](https://arxiv.org/pdf/2101.01321v3.pdf) - *University of California, Berkeley*, `ICML 2021`

* :star:[Understanding and Overcoming the Challenges of Efficient Transformer Quantization](https://aclanthology.org/2021.emnlp-main.627) - *Qualcomm AI Research*, `EMNLP 2021`

* [Optimal Clipping and Magnitude-aware Differentiation for Improved Quantization-aware Training](https://arxiv.org/abs/2206.06501) - *NVIDIA*, `ICML 2022`

* [ZeroQuant: Efficient and Affordable Post-Training Quantization for Large-Scale Transformers](https://arxiv.org/pdf/2206.01861.pdf) - *Microsoft*, `arxiv 2022`

* [Outlier Suppression: Pushing the Limit of Low-bit Transformer](https://arxiv.org/abs/2209.13325) - *BUAA & SenseTime & PKU & UESTC*, `NIPS 2022`

### GPT

* [Compression of Generative Pre-trained Language Models via Quantization](https://arxiv.org/pdf/2203.10705.pdf) - *The University of Hong Kong & Huawei Noah’s Ark Lab*, `ACL 2022`

* [NUQMM: QUANTIZED MATMUL FOR EFFICIENT INFERENCE OF LARGE-SCALE GENERATIVE LANGUAGE MODELS](https://arxiv.org/pdf/2206.09557.pdf) - *Pohang University of Science and Technology*, `arxiv 2022`

* :star:[LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/abs/2208.07339) - *University of Washington & FAIR*, `NIPS 2022`
  
* :star:[SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models](http://arxiv.org/abs/2211.10438) - *MIT*, `arxiv 2022`

* [GPTQ: ACCURATE POST-TRAINING QUANTIZATION FOR GENERATIVE PRE-TRAINED TRANSFORMERS](https://arxiv.org/pdf/2210.17323.pdf) - *IST Austria & ETH Zurich*,  `arxiv 2022`

* [The case for 4-bit precision: k-bit Inference Scaling Laws](https://arxiv.org/pdf/2212.09720.pdf) - *University of Washington*, `arxiv 2022`

* [Quadapter: Adapter for GPT-2 Quantization](https://arxiv.org/pdf/2211.16912.pdf) - *Qualcomm AI Research*,  `arxiv 2022`

* [A Comprehensive Study on Post-Training Quantization for Large Language Models](https://arxiv.org/abs/2303.08302) - *Microsoft*, `arxiv 2023`

* [RPTQ: Reorder-based Post-training Quantization for Large Language Models](https://arxiv.org/abs/2304.01089) - *Houmo AI*, `arxiv 2023`

* [Outlier Suppression+: Accurate quantization of large language models by equivalent and optimal shifting and scaling](https://arxiv.org/abs/2304.09145) - *BUAA & SenseTime & PKU & UESTC*, `arxiv 2023`

* :star:[QLORA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314) - *University of Washington*, `arxiv 2023`

* [AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://arxiv.org/abs/2306.00978) - *MIT*, `arxiv 2023`

* [Scissorhands: Exploiting the Persistence of Importance Hypothesis for LLM KV Cache Compression at Test Time](https://arxiv.org/abs/2305.17118) - *Rice University*, `arxiv 2023`

## Software Algorithms -- Pruning

* [A Fast Post-Training Pruning Framework for Transformers](https://arxiv.org/pdf/2204.09656.pdf) - *UC Berkeley*, `arxiv 2022`

* [SPARSEGPT: MASSIVE LANGUAGE MODELS CAN BE ACCURATELY PRUNED IN ONE-SHOT](https://arxiv.org/pdf/2301.00774.pdf) - *IST Austria*, `arxiv 2023`

* [WHAT MATTERS IN THE STRUCTURED PRUNING OF GENERATIVE LANGUAGE MODELS?](http://arxiv.org/abs/2302.03773) - *CMU & Microsoft*, `arxiv 2023`

* [ZipLM: Hardware-Aware Structured Pruning of Language Models](https://arxiv.org/pdf/2302.04089.pdf) - *IST Austria*, `arxiv 2023`

## System Implementations -- Machine Learning System

* [DeepSpeed Inference: Enabling Efficient Inference of Transformer Models at Unprecedented Scale](https://arxiv.org/pdf/2207.00032.pdf) - *Microsoft*, `arxiv 2022`

* [PETALS: Collaborative Inference and Fine-tuning of Large Models](http://arxiv.org/abs/2209.01188) - *Yandex*, `arxiv 2022`

* [EFFICIENTLY SCALING TRANSFORMER INFERENCE](https://arxiv.org/pdf/2211.05102.pdf) - *Google*, `arxiv 2022`

* :star:[High-throughput Generative Inference of Large Language Models with a Single GPU](https://github.com/FMInference/FlexGen/blob/main/docs/paper.pdf) - *Stanford etc.*, `arxiv 2023`

* [Accelerating Large Language Model Decoding with Speculative Sampling](https://arxiv.org/pdf/2302.01318.pdf) - *Deep Mind*, `arxiv 2023`

* :star:[SpecInfer: Accelerating Generative LLM Serving with Speculative Inference and Token Tree Verification](https://arxiv.org/abs/2305.09781) - *CMU & UCSD*, `arxiv 2023`

* [vLLM: Easy, Fast, and Cheap LLM Serving with PagedAttention](https://vllm.ai/) - *UCB*

## Hardware Implementations -- Acclerators

* [A3: Accelerating Attention Mechanisms in Neural Networks with Approximation](https://ieeexplore.ieee.org/abstract/document/9065498/) - *Seoul National University & Hynix*, `HPCA 2020`

* [ELSA: Hardware-Software Co-design for Efficient, Lightweight Self-Attention Mechanism in Neural Networks](https://ieeexplore.ieee.org/document/9499860/) - *Seoul National University*, `ISCA 2021`

* [Accelerating Framework of Transformer by Hardware Design and Model Compression Co-Optimization](https://ieeexplore.ieee.org/abstract/document/9643586) - *ECNU*, `ICCAD 2022`

* [Accelerating attention through gradient-based learned runtime pruning](https://dl.acm.org/doi/abs/10.1145/3470496.3527423) - *UCSD & Google*, `ISCA 2022`

## Hardware Implementations -- Datatype

* [Hybrid 8-bit Floating Point (HFP8) Training and Inference for Deep Neural Networks](https://proceedings.neurips.cc/paper/2019/hash/65fc9fb4897a89789352e211ca2d398f-Abstract.html) - *IBM*, `NIPS 2019`

* [FP8 Quantization: The Power of the Exponent](https://arxiv.org/abs/2208.09225) - *Qualcomm AI Research*, `arxiv 2022`

* [FP8 Formats for Deep Learning](http://arxiv.org/abs/2209.05433) - *NVIDIA & ARM & Intel*, `arxiv 2022`

updating ...
