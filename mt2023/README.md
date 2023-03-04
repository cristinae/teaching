# Machine Translation
## General Info
```
Where: 
When: Mondays & Tuesdays, 16:15-17:45
Who: Cristina España-Bonet, Koel Dutta Chowdhury, Yasser Hamidullah
     
```

### See the course [calendar](../calendars/calendarMT.md)
<br>

## Objectives

The course gives an introduction to machine translation going from statistical to neural machine translation systems and paying special attention to the current state of the art which is almost 100% neural. A strong background on mathematics, statistics and machine learning is not required but a basic knowledge is expected to follow the course.
<br>

## Evaluation

The evaluation consists of 2 mandatory assignments (20%), a bonus (extra 10%!) and a final exam (80%):
* SMT assignment (lab week 5/6, deadline week 9)
* NMT assignment (lab week 11, deadline week 14)
* MT Challenge, the bonus (temptative, to discuss, week 15)
* Final exam: <span style="color:red"> TBD </span> 
* Resit exam: <span style="color:red"> TBD </span>
<br>


## Basic Bibliography

There is no textbook for the course, but you can find general information in the following references. More especific texts or slides will be provided for each session.

* Speech and Language Processing: An introduction to natural language processing, computational linguistics,
and speech recognition by Daniel Jurafsky & James H. Martin. 2007 [[Chapter 25]](.//slides2018/biblio/JurafskyMartinChap25Draft.pdf) [[New draft 3rd edition]](https://web.stanford.edu/~jurafsky/slp3/)
* Statistical Machine Translation book by Philipp Koehn [[slides]](http://www.statmt.org/book/)
* From SMT to NMT, three posts in a blog to understand the basics of NMT [[blog]](https://devblogs.nvidia.com/introduction-neural-machine-translation-with-gpus/)
* Chapter on Neural Machine Translation by Philipp Koehn [[pdf]](https://arxiv.org/pdf/1709.07809.pdf)
<br>

## Syllabus

### Week 1

Let's start! <br>

* Easter Monday
* All: Introduction to the course [[slides]](.//slides2023/lectures/) + Languages [[slides]](.//slides2018/lectures/2-introMThard.pdf) 

### Week 2

Why languages are difficult? Why MT evaluation is a challenge? <br>
Human evaluation vs. automatic evaluation. String matching automatic metrics and neural metrics.  <br>

* K1: MT Evaluation I 
* K2: MT Evaluation II
 

### Week 3 

What's machine translation about? Types of MT systems: rule-based, statistical and neural. <br>
A few words on statistical machine translation (SMT) and language models. Why in 2023!?  <br>

* C1: Introduction to MT [[slides]](.//slides2023/lectures/) 
* C2: Statistical Machine Translation I

### Week 4

More on SMT: IBM models, alignment, phrase tables and beam search. <br>

* May 1st
* C3: Statistical Machine Translation II

### Week 5

More on SMT: IBM models, alignment, phrase tables and beam search. <br>
And after that, let's put everything in practice! Hands on SMT. <br>

* C4: Statistical Machine Translation III
* C5: Lab1, Statistical Machine Translation [[guidelines]](.//slides2023/lectures/) 

### Week 6

Continue with our hands on. <br>
Transition to neural machine translation, word embeddings: the basic units. <br>

* C6: Lab1, Statistical Machine Translation [[guidelines]](.//slides2023/lectures/) 
* C7: Word embeddings


### Week 7
 
The basics of neural networks with relevance to machine translation. <br>

* K3: Neural networks for translation technologies I
* K4: Neural networks for translation technologies II


### Week 8

Serious neural networks stuff! <br>

* Whit Monday
* Y1: Backpropagation

### Week 9

* C8: Lab1 Q&A (on-site, bring your laptop!)
* C9: Evaluation (bring your laptop!) [[slides]](.//slides2018/lectures/7-MTEval.pdf) 
* <span style="color:red">01/05/2018 Deadline for Lab1 report</span>

* C10: Lab3, presentation [[slides]](.//slides2018/lectures/8-oralPresentation.pdf) 
<br>Chose a [[paper]](https://docs.google.com/document/d/1wtGHDMnnHmCnY6uv-9bRO4FfsRHZqRuCvYVfRaCp83A/edit?usp=sharing) 
<br>Chose a [[date]](https://doodle.com/poll/pzcv2bngb4hiv38u)
* R4: Neural Machine Translation [[slides]](http://raphael.rubino.free.fr/uds_summer2018_nmt4.pdf)
* R5: Neural Machine Translation [[slides]](http://raphael.rubino.free.fr/uds_summer2018_nmt5.pdf)
* R6: Lab2, Neural Machine Translation [[PDF]](http://raphael.rubino.free.fr/uds_summer2018_nmt_lab1.pdf)

### Week 10

* R7: Lab2, Neural Machine Translation 
* R8: Quality Estimation

### Week 11

* R9: Lab2 Q&A (on-site, bring your laptop!)
* R10: Selected Topics

### Week 12 

* 02/07/2018 Written Exam
<br>Chose a [[date]](https://doodle.com/poll/yx5pithafigxdkxa) for the Resit Exam 
* Free 

### Week 13

* *09/07/2018   Lab3: Student Presentations I*
<br> <br> 2:15-2:35 -- Matt Kuhn
<br> _Europarl: A Parallel Corpus for Statistical Machine Translation_  [[slides]](.//slides2018/students/matt.pptx) 
<br> 2:40-3:00 -- Tanja Bäumel
<br> _Beyond Parallel Data: Joint Word Alignment and Decipherment Improves Machine Translation_
<br> 3:05-3:25 -- Christine Schäfer
<br> _Phrase-Based & Neural Unsupervised Machine Translation_
<br> 3:30-3:50 -- Anastasija Amann
<br> _A Sense-Based Translation Model for Statistical Machine Translation_  [[slides]](.//slides2018/students/anastasija.pdf) 

 
* *11/07/2018   Lab3: Student Presentations II*
<br> <br> 2:05-2:25 -- Polina Stadnikova
<br> _Hierarchical Phrase-Based Translation_
<br> 2:25-2:45 -- Azin Zahraei
<br> _Hierarchical Phrase-Based Translation_
<br> 2:50-3:10 -- Kirstin Kolmorgen
<br> _Docent: A Document-Level Decoder for Phrase-Based Statistical Machine Translation_
<br> 3:15-3:35 -- Damyana Gateva
<br> _Exploiting cross-sentence context for neural machine translation_
<br> 3:40-4:00 -- Iza Škrjanec
<br> _Modeling Selectional Preferences of Verbs and Nouns in String-to-Tree Machine Translation_

### Week 14

* *16/07/2018   Lab3: Student Presentations III*
<br> <br> 2:15-2:35 -- Daria Pylypenko
<br> _Modeling Source Syntax for Neural Machine Translation_
<br> 2:40-3:00 -- Mario Magued Mina
<br> _Neural Machine Translation with Word Predictions_
<br> 3:05-3:25 -- Dominik Stammbach
<br> _Unsupervised Neural Machine Translation with Weight Sharing_
<br> 3:30-3:50 -- Yanzhe Guo  [[slides]](.//slides2018/students/yanzhe.pptm) 
<br> _Lattice-Based Recurrent Neural Network Encoders for Neural Machine Translation_

 
* *18/07/2018   Lab3: Student Presentations IV*
<br><br> 2:00-2:20 -- Tanja Bäumel
<br> _Beyond Parallel Data: Joint Word Alignment and Decipherment Improves Machine Translation_
<br> 2:25-2:45 -- Hali Lindsay
<br> _Is Neural Machine Translation Ready for Deployment? A Case Study on 30 Translation Directions_
<br> 2:50-3:10 -- Lukas Schmitt
<br> _Google’s Multilingual Neural Machine Translation System: Enabling Zero-Shot Translation_
<br> 3:15-3:35 -- Meisyarah Dwiastuti
<br> _Convolutional Sequence to Sequence Learning_
<br> 3:40-4:00 -- Insa Kröger
<br> _A neural interlingua for multilingual machine translation_



