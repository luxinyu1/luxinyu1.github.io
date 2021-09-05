---
title: "An Unsupervised Method for Building Sentence Simplification corpora in Multiple Languages"
collection: publications
permalink: /publication/an-unsupervised-method-for-building-sentence-simplification-corpora-in-multiple-languages
excerpt: ''
date: 2021-8-25
authors: Xinyu Lu, Jipeng Qiang, Yun Li, Yunhao Yuan and Yi Zhu
venue: 'The 2021 Conference on Empirical Methods in Natural Language Processing'
paperurl: 'https://arxiv.org/pdf/2109.00165.pdf'
citation: ''
---

The availability of parallel sentence simplification (SS) is scarce for neural SS modelings. We propose an unsupervised method to build SS corpora from large-scale bilingual translation corpora, alleviating the need for SS supervised corpora. Our method is motivated by the following two findings: neural machine translation model usually tends to generate more high-frequency tokens and the difference of text complexity levels exists between the source and target language of a translation corpus. By taking the pair of the source sentences of translation corpus and the translations of their references in a bridge language, we can construct large-scale pseudo parallel SS data. Then, we keep these sentence pairs with a higher complexity difference as SS sentence pairs. The building SS corpora with an unsupervised approach can satisfy the expectations that the aligned sentences preserve the same meanings and have difference in text complexity levels. Experimental results show that SS methods trained by our corpora achieve the state-of-the-art results and significantly outperform the results on English benchmark WikiLarge. 