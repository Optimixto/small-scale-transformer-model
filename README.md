# small-scale-transformer-model

This project is a collection of various natural language processing (NLP) tasks implemented with PyTorch. The project focuses on text classification and text generation tasks in Spanish. The project also showcases various techniques such as pre-training, fine-tuning, and transfer learning.

The following files are included:

 - data_preprocessing.py: A script for preprocessing Spanish data and performing exploratory data analysis (EDA) on the datasets.

 - decoder_only_small_4AH_256EMB_3LYR: A trained encoder-only model checkpoint that can be used for text generation. Can be run in the transformer_decoder_only.ipynb.

 - Finetuning_test.ipynb: A notebook showcasing the fine-tuning of a small BERT model for text classification.

 - spanish_lm.model: A tokenizer model trained with SentencePiece.

 - testing_GPU.py: A small script that tests if the GPU is available for training.

 - tokenizer.ipynb: A notebook that trains and creates the tokenizer.

 - transformer_decoder_only.ipynb: A notebook that contains a small text generative model based on GPT-2.

To train and test the models, you will need to have PyTorch and the Hugging Face Transformers library installed.
