# AI-Industry-Impact-Analysis
This repository contains my analysis on the impact of AI across various industries and the key factors contributing to the success of AI applications. The sectors focused on include photography and video, customer service, health care, weather alerts, music, home, finance, real estate, entertainment, and brand voice.

## Project Overview
My work involved the following major steps:
* Data Cleaning and Filtering: This step was crucial to prepare the dataset for further analysis. I removed special characters, long words, numbers, links, extra spaces, non-printable characters, and performed tokenisation, lemmatisation, and other cleaning operations. The data was also filtered to remove irrelevant articles and duplicates.
* Topic Detection: I utilized the Gensim library and Latent Dirichlet Allocation (LDA) model to detect the most common topics related to AI and their potential for AI applications.
* Sentiment Analysis: I trained a sentiment analysis model using a large dataset. This helped me understand what contributes to the success or failure of AI applications. I also analyzed the sentiment over time of popular AI initiatives.
* Entity Identification using NER: I used Named Entity Recognition (NER) using Spacy's pre-trained model to extract the most common organization and government entities involved in data science initiatives.
* Targeted Sentiment Identification: Based on the entities identified, I performed targeted sentiment analysis to understand how various sectors can leverage data science initiatives and the challenges they may face.
