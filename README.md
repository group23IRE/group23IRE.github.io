# Project Page - Group 23

Problem Statement
=================

Creating short summaries of documents with respect to a query has
applications in for example search engines, where it may help inform
users of the most relevant results. Constructing such a summary
automatically, with the potential expressiveness of a human-written
summary, is a difficult problem yet to be fully solved.

Introduction
============

-   Difference between extractive and abstractive summarization:

    -   Extractive summarization:

        -   Extractive methods work by selecting a subset of existing
            words, phrases, or sentences in the original text to form
            the summary.

        -   There is no natural language generation involved.

    -   Abstractive summarization

        -   Abstractive methods build an internal semantic
            representation and then use natural language generation
            techniques to create a summary that is closer to what a
            human might express. Such a summary might include verbal
            innovations.

-   In Query based abstractive text summarization the aim is to generate
    the summary of a document in the context of a query. In general,
    abstractive summarization, aims to cover all the salient points of a
    document in a compact and coherent fashion.

-   Query focused summarization highlights those points that are
    relevant in the context of the query.

-   Each summary is abstractive and not extractive in the sense that the
    summary does not necessarily comprise of a sentence which is simply
    copied from the original document.

Applications
============

-   Can be used in search engines :

    -   When asked a query to the search engine, the most relevant
        document is fetched and the summary of the document in
        accordance with the query can be generated as humans do .

-   There can be multiple such business scenarios where we can feed
    large documents and then get results.

-   Useful for Q and A platforms, where the system can answer queries
    based on relevant tags/sources.

Dataset
=======

The dataset is from Debatepedia an encyclopedia of pro and con arguments
and quotes on critical debate topics. There are 663 debates in the
corpus (only those debates are considered which have at least one query
with one document). These 663 debates belong to 53 overlapping
categories such as Politics, Law, Crime, Environment, Health, Morality,
Religion, etc. A given topic can belong to more than one category. For
example, the topic "Eye for an Eye philos

Scores and Results
==================
```
rouge-1:  28.074
rouge-2:  2.183
rouge-L:  21.681
```
Challenges and limitations
==========================

-   To get comfortable with deep learning techniques.

-   Understanding the intuition behind the working of different models.

-   Generating large dataset including the ground truth of queries.

-   The above task is limited to single-document summarization.

Link to code base, dataset
==========================

-   Code and Dataset:\
    <https://github.com/group23IRE/diversity_based_attention>

-   Project Webpage:\
    <https://group23ire.github.io>

References
==========

-   Encoder -Decoder Model:\
    <https://cs224d.stanford.edu/reports/urvashik.pdf>

-   A neural attention model for abstractive text summarization\
    <https://arxiv.org/pdf/1509.00685.pdf>

-   TENSORFLOW RNN\
    <https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767>

-   <http://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html>

-   <https://arxiv.org/pdf/1409.0473v7.pdf>

-   <http://publications.lib.chalmers.se/records/fulltext/249908/249908.pdf>

-   <https://github.com/helmertz/querysum-data>

-   <https://github.com/helmertz/querysum>

-   <https://github.com/PrekshaNema25/diversity_based_attention>

-   <https://deeplearning4j.org/>
