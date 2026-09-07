---
task_categories:
- text-generation
language:
- en
tags:
- genz
- nlp
- slang
- acronym
size_categories:
- 1K<n<10K
---

## Dataset Details
- This dataset contains a rich collection of popular slang terms and acronyms used primarily by Generation Z. It includes detailed descriptions of each term, its context of use, and practical examples that demonstrate how the slang is used in real-life conversations.<br>
- The dataset is designed to capture the unique and evolving language patterns of GenZ, reflecting their communication style in digital spaces such as social media, text messaging, and online forums. Each entry provides the following:
  - Slang/Acronym: The specific slang or acronym used by GenZ.
  - Description: A brief explanation of the meaning and nuances of the term.
  - Example: A sentence or short conversation showcasing the slang in action. 
  - Context: The typical scenario or environment where the slang is used, including cultural or social references. <br>
- This dataset was specifically compiled and used for the fine-tuning phase of the [GenZ Slang Generator](https://huggingface.co/SeoyeonPark1223/genz-slang-generator) project. It enabled the model to generate slang terms and responses that are contextually relevant and aligned with the linguistic tendencies of Generation Z.

## Datasset Sources
- **Dataset:**
  - Source 1: [Social Media Slangs and Acronyms](https://www.kaggle.com/datasets/rizdelhi/socialmediaabbrevations)
  - Source 2: [GenZ Dataset](https://github.com/kaspercools/genz-dataset.git)
  - Added `Example`, `Context` columns by scraping publicly available websites and using generative AI.