# CMCS 383 - Computational Text Analysis Course

## Short summary (Catalog Description)

This course will introduce students to the methods and tools used in computational text analysis, aka <i>text as data</i>.
This course focuses on methods used to <i>discover</i> and <i>measure</i> concepts and phenomena from large amounts of text. Students will implement methods covered in class and apply these methods to texts of their choosing.

## Longer description (Course Overview)

This course covers foundational concepts in computational text analysis. 
The course is designed for Computer Science students
interested in using text analysis methods to discover and measure concepts and phenomena in large amounts of text. 
Topics include 
core computational text analysis concepts, text-based machine learning, 
deep learning, basic statistical methods, and data collection. 
The course will culminate around research projects where groups of students will formulate and iteratively refine an empirical question; collect relevant textual data; implement appropriate methods of analysis; and interpret and present their results.


## Course Components:
The course contains the following components:

- Lectures computational text analysis topics.
- In-Class (lab) pair-programming activities implementing the methods discussed in lecture.
- One group project using text analysis tools to empirically investigate a research question.
- During the first 2/3 of the semester, weekly individual assignments for students to master the material and concepts
- One midterm exam testing students' mastery of the material.


## Learning Outcomes:
By the end of this course, students will have introductory software skills in Python and be able to:

- Implement core computational text analysis methods in Python
- Leverage advanced computational text analysis toolkits to *discover*, *measure*, and *explain* latent concepts, trends, phenomena in text 
- Develop and iteratively refine a research question and use text as data to empirically interpret their results 


##Course Materials
###Textbooks Required:
There are no textbooks required for this course. All course readings will be made
available online.

Course readings will include chapters from (at least the following):

* Draft of Grimmer, Roberts and Stewart's textbook
* 	Moretti, F. 2005 *Distant Reading*
*  Jurafsky, D., & Martin, J. H. 2009. *Speech and Language Processing* 2nd ed. Pearson.

## Course Overview
### Course Topics:

1. Working with Text  
2. Representing Text (word representations, document representations)
3. Discovery - illuminate new concepts and suggest insights that deserve further investigation
4. Measurement -  quantifying and explaining the discovered concept
5. Machine Learning and Deep Learning


### Schedule (Tentative)
 Week | Date      | Title | Topics | Readings | HW due |
| ----------- | ----------- | ----------- | ----- | -----| -----|
| 1 | 01/18    | Lecture 1  <br> Course Intro & Linguistics | Tokenization, Lemmatization, Stemming, Stopwords, Syntax, Named Entities |
| 2 | 01/23   | Lecture 2  <br> Language Modeling    | Conditional Probability, n-Grams, Applications, Perplexity, Smoothing | | HW1: <br>Limerick |
|  | 01/25   | Lecture 3 <br> Document Term Matrix | bag-of-words, cosine-similarity, TF-IDF  | 
| 3 | 01/30   | Lecture 4   <br>  Classification   (Naive-Bayes)   | Supervised Learning, Evaluation: train/dev/test vs k-fold, Bayes Rule |   | HW2: <br> TF-IDF |
|   | 02/01   | Lecture 5 <br> Linear & Logistic Regression        | Regression vs Classification, Stochastic Gradient Descent, Interpreting Weights 
| 4 | 02/06   | Lecture 6 <br> Deep Learning I      | Logistic Regression with multiple layers, Backpropagation (Objective Function revisited, Partial Derivatives), PyTorch | | HW3: <br> Language Modeling |
| | 02/08   | Lecture 7   <br> Deep Learning II     | Deep Averaging Networks | | |
| 5 | 02/13   | Lecture 8   <br> Neural Language Models I     | RNNs, LSTM | | HW4: <br> Classification | 
|   | 02/15   | Lecture 9    <br> Neural Language Models II    | Transformers | Attention, Contextual Representations, Transform, BERT
| 6 | 02/20   | Lecture 10   <br> Word Representations  I   | Dimensionality Reduction, Word2Vec| | HW5: <br> Deep Averaging Networks | 
|   | 02/22   | Lecture 11  <br> Word Representations II     | Embeddings for text analysis | |
| 7 |02/27   | Lecture 12    <br> Midterm Review   | Project Discussions | | HW6: <br> Fine-Tuning Transformers
|   | 03/01   | Lecture 13   <br> Midterm   |
|   | 03/06   | SPRING BREAK <br> NO CLASS       |
|   | 03/08   | SPRING BREAK <br> NO CLASS |   |
| 8 | 03/13   | Lecture 14    <br> Topic Modeling I    | Project Discussions | | |
|   | 03/15   | Lecture 15   <br> Topic Modeling II     | |  | Project Proposals (due 03/16)|
| 9 | 03/20   | Lecture 16  <br> Dictionary based methods I      | LWIC, Vader | | HW7:<br> Topic Modeling
|   | 03/22   | Lecture 17   <br> Dictionary based methods II     |
| 10 | 03/27   | Lecture 18    <br> Clustering     |
|    |03/29   | Lecture 19   <br> Dimentionality Reduction     |
| 11 | 04/03   | Lecture 20  <br> Hypothesis Testing  I    |
|    | 04/05   | Lecture 21 <br> Hypothesis Testing II <br> Passover Eve        |
| 12 |04/10   | Lecture 22 <br> REMOTE LECTURE or Guest Speaker       | | | Project Update |
|    | 04/12   | NO CLASS (or guest speaker) <br> PASSOVER       |
| 13 | 04/17   | Lecture 23  <br> Causal Inference I     |
|    | 04/19   | Lecture 24  <br> Causal Inference II      |
| 14 | 04/24   | Lecture 25  <br> TBD      |
|    | 04/26   | Lecture 26 <br> Project Presentations       |

### Grading
|    |  Percent    |
|----|------|
| HW | 30% |
| Project | 30% |
| Midterm | 25% |
| Weekly Paper Reviews | 10% |
| Participation | 5% |

#### Project 
The goal will be to use different tools for *discover* and *analysis* of a textual dataset of interest.


|    |  Percent  = 35%  |
|----|------|
|  Proposal  |  5%    |
|  Mid-project update |  7%    |
|  Code artifact |   4%  |
|   Final paper |   14%    |            

## Credits
[Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/)

### Relevant Tutorials

1. [Barnard Computational Social Science's python for social sciences](https://github.com/Barnard-Computational-Science-Center/python-social-sciences-spring2)

### Related Courses:
  
As social science and humanities research heavily incorporates textual data, numerous classes similar to this exist.
Here I will try to keep a running list of related courses

1. Classes that require prior statistical and programmings knowledge
  1. [Text as Data](https://cbail.github.io/textasdata/Text_as_Data.html) by Chris Bail (Sociology, Public Policy, and Data Science) at Duke
  1. [Text as Data](https://github.com/justingrimmer/tad_19/blob/master/mac19.pdf) by Justin Grimmer (Political Science) at Stanford
  2. [Text as Data](https://www.dropbox.com/s/wmqycp11757cekv/TAD_syllabus.pdf?dl=0) by Tamar Mitts (Political Science) at Columbia SIPA                               
