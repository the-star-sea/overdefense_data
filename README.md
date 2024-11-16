

# Processed Input Data for LLM Defense Mechanism Analysis

This repository contains processed input datasets used in the study **"Unintended Side Effects of Defense Mechanisms in Large Language Models: A Comprehensive Study"**. These datasets are designed to facilitate benchmarking and evaluation of LLM defense mechanisms across multiple dimensions such as performance, over-refusal, and inference costs.

## Repository Contents

The repository includes the following processed datasets:

- **`dirty.csv`**: Contains adversarial input prompts and their associated outcomes from various defense mechanisms.
- **`gsmeval.csv`**: Processed input data for the GSM8K dataset, focusing on mathematical reasoning tasks.
- **`ifeval.csv`**: Processed prompts and evaluation data for the IFEval dataset, emphasizing instruction-following tasks.
- **`mmlupro.csv`**: Domain-specific processed inputs from the MMLU-Pro dataset, including tasks in health, law, and mathematics.
- **`oa_eval.csv`**: Clean and safe prompts derived from the Open Assistant dataset.
- **`xstest_v2_prompts.csv`**: Crafted and processed prompts from the XSTest dataset for stress-testing LLM defenses against ambiguous or sensitive inputs.

## Purpose of the Data

The datasets are pre-processed inputs, curated for analyzing the effects of various LLM defense mechanisms, focusing on:
- Evaluating performance impact across tasks.
- Understanding over-refusal tendencies when handling safe prompts.
- Assessing computational overhead introduced by defense strategies.

These datasets aim to standardize testing across defense mechanisms and benchmark their trade-offs.




## Data Availability Statement

The datasets provided in this repository represent processed versions of publicly available benchmarks, including GSM8K, IFEval, MMLU-Pro, Open Assistant, and XSTest. The data has been processed to align with the experimental requirements of the study and is anonymized to ensure no personal or sensitive information is included.

These datasets are available for academic and research purposes under open access. If you require additional raw data or pre-processing details, please contact the authors via the corresponding publication channel.

