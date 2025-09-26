# Lafaek-Corpus-1M+ & Lafaek-Llama-3.1-8B
LAFAEK-CORPUS-1M+: A LARGE-SCALE TETUN CORPUS TO BUILD A LOW-RESOURCED LLM FOR SPEECH AND TEXT PROCESSING
*Accepted at O-COCOSDA 2025*

[📄 Paper (View on arXiv)](link-to-paper) | [📄 Paper (View on IEEE xplore)](link-to-paper)  | [🤗 Dataset (download Huggingface)](link-to-paper)

---

<p align="center">
  <img src="https://github.com/yuichi-1218/Lafaek-Corpus-1M-/blob/main/Lafeak.png" alt="Demo" width="400"/>
</p>


## 📖 Overview (Paper Abstruct)
This paper introduces a Tetun text corpus Lafaek-Corpus1M+. A Large Language Model (LLM) has attracted full
attention in natural language processing and speech processing. To build an LLM, huge corpora are basically needed,
however, it is quite hard for low-resourced languages. We focus on one Asian language Tetun, and make a text corpus for
a Tetun LLM. We collect more than million Tetun sentences from various resources. After that, we applied continual pretraining to a Llama-3.1 model using our corpus to build a
Tetun LLM. We conducted machine translation experiments. It is found that our LLM achieved better performance than the original model, and the effectiveness of our corpus is clarified.

## 📂 Dataset　
We are confirming attribution rights and obtaining permissions to make each resource available.

- **Wikipedia**
- **MADLAD-400-tetun**
- **Labadain-30k+**
- **News Transcription Data**

---

## ⚙️ How to Use
Lafaek-Corpus-1M+ Web resources can use Huggingface🤗 
[HF Dataset Link](link dataset)
```python
import datasets
```
---
## 📚 Citation
If you use this dataset, please cite:

```bibtex
@inproceedings{nishida2025LafaekCorpus,
  title={LAFAEK-CORPUS-1M+: A LARGE-SCALE TETUN CORPUS TO BUILD A LOW-RESOURCED LLM FOR SPEECH AND TEXT PROCESSING},
  author={Nishida, Yuichi AND Kuroda, Yuto AND Tamura, Satoshi },
  booktitle={O-COCOSDA},
  year={2025}
}
