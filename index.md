---
layout: index
---


# Homepage
-----> [LinkedIn Profile](https://www.linkedin.com/in/dimitrios-alexandridis-49334b273)

## Current Projects

#### Vesuvius Challenge

The [Vesuvius Challenge](https://scrollprize.org/) is a machine learning and computer vision competition that aims to extract passages of never-before-seen text from inside an unopened (and unopenable) **carbonized scroll**. The goal is to use computer vision and image segmentation techniques to extract faded ink from X-rays and other medical scans of papyri that were carbonized during the eruption of Mount Vesuvius.

#### Language Learning App
An app focused on grammar and vocabulary practice based on multiple choice questions (cloze). Starting with French and Spanish with translations provided in English. Currently working on a Flask implementation, which will then be ported into Flutter. Rough development draft follows.

* Web Scraping for Sentences:
Use resources like news articles or language learning websites (https://context.reverso.net/translation/).
Use Python libraries such as BeautifulSoup or Scrapy to scrape sentences from these sources and store the sentences in a structured format like a list or a database.
* Extraction of Words for Blanks:
Tokenize each sentence into words. Determine a strategy for selecting words to be replaced with blanks. Nouns, **verbs**, or words of a certain length.
Implement a function to replace selected words with blank placeholders.
* Generation of Alternative (False) Answers:
Synonym replacement, word scrambling, or context-based word selection to generate plausible false answers.
Store the correct answer and false answers for each question in a structured format like a dictionary or a database.
* User Interface Development:
Create a user-friendly interface for the language learning app using Python libraries such as Tkinter before eventual deployment as a Flutter app.
Implement navigation controls and feedback mechanisms to guide users through the learning process and provide insights into their progress.

#### News aggregator site
Currently setting up a news aggregator, to feature a rolling feed of breaking news in a 48-hour cycle.

## Demos

1.  [Simple game with CI/CD](http://cicdgame.s3-website-us-east-1.amazonaws.com).
    A simple Javascript game that uses AWS Code Pipeline to automatically update on push to Github. Repo [here](https://github.com/di-mitris/codepipeline-s3-game).
2.  [Background Remover](https://test-img-1044824125830.europe-central2.run.app).
    A docker container deployed on GCP Cloud Run (serverless) that can remove the background from an image.
3.  [Simple summary](https://huggingface.co/spaces/di-mitris/demo-1).
    A HuggingFace Space that summarizes raw text.
4.  [Wikipedia summary](https://huggingface.co/spaces/di-mitris/demo-2-wiki-summary).
    A HuggingFace Space that summarizes a Wikipedia article based on its title (titles without disambiguations work better).
5.  [Pet classifier](https://huggingface.co/spaces/di-mitris/classifier).
    A HuggingFace Space that classifies images og dogs and cats.
6.  [Image Captioning](https://huggingface.co/spaces/di-mitris/Fast-Captions).
    A HuggingFace Space that takes an image and produces a caption (relatively quickly).
7.  [Text to Speech](https://huggingface.co/spaces/di-mitris/TextToSpeech)
    A HuggingFace Space that rapidly produces audio from text.

## Thesis
Here is a link to my [thesis](https://drive.google.com/file/d/1BUvra2-Q_VPrjHNwgIGKAkRCuEIoBCyn/view?usp=sharing) titled: "Modeling, Prediction and Categorization of elderly fall with deep learning techniques" (in Greek).

[About page](./about.html).

