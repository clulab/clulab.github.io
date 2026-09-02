---
layout: default
title: "Software"
order: 4
---

See our [github page](https://github.com/clulab) for all our projects.

#### [REACH](https://github.com/clulab/reach) ####
REACH stands for **Re**ading and **A**ssembling **C**ontextual
and **H**olistic Mechanisms from Text. In plain English, REACH is an
information extraction system for the biomedical domain, which aims to
read scientific literature and extract cancer signaling pathways.
REACH implements a fairly complete extraction pipeline, including:
recognition of biochemical entities (proteins, chemicals, etc.),
grounding them to known knowledge bases such as Uniprot, extraction of
BioPAX-like interactions, e.g., phosphorylation, complex assembly,
positive/negative regulations, and coreference resolution, for both
entities and interactions.

#### [Processors](https://github.com/clulab/processors) ####
This aims to be a one-stop place for natural language (NL) processors
and information extraction (IE) tools.
This package includes Odin, our rule-based IE framework.
For generic text preprocessing, we currently provide Scala APIs for Stanford's CoreNLP and maltparser.
This package also includes a full-fledged Rhetorical Structure Theory (RST) discourse parser,
and a machine learning package containing implementations for common algorithms
for both classification and ranking.

#### [Language of Food on Social Media](https://sites.google.com/site/twitter4food/) ####
This project investigates the data-driven connections between the language of food and multiple
ommunity characteristics, such as diabetes and overweight rate and geographic locale of authors.
We collected a corpus of over three million food-related posts from Twitter. Using these tweets,
we built a system that predicts various community characteristics, such as likelihood of a community to be more overweight
than average.

#### [Straw2Gold](http://www.surdeanu.info/mihai/papers/straw2gold.zip) ####
This archive contains the source code and some of the generated data from our *Spinning Straw into Gold:
Using Free Text to Train Monolingual Alignment Models for Non-factoid Question Answering* NAACL
2015 paper.

#### [Discourse for Question Answering](http://nlp.sista.arizona.edu/releases/acl2014/) ####
This archive contains the source code and data from our *Discourse Complements Lexical Semantics for
Non-factoid Answer Reranking* ACL 2014 paper.
