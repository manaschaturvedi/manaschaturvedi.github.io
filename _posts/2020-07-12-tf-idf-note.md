---
layout: post
title: "TF-IDF"
date: 2020-07-12
tags: [notes, NLP]
---

<p>Tf-idf stands for term frequency-inverse document frequency</p>

<p>The tf-idf weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus</p>

<p>The tf-idf weight is composed by two terms: the first computes the normalized <strong>Term Frequency (TF)</strong>, aka. the number of times a word appears in a document, divided by the total number of words in that document; the second term is the <strong>Inverse Document Frequency (IDF)</strong>, computed as the logarithm of the number of the documents in the corpus divided by the number of documents where the specific term appears</p>

- ![https://s3.us-west-2.amazonaws.com/secure.notion-static.com/b5786889-3426-4a59-8e42-59f7a851935a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200712%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200712T001716Z&X-Amz-Expires=86400&X-Amz-Signature=382096ce45daa99255e3046908123d0e89207b3e71cdae672c60c2d10155892a&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/b5786889-3426-4a59-8e42-59f7a851935a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200712%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200712T001716Z&X-Amz-Expires=86400&X-Amz-Signature=382096ce45daa99255e3046908123d0e89207b3e71cdae672c60c2d10155892a&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

- ![https://s3.us-west-2.amazonaws.com/secure.notion-static.com/857d7ae7-d91a-4339-98f9-769d35c1464e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200712%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200712T001754Z&X-Amz-Expires=86400&X-Amz-Signature=4b8a9c17181fa3986d8c4af979653fe1505bcde46a944b068888bdf73432c64c&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/857d7ae7-d91a-4339-98f9-769d35c1464e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200712%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200712T001754Z&X-Amz-Expires=86400&X-Amz-Signature=4b8a9c17181fa3986d8c4af979653fe1505bcde46a944b068888bdf73432c64c&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)