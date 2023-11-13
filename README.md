# LongTextTransformers: Fine-Tuning BigBird and Longformer on WIKIHOP

## Overview

This repository is dedicated to the fine-tuning of two state-of-the-art natural language processing models, BigBird and Longformer, utilizing the WIKIHOP dataset. Our objective is to enhance the handling of long-range dependencies and complex question-answering tasks.

## WIKIHOP Dataset

**WIKIHOP** is specifically designed for multi-hop reading comprehension, a challenging area in NLP. It consists of queries that necessitate the understanding and synthesis of information from multiple documents to answer. The dataset is intended for advancing research in document-level comprehension and reasoning.

- **Reference**: Welbl, J., Stenetorp, P., & Riedel, S. (2018). Constructing Datasets for Multi-hop Reading Comprehension Across Documents. [arXiv:1710.06481](https://arxiv.org/abs/1710.06481).

## BigBird Model

**BigBird**, developed by Google Research, is a transformer-based model that extends the capabilities of standard models like BERT for longer sequences. It's particularly effective for tasks involving long documents or contexts, making it ideal for the WIKIHOP dataset.

- **Reference**: Zaheer, M., Guruganesh, G., Dubey, K. A., et al. (2020). Big Bird: Transformers for Longer Sequences. [arXiv:2007.14062](https://arxiv.org/abs/2007.14062).

## Longformer Model

**Longformer** is designed to efficiently process long documents by extending the traditional transformer model with a combination of sliding window attention and global attention mechanisms. This makes it suitable for tasks that require the understanding of lengthy texts.

- **Reference**: Beltagy, I., Peters, M. E., & Cohan, A. (2020). Longformer: The Long-Document Transformer. [arXiv:2004.05150](https://arxiv.org/abs/2004.05150).

