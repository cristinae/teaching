# Machine Translation
## General Info
```
Where: Building B3.2, Room 0.03
When: Mondays & Tuesdays, 16:00-18:00, from 11/04/23 to 18/07/23
Who: Cristina España-Bonet, Koel Dutta Chowdhury, Yasser Hamidullah
     
```

## See the course [calendar](../calendars/calendarMT.md)
<br>

## Objectives

The course gives an introduction to machine translation going from statistical to neural machine translation systems and paying special attention to the current state of the art which is almost 100% neural. A strong background on mathematics, statistics and machine learning is not required but a basic knowledge is expected to follow the course.
<br>


## Evaluation

The evaluation consists of 2 mandatory labs with an assignment (30%), a final exam (70%) and a challenge bonus (extra 10%!):
* SMT assignment (lab week 5, deadline week 8)
* NMT assignment (lab week 11, deadline week 13)
* MT Challenge, the bonus (temptative, to discuss, week 15)

* Final exam: <span style="color:red"> 17/07/2023 </span> 
* Resit exam: <span style="color:red"> 17/10/2023 </span>
<br>


## Basic Bibliography

There is no textbook for the course, but you can find basic general information in the following references. More especific texts or slides will be provided for each session.

* Speech and Language Processing: An introduction to natural language processing, computational linguistics,
and speech recognition by Daniel Jurafsky & James H. Martin. 2007 [[Chapter 25]](.//slides2018/biblio/JurafskyMartinChap25Draft.pdf) [[New draft 3rd edition]](https://web.stanford.edu/~jurafsky/slp3/)
* Statistical Machine Translation book by Philipp Koehn [[slides]](http://www.statmt.org/book/)
* From SMT to NMT, three posts by Kyunghyun Cho to understand the basics of NMT [[blog]](https://devblogs.nvidia.com/introduction-neural-machine-translation-with-gpus/)
* Chapter on Neural Machine Translation by Philipp Koehn [[pdf]](https://arxiv.org/pdf/1709.07809.pdf)
* The illustrated transformer by Jay Alammar, a blog to understand the insights of a transformer [[blog]](https://jalammar.github.io/illustrated-transformer/)
<br>

## Related Exercises

We will do some simple excercises during the lectures and devote one lecture for exercises. We suggest practical exercises in the syllabus related to the week's topic. Also, we recommend that you practice every week with additional related [exercises](https://lms.sulb.uni-saarland.de/moodle/course/view.php?id=8655). These exercises will not be corrected in class and bear in mind that they are not exhaustive, not all the topics that will be evaluated are covered in this additional set.


## Syllabus

### Week 1

Let's start! 

* Easter Monday
* C1: Introduction to the course [[slides]](.//slides2023/lectures/1-introCourse.pdf) <br>
C1: Richness of natural languages, why is MT difficult? [[slides]](.//slides2023/lectures/2-introLanguages.pdf) <br>

Suggested exercise: Fill in the form with CA-WEAT lists in your mother tongue. Form is available in [Catalan](https://docs.google.com/forms/d/e/1FAIpQLSfuCtPWl6MgpnitOLWbbncslIVE9ggY1HcezkPwmOvTu9R7SQ/viewform?usp=sf_link), [English](https://docs.google.com/forms/d/e/1FAIpQLSe7PxnTNox-TYTQZFz0S6j0XNv_fcZIg6RgZdOURveKIKs9Pw/viewform?usp=sf_link), [French](https://docs.google.com/forms/d/e/1FAIpQLSeyOaVTzNlpcIhWvbHLisX7VO72Gr3PL7K5gnFLKzDDimLGag/viewform?usp=sf_link), [German](https://docs.google.com/forms/d/e/1FAIpQLSeLsN2u8NWS-glF91uyMpE6UooyiZtfM_yB0c0AmolUsxYrBA/viewform?usp=sf_link), [Italian](https://docs.google.com/forms/d/e/1FAIpQLScFcw_ORqR9NwSzL3jY3s18e4Z2hEBNCbZjSgEhewmOymvIHA/viewform?usp=sf_link) and [Spanish](https://docs.google.com/forms/d/e/1FAIpQLSciZNJr-xxk-W4lvCc5Ja_BixdWy68doagOKmhJx7VmZILyaw/viewform?usp=sf_link). Please, use the English form and add words in your native language if the specific form is not available.

### Week 2

Richness of natural languages, why MT evaluation is a challenge? <br>
Human evaluation vs. automatic evaluation. String matching automatic metrics and neural metrics. 

* K1: MT Evaluation I  [[slides in Moodle]](https://lms.sulb.uni-saarland.de/moodle/course/view.php?id=8655) <br>
* K2: MT Evaluation II  [[slides]](.//slides2023/lectures/4-MT_evaluation_II.pdf)

Suggested exercise: Chose two short sentences (a hypohesis and a reference translation) and calculate some n-gram based metrics by hand. Use [sacreBLEU](https://github.com/mjpost/sacrebleu) to check your results. Go to your preferred online MT system and get longer hypotheses-reference pairs. Evaluate them with sacreBLEU. Install at least [COMET](https://unbabel.github.io/COMET/html/index.html) as semantic metric and compare the results. We'll use these softwares later in the labs. Advice: don't try Windows!

### Week 3 

What's machine translation about? Types of MT systems: rule-based, statistical and neural. <br>
A few words on statistical machine translation (SMT) and language models. Why in 2023!? 

* C2: Recap! Richness of natural languages, why is MT difficult? [[slides]](.//slides2023/lectures/2b-introLanguagesRecap.pdf) <br>
Introduction to Machine Translation [[slides]](.//slides2023/lectures/5-MTinNutshell.pdf) 
* C3: Statistical Machine Translation I [[slides]](.//slides2023/lectures/6-SMT.pdf) <span style="color:red"> Achtung! </span> These slides might not be the final ones, they might be actualised.

Suggested exercise: Read about how everything started, history never harms! [[John Hutchin summary](https://www.infoamerica.org/documentos_pdf/bar05.pdf)] [[blog]](https://www.freecodecamp.org/news/a-history-of-machine-translation-from-the-cold-war-to-deep-learning-f1d335ce8b5/)

### Week 4

More on SMT: IBM models, alignment, phrase tables and beam search.

* May 1st
* C4: Statistical Machine Translation II

### Week 5

More on SMT: IBM models, alignment, phrase tables and beam search. <br>
And after that, let's put everything in practice! Hands on SMT.

* C5: <span style="color:red"> (temptative) </span> Statistical Machine Translation III
* C6: <span style="color:red"> (temptative) </span> Lab1, Statistical Machine Translation [[guidelines]](.//slides2023/lectures/) 

### Week 6

Continue with our hands on. <br>
Transition to neural machine translation, word embeddings: the basic units.

* C7: <span style="color:red"> (temptative) </span> Lab1, Statistical Machine Translation [[guidelines]](.//slides2023/lectures/) 
* C8: <span style="color:red"> (temptative) </span> Word embeddings (+ cross-lingual + Unsupervised MT?)

### Week 7
 
The basics of neural networks with relevance to machine translation. 

* K3: Neural networks for translation technologies I
* K4: Neural networks for translation technologies II


### Week 8

Serious neural networks stuff! 

* Whit Monday
* Y1: Neural networks I: backpropagation

<span style="color:red">Deadline for Lab1 report</span>

### Week 9

Deeper into neural networks and logistic regression. <br>
Neural machine translation (NMT), LSTMs and attention. <br>

* Y2: Neural networks II: Andrew Ng like introduction
* Y3: Neural Machine Translation I

### Week 10

More on Neural machine translation, sequence-to-sequence models with attention and transformers.

* Y4: Neural Machine Translation II
* Y5: Neural Machine Translation III


### Week 11

NMT, new technology, let's put everything in practice again! Hands on NMT.

* C9: Lab2, Neural Machine Translation [[guidelines]](.//slides2023/lectures/) 
* C10: Lab2, Neural Machine Translation [[guidelines]](.//slides2023/lectures/) 

### Week 12 

A moment to stop, breath, we do some exercises, clarify general doubts.</br>
Starting multimodality.

* K5: Selected exercises, Q/A
* K6: Multimodal Machine Translation

### Week 13

More on multimodality, sign language translation. 

* Y6: Sign Language Translation I 
* Y7: Sign Language Translation II

<span style="color:red">Deadline for Lab2 report</span>

### Week 14

A couple of selected topics.

* C11: Cross-lingual embeddings and unsupervised MT
* C12: Low-resource and multilingual MT

### Week 15

* <span style="color:red"> 17/07/2023 EXAM </span>
* Challenge discussion


