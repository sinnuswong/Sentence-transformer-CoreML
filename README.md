# Sentence-Transformer-coreML of Chinese and multilangual
CoreML version of sentence transformer for sentence embeddings, text matching or semantic search.

# Swift Core ML implementations of Transformers: GPT-2, DistilGPT-2, BERT, DistilBERT, more coming soon!

This repository contains:
- For **Tokenizer**:
	- pretrained [Google BERT](https://github.com/google-research/bert) and [Hugging Face DistilBERT](https://arxiv.org/abs/1910.01108) models fine-tuned for Question answering on the SQuAD dataset.
	- Swift implementations of the [BERT tokenizer](https://github.com/huggingface/swift-coreml-transformers/blob/master/Sources/BertTokenizer.swift) (`BasicTokenizer` and `WordpieceTokenizer`) and SQuAD dataset parsing utilities.

# 🦄 Chinese Sentence transformer

Unleash the full power of text generation with GPT-2 on device!!

![demo](https://raw.githubusercontent.com/huggingface/swift-coreml-transformers/master/media/coreml-gpt2.gif)

# 🐸 Multilangual Sentence transformer

The `BERTSQUADFP16` Core ML model was packaged by Apple and is linked from the [main ML models page](https://developer.apple.com/machine-learning/models/#text). It was demoed at WWDC 2019 as part of the Core ML 3 launch.

The `DistilBERT` Core ML models were converted from [`🤗/transformers`](https://github.com/huggingface/transformers) exports using the scripts in this repo.

![core ml 3](https://raw.githubusercontent.com/huggingface/swift-coreml-transformers/master/media/coreml3-models-tweaked.png)



## BERT Architecture (wwdc slide)

![bert](https://raw.githubusercontent.com/huggingface/swift-coreml-transformers/master/media/bert-architecture.png)

## Notes

We use `git-lfs` to store large model files and it is required to obtain some of the files the app needs to run.
See how to install `git-lfs`on the [installation page](https://git-lfs.github.com/)
