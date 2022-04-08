# NLP-Identifying-Emotions-Research_Submission
These files belong to "NLDB Conference - 2022".


This repository contains files for NLP research project- "Identifying Emotions for Code Mixed-Hindi-English Tweets". 
There is no publicly good quality data and pre-trained models for Code Mixed Hindi–English data, also it is expensive to collect, pre-process and run various machine and deep learning models. How efficiently can machine and deep learning models predict emotions from Code Mixed Hindi–English tweets? -> This is my MSc. Data Analytics - Thesis

Steps:

1. Extracted bilingual Code Mixed Hindi-English tweets using Twitter's official API 'Tweepy'.
2. Performed data cleaning by removing all those tweets which are less than 2-3 words and tweets that are completely in English or Hindi script. Cleaned noises such as links, RT, @, emojis, flags, etc. Converted many words in which had the same meaning but users used different spellings, such as 'hum', which means 'we' in English can be written as 'humm', 'hm, 'humm', etc. Most of those words are changed into a single word using Python's 'Regular Expression - re library'.
3. Manually annotated dataset into 7 emotions classes: Happy, Sad, Angry, Fear, Disgust, Surprise, or No emotions.
4. Performed pre-processing by removing punctuations, stopwords, numbers, converting all texts into lower case. This is using 1036 Hindi--English stopwords from Sourc https://github.com/TrigonaMinima/HinglishNLP/blob/master/data/assets/stop_hinglish
5. Extracted features using Vectorizers and Word Embeddings.
6. Implemented supervised machine learning models: SVM, Logistic Regression, and Random Forest.
7. Implemented supervised deep learning models: LSTM and BERT with neural networks.
8. Evaluated Results.


Project Report: I Will be uploading the project Report in 'Feb - 2022' because right now I have submitted the paper and if I upload it here, there may be a chance of 'Plagiarism'.

Note: I'm uploading only Tweet's ID as a dataset because of Twitter Policy, which says I can't share data publically.

Note: If you are unable to view the code, and it says 'An error occurred while reloading '.ipynb' file, which is a GitHub backend issue. You can try this:                         
Step 1: Open-> https://nbviewer.org/                                                                                                              
Step 2: Copy the link of the '.ipynb' code file and paste it into 'nbviewer'. You will be able to see the code file.

Thanks.
