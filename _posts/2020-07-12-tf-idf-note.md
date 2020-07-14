---
layout: post
title: "TF-IDF"
date: 2020-07-12
tags: [notes, NLP]
---

<p>Tf-idf stands for term frequency-inverse document frequency</p>

<p>The tf-idf weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus</p>

<p>The tf-idf weight is composed by two terms: the first computes the normalized <strong>Term Frequency (TF)</strong>, aka. the number of times a word appears in a document, divided by the total number of words in that document; the second term is the <strong>Inverse Document Frequency (IDF)</strong>, computed as the logarithm of the number of the documents in the corpus divided by the number of documents where the specific term appears</p>

![TF IDF](/assets/tf_idf_1.png)

![TF IDF](/assets/tf_idf_2.png)