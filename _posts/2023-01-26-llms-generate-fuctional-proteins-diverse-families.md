---
title: "Large language models generate functional protein sequences across diverse families"
author: greene-eric
publication: true
journal: "Nature Biotechnology"
citation: "41, 1099–1106 (2023)"
doi: "10.1038/s41587-022-01618-2"
authors:
  - Ali Madani
  - Ben Krause
  - Eric R. Greene
  - Subu Subramanian
  - Benjamin P. Mohr
  - James M. Holton
  - Jose Luis Olmos Jr.
  - Caiming Xiong
  - Zachary Z. Sun
  - Richard Socher
  - James S. Fraser
  - Nikhil Naik
abstract: "Deep-learning language models have shown promise in various biotechnological applications, including protein design and engineering. Here we describe ProGen, a language model that can generate protein sequences with a predictable function across large protein families, akin to generating grammatically and semantically correct natural language sentences on diverse topics. The model was trained on 280 million protein sequences from >19,000 families and is augmented with control tags specifying protein properties. ProGen can be further fine-tuned to curated sequences and tags to improve controllable generation performance of proteins from families with sufficient homologous samples. Artificial proteins fine-tuned to five distinct lysozyme families showed similar catalytic efficiencies as natural lysozymes, with sequence identity to natural proteins as low as 31.4%. ProGen is readily adapted to diverse protein families, as we demonstrate with chorismate mutase and malate dehydrogenase."
pdbs:
  - 7RGR
categories:
  - posts
tags:
  - deep learning
  - structures
---

We recently published ["{{page.title}}"](https://doi.org/{{page.doi}}) in *{{page.journal}}*.

{{page.abstract}}
