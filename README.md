# 📊 Decadal Oscillations in Fundamental Physical Constants

This repository contains the full dataset, analysis code, and supporting material for the scientific paper:

**"Statistical Evidence for Decadal Oscillations in Fundamental Physical Constants"**

---

## 📘 Abstract

We present historical and statistical evidence for periodic variations in fundamental constants, focusing on the von Klitzing constant (RK) and the fine-structure constant (α). Our analysis reveals consistent oscillations over multi-decade timescales, with statistically significant 9-year periodicity confirmed across independent datasets.

---

## 📂 Repository Contents

| Folder/File                | Description |
|---------------------------|-------------|
| `raw_measurements.csv`     | Raw RK and α measurement data |
| `processed_data.csv`       | Cleaned and normalized data used for analysis |
| `RK_periodogram_data.csv`  | Pre-computed spectral analysis results |
| `combined_analysis.py`     | Main Python script for statistical analysis and figure generation |
| `requirements.txt`         | Required Python libraries |
| `figures/`                 | Contains Figures 1–4 from the paper |

---

## 🖼️ Figures

| Figure | Preview |
|--------|---------|
| **Figure 1** – RK 9-year oscillation | ![](figures/Figure_1_Periodograms.jpg) |
| **Figure 2** – Time series of α | ![](figures/Figure_2_Time_Series.jpg) |
| **Figure 3** – RK periodogram | ![](figures/Figure_3_Correlation.jpg) |
| **Figure 4** – Cross-correlation between RK and α | ![](figures/Figure_4_Statistical_Comparison.jpg) |

---

## 🚀 How to Run the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/Emile-E/Decadal-oscillations.git
   cd Decadal-oscillations

2. Install the required packages:

pip install -r requirements.txt

3. Run the analysis:

python combined_analysis.py

This will reproduce all four figures and summary statistics reported in the paper.

---

📚 Citation

If you use this code or data in your work, please cite the paper:

> Emile Ekladuse. Statistical Evidence for Decadal Oscillations in Fundamental Physical Constants. (2025). GitHub Repository

---

📬 Contact

For questions or collaboration inquiries, please reach out via GitHub Issues or email.

---

📖 License

This project is licensed under the MIT License.
