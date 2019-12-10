# Embeddings for NLP and IR
## General Info
```
Where: NIT, Silchar
When: 
Who: Cristina España i Bonet
What: 
```

## [Calendar](../calendar.md)

## Objectives

### Knowledge
1. General notion of semantic representations of linguistic elements
2. Word embeddings, sentence embeddings and multilingual embeddings
3. Applications of embeddings to several NLP/IR tasks
4. Hands-on: using and evaluating embeddings in simple NLP tasks
5. Oral presentations

### Prerequisites
1. Basics of linear algebra
2. Basics of neural networks
3. Basic knowledge of python and notebooks (packages like gensim, nltk, sklearn and matplotlib)
3. Laptop with the possibility of using Google Colab if higher resources needed
<br>

## Course Structure

Please, <span style="color:red"> add your preferences </span> so that I can better distribute the second part of the course. Add your name under the different topics in the [<span style="color:red">document</span>](https://docs.google.com/document/d/1DkSnehmbL8S-PMgmScXW-Y5kSQCTrLf5NzQUcy7w4pY/edit?usp=sharing) following the instructions there.

#### Part I: Background knowledge 

* D1-M: Introduction to the course [[slides]](./)
* D1-M: Introduction to word embeddings [[slides]](./introWE.pdf)
* D1-A: How to do an oral presentation [[slides]](./oral.pdf)
* D1-A: Discussion on students talks, groups and structure
<br>

* D2-M: Introduction to PCA, SVD and others [[slides]](./introPCA.pdf)
* D2-M: Practical exercise word embeddings (set-up, bring your laptop with python!)
* D2-A: Practical exercise word embeddings 
<br>

* D3-M: Transformer architecture
* D3-M: Introduction to contextual embeddings
* D3-A: Introduction to contextual embeddings (ctd)
* D3-A: Practical exercise contextual embeddings (set-up, bring your laptop with python!)
<br>

* D4-M: Practical exercise contextual embeddings (ctd)
* D4-A: Introduction to multilingual embeddings
<br>

#### Part II: Embeddings, basic typologies and state of the art 
##### (Presentations by students)

The last 6 days of lectures will follow the **structure**:
* Morning: **presentations** by students on a specific topic
* Afternoon: End of the presentations and **exercises/discussion** on the day topic (all together)

#### D5: Evaluation of embeddings

* Amir Bakarov. 2018. Survey of Word Embeddings Evaluation Methods. _arXiv_.
 [[pdf]](https://arxiv.org/pdf/1801.09536.pdf)

* Tobias Schnabel, Igor Labutov, David Mimno, Thorsten Joachims. 2015. Evaluation methods for unsupervised word embeddings. _Conference on Empirical Methods in Natural Language Processing (EMNLP)_. Pages 298-307. [[pdf]](https://www.aclweb.org/anthology/D15-1036.pdf)

* Bin Wang, Angela Wang, Fenxiao Chen, Yuncheng Wang. 2019. Evaluating word embedding models: Methods and experimental results. _APSIPA Transactions on Signal and Information Processing_. Vol. 8, E19.  [[pdf]](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/EDF43F837150B94E71DBB36B28B85E79/S204877031900012Xa.pdf/evaluating_word_embedding_models_methods_and_experimental_results.pdf)

* TO BE ADDED

#### D6: Word2vec

* Tomas Mikolov, Kai Chen, Greg Corrado and Jeffrey Dean. 2013. Efficient Estimation of Word Representations in Vector Space. 
_Proceedings of the Workshop at International Conference on Learning Representations (ICLR)_. Pages 1-12. [[pdf]](https://arxiv.org/pdf/1301.3781)

* Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado and Jeffrey Dean. 2013. Distributed Representations of Words and Phrases and their Compositionality. _Advances in Neural Information Processing Systems 26_.  Pages 3111-3119. [[pdf]](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)

* Xin Rong. 2014. word2vec Parameter Learning Explained.
_arXiv_ [[pdf]](https://arxiv.org/abs/1411.2738)

* Tomas Mikolov, Quoc V. Le and Ilya Sutskever. 2014. Exploiting Similarities among Languages for Machine Translation. _CoRR, abs/1309.4168_. [[pdf]](https://arxiv.org/pdf/1309.4168.pdf)

* Quoc V. Le and Tomas Mikolov. (2014). Distributed Representations of Sentences and Documents. 
_Proceedings of the 31st International Conference on Machine Learning, in PMLR_ 32(2). Pages 1188-1196. [[pdf]](http://proceedings.mlr.press/v32/le14.pdf)


#### D7: GloVe & fastText

* Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. GloVe: Global Vectors for Word Representation. _Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)_.  Pages 1532-1543.
[[pdf]](https://nlp.stanford.edu/pubs/glove.pdf)

* Piotr Bojanowski, Edouard Grave, Armand Joulin, Tomas Mikolov. 2017. Enriching Word Vectors with Subword Information. _Transactions of the Association for Computational Linguistics_. Vol 5. Pages 135-146.
[[pdf]](http://aclweb.org/anthology/Q17-1010)

* Edouard Grave, Piotr Bojanowski, Prakhar Gupta, Armand Joulin, Tomas Mikolov. 2018. Learning Word Vectors for 157 Languages. _Proceedings of the International Conference on Language Resources and Evaluation (LREC 2018)_.
[[pdf]](http://www.lrec-conf.org/proceedings/lrec2018/pdf/627.pdf)

* Ben Athiwaratkun, Andrew Wilson, Anima Anandkumar. (2018). Probabilistic FastText for Multi-Sense Word Embeddings. _56th Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 1-11. [[pdf]](https://www.aclweb.org/anthology/P18-1001)

* TO BE ADDED

#### D8: Multilingual embeddings

* Manaal Faruqui and Chris Dyer. (2014). Improving Vector Space Word Representations Using Multilingual Correlation. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_. Vol. 1. Pages 789-798. [[pdf]](https://www.aclweb.org/anthology/E14-1049)

* Mikel Artetxe, Gorka Labaka, Eneko Agirre. (2018). A robust self-learning method for fully unsupervised cross-lingual mappings of word embeddings. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_. Vol. 1. Pages 789-798. [[pdf]](http://aclweb.org/anthology/P18-1073)

* Alexis Conneau, Guillaume Lample, Marc'Aurelio Ranzato, Ludovic Denoyer and Hervé Jégou. (2018). Word Translation Without Parallel Data. _ International Conference on Learning Representations (ICLR 2018)_. [[pdf]](https://arxiv.org/pdf/1710.04087.pdf)

* TO BE ADDED


#### D9: Contextual embeddings

* Alexis Conneau, Douwe Kiela, Holger Schwenk, Loic Barrault, Antoine Bordes. (2017). Supervised Learning of Universal Sentence Representations from Natural Language Inference Data. _Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing (EMNLP)_. Pages 670-680. [[pdf]](https://www.aclweb.org/anthology/D17-1070)

* Matthew E. Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, Luke Zettlemoyer. 2018. Deep contextualized word representations. _Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_. Vol. 1. Pages 2227-2237.
[[pdf]](http://aclweb.org/anthology/N18-1202)

* Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova. 2018. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. _arXiv_ [[pdf]](https://arxiv.org/abs/1810.04805)

* Alan Akbik, Duncan Blythe, Roland Vollgraf. Contextual String Embeddings for Sequence Labeling. 2018. _Proceedings of the 27th International Conference on Computational Linguistics_. Pages 1638-1649.
[[pdf]](http://aclweb.org/anthology/C18-1139)

* TO BE ADDED


#### D10: Miscellaneous

* Chengyue Gong, Di He, Xu Tan, Tao Qin, Liwei Wang and Tie-Yan Liu. (2018). FRAGE: Frequency-Agnostic Word Representation. _32nd Conference on Neural Information Processing Systems (NeurIPS 2018)_. [[pdf]](https://papers.nips.cc/paper/7408-frage-frequency-agnostic-word-representation.pdf)

* Jiaqi Mu, Suma Bhat, Pramod Viswanath. (2018). All-but-the-Top: Simple and Effective Postprocessing for Word Representations. _International Conference on Learning Representations (ICLR)_. [[pdf]](https://arxiv.org/pdf/1702.01417.pdf)

* Goran Glavaš, Ivan Vulić. (2018). Explicit Retrofitting of Distributional Word Vectors. _56th Annual Meeting of the Association for Computational Linguistics (ACL)_. Vol. 1. Pages 34-45. [[pdf]](https://www.aclweb.org/anthology/P18-1004)

* Kawin Ethayarajh. (2019). How Contextual are Contextualized Word Representations? Comparing the Geometry of BERT, ELMo, and GPT-2 Embeddings. _Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)_. Pages 55-65.
[[pdf]](https://www.aclweb.org/anthology/D19-1006.pdf)

* **Add your favourite paper you'd like to discuss!**

* TO BE ADDED




