# 5th-sem-Mini-project
Working on hindi wordnet using iNLTK 
Abstract:  
This project is about Natural Language Processing (NLP) on Hindi wordnet. This task was fulfilled by using Indie Natural Language Tool-kit a.k.a iNLTK. It is an open-source NLP library consisting of pre-trained language models and out-of-the-box support for Data Augmentation, Textual Similarity, Sentence Embeddings, Word Embeddings, Tokenization and Text Generation in 13 Indic Languages. I used these pre-trained models from iNLTK for text classification on publicly available dataset.
Project Introduction and Motivation:
Indic languages, widely spoken by more than a billion speakers, but there’s lack of Indic languages support in NLP libraries like spacy1 , nltk2 - creating a barrier to entry for working with Indic languages. iNLTK, an open-source natural language toolkit for Indic languages, is designed to address these problems and to significantly lower barriers to doing NLP in Indic Languages by 
 sharing pre-trained deep language models, which can then be fine-tuned and used for downstream tasks like text classification 
 providing out-of-the-box support for Data Augmentation, Textual Similarity, Sentence Embeddings, Word Embeddings, Tokenization and Text Generation built on top of pretrained language models, lowering the barrier for doing applied research and building products in Indic languages 
iNLTK library supports 13 Indic languages, including English
Supported languages
Native languages
Language
Code
Hindi
Hi
Punjabi
Pa
Gujarati
Gu
Kannada
Kn
Malayalam
Ml
Oriya
Or
Marathi
Mr
Bengali
Bn
Tamil
Ta
Urdu
Ur
Nepali
Ne
Sanskrit
Sa
English
En
Telugu
Te

Code Mixed languages
Language
Script
Code
Hinglish (Hindi+English)
Latin
hi-en
Tanglish (Tamil+English)
Latin
ta-en
Manglish (Malayalam+English)
Latin
ml-en


This was my first data learning project. The project gave me a clear insight on the life cycle of a data learning Project i.e. how the prepared dataset is tokenized and classified, and used in natural language processing learning tasks under unified APIs which can be used for data Learning for real world datasets. Also, being a proud Indian I am obliged to work on a project associated with Indie languages (hindi here).
Methodology followed:
I, mounted a public dataset in my code (via google cloud as I used Google Collaboratory).
Installed some libraries and packages such as:
pandas: to read dataset with .csv extension.
numpy: linear algebra
pytorch
iNLTK: to work with Hindi language



Setting up language that we will be using from iNLTK as ‘hi’ which is the code for Hindi.

Selecting a text index from dataset on which we want to work and Performing API on tokenized string
tokenization

generating similar sentences

prediction of next ‘n’ words

get embedding vectors (400 for Hindi)
                                                                                                                                                                                                                                                                                                                            

Result Analysis: 
Python code using google Collaboratory. (other suitable IDE or jupyter notebook can also be used like anaconda).
By using iNLTK APIs its easier to work on indie languages, generate related text and predict words.
