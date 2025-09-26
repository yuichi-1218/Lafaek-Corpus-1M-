# Lafaek-Corpus-1M+
LAFAEK-CORPUS-1M+: A LARGE-SCALE TETUN CORPUS TO BUILD A LOW-RESOURCED LLM FOR SPEECH AND TEXT PROCESSING
*Accepted at O-COCOSDA 2025*

[📄 Paper (View on arXiv)](link-to-paper) | [📄 Paper (View on IEEE xplore)](link-to-paper)  | [🤗 Dataset (download Huggingface)](link-to-paper)

---

## 📖 Overview (Paper Abstruct)
This paper introduces a Tetun text corpus Lafaek-Corpus1M+. A Large Language Model (LLM) has attracted full
attention in natural language processing and speech processing. To build an LLM, huge corpora are basically needed,
however, it is quite hard for low-resourced languages. We focus on one Asian language Tetun, and make a text corpus for
a Tetun LLM. We collect more than million Tetun sentences from various resources. After that, we applied continual pretraining to a Llama-3.1 model using our corpus to build a
Tetun LLM. We conducted machine translation experiments. It is found that our LLM achieved better performance than the original model, and the effectiveness of our corpus is clarified.

## 📂 Dataset Access
We provide different access levels to balance **research priority** and **community contribution**.

- **Sample Release (10%)**: [📥 Download sample subset](link-to-sample)  
- **Full Dataset**: Available **upon request** for non-commercial research only.  
  Please fill this [Access Request Form](link-to-form) or contact [email].

---

## ⚙️ Installation
```bash
git clone https://github.com/username/repo.git
cd repo
pip install -r requirements.txt

---
##📚 Citation
If you use this dataset, please cite:

```bibtex
@inproceedings{nishida2025lafaekavsr,
  title={Lafaek-AVSR: Cross-Lingual Audio-Visual Speech Recognition for Tetun},
  author={Nishida, Yuichi and Tamura, Satoshi},
  booktitle={O-COCOSDA},
  year={2025}
}
