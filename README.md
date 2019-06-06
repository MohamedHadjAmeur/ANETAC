# ANETAC: Arabic Named Entity Transliteration and Classification Dataset

## Description

ANETAC is an English-Arabic named entity transliteration and classification dataset that has been built as part of the research work made by [Hadj Ameur et al.] (https://www.sciencedirect.com/science/article/pii/S1877050917321774). 
The dataset contains 79,924 English-Arabic named entities along with their respective classes that can be either a Person, a Location, or an Organization. 

An example of the instances present in the dataset are provided in the below Table: 
![Cat](https://github.com/MohamedHadjAmeur/ANETC-Arabic-Named-Entity-Transliteration-and-Classification-Dataset/blob/master/image.png)

## CONTENTS


This repository contains two folders:
* EN-AR NE: which contains the English-Arabic named entities along with their classes as described in the above table.
* EN-AR Translit: is a benchmark that splits the above-mentioned transliteration data into train, development, and test sets for direct usage in English-Arabic transliteration tasks.

The count of the Person, Location and Organization named entities that are present in this transliteration dataset are provided in the below Table: 
![Cat](https://github.com/MohamedHadjAmeur/ANETC-Arabic-Named-Entity-Transliteration-and-Classification-Dataset/blob/master/stats.png)

## Usage
We note that first results using this EN-AR transliteration data (the one in EN-AR Translit folder) has been already published in the work of Hadj Ameur et al. "Arabic Machine Transliteration using an Attention-based Encoder-decoder Model".

## Citations
If you want to use the ANETC dataset please cite the following paper:

```
@article{HADJAMEUR2017287,
title = "Arabic Machine Transliteration using an Attention-based Encoder-decoder Model",
journal = "Procedia Computer Science",
volume = "117",
pages = "287 - 297",
year = "2017",
note = "Arabic Computational Linguistics",
issn = "1877-0509",
doi = "https://doi.org/10.1016/j.procs.2017.10.120",
url = "http://www.sciencedirect.com/science/article/pii/S1877050917321774",
author = "Mohamed Seghir Hadj Ameur and Farid Meziane and Ahmed Guessoum",
keywords = "Natural Language Processing, Arabic Language, Arabic Transliteration, Deep Learning, Sequence-to-sequence Models, Encoder-decoder Architecture, Recurrent Neural Networks",
abstract = "Transliteration is the process of converting words from a given source language alphabet to a target language alphabet, in a way that best preserves the phonetic and orthographic aspects of the transliterated words. Even though an important effort has been made towards improving this process for many languages such as English, French and Chinese, little research work has been accomplished with regard to the Arabic language. In this work, an attention-based encoder-decoder system is proposed for the task of Machine Transliteration between the Arabic and English languages. Our experiments proved the efficiency of our proposal approach in comparison to some previous research developed in this area."
}
```

## Contacts:
For all questions please contact ``mohamedhadjameur@gmail.com`` 

