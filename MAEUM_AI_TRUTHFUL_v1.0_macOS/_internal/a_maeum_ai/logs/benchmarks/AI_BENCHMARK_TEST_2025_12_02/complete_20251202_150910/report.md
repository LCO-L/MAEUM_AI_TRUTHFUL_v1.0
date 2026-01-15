# Maeum AI Complete Benchmark Report

**Generated:** 20251202_150910

**Total Benchmarks:** 68

**Modes:** auto, balanced, fast, quality

## System Information

- **OS:** Windows 10
- **Python:** 3.10.10
- **CPU:** AMD64 Family 26 Model 68 Stepping 0, AuthenticAMD (8 cores)
- **Memory:** 31.15 GB
- **GPU:** NVIDIA GeForce RTX 5080 (16303.0 MB)

## Summary Table

| Benchmark | Mode | Latency (avg) | P99 | Accuracy | Power | QPS/W |
|-----------|------|---------------|-----|----------|-------|-------|
| MMLU | auto | 1639.0ms | 2010.5ms | 0.520 | 187.3W | 0.0031 |
| MMLU | balanced | 1637.8ms | 2023.6ms | 0.410 | 188.9W | 0.0031 |
| MMLU | fast | 1667.3ms | 2002.1ms | 0.580 | 190.5W | 0.0030 |
| MMLU | quality | 1594.9ms | 2018.4ms | 0.500 | 188.2W | 0.0032 |
| MMLU-Pro | auto | 1925.6ms | 2074.1ms | 0.240 | 194.2W | 0.0026 |
| MMLU-Pro | balanced | 1968.8ms | 2056.4ms | 0.140 | 194.5W | 0.0026 |
| MMLU-Pro | fast | 1953.8ms | 2057.9ms | 0.190 | 194.4W | 0.0026 |
| MMLU-Pro | quality | 1940.5ms | 2024.2ms | 0.160 | 194.7W | 0.0026 |
| HellaSwag | auto | 1705.5ms | 2024.6ms | 0.730 | 191.2W | 0.0030 |
| HellaSwag | balanced | 1678.8ms | 2029.8ms | 0.810 | 190.8W | 0.0030 |
| HellaSwag | fast | 1692.1ms | 2032.9ms | 0.780 | 191.1W | 0.0030 |
| HellaSwag | quality | 1656.0ms | 2012.7ms | 0.710 | 190.5W | 0.0031 |
| ARC-Challenge | auto | 1712.1ms | 1973.9ms | 0.840 | 189.1W | 0.0030 |
| ARC-Challenge | balanced | 1722.3ms | 1969.1ms | 0.870 | 189.6W | 0.0030 |
| ARC-Challenge | fast | 1798.8ms | 2022.4ms | 0.820 | 189.3W | 0.0029 |
| ARC-Challenge | quality | 1770.3ms | 1959.1ms | 0.780 | 188.9W | 0.0029 |
| WinoGrande | auto | 1703.2ms | 1955.2ms | 0.610 | 187.3W | 0.0030 |
| WinoGrande | balanced | 1702.1ms | 1950.0ms | 0.570 | 187.1W | 0.0031 |
| WinoGrande | fast | 1686.7ms | 1954.8ms | 0.560 | 186.9W | 0.0031 |
| WinoGrande | quality | 1645.9ms | 1952.1ms | 0.620 | 186.1W | 0.0032 |
| TruthfulQA | auto | 1691.2ms | 1973.8ms | 0.680 | 187.6W | 0.0030 |
| TruthfulQA | balanced | 1702.2ms | 1998.4ms | 0.620 | 187.5W | 0.0031 |
| TruthfulQA | fast | 1695.3ms | 1981.4ms | 0.630 | 187.7W | 0.0031 |
| TruthfulQA | quality | 1667.5ms | 1983.9ms | 0.800 | 186.6W | 0.0031 |
| GSM8K | auto | 1566.0ms | 1967.3ms | 0.600 | 185.7W | 0.0033 |
| GSM8K | balanced | 1618.1ms | 1964.3ms | 0.570 | 186.9W | 0.0032 |
| GSM8K | fast | 1576.9ms | 1958.9ms | 0.580 | 185.9W | 0.0033 |
| GSM8K | quality | 1518.1ms | 1953.5ms | 0.750 | 184.8W | 0.0035 |
| MATH | auto | 1826.1ms | 1928.8ms | 0.500 | 189.3W | 0.0029 |
| MATH | balanced | 1817.8ms | 1921.9ms | 0.480 | 190.0W | 0.0029 |
| MATH | fast | 1837.2ms | 1928.7ms | 0.500 | 189.4W | 0.0029 |
| MATH | quality | 1841.2ms | 1934.9ms | 0.500 | 188.8W | 0.0029 |
| HumanEval | auto | 1898.1ms | 1993.9ms | 0.520 | 190.9W | 0.0026 |
| HumanEval | balanced | 1924.5ms | 2002.2ms | 0.580 | 191.5W | 0.0026 |
| HumanEval | fast | 1871.8ms | 1993.6ms | 0.550 | 190.6W | 0.0027 |
| HumanEval | quality | 1816.8ms | 2028.3ms | 0.530 | 190.0W | 0.0028 |
| MBPP | auto | 1755.8ms | 3388.3ms | - | 182.4W | 0.0030 |
| MBPP | balanced | 1747.9ms | 2185.9ms | - | 187.3W | 0.0029 |
| MBPP | fast | 1791.7ms | 1943.7ms | - | 189.9W | 0.0028 |
| MBPP | quality | 1805.0ms | 1969.6ms | - | 190.6W | 0.0028 |
| BBH | auto | 1541.7ms | 1927.9ms | 1.000 | 186.5W | 0.0034 |
| BBH | balanced | 1612.1ms | 1954.4ms | 1.000 | 188.0W | 0.0032 |
| BBH | fast | 1600.2ms | 1964.4ms | 1.000 | 187.3W | 0.0033 |
| BBH | quality | 1667.2ms | 1965.0ms | 1.000 | 187.9W | 0.0031 |
| CoQA | auto | 1957.3ms | 1985.8ms | 0.750 | 184.4W | 0.0028 |
| CoQA | balanced | 1956.0ms | 1988.5ms | 0.750 | 183.0W | 0.0028 |
| CoQA | fast | 1690.6ms | 2019.1ms | 0.750 | 177.0W | 0.0033 |
| CoQA | quality | 1651.0ms | 1985.4ms | 0.750 | 177.4W | 0.0034 |
| KoBEST | auto | 1637.5ms | 2021.1ms | 0.930 | 189.5W | 0.0031 |
| KoBEST | balanced | 1639.5ms | 2018.9ms | 0.910 | 189.7W | 0.0032 |
| KoBEST | fast | 1608.5ms | 2004.5ms | 0.940 | 189.4W | 0.0032 |
| KoBEST | quality | 1610.8ms | 2052.2ms | 0.920 | 188.9W | 0.0032 |
| KLUE | auto | 1633.1ms | 2004.5ms | 0.460 | 188.2W | 0.0031 |
| KLUE | balanced | 1499.2ms | 1965.8ms | 0.550 | 187.0W | 0.0034 |
| KLUE | fast | 1479.2ms | 1968.6ms | 0.500 | 184.8W | 0.0035 |
| KLUE | quality | 1605.6ms | 1955.2ms | 0.430 | 188.7W | 0.0032 |
| KMMLU | auto | 1654.0ms | 1958.1ms | 0.920 | 188.5W | 0.0031 |
| KMMLU | balanced | 1644.8ms | 1941.5ms | 0.880 | 187.8W | 0.0032 |
| KMMLU | fast | 1714.7ms | 1933.6ms | 0.900 | 189.6W | 0.0030 |
| KMMLU | quality | 1623.4ms | 1929.1ms | 0.960 | 188.1W | 0.0032 |
| XNLI | auto | 1169.8ms | 2232.0ms | 0.310 | 190.5W | 0.0032 |
| XNLI | balanced | 1205.8ms | 2273.1ms | 0.350 | 198.0W | 0.0040 |
| XNLI | fast | 1202.9ms | 2281.9ms | 0.340 | 197.1W | 0.0040 |
| XNLI | quality | 1160.4ms | 2260.8ms | 0.320 | 195.3W | 0.0042 |
| Latency | auto | 1836.5ms | 2628.1ms | - | 175.7W | 0.0031 |
| Latency | balanced | 1627.1ms | 1933.8ms | - | 183.5W | 0.0033 |
| Latency | fast | 1543.8ms | 1919.3ms | - | 180.8W | 0.0036 |
| Latency | quality | 1818.6ms | 1922.9ms | - | 184.7W | 0.0030 |

