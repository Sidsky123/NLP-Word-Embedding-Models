# NLP-Word-Embedding-Models
This repository contains code to demonstrate NLP tasks like Tokenization, Corpus processing, Word Embeddings with Comparison between Embeddings of General transformers and Other Generative AI Embeddings
Please refer to the report to understand more about this task

Task Part 1: Corpus processing (legal text): tokenization and word counting [50 points]

Implement a word tokenizer that splits texts into tokens and separates punctuation marks and other symbols from the words. Please describe in your report all the decisions you made relative to pre-processing and tokenization.  Implement a program that counts the number of occurrences of each token in the corpus.

Task Part 2: Evaluation of pre-trained sentence embedding models  [50 points]

 Word embeddings are dense representations of the meaning of words, build via neural language models. Sentence embeddings are dense representations of sentences, that can be composed by averaging the word vectors or sentence representations can be learned directly.

Chose at least 5 pre-trained sentence embeddings. If they have different parameters, you can experiment with them, but choose one for your report. Also make sure to include a version of SBERT (Reimers and Gurevych, 2019, https://aclanthology.org/D19-1410/) (https://www.sbert.net/) and at least one model based on recent generative LLM models, in addition to other pre-trained language models that can represent sentences.

Use the dataset from the Semeval 2016-Task1 Semantic Textual Similarity (STS).

Use the test data STS Core (English Monolingual subtask) - test data with gold labels.  Do not use the training data. Read more about the task at https://alt.qcri.org/semeval2016/task1/#

 

You can write your code or reuse existing code or tools (as long as you acknowledge them and extend them if needed).

 

Include in your report details about what sentence embeddings you chose (with what parameters and what mechanism is behind them), and add in the table below with the results of their evaluations on the above-mentioned benchmark dataset (if you used more than 5 embeddings, mention in the report but put the best 5 results in the table). Include in your report your system output for your best model for all the files in the test data.

 

We will have a mini-competition for the best score over the benchmark dataset for your best sentence embedding results. The evaluation score to report is the Pearson correlation between the score obtained by your model and the expected solution. The expected solution scores are numeric values between and 5 (from low similarity to high similarity). There is script that you can use to compute the correlations (included in the zip file for the test data).

 
