AllenNLP
--------

An open-source NLP research library, built on PyTorch. AllenNLP is a NLP
research library, built on PyTorch, for developing state-of-the-art deep
learning models on a wide variety of linguistic tasks. AllenNLP makes it
easy to design and evaluate new deep learning models for nearly any NLP
problem, along with the infrastructure to easily run them in the cloud
or on your laptop.

AllenNLP was designed with the following principles:

-  *Hyper-modular and lightweight.* Use the parts which you like
   seamlessly with PyTorch.
-  *Extensively tested and easy to extend.* Test coverage is above 90%
   and the example models provide a template for contributions.
-  *Take padding and masking seriously*, making it easy to implement
   correct models without the pain.
-  *Experiment friendly.* Run reproducible experiments from a json
   specification with comprehensive logging.

+-----------------------+---------------------------------------+
| **SBB License**       | Apache License 2.0                    |
+-----------------------+---------------------------------------+
| **Core Technology**   | Python                                |
+-----------------------+---------------------------------------+
| **Project URL**       | http://allennlp.org/                  |
+-----------------------+---------------------------------------+
| **Source Location**   | https://github.com/allenai/allennlp   |
+-----------------------+---------------------------------------+
| **Tag(s)**            | ML, NLP, Python                       |
+-----------------------+---------------------------------------+

| 

Apache OpenNLP
--------------

The Apache OpenNLP library is a machine learning based toolkit for the
processing of natural language text.

The Apache OpenNLP library is a machine learning based toolkit for the
processing of natural language text. It supports the most common NLP
tasks, such as tokenization, sentence segmentation, part-of-speech
tagging, named entity extraction, chunking, parsing, and coreference
resolution. These tasks are usually required to build more advanced text
processing services. OpenNLP also included maximum entropy and
perceptron based machine learning.

The goal of the OpenNLP project will be to create a mature toolkit for
the abovementioned tasks. An additional goal is to provide a large
number of pre-built models for a variety of languages, as well as the
annotated text resources that those models are derived from.

+-----------------------+----------------------------------------------+
| **SBB License**       | Apache License 2.0                           |
+-----------------------+----------------------------------------------+
| **Core Technology**   | Java                                         |
+-----------------------+----------------------------------------------+
| **Project URL**       | http://opennlp.apache.org/                   |
+-----------------------+----------------------------------------------+
| **Source Location**   | http://opennlp.apache.org/source-code.html   |
+-----------------------+----------------------------------------------+
| **Tag(s)**            | NLP                                          |
+-----------------------+----------------------------------------------+

| 

Apache Tika
-----------

The Apache Tika™ toolkit detects and extracts metadata and text from
over a thousand different file types (such as PPT, XLS, and PDF). All of
these file types can be parsed through a single interface, making Tika
useful for search engine indexing, content analysis, translation, and
much more.

Several wrappers are available to use Tika in another programming
language, such as `Julia <https://github.com/aviks/Taro.jl>`__ or
`Python <https://github.com/chrismattmann/tika-python>`__

+-----------------------+----------------------------+
| **SBB License**       | Apache License 2.0         |
+-----------------------+----------------------------+
| **Core Technology**   | Java                       |
+-----------------------+----------------------------+
| **Project URL**       | https://tika.apache.org/   |
+-----------------------+----------------------------+
| **Source Location**   | https://tika.apache.org/   |
+-----------------------+----------------------------+
| **Tag(s)**            | NLP                        |
+-----------------------+----------------------------+

| 

Bling Fire
----------

A lightning fast Finite State machine and REgular expression
manipulation library. Bling Fire Tokenizer is a tokenizer designed for
fast-speed and quality tokenization of Natural Language text. It mostly
follows the tokenization logic of NLTK, except hyphenated words are
split and a few errors are fixed.

+-----------------------+------------------------------------------+
| **SBB License**       | MIT License                              |
+-----------------------+------------------------------------------+
| **Core Technology**   | CPP                                      |
+-----------------------+------------------------------------------+
| **Project URL**       | https://github.com/Microsoft/BlingFire   |
+-----------------------+------------------------------------------+
| **Source Location**   | https://github.com/Microsoft/BlingFire   |
+-----------------------+------------------------------------------+
| **Tag(s)**            | NLP                                      |
+-----------------------+------------------------------------------+

| 

ERNIE
-----

