# Word Embeddings for NLP and IR
## General Info
```
Where: Building C7.2, U15
When: T??
Who: Cristina España i Bonet
What: 
```

[Calendar](../calendar.md)

## Objectives

### Knowledge
1. General notion of semantic representations of linguistic elements
2. Focus on word embeddings (WE) as semantic representations
3. Applications of WE to several NLP/IR tasks
4. From words to sentences to documents to multimodal

### Scientific Presentations
1. Oral Presentation [[slides]](./oral.pdf)
2. Technical Paper [[slides]](./paper.pdf)
<br>

## Course Structure

* Background knowledge

* Word Embeddings, basic typologies
1 presentation per student (selected papers below)

* Embeddings, advanced notions
1 presentation per student (selected papers below)

* Embeddings in action
1 presentation per student (papers must be selected from ACL, EMNLP or consulted otherwise)

## References

(Provisional: the papers and its distribution depend on the number of students)

### Word Embeddings, basic typologies
 
#### word2vec

* MAIN: Tomas Mikolov, Kai Chen, Greg Corrado and Jeffrey Dean. 2013. Efficient Estimation of Word Representations in Vector Space. 
_Proceedings of the Workshop at International Conference on Learning Representations (ICLR)_. Pages 1-12. [[pdf]](https://arxiv.org/pdf/1301.3781)

* RELATED: Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado and Jeffrey Dean. 2013. Distributed Representations of Words and Phrases and their Compositionality. _Advances in Neural Information Processing Systems 26_.  Pages 3111-3119. [[pdf]](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)

* STEP BY STEP: Xin Rong. 2014. word2vec Parameter Learning Explained.
_arXiv_ [[pdf]](https://arxiv.org/abs/1411.2738)

<br><span style="color:green"> team work, date TBD  [[slides]](./slides2019/)</span>

#### GloVe

* Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. GloVe: Global Vectors for Word Representation. _Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)_.  Pages 1532-1543.
[[pdf]](https://nlp.stanford.edu/pubs/glove.pdf)
<br><span style="color:green"> 1 person, date TBD  [[slides]](./slides2019/)</span>

#### Fastext

* Piotr Bojanowski, Edouard Grave, Armand Joulin, Tomas Mikolov. 2017. Enriching Word Vectors with Subword Information. _Transactions of the Association for Computational Linguistics_. Vol 5. Pages 135-146.
[[pdf]](http://aclweb.org/anthology/Q17-1010)
<br><span style="color:green"> 1 person, date TBD  [[slides]](./slides2019/)</span>

#### ELMo, BERT and Family

* Matthew E. Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, Luke Zettlemoyer. 2018. Deep contextualized word representations. _Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_. Vol. 1. Pages 2227-2237.
[[pdf]](http://aclweb.org/anthology/N18-1202)

* Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova. 2018. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. _arXiv_ [[pdf]](https://arxiv.org/abs/1810.04805)

* Alan Akbik, Duncan Blythe, Roland Vollgraf. Contextual String Embeddings for Sequence Labeling. 2018. _Proceedings of the 27th International Conference on Computational Linguistics_. Pages 1638-1649.
[[pdf]](http://aclweb.org/anthology/C18-1139)

<br><span style="color:green"> team work, date TBD  [[slides]](./slides2019/)</span>


### Advanced Notions

<span style="color:red"> Very provisional </span>

* Quoc V. Le and Tomas Mikolov. (2014). Distributed Representations of Sentences and Documents. 
_Proceedings of the 31st International Conference on Machine Learning, in PMLR_ 32(2). Pages 1188-1196. [[pdf]](http://proceedings.mlr.press/v32/le14.pdf)

* Xinxiong Chen, Lei Xu, Zhiyuan Liu, Maosong Sun and Huanbo Luan. (2015). Joint Learning of Character and Word Embeddings.
_Proceedings of the Twenty-Fourth International Joint Conference on Artificial Intelligence (IJCAI)_. Pages 1236-1242. [[pdf]](https://www.ijcai.org/Proceedings/15/Papers/178.pdf)

* Jiaqi Mu, Suma Bhat, Pramod Viswanath. (2018). All-but-the-Top: Simple and Effective Postprocessing for Word Representations. _International Conference on Learning Representations (ICLR)_. [[pdf]](https://arxiv.org/pdf/1702.01417.pdf)

* Anders Søgaard, Zeljko Agic, Hector Martinez Alonso, Barbara Plank, Bernd Bohnet. (2015). Inverted indexing for cross-lingual NLP.  _53rd Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 1713-1722. [[pdf]](http://www.aclweb.org/anthology/P15-1165)

* Sanjeev Arora, Yuanzhi Li, Yingyu Liang, Tengyu Ma, Andrej Risteski. (2016). A Latent Variable Model Approach to PMI-based Word Embeddings.  _Transactions of the Association for Computational Linguistics_. Vol. 4. Pages 385–399. [[pdf]](https://www.transacl.org/ojs/index.php/tacl/article/download/742/204)

* Maximilian Nickel, Douwe Kiela. (2017) Poincaré Embeddings for Learning Hierarchical Representations. _eprint arXiv:1705.08039_. [[pdf]](https://arxiv.org/pdf/1705.08039.pdf)

* Mikel Artetxe, Gorka Labaka, Eneko Agirre. (2018). A robust self-learning method for fully unsupervised cross-lingual mappings of word embeddings. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_. Vol. 1. Pages 789-798. [[pdf]](http://aclweb.org/anthology/P18-1073)

* Christopher E Moody. (2016) Mixing Dirichlet Topic Models and Word Embeddings to Make lda2vec. _eprint arXiv:1605.02019_. [[pdf]](https://arxiv.org/pdf/1605.02019.pdf)

* Lucie Flekova and Iryna Gurevych. (2016). Supersense Embeddings: A Unified Model for Supersense Interpretation, Prediction, and Utilization.
_Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics_. Pages 2029-2041. [[pdf]](http://www.aclweb.org/anthology/P16-1191)

* Massimiliano Mancini, Jose Camacho-Collados, Ignacio Iacobacci and Roberto Navigli. (2017). Embedding Words and Senses Together via Joint Knowledge-Enhanced Training.
_Proceedings of the 21st Conference on Computational Natural Language Learning (CoNLL 2017)_. Pages 100–111. [[pdf]](https://www.aclweb.org/anthology/K/K17/K17-1012.pdf)

* Shyam Upadhyay, Kai-Wei Chang, Matt Taddy, Adam Kalai and James Zou. (2017). Beyond Bilingual: Multi-sense Word Embeddings using Multilingual Context. 
_Proceedings of the 2nd Workshop on Representation Learning for NLP (RepL4NLP)_. Pages 139-145. Vancouver, Canada. [[pdf]](http://aclweb.org/anthology/W/W17/W17-2613.pdf)

* Ben Athiwaratkun and Andrew Gordon Wilson. (2017). Multimodal Word Distributions. 
_Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 1645-1656. Vancouver, Canada. [[pdf]](http://www.aclweb.org/anthology/P/P17/P17-1151.pdf)

* Spandana Gella, Rico Sennrich, Frank Keller and Mirella Lapata. (2017). Image Pivoting for Learning Multilingual Multimodal Representations. 
_Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing (EMNLP)_. Pages 2829-2835. Copenhagen, Denmark. [[pdf]](https://arxiv.org/pdf/1707.07601.pdf)


### Applications

Suggested papers will be added here



<br>
## Term Paper

The topic <span style="color:red"> must </span> be agreed in advance

### Topics

* Option 1: Analysis of Word Embeddings according to Corpus Size and Domain/Language

* Option 2: Word Embeddings with Multiword Expressions

* Option 3: Word Embeddings on Semantic Features

* Option 4: Other (ask/propose!)


### Format

8 pages paper in ACL format

[LaTeX template](http://acl2017.org/downloads/acl17-latex.zip)


### Deadline

<span style="color:red"> TBD </span>
