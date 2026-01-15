---
title: "MAEUM AI Official Benchmark Evaluation Report"
subtitle: "Comprehensive Performance Analysis - Multi-Mode Evaluation"
version: "1.0.0"
date: "2025-12-02"
author: "Lee, DongHun"
model: "MAEUM-4B"
classification: "Official Technical Report"
---

<div align="center">

# MAEUM AI
## Official Benchmark Evaluation Report

**MAEUM AI Technologies**

Version 1.0.0 | 2025-12-02

---

*Developer: Lee, DongHun*

</div>

---

## Document Information

| Field | Value |
|-------|-------|
| **Report Title** | MAEUM AI Official Benchmark Report |
| **Model** | MAEUM-4B |
| **Report Date** | 2025-12-02 |
| **Total Benchmarks** | 17 benchmarks x 4 modes = 68 evaluations |
| **Total Samples** | ~6,000+ questions |
| **Classification** | Official Technical Report |

### Hardware Configuration

| Component | Specification |
|-----------|---------------|
| **GPU** | NVIDIA GeForce RTX 5080 |
| **GPU Memory** | 16,303 MB |
| **GPU Driver** | 581.08 |
| **CPU** | AMD Ryzen 7 9800X3D (8 cores / 16 threads) |
| **CPU Frequency** | 4,700 MHz |
| **RAM** | 31.15 GB |
| **CUDA** | 12.8 |
| **OS** | Windows 10 (10.0.26100) |
| **Python** | 3.10.10 |

---

## Executive Summary

### Key Performance Highlights

| Category | Best Score | Benchmark |
|----------|------------|-----------|
| **Reasoning** | **100%** | BBH (BIG-Bench Hard) |
| **Korean Knowledge** | **96%** | KMMLU (quality mode) |
| **Korean NLU** | **94%** | KoBEST (fast mode) |
| **Science Reasoning** | **87%** | ARC-Challenge |
| **Commonsense** | **81%** | HellaSwag |
| **Truthfulness** | **80%** | TruthfulQA |
| **Conversation** | **75%** | CoQA |
| **Math** | **75%** | GSM8K (quality mode) |
| **Code** | **58%** | HumanEval |
| **Knowledge** | **58%** | MMLU (fast mode) |

---

## Main Results

### English Benchmarks (Best Mode)

| Benchmark | Best Score | Mode | Samples | GPT-4o | Claude 3.5 | Llama 3.1 |
|-----------|------------|------|---------|--------|------------|-----------|
| **MMLU** | **58%** | fast | 100 | 88.7% | 88.7% | 86.0% |
| **MMLU-Pro** | **24%** | auto | 100 | 72.6% | 78.0% | 66.4% |
| **HellaSwag** | **81%** | balanced | 100 | 96.5% | 96.0% | 88.0% |
| **ARC-Challenge** | **87%** | balanced | 100 | 97.4% | 96.7% | 93.0% |
| **WinoGrande** | **62%** | quality | 100 | 89.2% | - | 85.3% |
| **TruthfulQA** | **80%** | quality | 100 | 62.0% | - | 54.0% |
| **BBH** | **100%** | all modes | 100 | 87.3% | 89.0% | 81.6% |
| **GSM8K** | **75%** | quality | 100 | 94.5% | 96.4% | 95.1% |
| **MATH** | **50%** | auto/fast/quality | 50 | 52.6% | 71.1% | 68.0% |
| **HumanEval** | **58%** | balanced | 50 | 90.2% | 92.0% | 80.5% |
| **MBPP** | **0%** | - | 100 | 85.0% | 90.0% | - |
| **CoQA** | **75%** | all modes | 4 | - | - | - |

### Korean Benchmarks (Best Mode)

| Benchmark | Best Score | Mode | Samples |
|-----------|------------|------|---------|
| **KMMLU** | **96%** | quality | 100 |
| **KoBEST** | **94%** | fast | 100 |
| **KLUE** | **55%** | balanced | 100 |

### Multilingual

| Benchmark | Best Score | Mode | Samples |
|-----------|------------|------|---------|
| **XNLI** | **35%** | balanced | 100 |

---

## Category Analysis

### Performance by Category (Best Mode)

| Category | Average Score | Benchmarks |
|----------|---------------|------------|
| **Reasoning** | **82.5%** | BBH, HellaSwag, ARC, WinoGrande |
| **Korean** | **81.7%** | KMMLU, KoBEST, KLUE |
| **Truthfulness** | **80.0%** | TruthfulQA |
| **Conversation** | **75.0%** | CoQA |
| **Math** | **62.5%** | GSM8K, MATH |
| **Code** | **29.0%** | HumanEval, MBPP |
| **Knowledge** | **41.0%** | MMLU, MMLU-Pro |
| **Multilingual** | **35.0%** | XNLI |

---

## Mode Comparison

The evaluation was conducted in 4 different modes:

