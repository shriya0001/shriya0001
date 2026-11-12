## Hi, I'm Shriya Thakur

AI/ML researcher working on **medical and biological AI** and on **using and evaluating language models**: as labellers for messy real-world data, and as coding agents.

I lead applied AI research projects end to end, from problem framing and data pipelines to models, careful evaluation and the paper. I've supervised 50+ research projects and built several myself.

### Selected work

| Project | What it shows |
|---|---|
| [**hcc-survival-xai**](https://github.com/shriya0001/hcc-survival-xai) | Survival prediction for 1,357 liver-cancer patients from clinical and genomic data. CoxPH vs DeepSurv, then three explainability methods combined into a consensus biomarker ranking. *IEEE BMEiCON-2026 paper.* |
| **rsna-knee-llm-labels** | Only 58 of 4,407 knee MRIs had expert labels. An open-weight LLM (Qwen3-32B via vLLM) turns radiology reports in 9+ languages into soft labels for a 2.5D slice-attention model. Validation macro AUC 0.877, Kaggle public LB 0.900. Locked-protocol journal study in progress; *code released with the paper.* |
| [**biohub-cell-tracking**](https://github.com/shriya0001/biohub-cell-tracking) | 3D cell tracking in zebrafish embryo videos (Kaggle, about 3,900 teams). Fully offline inference repair, then trained association models on a frozen detector, with fixed acceptance gates. Private score 0.763, then 0.800 with a post-deadline submission. |

### Publications
- **S. Thakur**, S. Bhandari. *Explainable Survival Prediction and Biomarker Discovery in Hepatocellular Carcinoma.* IEEE BMEiCON-2026. [Accepted version](https://github.com/shriya0001/hcc-survival-xai/blob/main/paper/BMEiCON2026_HCC_Thakur_Bhandari_accepted.pdf)
- *Weakly supervised knee MRI abnormality detection with LLM-derived labels*: journal manuscript in preparation (target: IEEE JBHI)

### Now
- Building a calibrated evaluation bench for **coding agents** on small open models (Gemma 4): harness design across model sizes, contamination checks with pre- and post-cutoff tasks, and repeat runs. Code will be published after the competition closes.

### How I work
Leak-proof splits that are locked before any modelling. Preprocessing fit on training data only. Hyperparameters chosen by cross-validation, never on the test set. Results reported with their limitations.

### Background
About 10 years in industry: data analytics at **Amazon** and **Xiaomi**, then 5+ years designing, reviewing and assessing coding curricula (**WhiteHat Jr**, **JetLearn**), and now leading applied AI research. B.E. in Computer Science.

**Tools:** Python · PyTorch · scikit-learn · lifelines / scikit-survival · Hugging Face · vLLM · Captum · Kaggle · Colab
