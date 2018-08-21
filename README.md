# Counting Words and Detecting Themes with Python: Corpus Linguistics and Topic Modelling Approaches
*A two-day workshop for the [University of Tartu Digital Methods in Humanities and Social Sciences Summer School](https://digitalmethods.ut.ee/) on 22-23 August 2018.*

The goal of this workshop is twofold: 1) to demonstrate how Python’s Natural Language Toolkit (NLTK) library can be used to analyse large volumes of textual data, and 2) to empirically detect themes in this data through topic modelling. We will begin by exploring fundamental corpus linguistics functions using NLTK: tokenization, frequency distributions of keywords, part-of-speech tagging, stemming, lemmatization, n-grams, collocations, and concordances. This will allow for a descriptive understanding of the corpus (word categories and counts), which sets the stage for the unsupervised detection of themes.

A ‘theme’ is essentially a collection of words; topic models assign themes to documents based upon the co-occurrences of words in the documents. They operate under a naïve ‘bag of words’ assumption: a document is defined by the distribution of its vocabulary across various themes; syntax (and thereby context) is not taken into consideration. That being said, this naïve model can generate powerful insights about a corpus of text that instigate further qualitative analyses. In this workshop, the canonical topic model Latent Dirichlet Allocation (LDA) will be introduced. Results will be visualised through the interactive pyLDAvis library.

To attend and fully benefit from this workshop, participants should have basic knowledge of the programming language Python and its ecosystem, and should bring laptops equipped with Python 3.6 or higher. Installation through the [Anaconda distribution](https://www.continuum.io/) is highly recommended, as it bundles together a range of open-source Python packages and libraries used in data analysis and scientific computing—including Jupyter Notebook, the web application that we will be using in the workshop to run our code. Alternatively, Python can be installed through a binary installer from the [Python Software Foundation](https://www.python.org/), or through an operating system’s package manager (e.g., apt on Debian Linux and homebrew on macOS).

As noted above, it is essential that participants download not only Python 3.6 or higher, but also Jupyter Notebook (which is included in the Anaconda distribution). A very useful [Quick Start Guide can be found here](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/install.html). Participants who are unfamiliar with Jupyter should watch [this 30-minute YouTube tutorial](https://www.youtube.com/watch?v=HW29067qVWk) prior to the workshop.


## About the instructor

[**Yin Yin Lu**](https://www.oii.ox.ac.uk/people/yinyin-lu/) is a final-year DPhil (PhD) Candidate at the Oxford Internet Institute and Balliol College (University of Oxford). She researches persuasion in the context of new media, focusing specifically on the rhetoric and resonance of Brexit tweets. Her multi-strategy design encompasses qualitative text analysis, multivariate regressions, semi-structured trace interviews, and natural language processing algorithms. She convenes the [#SocialHumanities network](https://www.torch.ox.ac.uk/socialhumanities) at The Oxford Research Centre in the Humanities (TORCH), blogs from [Whimsy & Wanderlust](perrinewynkel.blogspot.co.uk), tweets from [@Yinneth](https://twitter.com/yinneth), and is a media commentator on online propaganda.


## Licence

The materials of this workshop are available under a [Creative Commons BY-CC-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See LICENSE for text.

Copyright 2018 Yin Yin Lu
