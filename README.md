# The-Big-Bang-Theory-Scripts-Assignment

## Overview
This project involves text mining on scripts from "The Big Bang Theory" across the first 10 seasons, focusing on the character Howard Wolowitz. Participants will preprocess dialogues, analyze sentence/word counts, noun/person name mentions, important words per episode/season, and word co-occurrence.

## Dataset
The dataset comprises text scripts with attributes such as episode name, dialogue, and person scene, stored in a CSV file. Participants can use Python and pandas to import the dataset.

## Instructions
1. **Preprocessing Steps:**
   * Remove punctuations, convert to lowercase.
   * Perform sentence and word tokenization.
   * Remove stopwords using NLTK library.
   * Apply Porter stemmer for stemming.
   * Perform POS tagging and NER using the Spacy library.

2. **Analysis Questions (Howard Wolowitz):**
   * a. Average sentences and words per episode, exploring season deviations.
   * b. Global mentions of nouns and person names.
   * c. Identify important words using TF-IDF and bag-of-words, visualizing with Wordcloud.
   * d. Examine word co-occurrence using Positive Pointwise Mutual Information.