An Implementation of ERNIE For Language Understanding (including
Pre-training models and Fine-tuning tools)

**`ERNIE 2.0 <https://arxiv.org/abs/1907.12412v1>`__ is a continual
pre-training framework for language understanding** in which
pre-training tasks can be incrementally built and learned through
multi-task learning. In this framework, different customized tasks can
be incrementally introduced at any time. For example, the tasks
including named entity prediction, discourse relation recognition,
sentence order prediction are leveraged in order to enable the models to
learn language representations.

+-----------------------+-----------------------------------------+
| **SBB License**       | Apache License 2.0                      |
+-----------------------+-----------------------------------------+
| **Core Technology**   | Python                                  |
+-----------------------+-----------------------------------------+
| **Project URL**       | https://github.com/PaddlePaddle/ERNIE   |
+-----------------------+-----------------------------------------+
| **Source Location**   | https://github.com/PaddlePaddle/ERNIE   |
+-----------------------+-----------------------------------------+
| **Tag(s)**            | NLP, Python                             |
+-----------------------+-----------------------------------------+

| 

fastText
--------

`fastText <https://fasttext.cc/>`__ is a library for efficient learning
of word representations and sentence classification. Models can later be
reduced in size to even fit on mobile devices.

Created by Facebook Opensource, now available for us all. Also used for
the new search on StackOverflow, see
https://stackoverflow.blog/2019/08/14/crokage-a-new-way-to-search-stack-overflow/

+-----------------------+------------------------------------------------+
| **SBB License**       | MIT License                                    |
+-----------------------+------------------------------------------------+
| **Core Technology**   | CPP, Python                                    |
+-----------------------+------------------------------------------------+
| **Project URL**       | https://fasttext.cc/                           |
+-----------------------+------------------------------------------------+
| **Source Location**   | https://github.com/facebookresearch/fastText   |
+-----------------------+------------------------------------------------+
| **Tag(s)**            | NLP                                            |
+-----------------------+------------------------------------------------+

| 

Flair
-----

A very simple framework for **state-of-the-art NLP**. Developed by
`Zalando Research <https://research.zalando.com/>`__.

Flair is:

-  **A powerful NLP library.** Flair allows you to apply our
   state-of-the-art natural language processing (NLP) models to your
   text, such as named entity recognition (NER), part-of-speech tagging
   (PoS), sense disambiguation and classification.
-  **Multilingual.** Thanks to the Flair community, we support a rapidly
   growing number of languages. We also now include ‘\ *one model, many
   languages*\ ‘ taggers, i.e. single models that predict PoS or NER
   tags for input text in various languages.
-  **A text embedding library.** Flair has simple interfaces that allow
   you to use and combine different word and document embeddings,
   including our proposed **`Flair
   embeddings <https://drive.google.com/file/d/17yVpFA7MmXaQFTe-HDpZuqw9fJlmzg56/view?usp=sharing>`__**,
   BERT embeddings and ELMo embeddings.
-  **A Pytorch NLP framework.** Our framework builds directly on
   `Pytorch <https://pytorch.org/>`__, making it easy to train your own
   models and experiment with new approaches using Flair embeddings and
   classes.

+-----------------------+--------------------------------------------+
| **SBB License**       | MIT License                                |
+-----------------------+--------------------------------------------+
| **Core Technology**   | Python                                     |
+-----------------------+--------------------------------------------+
| **Project URL**       | https://github.com/zalandoresearch/flair   |
+-----------------------+--------------------------------------------+
| **Source Location**   | https://github.com/zalandoresearch/flair   |
+-----------------------+--------------------------------------------+
| **Tag(s)**            | ML, NLP, Python                            |
+-----------------------+--------------------------------------------+

| 

Gensim
------

Gensim is a Python library for *topic modelling*, *document indexing*
and *similarity retrieval* with large corpora. Target audience is the
*natural language processing* (NLP) and *information retrieval* (IR)
community.

 

+-----------------------+-----------------------------------------------+
| **SBB License**       | MIT License                                   |
+-----------------------+-----------------------------------------------+
| **Core Technology**   | Python                                        |
+-----------------------+-----------------------------------------------+
| **Project URL**       | https://github.com/RaRe-Technologies/gensim   |
+-----------------------+-----------------------------------------------+
| **Source Location**   | https://github.com/RaRe-Technologies/gensim   |
+-----------------------+-----------------------------------------------+
| **Tag(s)**            | ML, NLP, Python                               |
+-----------------------+-----------------------------------------------+

