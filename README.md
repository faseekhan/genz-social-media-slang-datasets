# Slang Datasets Collection

This repository aggregates two publicly available slang-related datasets collected from Hugging Face, Kaggle, and GitHub. These resources are useful for research on informal language, GenZ slang, acronyms, and definition modeling.

---

## 1. LM-Lexicon / Slang

**Source:** [Hugging Face – LM-Lexicon/Slang](https://huggingface.co/datasets/LM-Lexicon/Slang)

A dataset designed for improving definition modeling by harmonizing semantic experts. It contains slang terms with associated linguistic information, provided in train, validation, and test splits (JSONL format).

### Citation
```bibtex
@article{liu2026lmlexiconimprovingdefinitionmodeling,
  title={LM-Lexicon: Improving Definition Modeling via Harmonizing Semantic Experts}, 
  author={Yang Liu and Jiaye Yang and Weikang Li and Jiahui Liang and Yang Li and Lingyong Yan},
  year={2026},
  eprint={2602.14060},
  archivePrefix={arXiv},
  primaryClass={cs.CL},
  url={https://arxiv.org/abs/2602.14060}
}
```

---

## 2. MLBtrio / GenZ Slang Dataset

**Source:** [Hugging Face – MLBtrio/genz-slang-dataset](https://huggingface.co/datasets/MLBtrio/genz-slang-dataset)

A collection of popular slang terms and acronyms used primarily by Generation Z. Each entry typically includes:
* Slang / Acronym
* Description
* Example usage
* Context

The dataset was compiled for fine-tuning a GenZ slang generator model. Additional example and context columns were added by scraping publicly available websites and using generative AI.

### Additional Original Sources
1. Social Media Slangs and Acronyms ([Kaggle – Muhammad Rizwan](https://www.kaggle.com/datasets/rizdelhi/socialmediaabbrevations))
2. GenZ Dataset (`[caspercool]` (https://github.com/kaspercools/genz-dataset) )

---

## License & Usage Notes

Please refer to the original dataset licenses and terms of use before redistribution or commercial use. This repository is intended for academic and research purposes only. Always cite the original sources when using these datasets.