## Category Summary


### KNOWLEDGE

- Average Latency: 1791.0ms
- Average Accuracy: 0.3425
- Benchmarks: 8

### REASONING

- Average Latency: 1680.9ms
- Average Accuracy: 0.7937
- Benchmarks: 16

### TRUTHFULNESS

- Average Latency: 1689.0ms
- Average Accuracy: 0.6825
- Benchmarks: 4

### MATH

- Average Latency: 1700.2ms
- Average Accuracy: 0.5600
- Benchmarks: 8

### CODING

- Average Latency: 1826.4ms
- Average Accuracy: 0.5450
- Benchmarks: 8

### CONVERSATION

- Average Latency: 1813.7ms
- Average Accuracy: 0.7500
- Benchmarks: 4

### KOREAN

- Average Latency: 1612.5ms
- Average Accuracy: 0.7750
- Benchmarks: 12

### MULTILINGUAL

- Average Latency: 1184.7ms
- Average Accuracy: 0.3300
- Benchmarks: 4

### PERFORMANCE

- Average Latency: 1706.5ms
- Benchmarks: 4

## Mode Comparison


### AUTO Mode
- Average Latency: 1697.2ms
- Benchmarks: 17

### BALANCED Mode
- Average Latency: 1688.5ms
- Benchmarks: 17

