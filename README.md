# Transformer-Based DRL for Dynamic Portfolio Allocation

This repository contains the implementation notebooks and supporting materials for my undergraduate thesis on transformer-based deep reinforcement learning for dynamic portfolio allocation.

## Thesis Focus

This thesis studies a dynamic portfolio allocation framework in which:

- a Transformer encoder is used as a market representation module,
- PPO is used as the policy optimization algorithm,
- transaction costs are incorporated into the reward design,
- attention-based analysis is used as a supporting explainability component.

## Main Components

- Data pipeline and preprocessing
- Benchmark construction and evaluation metrics
- MLP-PPO baseline
- LSTM-PPO baseline
- Transformer-PPO model
- Reward comparison analysis
- Supplementary ten-year robustness analysis
- Attention-based explainability analysis

## Repository Contents

The notebooks are numbered according to the main experimental workflow used in the thesis. They cover data preparation, benchmark evaluation, learned model training, result generation, reward-design comparison, supplementary ten-year analysis, and attention-based interpretation.

## Thesis Documents

- [Thesis Report](Thesis_Report.pdf)
- [Thesis Presentation](Thesis_Presentation.pdf)

## Supplementary Materials

Additional thesis-related outputs are available in the following Google Drive folder:

[Google Drive Folder](https://drive.google.com/drive/folders/1hJupJTCHF8G7fR4SCTANaSeZ036b-xXH?usp=sharing)

## Notes

This repository is intended to accompany the thesis submission and document the main implementation workflow used in the empirical study. The results should be interpreted within the controlled experimental setting described in the thesis.

## Requirements

Install the required packages with:

```bash
pip install -r requirements.txt
```

## QR Code

Scan this QR code to access the repository:

![QR Code](https://api.qrserver.com/v1/create-qr-code/?size=250x250&data=https://github.com/lenhatquyen9803-glitch/transformer-ppo-portfolio-optimization-thesis)