| 

Neuralcoref
-----------

State-of-the-art coreference resolution based on neural nets and spaCy.

NeuralCoref is a pipeline extension for spaCy 2.0 that annotates and
resolves coreference clusters using a neural network. NeuralCoref is
production-ready, integrated in spaCy’s NLP pipeline and easily
extensible to new training datasets.

+-----------------------+----------------------------------------------+
| **SBB License**       | MIT License                                  |
+-----------------------+----------------------------------------------+
| **Core Technology**   | Python                                       |
+-----------------------+----------------------------------------------+
| **Project URL**       | https://huggingface.co/coref/                |
+-----------------------+----------------------------------------------+
| **Source Location**   | https://github.com/huggingface/neuralcoref   |
+-----------------------+----------------------------------------------+
| **Tag(s)**            | ML, NLP, Python                              |
+-----------------------+----------------------------------------------+

| 

NLP Architect
-------------

NLP Architect is an open-source Python library for exploring the
state-of-the-art deep learning topologies and techniques for natural
language processing and natural language understanding. It is intended
to be a platform for future research and collaboration.

.. raw:: html

   <div id="how-can-nlp-architect-be-used" class="section">

How can NLP Architect be used:

-  Train models using provided algorithms, reference datasets and
   configurations
-  Train models using your own data
-  Create new/extend models based on existing models or topologies
-  Explore how deep learning models tackle various NLP tasks
-  Experiment and optimize state-of-the-art deep learning algorithms
-  integrate modules and utilities from the library to solutions

.. raw:: html

   </div>

+-----------------------+---------------------------------------------------+
| **SBB License**       | Apache License 2.0                                |
+-----------------------+---------------------------------------------------+
| **Core Technology**   | Python                                            |
+-----------------------+---------------------------------------------------+
| **Project URL**       | http://nlp_architect.nervanasys.com/              |
+-----------------------+---------------------------------------------------+
| **Source Location**   | https://github.com/NervanaSystems/nlp-architect   |
+-----------------------+---------------------------------------------------+
| **Tag(s)**            | ML, NLP, Python                                   |
+-----------------------+---------------------------------------------------+

| 

NLTK (Natural Language Toolkit)
-------------------------------

NLTK is a leading platform for building Python programs to work with
human language data. It provides easy-to-use interfaces to `over 50
corpora and lexical resources <http://nltk.org/nltk_data/>`__ such as
WordNet, along with a suite of text processing libraries for
classification, tokenization, stemming, tagging, parsing, and semantic
reasoning, wrappers for industrial-strength NLP libraries.

Check also the (free) online Book (OReily published)

+-----------------------+--------------------------------+
| **SBB License**       | Apache License 2.0             |
+-----------------------+--------------------------------+
| **Core Technology**   | Python                         |
+-----------------------+--------------------------------+
| **Project URL**       | http://www.nltk.org            |
+-----------------------+--------------------------------+
| **Source Location**   | https://github.com/nltk/nltk   |
+-----------------------+--------------------------------+
| **Tag(s)**            | NLP                            |
+-----------------------+--------------------------------+

| 

Pattern
-------

Pattern is a web mining module for Python. It has tools for:

-  Data Mining: web services (Google, Twitter, Wikipedia), web crawler,
   HTML DOM parser
-  Natural Language Processing: part-of-speech taggers, n-gram search,
   sentiment analysis, WordNet
-  Machine Learning: vector space model, clustering, classification
   (KNN, SVM, Perceptron)
-  Network Analysis: graph centrality and visualization.

+-----------------------+------------------------------------------------------+
| **SBB License**       | BSD License 2.0 (3-clause, New or Revised) License   |
+-----------------------+------------------------------------------------------+
| **Core Technology**   | Python                                               |
+-----------------------+------------------------------------------------------+
| **Project URL**       | https://www.clips.uantwerpen.be/pages/pattern        |
+-----------------------+------------------------------------------------------+
| **Source Location**   | https://github.com/clips/pattern                     |
+-----------------------+------------------------------------------------------+
| **Tag(s)**            | ML, NLP, Web scraping                                |
+-----------------------+------------------------------------------------------+

| 

PDFx
----

Extract references (pdf, url, doi, arxiv) and metadata from a PDF.
Optionally download all referenced PDFs and check for broken links.

**Features**