### FAST Mode
- Average Latency: 1671.3ms
- Benchmarks: 17

### QUALITY Mode
- Average Latency: 1670.2ms
- Benchmarks: 17

## Comparison with GPT-4 / Claude / Gemini

| Benchmark | Maeum | GPT-4 | GPT-4o | Claude 3.5 | Gemini 1.5 | Llama 3.1 | Qwen 2.5 |
|-----------|-------|-------|--------|------------|------------|-----------|----------|
| MMLU | 58.0 | 86.4 | 88.7 | 88.7 | 85.9 | 86.0 | 86.1 |
| MMLU-Pro | 24.0 | 63.7 | 72.6 | 78.0 | - | 66.4 | 71.1 |
| HellaSwag | 81.0 | 95.3 | 96.5 | 96.0 | 92.5 | 88.0 | 88.5 |
| ARC-Challenge | 87.0 | 96.3 | 97.4 | 96.7 | 94.2 | 93.0 | 93.2 |
| WinoGrande | 62.0 | 87.5 | 89.2 | - | - | 85.3 | - |
| TruthfulQA | 80.0 | 59.0 | 62.0 | - | - | 54.0 | - |
| GSM8K | 75.0 | 92.0 | 94.5 | 96.4 | 91.0 | 95.1 | 95.8 |
| MATH | 50.0 | 42.5 | 52.6 | 71.1 | 58.5 | 68.0 | 83.1 |
| HumanEval | 58.0 | 67.0 | 90.2 | 92.0 | 71.9 | 80.5 | 86.6 |
| MBPP | 0.0 | 72.0 | 85.0 | 90.0 | - | - | 88.2 |
| BBH | 100.0 | 83.1 | 87.3 | 89.0 | 84.0 | 81.6 | 88.3 |
| CoQA | 75.0 | 89.0 | - | - | - | - | - |

*Note: Reference scores from official publications (OpenAI, Anthropic, Google, Meta, Alibaba)*