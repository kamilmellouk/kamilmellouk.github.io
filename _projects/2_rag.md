---
layout: page
title: DPO-finetuned RAG-augmented LLM for answering scientific MCQs
description: A project that integrates Direct Preference Optimization (DPO) and Retrieval-Augmented Generation (RAG) to develop an AI tutor for EPFL’s demanding curriculum.
img: assets/img/rag.png
importance: 2
category: past
giscus_comments: false
---
This project explores the development of an AI tutor tailored to EPFL’s curriculum, integrating Direct Preference Optimization (DPO) and Retrieval-Augmented Generation (RAG) to enhance the AI’s performance. The DPO process incorporates human preferences into the training, ensuring that the AI prioritizes desirable outcomes. RAG addresses issues like hallucinations and reliance on outdated data, enabling more accurate responses by retrieving relevant, up-to-date information.

We compared two models, Facebook’s Galactica and EleutherAI’s Pythia, and found that Galactica demonstrated superior accuracy in multiple-choice question (MCQ) answering tasks, especially when augmented with RAG. The project also included an in-depth ethical analysis, discussing potential academic misuse and ensuring inclusivity through multilingual support.

<div class="row"> <div class="col-sm mt-3 mt-md-0"> {% include figure.liquid loading="eager" path="assets/img/rag.png" title="RAG framework architecture" class="img-fluid rounded z-depth-1" %} </div> </div> <div class="caption"> RAG framework architecture </div>