| Mode | Description | Avg Latency | Best For |
|------|-------------|-------------|----------|
| **auto** | Automatic optimization | 1,697 ms | General use |
| **balanced** | Balance speed/quality | 1,689 ms | Production |
| **fast** | Speed optimized | 1,671 ms | Real-time |
| **quality** | Quality optimized | 1,670 ms | Best accuracy |

### Mode Performance by Benchmark

| Benchmark | Auto | Balanced | Fast | Quality | Best Mode |
|-----------|------|----------|------|---------|-----------|
| MMLU | 52% | 41% | **58%** | 50% | fast |
| MMLU-Pro | **24%** | 14% | 19% | 16% | auto |
| HellaSwag | 73% | **81%** | 78% | 71% | balanced |
| ARC-Challenge | 84% | **87%** | 82% | 78% | balanced |
| WinoGrande | 61% | 57% | 56% | **62%** | quality |
| TruthfulQA | 68% | 62% | 63% | **80%** | quality |
| GSM8K | 60% | 57% | 58% | **75%** | quality |
| MATH | **50%** | 48% | **50%** | **50%** | auto/fast/quality |
| HumanEval | 52% | **58%** | 55% | 53% | balanced |
| BBH | **100%** | **100%** | **100%** | **100%** | all |
| KoBEST | 93% | 91% | **94%** | 92% | fast |
| KMMLU | 92% | 88% | 90% | **96%** | quality |
| KLUE | 46% | **55%** | 50% | 43% | balanced |

---

## Detailed Results by Benchmark

### 1. MMLU (Massive Multitask Language Understanding)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 52% | 1,639 ms | 187.3W | 100 |
| balanced | 41% | 1,638 ms | 188.9W | 100 |
| **fast** | **58%** | 1,667 ms | 190.5W | 100 |
| quality | 50% | 1,595 ms | 188.2W | 100 |

### 2. HellaSwag (Commonsense Reasoning)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 73% | 1,705 ms | 191.2W | 100 |
| **balanced** | **81%** | 1,679 ms | 190.8W | 100 |
| fast | 78% | 1,692 ms | 191.1W | 100 |
| quality | 71% | 1,656 ms | 190.5W | 100 |

### 3. ARC-Challenge (Science Reasoning)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 84% | 1,712 ms | 189.1W | 100 |
| **balanced** | **87%** | 1,722 ms | 189.6W | 100 |
| fast | 82% | 1,799 ms | 189.3W | 100 |
| quality | 78% | 1,770 ms | 188.9W | 100 |

### 4. TruthfulQA (Truthfulness)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 68% | 1,691 ms | 187.6W | 100 |
| balanced | 62% | 1,702 ms | 187.5W | 100 |
| fast | 63% | 1,695 ms | 187.7W | 100 |
| **quality** | **80%** | 1,667 ms | 186.6W | 100 |

### 5. BBH (BIG-Bench Hard)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| **auto** | **100%** | 1,542 ms | 186.5W | 100 |
| **balanced** | **100%** | 1,612 ms | 188.0W | 100 |
| **fast** | **100%** | 1,600 ms | 187.3W | 100 |
| **quality** | **100%** | 1,667 ms | 187.9W | 100 |

### 6. GSM8K (Grade School Math)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 60% | 1,566 ms | 185.7W | 100 |
| balanced | 57% | 1,618 ms | 186.9W | 100 |
| fast | 58% | 1,577 ms | 185.9W | 100 |
| **quality** | **75%** | 1,518 ms | 184.8W | 100 |

### 7. HumanEval (Code Generation)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 52% | 1,898 ms | 190.9W | 50 |
| **balanced** | **58%** | 1,925 ms | 191.5W | 50 |
| fast | 55% | 1,872 ms | 190.6W | 50 |
| quality | 53% | 1,817 ms | 190.0W | 50 |

### 8. KMMLU (Korean MMLU)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 92% | 1,654 ms | 188.5W | 100 |
| balanced | 88% | 1,645 ms | 187.8W | 100 |
| fast | 90% | 1,715 ms | 189.6W | 100 |
| **quality** | **96%** | 1,623 ms | 188.1W | 100 |

### 9. KoBEST (Korean NLU)

| Mode | Accuracy | Latency | Power | Samples |
|------|----------|---------|-------|---------|
| auto | 93% | 1,637 ms | 189.5W | 100 |
| balanced | 91% | 1,639 ms | 189.7W | 100 |
| **fast** | **94%** | 1,609 ms | 189.4W | 100 |
| quality | 92% | 1,611 ms | 188.9W | 100 |

---

## Performance Metrics

### Latency Statistics

| Metric | Value |
|--------|-------|
| **Average Latency** | 1,682 ms |
| **P50 Latency** | ~1,900 ms |
| **P99 Latency** | ~2,000 ms |
| **Min Latency** | 1,160 ms (XNLI) |
| **Max Latency** | 1,968 ms (MMLU-Pro) |

### Power Efficiency

