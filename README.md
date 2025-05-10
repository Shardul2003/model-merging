# 🧠 Model Merging Project

This repository explores merging fine-tuned language models to evaluate task-specific performance improvements. The goal is to test whether combining representations from specialized models (e.g., medicine, toxicity) can produce a single model with enhanced multi-domain performance.

## 📁 Project Structure

- `mergeLM` – Stores initial benchmarks on math and finance base models. Our intial finetuned versions present here as well
- `weighted_MergeLM` – Contains custom merging logic and scaled task arithmetic. Also includes additional benchmarking and base model performance.
- `Model_merge_benchmark` – This incorporates the merging used and largely focuses on the several math benchmarks assessed from the lm-eval framework.
- `Custom_Model_Merge` – Focuses on the fine-tuned falcon models and merging approaches for these. Also includes several benchmarks on medical and toxicity datasets.

## 🚀 Quick Start

```bash
# Clone repo
git clone [https://github.com/yourusername/model-merging-project.git](https://github.com/Shardul2003/model-merging.git)

# Enter directory
cd model-merging

# Open files: Once in folder, type
jupyter notebook
# to launch the Jupyter Notebook server

# Note: If Jupyter Notebook is not installed, it can be done through
pip install notebook

# This will open the Jupyter Notebook server and display all files in the current directory, from where they can be accessed