-  Extract references and metadata from a given PDF
-  Detects pdf, url, arxiv and doi references
-  **Fast, parallel download of all referenced PDFs**
-  **Find broken hyperlinks (using the ``-c`` flag)**
   (`more <https://www.metachris.com/2016/03/find-broken-hyperlinks-in-a-pdf-document-with-pdfx/>`__)
-  Output as text or JSON (using the ``-j`` flag)
-  Extract the PDF text (using the ``--text`` flag)
-  Use as command-line tool or Python package
-  Compatible with Python 2 and 3
-  Works with local and online pdfs

+-----------------------+-------------------------------------+
| **SBB License**       | Apache License 2.0                  |
+-----------------------+-------------------------------------+
| **Core Technology**   | Python                              |
+-----------------------+-------------------------------------+
| **Project URL**       | https://www.metachris.com/pdfx/     |
+-----------------------+-------------------------------------+
| **Source Location**   | https://github.com/metachris/pdfx   |
+-----------------------+-------------------------------------+
| **Tag(s)**            | NLP, Text Extraction                |
+-----------------------+-------------------------------------+

| 

Rant
----

Rant is an all-purpose procedural text engine that is most simply
described as the opposite of Regex. It has been refined to include a
dizzying array of features for handling everything from the most basic
of string generation tasks to advanced dialogue generation, code
templating, automatic formatting, and more.

The goal of the project is to enable developers of all kinds to automate
repetitive writing tasks with a high degree of creative freedom.

Features:

-  Recursive, weighted branching with several selection modes
-  Queryable dictionaries
-  Automatic capitalization, rhyming, English indefinite articles, and
   multi-lingual number verbalization
-  Print to multiple separate outputs
-  Probability modifiers for pattern elements
-  Loops, conditional statements, and subroutines
-  Fully-functional object model
-  Import/Export resources easily with the .rantpkg format
-  Compatible with Unity 2017

+-----------------------+-------------------------------------+
| **SBB License**       | MIT License                         |
+-----------------------+-------------------------------------+
| **Core Technology**   | .NET                                |
+-----------------------+-------------------------------------+
| **Project URL**       | https://berkin.me/rant/             |
+-----------------------+-------------------------------------+
| **Source Location**   | https://github.com/TheBerkin/rant   |
+-----------------------+-------------------------------------+
| **Tag(s)**            | .NET, ML, NLP, text generation      |
+-----------------------+-------------------------------------+

| 

SpaCy
-----

.. raw:: html

   <div class="o-grid__col o-grid__col--third">

Industrial-strength Natural Language Processing (NLP) with Python and
Cython

Features:

-  Non-destructive **tokenization**
-  **Named entity** recognition
-  Support for **26+ languages**
-  **13 statistical models** for 8 languages
-  Pre-trained **word vectors**
-  Easy **deep learning** integration
-  Part-of-speech tagging
-  Labelled dependency parsing
-  Syntax-driven sentence segmentation
-  Built in **visualizers** for syntax and NER
-  Convenient string-to-hash mapping
-  Export to numpy data arrays
-  Efficient binary serialization
-  Easy **model packaging** and deployment
-  State-of-the-art speed
-  Robust, rigorously evaluated accuracy

.. raw:: html

   </div>

+-----------------------+--------------------------------------+
| **SBB License**       | MIT License                          |
+-----------------------+--------------------------------------+
| **Core Technology**   | Python                               |
+-----------------------+--------------------------------------+
| **Project URL**       | https://spacy.io/                    |
+-----------------------+--------------------------------------+
| **Source Location**   | https://github.com/explosion/spaCy   |
+-----------------------+--------------------------------------+
| **Tag(s)**            | NLP                                  |
+-----------------------+--------------------------------------+

| 

Stanford CoreNLP
----------------

Stanford CoreNLP provides a set of human language technology tools. It
can give the base forms of words, their parts of speech, whether they
are names of companies, people, etc., normalize dates, times, and
numeric quantities, mark up the structure of sentences in terms of
phrases and syntactic dependencies, indicate which noun phrases refer to
the same entities, indicate sentiment, extract particular or open-class
relations between entity mentions, get the quotes people said, etc.

Choose Stanford CoreNLP if you need:

-  An integrated NLP toolkit with a broad range of grammatical analysis
   tools
-  A fast, robust annotator for arbitrary texts, widely used in
   production
