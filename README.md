# Intro_ML_Python_Notes

This repository provides the notebooks which holds the note along with the code form the book "Introduction to Machine
Learning with Python" by [Andreas Mueller](http://amueller.io) and [Sarah Guido](https://twitter.com/sarah_guido).
You can find details about the book on the [O'Reilly website](http://shop.oreilly.com/product/0636920030515.do).

"This book is a fantastic, super-practical resourse for anyone who wants to start using machine learning in pyhton- I just wish that it had existed when I started using scikit-learn!"         -**Hanna Wallach**

This book has a additional library [mglearn](https://github.com/amueller/mglearn) as helper functions to create figures and
datasets. If you get ``ImportError: No module named mglearn`` you can try to install mglearn into your python environment. All datasets are included in the repository.

## Setup

To run the code, you need the packages ``numpy``, ``scipy``, ``scikit-learn``, ``matplotlib``, ``pandas`` and ``pillow``.
Some of the visualizations of decision trees and neural networks structures also require ``graphviz``. The chapter
on text processing also requirs ``nltk`` and ``spacy``.

The easiest way to set up an environment is by installing [Anaconda](https://www.continuum.io/downloads), Or you can use cloud computing python environment called [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb).

### Installing packages with conda:
If you already have a Python environment set up, and you are using the ``conda`` package manager, you can get all packages by running

    conda install numpy scipy scikit-learn matplotlib mglearn pandas pillow graphviz python-graphviz

For the chapter on text processing you also need to install ``nltk`` and ``spacy``:

    conda install nltk spacy

In google colab all the libraries are preinstalled except mglearn

## Introduction to Machine Learning with Python

![](./Images/IntroML_cover.jpg)

This book is for Machine learnig practitioners looking to implement solution to the real-world ML problems, this book doesn't require any previous knowledge of ML, but it is understood that reader of the book has prior knowledge of linear algebra and probabilities though this book doesn't go indeapth analysis of algoritms.

### Navigation of this book:

- **Chapter 1:** Introduces the fundamental concepts of machine learning and its applications.
- **Chapters 2 & 3:** Describes the actual machine learning algorithms that are most widely used in practice,
and discuss their advantages and shortcomings.
- **Chapter 4:** Discusses the importance of how we represent data that is processed by machine learning.
- **Chapter 5:** Covers advanced methods for model evaluation and parameter tuning.
- **Chapter 6:** Explains the concept of pipelines for chaining models and encapsulating the workflow.
- **Chapter 7:** Shows how to apply the methods described in earlier chapters to text data, and introduces some text-specific processing techniques.
- **Chapter 8:** Offers a high-level overview, and includes references to more advanced topics.
