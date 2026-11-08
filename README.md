# DNN Programming Assignment 2 - Submission

**Student ID:** 2026aj05305  
**Variant:** Odd ID variant -> LSTM forget-gate bias initialized to 0 vs 1 at T = 200.

## Environment & Setup
- Python Version: 3.10+
- PyTorch Version: 2.1.0
- GPU: Google Colab T4 GPU
- Key Packages: `torch`, `numpy`, `pandas`, `matplotlib`, `scikit-learn`

To install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run Notebooks
1. **Problem 1 (`problem1/problem1.ipynb`):**
   - Open in Jupyter / Colab with T4 GPU.
   - Run all cells top-to-bottom (`Restart and Run All`).
   - Downloads UCI HAR data automatically and creates adding problem data.
   - Saves generated figures to `problem1/figures/` and updates `results.csv`.

2. **Problem 2 (`problem2/problem2.ipynb`):**
   - Open in Jupyter / Colab with T4 GPU.
   - Run all cells top-to-bottom (`Restart and Run All`).
   - Downloads Tiny Shakespeare data automatically.
   - Saves output samples to `generated_samples.txt`, figures to `problem2/figures/`, and updates `results.csv`.

## Run Time Summary (Colab T4 GPU)
- **Problem 1 total run time:** ~12-15 minutes
- **Problem 2 total run time:** ~15-20 minutes
- **Total Pipeline Execution:** ~30 minutes

## Notes & Verification
- Unit test assertions are embedded directly after custom cell definitions and attention functions.
- All random seeds fixed (torch, numpy, random) to 0, 1, 2 for reproducibility.
