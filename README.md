# HumanModelComparison
What do other LLMs think about the quality of other LLMs when compared to humans?

# What do Models Think About Other Models?

## About the Dataset

SEAHORSE is a dataset introduced for multilingual, multifaceted summarization evaluation. The dataset consists of 96K summaries with human ratings along six quality dimensions: comprehensibility, repetition, grammar, attribution, main ideas, and conciseness[[11†source]](https://www.semanticscholar.org/paper/SEAHORSE%3A-A-Multilingual%2C-Multifaceted-Dataset-for/).

## Project Idea

The main idea of this project is to utilize Language Learning Models (LLMs) to evaluate the quality of summaries generated by other machine learning models. These evaluations will be compared to the human ratings present in the SEAHORSE dataset, and the consistency between human and model evaluations will be analyzed. The parameters being considered are:

1. Comprehensibility: The summary can be read and understood by the rater.
2. Repetition: The summary is free of unnecessarily repeated information.
3. Grammar: The summary is grammatically correct.
4. Attribution: All of the information provided by the summary is fully attributable to the source article.
5. Main Ideas: The summary captures the main idea(s) of the source article.
6. Conciseness: The summary concisely represents the information in the source article.

## Objective

The objective of this project is to evaluate how well LLMs align with human judgment in evaluating the quality of summaries generated by other models, providing insight into the reliability and limitations of LLMs as evaluators of summarization quality. Currently the objective used is MSE between human vs model generated ratings.
