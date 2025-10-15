# PrivaSector: A Large-Scale Sectoral Analysis of Privacy Policies from 2022-2025

This repository contains the **PrivaSector** dataset, a corpus of 59,590 privacy policies collected between 2022 and 2025 (https://huggingface.co/datasets/Anonymous929292/PrivaSector).

## Dataset Description

PrivaSector was created to enable the large-scale, computational analysis of how privacy disclosure practices differ across industries and evolve over time. Each policy in the corpus is labeled with one of 10 sectors of industry, allowing for quantitative comparisons of data practices.

The dataset is particularly focused on the 2022-2025 period, a time of significant global regulatory updates, making it a valuable resource for studying how organizations update their policies in response to new legislation.

### How to Use

You can load the dataset using the `datasets` library:
```python
from datasets import load_dataset

dataset = load_dataset("Anonymous929292/PrivaSector")