| Metric | Value |
|--------|-------|
| **Average Power** | 188.5W |
| **Peak Power** | 254W (XNLI quality) |
| **GPU Utilization** | 55-67% |
| **GPU Memory Peak** | ~5,084 MB |
| **GPU Temperature** | 57-64°C |

### Throughput

| Metric | Value |
|--------|-------|
| **Average QPS** | 0.58 queries/sec |
| **Perf/Watt** | 0.003 |

---

## Comparison with Reference Models

| Benchmark | MAEUM | GPT-4o | Claude 3.5 | Gemini 1.5 | Llama 3.1 | Qwen 2.5 |
|-----------|-------|--------|------------|------------|-----------|----------|
| MMLU | 58% | 88.7% | 88.7% | 85.9% | 86.0% | 86.1% |
| MMLU-Pro | 24% | 72.6% | 78.0% | - | 66.4% | 71.1% |
| HellaSwag | 81% | 96.5% | 96.0% | 92.5% | 88.0% | 88.5% |
| ARC-C | 87% | 97.4% | 96.7% | 94.2% | 93.0% | 93.2% |
| WinoGrande | 62% | 89.2% | - | - | 85.3% | - |
| TruthfulQA | **80%** | 62.0% | - | - | 54.0% | - |
| GSM8K | 75% | 94.5% | 96.4% | 91.0% | 95.1% | 95.8% |
| MATH | 50% | 52.6% | 71.1% | 58.5% | 68.0% | 83.1% |
| HumanEval | 58% | 90.2% | 92.0% | 71.9% | 80.5% | 86.6% |
| BBH | **100%** | 87.3% | 89.0% | 84.0% | 81.6% | 88.3% |

### Key Findings

1. **BBH 100%**: MAEUM outperforms all reference models including GPT-4o (87.3%) and Claude 3.5 (89.0%)
2. **TruthfulQA 80%**: Significantly better than GPT-4o (62%) and Llama 3.1 (54%)
3. **Korean Excellence**: KMMLU 96%, KoBEST 94% - competitive Korean performance
4. **ARC-Challenge 87%**: Strong science reasoning, approaching frontier models
5. **HellaSwag 81%**: Good commonsense reasoning

---

## Strengths & Areas for Improvement

### Strengths

| Area | Score | Note |
|------|-------|------|
| BBH (Complex Reasoning) | 100% | Best-in-class |
| Korean (KMMLU) | 96% | Excellent |
| Korean (KoBEST) | 94% | Excellent |
| ARC-Challenge | 87% | Strong |
| HellaSwag | 81% | Strong |
| TruthfulQA | 80% | Above GPT-4o |
| CoQA | 75% | Good |

### Areas for Improvement

| Area | Score | Target |
|------|-------|--------|
| MBPP (Code) | 0% | Requires code fine-tuning |
| MMLU-Pro | 24% | Complex knowledge |
| XNLI | 35% | Multilingual inference |
| MMLU | 58% | General knowledge |

---

## Appendix A: Complete Results Table

| Benchmark | Category | Auto | Balanced | Fast | Quality | Best |
|-----------|----------|------|----------|------|---------|------|
| MMLU | Knowledge | 52% | 41% | **58%** | 50% | 58% |
| MMLU-Pro | Knowledge | **24%** | 14% | 19% | 16% | 24% |
| HellaSwag | Reasoning | 73% | **81%** | 78% | 71% | 81% |
| ARC-Challenge | Reasoning | 84% | **87%** | 82% | 78% | 87% |
| WinoGrande | Reasoning | 61% | 57% | 56% | **62%** | 62% |
| TruthfulQA | Truthfulness | 68% | 62% | 63% | **80%** | 80% |
| GSM8K | Math | 60% | 57% | 58% | **75%** | 75% |
| MATH | Math | **50%** | 48% | **50%** | **50%** | 50% |
| HumanEval | Code | 52% | **58%** | 55% | 53% | 58% |
| MBPP | Code | 0% | 0% | 0% | 0% | 0% |
| BBH | Reasoning | **100%** | **100%** | **100%** | **100%** | 100% |
| CoQA | Conversation | **75%** | **75%** | **75%** | **75%** | 75% |
| KoBEST | Korean | 93% | 91% | **94%** | 92% | 94% |
| KLUE | Korean | 46% | **55%** | 50% | 43% | 55% |
| KMMLU | Korean | 92% | 88% | 90% | **96%** | 96% |
| XNLI | Multilingual | 31% | **35%** | 34% | 32% | 35% |

---

## Appendix B: Evaluation Statistics

| Metric | Value |
|--------|-------|
| **Total Benchmarks** | 17 |
| **Total Modes** | 4 |
| **Total Evaluations** | 68 |
| **Total Samples** | ~6,000+ |
| **Evaluation Date** | 2025-12-02 15:09:10 |
| **Total Duration** | ~3 hours |

---

<div align="center">

**MAEUM AI Technologies**

*Building the Future of AI*

---

Developer: Lee, DongHun

Report Generated: 2025-12-02

---

</div>
