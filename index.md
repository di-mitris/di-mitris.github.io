---
layout: index
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./about.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Current Projects

#### Vesuvius Challenge

The Vesuvius Challenge is a machine learning and computer vision competition that aims to extract passages of never-before-seen text from inside an unopened (and unopenable) carbonized scroll. The goal is to use computer vision and image segmentation techniques to extract faded ink from X-rays and other medical scans of papyri that were carbonized during the eruption of Mount Vesuvius.

#### Language Learning App
Target-language to English app. Starting with French/Spanish.

* Web Scraping for Sentences:
Consider using resources like news articles, blogs, or language learning websites (https://context.reverso.net/translation/).
Use Python libraries such as BeautifulSoup or Scrapy to scrape sentences from these sources. Extract text data from HTML elements and store the sentences in a structured format like a list or a database.
* Extraction of Words for Blanks:
Once you have a collection of sentences, tokenize each sentence into words or subwords.
Determine a strategy for selecting words to be replaced with blanks. For example, you could choose nouns, verbs, or words of a certain length.
Implement a function to replace selected words with blank placeholders (e.g., underscores or empty strings). Ensure that the context of the sentence remains intact after word replacement.
* Generation of Alternative (False) Answers:
After identifying the words to be replaced with blanks, generate alternative answers for the multiple-choice questions.
Use techniques such as synonym replacement, word scrambling, or context-based word selection to generate plausible false answers.
Ensure that false answers are grammatically correct and contextually relevant to the sentence.
Store the correct answer and false answers for each question in a structured format like a dictionary or a database.
* Implementation of Sliding Difficulty Feature:
Define criteria for adjusting the difficulty level of the multiple-choice questions. This could include factors like word frequency, sentence complexity, or linguistic features.
Implement a mechanism to dynamically adjust the difficulty level based on user performance or preferences.
Modify the word selection and false answer generation algorithms to reflect changes in difficulty level. For example, increase the complexity of sentences or choose less common words for blanks at higher difficulty levels.
* User Interface Development:
Create a user-friendly interface for the language learning app using Python libraries such as Tkinter before eventual deployment as a Flutter app (most likely).
Design screens for displaying sentences with blanks and multiple-choice questions. Include features for user interaction, such as selecting answers and progressing through questions.
Implement navigation controls and feedback mechanisms to guide users through the learning process and provide insights into their progress.


#### YouTube thumbnail generator (clickbait)



#### RAG in Greek


https://medium.com/11tensors/are-llama3-and-mixtral-open-models-ready-for-rag-in-greek-7cc1ab7579ed
https://medium.com/institute-for-language-and-speech-processing/meltemi-a-large-language-model-for-greek-9f5ef1d4a10f

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

