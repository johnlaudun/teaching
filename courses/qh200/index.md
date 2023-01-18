---
title: QH 200
nav_exclude: true
---

# Introduction to Text Analytics

##### John Laudun

## Course Design & Goals

Of the many dimensions that computation can address, perhaps one of the most difficult is the task of dealing with how humans actually use language. While a great deal can be gleaned from a variety of bounded events and actions--for example, by limiting the possible responses to a question, much more can be learned when we allow humans to produce the texts they wish to produce and then we as analysts set about finding better ways to understand them.

This course is designed to familiarize students with text analytics, from text processing to vector semantics. The course assumes that participants have a familiarity with the fundamental features of Python, the programming language we will be using to examine natural language. To be clear, most of our examples will be drawn from English, but some of our discussion will be focused on what it means to work across languages. We will also give some consideration to how a focus on English has shaped the development of NLP, which in turn has shaped what the functionality of many NLP operations available in Python and other programming languages.

The course sequence begins with a quick review of Python and basic text processing operations. From there we spend time with regular expressions, parsers, and state machines. After that, we take up the necessity of collecting data and then working with our data set to answer questions that arise from the data itself. As participants work through the course, they will be expected to:

* understand the basics of string operations and text processing in Python
* build upon those basics to develop approaches to text processing

We will use a variety of data sets throughout the course, and it is expected that those data sets, also known as corpora in some instances, will act as models/examples for you to build your own.

## Requirements

We will read broadly from corpus linguistics, corpus stylistics, and information and data science essays and texts. Successful participation requires that you keep up with the reading. In addition to participation, this course also requires a number of exams as well as a course project which consists of a portfolio of pieces which you will assemble across the span of the course: a curated data set, a set of useful algorithms that process the texts, 3 visualizations of the material, and a short paper of 2000 words that describes a facet of the data set and your exploration.

## Schedule

### On Quantification

We begin with a quick review of what it means to *quantify* something or a collection of somethings: what, how, why we count. While there are a number of texts we could read, including Cathy O’Neil’s _Weapons of Math Destruction_ and Brandeis Hill Marshall’s _Data Conscience_, we will focus our discussion on _A Primer on Powerful Numbers: Selected Readings in the Social Study of Publc Data and Official Numbers_, which is available from [Data & Society](https://datasociety.net/library/a-primer-on-powerful-numbers-selected-readings-in-the-social-study-of-public-data-and-official-numbers/). 

### Text Basics

* The ["The Zipf Mystery"](https://www.youtube.com/watch?v=fCn8zs912OE).

### Python Basics

In the initial module of the course, we take up the basics of a language like Python, with an eye to identifying essential **techniques and patterns** and being familiar with and using the **standard modules**. **Computing with strings** to everything else that occurs later in the course, and we must make sure that we understanding the relationships between **decision structures**, **loop structures**, and **Booleans** in relationship to strings. In regards to strings, we introduce concerns about **tokens** and **types**  in order to introduce questions about **parsing**.

### Basic String Operations

There is always the temptation to use "the shiny," whatever that is in a current moment, but everything shiny was built on top of the standard modules, and it's always a good idea to ask if you can accomplish a given task or goal using simpler techniques, both because you control what happens but also because you understand what happens. This unit focuses common problems in text processing that can be solved rather readily using techniques we discuss. With these basic recipes in hand, and the mindset to produce them, you should be able to adapt them to more complex problems.

### Regular Expressions

If regular expressions were easy, there would not be so many books and sites dedicated to explaining them or making it easy to develop regex without actually understanding it. This short unit explains the essentials of regex, with a lot of examples of different kinds of problems, e.g. lookaheads, on which to work. The goal is to have a place to begin asking the right questions, not necessarily always to have the right answer.

* [A Short History and Explanation of GREP](https://www.youtube.com/watch?v=NTfOnGZUZDk).

### Parsers & State Machines

So far in this course we have dealt with strings as flat texts—that is, as if everything within them lies at the same formal or semantic level. Anyone who has ever struggled with a sentence diagram knows that is not the case when it comes to even simple strings like sentences, let along more complex ones. In this unit, we will consider how to deal with texts that (at least appear to) possess a deeper structure than the linear sequence of bytes that make up strings. In some text processing instances, how we handle a part of a text needs to be *stateful*: it needs to be aware of what has come before. In those moments, we need to develop state machines.

### Frequencies

It may or may not surprise you that a great deal of analysis done on texts and large collections of texts, which when more structured are sometimes called *corpora*, is based on little more than counting. Counting and normalizing in order to arrive at frequencies. We will begin with frequencies, expand to word pairs, which will allow us to build toward concordances and collocations in the next unit.

### Concordances & Collocations

Concordances and collocations, unlike the co-occurences we explored in the previous unit, begin to highlight the dimension of texts upon which most of depend, their sequentiality, aka their discursive nature.

Rusu, Delia, Lorand Dali, Blaz Fortuna, Marko Grobelnik, and Dunja Mladenic. 2007. Triplet Extraction from Sentences. *Proceedings of the 10th International Multiconference Information Society*: 8–12.

### Sentiment Analysis

Clark, Eric M, Ted James, Chris A Jones, Amulya Alapati, Promise Ukandu, Christopher M Danforth, and Peter Sheridan Dodds. 2018. A Sentiment Analysis of Breast Cancer Treatment Experiences and Healthcare Perceptions Across Twitter. *arXiv preprint arXiv:1805.09959*

Frank, MR, L Mitchell, PS Dodds, and CM Danforth. 2013. Happiness and the Patterns of Life: A Study of Geolocated Tweets. *Sci Rep* 3 2625.

Gao, Jianbo, Matthew L Jockers, John Laudun, and Timothy Tangherlini. A Multiscale Theory for Sentiment Variation in Novels.

Keith, Ellyn Rolleston. 2017. A Sentiment Analysis of Language & Gender Using Word Embedding Models.

Mohammad, Saif. 2011. From Once Upon a Time to Happily Ever After: Tracking Emotions in Novels and Fairy Tales. Proceedings of the 5th ACL-HLT Workshop on Language Technology for Cultural Heritage, Social Sciences, and Humanities 105–14.

### Figurative Language Detection: Metaphors & Sarcasm

Burfoot, Clint, and Timothy Baldwin. 2009. Automatic Satire Detection: Are You Having a Laugh. *Proceedings of the ACL-IJCNLP*: 161–64.

Reyes, Antonio, Paolo Rosso, and Davide Buscaldi. 2012. From Humor Recognition to Irony Detection: The Figurative Language of Social Media. *Data & Knowledge Engineering* 74 1–12.

The shared tasks of[FigLang2020](https://sites.google.com/view/figlang2020/shared-tasks) gives us some idea of where we are going. Be sure to check out their competition: [CodaLab](https://competitions.codalab.org/competitions/22188).

Metaphors is a form of figurative language used pervasively in our everyday lives. Consider the following examples:

... it would change the **trajectory** of your legal career ...

... Washington and the media just **explodes** on you, you just don’t know where you are at the moment ...

... those statements are **deeply** concerning ...

... Out of the abundance of the heart, the mouth speaks, and the hand **tweets** ...

... the fake news were personalized and delivered above the **radar** and beyond the **radar** ...

The goal in this shared task is to detect, at word level, all content-word metaphors in a given text (we will also have a separate evaluation for just the verbs, as many researchers are working specifically on verb metaphors).
