# Regional Activity of Risk Anticipation: A fMRI Study

## Introduction

The Human Connectome Project (HCP) is a project sponsored by sixteen components of the National Institutes of Health, split between two consortia of research institutions. The project was launched in July 2009 as the first of three Grand Challenges of the NIH's Blueprint for Neuroscience Research.

The goal of the Human Connectome Project is to build a "network map" (connectome) that will shed light on the anatomical and functional connectivity within the healthy human brain, as well as to produce a body of data that will facilitate research into brain disorders such as dyslexia, autism, Alzheimer's disease, and schizophrenia.

In this project we took the data from the Gambling Task of HCP fMRI 7T dataset and explored the question: "Does the expectation of win vs. loss give rise to significantly different activity levels in some brain regions? Can we predict the clue itself [either win or loss dominance in trials] given regional activities?".

Our approach consists of two main parts:

1- Running a permutation test between the activity of win and loss to find regions with a significant activity difference in win vs. loss.

2- Predicting the class of each block (mostly win/mostly loss) using brain region activities as features, with Logistic Regression and SVM classifiers

The slides of our presentation at NMA 2021 are available through [google slides](https://docs.google.com/presentation/d/1zRrYoo-wC2llhebMpD58NXA_URQ5LrPTi70cfvyBkbQ/edit#slide=id.ge51dc41796_2_83).
