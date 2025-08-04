# High-Performance Machine Learning (HPML)

## Instructors

- **Dr. Kaoutar El Maghraoui**  
  *Adjunct Professor of Computer Science and Principal Research Scientist, IBM T.J. Watson Research Center, NY*

- **Dr. Parijat Dube**  
  *Adjunct Associate Professor of Computer Science and Senior Research Scientist, IBM T.J. Watson Research Center, NY*

---

## Course Description

High-Performance Computing (HPC) has long driven scientific progress by harnessing supercomputers and cutting-edge hardware (GPUs, low-latency interconnects, etc.) for solving complex, data-intensive problems.

A crucial driver of recent Machine Learning (ML) breakthroughs is scalable computation on large datasets. Applying **HPC techniques to ML algorithms** is central to Artificial Intelligence progress.

This course teaches:
- HPC techniques as applied to supercomputing software and modern ML
- Maximizing ML performance with software and hardware optimizations
- Efficient system design for large models (e.g., GPT, LLAMA)
- Training + inference efficiency: model compression, pruning, quantization, knowledge distillation, NAS, parallelism & distributed training

**Technologies:** PyTorch and CUDA.

---

## Objectives

After this course, you will be able to:

- Identify and solve performance bottlenecks in ML systems
- Perform benchmarking and profiling on ML software
- Compare and evaluate ML stacks and hardware platforms
- Build distributed, high-performance training algorithms
- Accelerate ML with CUDA, C++, and optimized math libraries
- Apply model compression: quantization, pruning, distillation
- Use essential HPC strategies for Large Language Models (LLMs)

---

## Prerequisites

- Understanding of computer architecture & operating systems
- C/C++: intermediate programming experience
- Python: intermediate programming experience
- ML fundamentals (neural networks, common algorithms)

**Strongly recommended:**
- Logistic regression
- Feed-forward/basic neural networks
- CNNs, RNNs, Transformer architectures

---

## Course Materials

- *Introduction to High-Performance Computing for Scientists and Engineers*  
  Georg Hager, Gerhard Wellein (CRC Press, ISBN: 9781439811924)
- *Introduction to High-Performance Scientific Computing* (online)  
  Victor Eijkhout with Edmond Chow, Robert van de Geijn
- *Computer Architecture: A Quantitative Approach (5th Edition)*  
  John Hennessy, David Patterson (Morgan Kaufmann, ISBN: 9780123838728)
- *Efficient Processing of Deep Neural Networks*  
  Vivienne Sze, Yu-Hsin Chen, Tien-Ju Yang, Joel Emer (Morgan & Claypool, ISBN: 978-1681738352)

Specific readings and web resources are provided in class.

---

## Topics Covered

- ML/DL & PyTorch foundations
- PyTorch performance and profiling
- Performance optimization in PyTorch
- Parallel performance modeling
- CUDA basics and advanced topics
- Math libraries for ML (cuDNN)
- Distributed ML techniques
- Distributed PyTorch, parallel data loading, ring reduction
- Hardware acceleration for ML and AI
- Quantization, pruning, compression
- Neural Architecture Search (NAS)
- In-Memory & neuromorphic computing

---

## Course Information

- **Instructors:** Dr. Kaoutar El Maghraoui & Dr. Parijat Dube
- **Grading:**
  - Homework: 40%
  - Final Project: 30%
  - Final Exam: 20%
  - Quizzes: 10%
  - Attendance & Participation: Bonus +5%
- **Homework:** Five programming assignments (C/C++, Python, PyTorch) using GPUs
- **Course Project:**
  - Proposal due by midterm
  - Final presentation at end of course

---

## Weekly Lesson Plan

| **Week**   | **Topic**                                                                             | **Details**                                                                                                |
|------------|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 1          | Introduction to HPC & ML                                                              | Course overview, HPC/ML tech, drivers for ML/DL, hardware/software intro                                   |
| 2          | ML Performance Optimization                                                           | Performance factors, measurement, profiling, Roofline model                                                |
| 3          | Gradient Descent Optimization Algorithms in PyTorch                                   | Tensors, computation graph, optimizers, multiprocessing, CUDA, data loading                                |
| 4          | PyTorch Performance                                                                  | Python internals, computation graph, JIT compilation, profiling                                            |
| 5          | CUDA Basics                                                                          | GPU architectures, CUDA programming model, runtime, driver, AoT/JIT compilation                            |
| 6          | CUDA Advanced Topics                                                                 | UVM, block/warp scheduling, streams, memory access patterns, cuDNN                                         |
| 7          | Distributed Deep Learning Algorithms and PyTorch                                      | Model/data/hybrid parallelism, DDL, PyTorch modules, All-Reduce, NCCL, efficient transformers              |
| 8          | Sparsity, Model Pruning/Compression                                                   | Activation/weight sparsity, compression, knowledge distillation                                            |
| 9          | Reduced Precision and Quantization                                                    | Bit width, mixed/varying precision, quantization techniques                                                |
| 10         | Knowledge Distillation                                                                | Distillation in CNNs, RNNs, vision transformers                                                           |
| 11         | Efficient Transformers and LLMs                                                       | Encoder/decoder, KV cache, FlashAttention, LoRA, adapters, attention sparsity                              |
| 12         | Efficient Vision Architectures and Implementations                                    | Efficient CNNs, Vision Transformers                                                                       |
| 13         | Designing Efficient DNNs with Neural Architecture Search                              | Manual and hardware-aware NAS                                                                              |
| 14         | In-Memory Computing                                                                  | Analog AI, in-memory and neuromorphic computing                                                          |
| 15-16      | Final Project Presentations                                                           | Project presentations and course wrap-up                                                                  |

---
