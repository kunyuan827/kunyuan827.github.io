---
title: ""
permalink: "/llmopt2026/"
layout: page
---

## Lectures 2026: Optimization for Large Language Models

Instructor: **Kun Yuan** (kunyuan@pku.edu.cn) <br>

This is a 10-hour intensive course on Optimization for Large Language Models. I would like to express my sincere gratitude to the [Operations Research Society of China](https://www.orsc.org.cn/article/detail?id=1007) for the invitation and excellent organization.

Classroom: To be announced

Time: To be annouced

## References
Martin Jaggi and Nicolas Flammarion, *[Optimization for Machine Learning](https://github.com/epfml/OptML_course)*, EPFL Class CS-439 <br>
Chris De Sa, *[Advanced Machine Learning Systems](https://www.cs.cornell.edu/courses/cs6787/2021fa/)*, Cornell CS6787 <br>
Zaiwen Wen, *[Optimization Methods](http://faculty.bicmr.pku.edu.cn/~wenzw/opt-2024-fall.html)*, PKU 2024 Fall<br>
Kun Yuan, *[Introduction to LLM](https://kunyuan827.github.io/llm2025/)*, PKU 2025 Spring


## Materials

### Lecture 1: Gradient Descent <br>
- Introduction; Gradient Descent; Forward-Backward Splitting [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/Intro1.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/LLM2025/03_GD.pdf) [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/LLM2025/notes_2.pdf)

### Lecture 2: Stochastic Gradient Descent <br>
- SGD; Momentum SGD; Adaptive SGD [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/06_SGD.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/11_Adaptive_SGD.pdf) 

### Lecture 3: LLM Foundations - Part I
- Word embedding; Language Models; RNN; Seq2Seq [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/02_MLBasics.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/03_langmodel.pdf)

### Lecture 4: LLM Foundations - Part II
- Attention; Transformers [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/04_transformer.pdf)

### Lecture 5: Costs in LLM Pre-Training
- Parameters, Computations, and Memory Costs [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/04_Parameter_analysis.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/12_memory_analysis.pdf)

### Lecture 6: Perturbed SGD and Mixed-Precision Training
- Perturbed SGD; Mixed-Precision Training [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/13_mixed.pdf)

### Lecture 7: Coordinate Descent and Layer-wise Training
- Coordinate Descent; Layer-wise Training; LISA; BAdam; MISA [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/14_CD.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/15_LISA.pdf)

### Lecture 8: Subspace Optimization and Low-Rank Training
- Subspace Optimization; Low-rank gradient projection

### Lecture 9: Zeroth-order Optimization and Activation-Free LLM Training
- Zeros-Order Optimization; MeZO; LoZO [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/ZO_GD.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/2025_LOZO.pdf)

### Lecture 10: Distributed Optimization for LLM Training
- Distributed SGD; Decentralized SGD; Local SGD; Communication Compression [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/19_Parallesm.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/20_Decentralized.pdf) [[Slides03]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/21_Local_Compressed.pdf)

<!-- 
- Warm up: Preliminary [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch0.pdf) <br>
- Part   I: Introduction to Deep Learning [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/Intro1.pdf) <br> 
- Part  II: Introduction to LLM [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/Intro2.pdf)

### Lecture 2: Basics in Machine Learning and Langugae Models <br>
- Part   I: Basics in Machine Learning [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/02_MLBasics.pdf) <br>
- Part  II: Basics in Language models [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/03_langmodel.pdf)

### Lecture 3: Transformer <br>
- Part I: Seq2Seq; Attention; Transformer [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/04_transformer.pdf)
- Part II: Parameters, Computations, and Memory Costs in Transformer [[Slides01]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/04_Parameter_analysis.pdf) [[Slides02]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/12_memory_analysis.pdf)

### Lecture 4: Some LLM Models <br>
- Teacher forcing; Pretrain and Finetuning; BERT; GPTs [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/LLM2025/11_Bert_and_GPT.pdf)
- DeepSeek [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/19_Parallesm.pdf)

### Lecture 5: Gradient Descent <br>
- Convex set; Convex functions; Convex problems; Gradient descent [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/LLM2025/03_GD.pdf) [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/LLM2025/notes_1.pdf)
- Forward-backward propagation [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/LLM2025/notes_2.pdf)

### Lecture 6: Accelerated Gradient Descent <br>
- Momentum gradient descent; Nesterov acceleration; Anderson acceleration [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/08_ACC_GD.pdf) [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch3.pdf) <br>

### Lecture 7: Stochastic Gradient Descent <br>
- Stochastic gradient descent [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/06_SGD.pdf) [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/Notes_SGD.pdf)  <br>
- Sampling in SGD [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/07_SGD_sampling.pdf)
- Stability in SGD [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/09_SGD_stability.pdf)

### Lecture 8: Momentum and Adaptive SGD <br>
- Momentum SGD [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/10_ACC_SGD.pdf) [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch8_1.pdf) <br>
- AdaGrad; RMSProp; Adam [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/11_Adaptive_SGD.pdf) 

### Lecture 9: Midterm <br>

### Lecture 10: FlashAttention <br>
- Memory access cost; Kernal fusion; Flash attention [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/22_FlashAttention.pdf)

### Lecture 11: Block Coordinate Descent <br>
- Block coordinate descent; Coordinate friendly structure [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/14_CD.pdf)
- Block-wise training in LLMs [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/15_LISA.pdf)

### Lecture 12: Zeroth-Order Optimization <br>
- Finite difference; linear interpolation; sphere smoothing [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/ZO_GD.pdf) [[Notes]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/Notes_ZO.pdf)
- Memory-efficient zeroth-order optimization; Low-rank zeroth-order optimization [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/2025_LOZO.pdf)

### Lecture 13: Distributed Optimization <br>
- Data Parallelism; Pipeline Parallelism; Tensor Parallelism [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/19_Parallesm.pdf)
- Decentralized Learning [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/20_Decentralized.pdf)
- Communication Compression; Local Learning [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/21_Local_Compressed.pdf)

### Lecture 14: Mixed-Precision Training <br>
- FP16; FP32; Mixed-Precision [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/13_mixed.pdf)
- FP8; NVFP4 [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/mixed_precision_training_FP8.pdf)

### Lecture 15: Advanced Optimizers <br>
- Memory-efficient Optimizers [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/GoLore+RSO_compressed.pdf)
- Adafactor; Adam-mini; Shampoo; SOAP; Muon  [[Slides]](https://kunyuan827.github.io/teaching/DLOpt2025/AdvancedOpt.pdf)

### Lecture 16: Efficient Fine-tuning and Inference <br>
- Motivation; Adapter; LoRA; DoRA; LISA [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/23_fine_tune.pdf)
- KV Cache; Streaming LLM; Quest; vLLM [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2024/24_efficient_inference.pdf)

### Lecture 17: Efficient Attention <br>
- Mixture of Block Attention (MOBA); Natively Trainable Sparse Attention (NSA); Kernelized Attention; Linear Attention [[Slides]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/teaching/DLOpt2025/EfficientAttn.pdf)
-->
