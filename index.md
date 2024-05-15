---
layout: index
---


# Homepage
## Current Projects

#### Vesuvius Challenge

The [Vesuvius Challenge](https://scrollprize.org/) is a machine learning and computer vision competition that aims to extract passages of never-before-seen text from inside an unopened (and unopenable) **carbonized scroll**. The goal is to use computer vision and image segmentation techniques to extract faded ink from X-rays and other medical scans of papyri that were carbonized during the eruption of Mount Vesuvius.

#### Language Learning App
An app focused on grammar and vocabulary practice based on multiple choice questions (cloze). Starting with French and Spanish with translations provided in English. Currently working on a Flask implementation, which will then be ported into Flutter. Rough development draft follows.

* Web Scraping for Sentences:
Consider using resources like news articles, blogs, or language learning websites (https://context.reverso.net/translation/).
Use Python libraries such as BeautifulSoup or Scrapy to scrape sentences from these sources. Extract text data from HTML elements and store the sentences in a structured format like a list or a database.
* Extraction of Words for Blanks:
Tokenize each sentence into words.
Determine a strategy for selecting words to be replaced with blanks. Nouns, **verbs**, or words of a certain length.
Implement a function to replace selected words with blank placeholders (e.g., underscores or empty strings). Ensure that the context of the sentence remains intact after word replacement.
* Generation of Alternative (False) Answers:
After identifying the words to be replaced with blanks, generate alternative answers for the multiple-choice questions.
Synonym replacement, word scrambling, or context-based word selection to generate plausible false answers.
Store the correct answer and false answers for each question in a structured format like a dictionary or a database.
* Implementation of Sliding Difficulty Feature:
Define criteria for adjusting the difficulty level of the multiple-choice questions. This could include factors like word frequency, sentence complexity, or word length.
Modify the word selection and false answer generation algorithms to reflect changes in difficulty level.
* User Interface Development:
Create a user-friendly interface for the language learning app using Python libraries such as Tkinter before eventual deployment as a Flutter app (most likely).
Design screens for displaying sentences with blanks and multiple-choice questions. Include features for user interaction, such as selecting answers and progressing through questions.
Implement navigation controls and feedback mechanisms to guide users through the learning process and provide insights into their progress.



## Demos

1.  [Background Remover](https://shorturl.at/cvzEG).
    A docker container deployed on GCP Cloud Run (serverless) that can remove the background from an image.
2.  [Simple summary](https://huggingface.co/spaces/di-mitris/demo-1).
    A HuggingFace Space that summarizes raw text.
3.  [Wikipedia summary](https://huggingface.co/spaces/di-mitris/demo-2-wiki-summary).
    A HuggingFace Space that summarizes a Wikipedia article based on its title (titles without disambiguations work better).
4.  [Pet classifier](https://huggingface.co/spaces/di-mitris/classifier).
    A HuggingFace Space that classifies images og dogs and cats.
5.  [Image Captioning](https://huggingface.co/spaces/di-mitris/Fast-Captions).
    A HuggingFace Space that takes an image and produces a caption (relatively quickly).
6.  [Text to Speech](https://huggingface.co/spaces/di-mitris/TextToSpeech)
    A HuggingFace Space that rapidly produces audio from text.

##

[About page](./about.html).