-  A modern, regularly updated package, with the overall highest quality
   text analytics
-  Support for a number of major (human) languages
-  Available APIs for most major modern programming languages
-  Ability to run as a simple web service

+-----------------------+------------------------------------------+
| **SBB License**       | GNU General Public License (GPL) 3.0     |
+-----------------------+------------------------------------------+
| **Core Technology**   | Java                                     |
+-----------------------+------------------------------------------+
| **Project URL**       | https://stanfordnlp.github.io/CoreNLP/   |
+-----------------------+------------------------------------------+
| **Source Location**   | https://github.com/stanfordnlp/CoreNLP   |
+-----------------------+------------------------------------------+
| **Tag(s)**            | NLP                                      |
+-----------------------+------------------------------------------+

| 

Sumeval
-------

Well tested & Multi-language evaluation framework for text
summarization. Multi-language.

+-----------------------+-------------------------------------------+
| **SBB License**       | Apache License 2.0                        |
+-----------------------+-------------------------------------------+
| **Core Technology**   | Python                                    |
+-----------------------+-------------------------------------------+
| **Project URL**       | https://github.com/chakki-works/sumeval   |
+-----------------------+-------------------------------------------+
| **Source Location**   | https://github.com/chakki-works/sumeval   |
+-----------------------+-------------------------------------------+
| **Tag(s)**            | NLP, Python                               |
+-----------------------+-------------------------------------------+

| 

TextBlob: Simplified Text Processing
------------------------------------

*TextBlob* is a Python (2 and 3) library for processing textual data. It
provides a simple API for diving into common natural language processing
(NLP) tasks such as part-of-speech tagging, noun phrase extraction,
sentiment analysis, classification, translation, and more.

Features
--------

-  Noun phrase extraction
-  Part-of-speech tagging
-  Sentiment analysis
-  Classification (Naive Bayes, Decision Tree)
-  Language translation and detection powered by Google Translate
-  Tokenization (splitting text into words and sentences)
-  Word and phrase frequencies
-  Parsing
-  n-grams
-  Word inflection (pluralization and singularization) and lemmatization
-  Spelling correction
-  Add new models or languages through extensions
-  WordNet integration

+-----------------------+-------------------------------------------+
| **SBB License**       | MIT License                               |
+-----------------------+-------------------------------------------+
| **Core Technology**   | Python                                    |
+-----------------------+-------------------------------------------+
| **Project URL**       | https://textblob.readthedocs.io/en/dev/   |
+-----------------------+-------------------------------------------+
| **Source Location**   | https://github.com/sloria/textblob        |
+-----------------------+-------------------------------------------+
| **Tag(s)**            | ML, NLP, Python                           |
+-----------------------+-------------------------------------------+

| 

Thinc
-----

Thinc is the machine learning library powering spaCy. It features a
battle-tested linear model designed for large sparse learning problems,
and a flexible neural network model under development for spaCy v2.0.

Thinc is a practical toolkit for implementing models that follow the
“Embed, encode, attend, predict” architecture. It’s designed to be easy
to install, efficient for CPU usage and optimised for NLP and deep
learning with text – in particular, hierarchically structured input and
variable-length sequences.

+-----------------------+----------------------------------------+
| **SBB License**       | GNU General Public License (GPL) 2.0   |
+-----------------------+----------------------------------------+
| **Core Technology**   | Python                                 |
+-----------------------+----------------------------------------+
| **Project URL**       | https://explosion.ai/                  |
+-----------------------+----------------------------------------+
| **Source Location**   | https://github.com/explosion/thinc     |
+-----------------------+----------------------------------------+
| **Tag(s)**            | ML, NLP, Python                        |
+-----------------------+----------------------------------------+

| 

Torchtext
---------

Data loaders and abstractions for text and NLP. Build on PyTorch.

 

+-----------------------+------------------------------------------------------+
| **SBB License**       | BSD License 2.0 (3-clause, New or Revised) License   |
+-----------------------+------------------------------------------------------+
| **Core Technology**   |                                                      |
+-----------------------+------------------------------------------------------+
| **Project URL**       | https://github.com/pytorch/text                      |
+-----------------------+------------------------------------------------------+
| **Source Location**   | https://github.com/pytorch/text                      |
+-----------------------+------------------------------------------------------+
| **Tag(s)**            | NLP                                                  |
+-----------------------+------------------------------------------------------+

| 
| End of SBB list
