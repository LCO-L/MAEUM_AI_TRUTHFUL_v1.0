# Maeum AI Benchmark Report

이 리포트는 Maeum AI LLM에 대해 수행된 벤치마크 실행(JSONL 로그)을 요약한 것입니다.

## System Overview

- **System**: Windows 10
- **Python**: 3.10.10
- **CPU**: AMD64 Family 26 Model 68 Stepping 0, AuthenticAMD (8 cores)
- **Memory**: 31.15 GB
- **Model**: MAEUM-3-4B-IT ()

## Benchmark Summary

| Suite | Benchmark | Runs | Avg Latency (ms) | P90 Latency (ms) | Throughput (qps) | Power Avg (W) | Power Max (W) | Accuracy |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| top8 | simple_latency | 3 | 12009.3 | 15048.0 | 0.20 | 0.0 | 0.0 | 0.000 |
| top8 | perplexity_long | 3 | 4961.4 | 9080.4 | 0.20 | 0.0 | 0.0 | 0.000 |
| top8 | coqa_simple | 3 | 6070.4 | 9095.6 | 0.17 | 0.0 | 0.0 | 1.000 |
| top8 | klue_mini | 3 | 5671.9 | 9098.5 | 0.18 | 0.0 | 0.0 | 0.500 |
| mlperf_tiny | mlperf_tiny | 3 | 2636.9 | 3038.4 | 0.04 | 0.0 | 0.0 | 0.000 |
| aix | aix | 3 | 2641.1 | 3032.5 | 0.04 | 0.0 | 0.0 | 0.000 |
| korean_core | kobest | 3 | 2639.7 | 3024.5 | 0.04 | 0.0 | 0.0 | 0.000 |
| korean_core | klue_full | 3 | 2660.4 | 3048.2 | 0.04 | 0.0 | 0.0 | 0.000 |
| korean_core | kmmlu | 3 | 2645.9 | 3048.4 | 0.04 | 0.0 | 0.0 | 0.000 |
| safety | k_safety | 3 | 2663.4 | 3041.5 | 0.04 | 0.0 | 0.0 | 0.000 |
| emotion | k_emotion | 3 | 2638.2 | 3018.6 | 0.04 | 0.0 | 0.0 | 0.000 |
| leaderboard | ko_llm_leaderboard | 3 | 2634.9 | 3031.8 | 0.04 | 0.0 | 0.0 | 0.000 |
| multilingual | xtreme | 3 | 2633.5 | 3023.4 | 0.04 | 0.0 | 0.0 | 0.000 |
| multilingual | xnli | 3 | 2644.3 | 3031.1 | 0.04 | 0.0 | 0.0 | 0.000 |
| dialog_ux | dstc | 3 | 2652.5 | 3028.5 | 0.04 | 0.0 | 0.0 | 0.000 |
| robustness | robustness | 3 | 2641.1 | 3039.0 | 0.04 | 0.0 | 0.0 | 0.000 |
| b2g | custom_b2g | 3 | 2645.7 | 3042.2 | 0.04 | 0.0 | 0.0 | 0.000 |

## Executive Summary

- **Latency/Throughput**: 위 표의 평균 지연시간과 QPS를 기준으로, Maeum AI의 저지연·고처리량 특성을 설명할 수 있습니다.
- **Power Efficiency**: GPU 전력 평균/최대치를 통해, RTX 5080 환경에서의 전력 대비 성능을 정량화할 수 있습니다.
- **Accuracy/Task Performance**: Accuracy/F1/Score 필드는 각 벤치마크별 태스크 성능을 반영하며, Quantization/Compression 이후의 정확도 유지 정도를 비교하는 데 활용할 수 있습니다.