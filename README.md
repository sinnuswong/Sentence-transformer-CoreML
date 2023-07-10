# Sentence-Transformer-coreML of Chinese and multilangual
CoreML version of sentence transformer for sentence embeddings, text matching or semantic search.

This repository contains:
- For **Tokenizer**:
	- pretrained [Google BERT](https://github.com/google-research/bert) and [Hugging Face DistilBERT](https://arxiv.org/abs/1910.01108) models fine-tuned for Question answering on the SQuAD dataset.
	- Swift implementations of the [BERT tokenizer](https://github.com/huggingface/swift-coreml-transformers/blob/master/Sources/BertTokenizer.swift) (`BasicTokenizer` and `WordpieceTokenizer`) and SQuAD dataset parsing utilities.

#  Chinese Sentence transformer


![demo](https://raw.githubusercontent.com/sinnuswong/Sentence-transformer-CoreML/blob/main/chinese/WechatIMG11162.jpeg)

#  Multilangual Sentence transformer

![bert](https://raw.githubusercontent.com/huggingface/swift-coreml-transformers/master/media/bert-architecture.png)

## Notes

We use `git-lfs` to store large model files and it is required to obtain some of the files the app needs to run.
See how to install `git-lfs`on the [installation page](https://git-lfs.github.com/)
