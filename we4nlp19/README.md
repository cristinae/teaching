# Embeddings for NLP and IR
## General Info
```
Where: Building C7.2, Room -1.05
When: Wednesdays 8:30-10:00 (2h sessions for Part II)
Who: Cristina España i Bonet (and Koel Dutta)
What: 
```

## [Calendar](../calendar.md)

## Objectives

### Knowledge
1. General notion of semantic representations of linguistic elements
2. Focus on word embeddings (WE) as semantic representations
3. Applications of WE to several NLP/IR tasks
4. From words to sentences to documents to multimodal

### Scientific Presentations
1. Oral Presentation (W4) [[slides]](./oral.pdf)
2. Technical Paper [[slides]](./paper.pdf)
<br>

## Course Structure

#### Part I: Background knowledge

* W1: Introduction to the course [[slides]](./introCourse.pdf)

**3 weeks** (lectures in the classical way)
* W2: Introduction to embeddings [[slides]](./introWE.pdf)
* W3: Practical exercise (bring your laptop with python!)
* W4: Introduction to PCA, SVD and others [[slides]](./introPCA.pdf)


#### Part II: Embeddings, basic typologies and state of the art

**1 presentation per student** (group topics, selected papers below)

* W5, W6, W7, W8:  Chose a [[topic]](https://doodle.com/poll/re3ksp9t9sqv9xwb)

#### Part III: Advanced notions and embeddings in action 

**1 presentation per student** (2 people per paper, selected papers below, or a chosen paper from ACL, EMNLP, ICLR -consulted otherwise)

<br>

## References

### Word Embeddings, basic typologies

Seed papers for presentations:
 
#### word2vec

* Tomas Mikolov, Kai Chen, Greg Corrado and Jeffrey Dean. 2013. Efficient Estimation of Word Representations in Vector Space. 
_Proceedings of the Workshop at International Conference on Learning Representations (ICLR)_. Pages 1-12. [[pdf]](https://arxiv.org/pdf/1301.3781)

* Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado and Jeffrey Dean. 2013. Distributed Representations of Words and Phrases and their Compositionality. _Advances in Neural Information Processing Systems 26_.  Pages 3111-3119. [[pdf]](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)

* Xin Rong. 2014. word2vec Parameter Learning Explained.
_arXiv_ [[pdf]](https://arxiv.org/abs/1411.2738)

* Tomas Mikolov, Quoc V. Le and Ilya Sutskever. 2014. Exploiting Similarities among Languages for Machine Translation. _CoRR, abs/1309.4168_. [[pdf]](https://arxiv.org/pdf/1309.4168.pdf)


<span style="color:green"> 22/05/2019 (2h) - Lisa Kluge, Jesujoba Alabi, Kwabena Amponsah, Daria Pylypenko, Morgan Wixted [[slides]](./slides2019/w2v.pdf)</span>

#### GloVe

* Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. GloVe: Global Vectors for Word Representation. _Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)_.  Pages 1532-1543.
[[pdf]](https://nlp.stanford.edu/pubs/glove.pdf)

#### Fastext

* Piotr Bojanowski, Edouard Grave, Armand Joulin, Tomas Mikolov. 2017. Enriching Word Vectors with Subword Information. _Transactions of the Association for Computational Linguistics_. Vol 5. Pages 135-146.
[[pdf]](http://aclweb.org/anthology/Q17-1010)

<span style="color:green"> 29/05/2019 (1h45) - Egla Hajdini, Nora Graichen, Aqsa Nazir, Insa Kröger [[slides]](./slides2019/GloVeFastText.pdf)</span>

#### ELMo, BERT, OpenAI-GTP and Family

* Matthew E. Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, Luke Zettlemoyer. 2018. Deep contextualized word representations. _Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_. Vol. 1. Pages 2227-2237.
[[pdf]](http://aclweb.org/anthology/N18-1202)

* Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova. 2018. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. _arXiv_ [[pdf]](https://arxiv.org/abs/1810.04805)

* Alan Akbik, Duncan Blythe, Roland Vollgraf. Contextual String Embeddings for Sequence Labeling. 2018. _Proceedings of the 27th International Conference on Computational Linguistics_. Pages 1638-1649.
[[pdf]](http://aclweb.org/anthology/C18-1139)

<span style="color:green"> 05/06/2019 (2h) - Vanessa Hahn, Tatiana Anikina, Marc Altmeyer, Sourav Dutta  [[slides]](./slides2019/Embeddings.pptx)</span>

#### Multilingual embeddings

* Manaal Faruqui and Chris Dyer. (2014). Improving Vector Space Word Representations Using Multilingual Correlation. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_. Vol. 1. Pages 789-798. [[pdf]](https://www.aclweb.org/anthology/E14-1049)

* Mikel Artetxe, Gorka Labaka, Eneko Agirre. (2018). A robust self-learning method for fully unsupervised cross-lingual mappings of word embeddings. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_. Vol. 1. Pages 789-798. [[pdf]](http://aclweb.org/anthology/P18-1073)

* Alexis Conneau, Guillaume Lample, Marc'Aurelio Ranzato, Ludovic Denoyer and Hervé Jégou. (2018). Word Translation Without Parallel Data. _ International Conference on Learning Representations (ICLR 2018)_. [[pdf]](https://arxiv.org/pdf/1710.04087.pdf)

<span style="color:green"> 12/06/2019 (1h45m) - Susann Boy, Kathryn Chapman, Natalia Skachkova, Guadalupe Romero [[slides]](./slides2019/multilingual_embeddings.pdf)</span>


### Advanced Notions and Applications

<span style="color:red"> Provisional, you can add! </span>

* Chengyue Gong, Di He, Xu Tan, Tao Qin, Liwei Wang and Tie-Yan Liu. (2018). FRAGE: Frequency-Agnostic Word Representation. _32nd Conference on Neural Information Processing Systems (NeurIPS 2018)_. [[pdf]](https://papers.nips.cc/paper/7408-frage-frequency-agnostic-word-representation.pdf)

* Quoc V. Le and Tomas Mikolov. (2014). Distributed Representations of Sentences and Documents. 
_Proceedings of the 31st International Conference on Machine Learning, in PMLR_ 32(2). Pages 1188-1196. [[pdf]](http://proceedings.mlr.press/v32/le14.pdf)

* Xinxiong Chen, Lei Xu, Zhiyuan Liu, Maosong Sun and Huanbo Luan. (2015). Joint Learning of Character and Word Embeddings.
_Proceedings of the Twenty-Fourth International Joint Conference on Artificial Intelligence (IJCAI)_. Pages 1236-1242. [[pdf]](https://www.ijcai.org/Proceedings/15/Papers/178.pdf)
<span style="color:green"> ASSIGNED: Jesujoba Alabi, SOMEONE ELSE!! [[slides]](./slides2019/)</span>

* Ben Athiwaratkun, Andrew Wilson, Anima Anandkumar. (2018). Probabilistic FastText for Multi-Sense Word Embeddings. _56th Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 1-11. [[pdf]](https://www.aclweb.org/anthology/P18-1001)

* Jiaqi Mu, Suma Bhat, Pramod Viswanath. (2018). All-but-the-Top: Simple and Effective Postprocessing for Word Representations. _International Conference on Learning Representations (ICLR)_. [[pdf]](https://arxiv.org/pdf/1702.01417.pdf)

* Goran Glavaš, Ivan Vulić. (2018). Explicit Retrofitting of Distributional Word Vectors. _56th Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 34-45. [[pdf]](https://www.aclweb.org/anthology/P18-1004)

* Alexis Conneau, Douwe Kiela, Holger Schwenk, Loic Barrault, Antoine Bordes. (2017). Supervised Learning of Universal Sentence Representations from Natural Language Inference Data. _Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing (EMNLP)_. Pages 670-680. [[pdf]](https://www.aclweb.org/anthology/D17-1070)

* Dani Yogatama, Cyprien de Masson d'Autume, Jerome Connor, Tomás Kociský, Mike Chrzanowski, Lingpeng Kong, Angeliki Lazaridou, Wang Ling, Lei Yu, Chris Dyer, Phil Blunsom. (2019). Learning and Evaluating General Linguistic Intelligence. [[pdf]](https://arxiv.org/pdf/1901.11373.pdf) <span style="color:green"> ASSIGNED: Marc Altmeyer, Susann Boy [[slides]](./slides2019/)</span>

* Tolga Bolukbasi, Kai-Wei Chang, James Zou, Venkatesh Saligrama, Adam Kalai. (2017). Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings [[pdf]](https://arxiv.org/abs/1607.06520) <span style="color:green"> ASSIGNED: Vanessa Hahn, Kathryn Chapman [[slides]](./slides2019/)</span>

* Jieyu Zhao, Yichao Zhou, Zeyu Li, Wei Wang, Kai-Wei Chang. (2018). Learning Gender-Neutral Word Embeddings [[pdf]](https://arxiv.org/abs/1809.01496) <span style="color:green"> ASSIGNED: Vanessa Hahn, Kathryn Chapman [[slides]](./slides2019/)</span>

* Maximilian Nickel, Douwe Kiela. (2017). Poincaré Embeddings for Learning Hierarchical Representations. _eprint arXiv:1705.08039_. [[pdf]](https://arxiv.org/pdf/1705.08039.pdf)  <span style="color:green"> ASSIGNED: Tatiana Anikina, Natalia Skachkova [[slides]](./slides2019/)</span>

* Anders Søgaard, Zeljko Agic, Hector Martinez Alonso, Barbara Plank, Bernd Bohnet. (2015). Inverted indexing for cross-lingual NLP.  _53rd Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 1713-1722. [[pdf]](http://www.aclweb.org/anthology/P15-1165)

* Sanjeev Arora, Yuanzhi Li, Yingyu Liang, Tengyu Ma, Andrej Risteski. (2016). A Latent Variable Model Approach to PMI-based Word Embeddings.  _Transactions of the Association for Computational Linguistics_. Vol. 4. Pages 385–399. [[pdf]](https://www.transacl.org/ojs/index.php/tacl/article/download/742/204)

* Christopher E Moody. (2016) Mixing Dirichlet Topic Models and Word Embeddings to Make lda2vec. _eprint arXiv:1605.02019_. [[pdf]](https://arxiv.org/pdf/1605.02019.pdf) 
<span style="color:green"> ASSIGNED: Nora Graichen, Insa Kröger [[slides]](./slides2019/)</span>

* Lucie Flekova and Iryna Gurevych. (2016). Supersense Embeddings: A Unified Model for Supersense Interpretation, Prediction, and Utilization.
_Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics_. Pages 2029-2041. [[pdf]](http://www.aclweb.org/anthology/P16-1191)

* Massimiliano Mancini, Jose Camacho-Collados, Ignacio Iacobacci and Roberto Navigli. (2017). Embedding Words and Senses Together via Joint Knowledge-Enhanced Training.
_Proceedings of the 21st Conference on Computational Natural Language Learning (CoNLL 2017)_. Pages 100–111. [[pdf]](https://www.aclweb.org/anthology/K/K17/K17-1012.pdf)
<span style="color:green"> ASSIGNED: Morgan Wixted, Lisa Kluge [[slides]](./slides2019/)</span>


<br>

## Term Paper

The topic <span style="color:red"> **must** </span> be agreed in advance

### Topics

* Option 1: Analysis of Word Embeddings according to Corpus Size and Domain/Language (use Wikipedia dumps)

* Option 2: Word Embeddings with Multiword Expressions (use Wikipedia dumps)

* Option 3: Contextual Embeddings in use (pretrained contextual embeddings for an NLP task of your choice)

* Option 4: Other (ask/propose!)


### Format

8 pages paper in ACL format

[LaTeX template](http://acl2017.org/downloads/acl17-latex.zip)


### Deadline

<span style="color:red"> TBD </span>
