# LLM-Powered Structured Data Extraction & Evaluation (Zero-Shot vs Few-Shot)

## Overview

This project explores how Large Language Models (LLMs) can be used to transform unstructured text into structured, machine-readable data using prompt engineering and in-context learning techniques.

Using OpenAI’s GPT-5-mini model, I built an NLP pipeline that extracts structured attributes from free-text biographies and evaluates model performance across both zero-shot and few-shot learning approaches.

The project focuses on:

* Prompt engineering
* Information extraction
* In-context learning
* NLP evaluation metrics
* Structured data generation from unstructured text
* Real-world LLM debugging and optimization

The system was evaluated using precision, recall, and F1-score across 50+ biography samples.

---

# Project Highlights

* Built an NLP pipeline for structured information extraction using GPT-based models
* Implemented both zero-shot and few-shot prompting strategies
* Generated standardized key-value outputs from raw biography text
* Evaluated model performance using precision, recall, and F1-score
* Improved extraction quality through iterative prompt refinement and debugging
* Worked with real-world API compatibility and model behavior constraints
* Compared the effectiveness of in-context learning vs instruction-only prompting

---

# Technologies Used

* Python
* OpenAI API
* GPT-5-mini
* Google Colab
* Natural Language Processing (NLP)
* Prompt Engineering
* Information Extraction
* In-Context Learning
* Precision / Recall / F1 Evaluation

---

# Problem Statement

Large language models are capable of understanding natural language, but converting unstructured text into reliable structured outputs remains a challenging NLP task.

This project investigates:

* How well GPT models perform structured information extraction without examples (zero-shot)
* Whether providing demonstrations inside the prompt (few-shot learning) improves extraction quality
* How prompting strategies influence precision, recall, and overall extraction performance

The goal was to design a reliable extraction workflow that could transform biography text into structured attribute-value pairs.

---

# Example Input

```text
Sione'e Laufe (06 October 1915 - 13 June 1991) was a Samoan-born American musician. Laufe was born in Pago Pago, American Samoa, and was raised in Hawaii.
```

# Example Model Output

```text
name: Sione'e Laufe
birth_date: 06 October 1915
death_date: 13 June 1991
birth_place: Pago Pago, American Samoa
nationality: Samoan American
occupation: musician
```

---

# Model Evaluation

The extraction pipeline was evaluated using:

* Precision
* Recall
* F1-score

Results showed that the few-shot prompting approach significantly improved performance over the zero-shot baseline by helping the model better understand formatting patterns and expected attribute extraction behavior.

---

# Key Learnings

This project provided hands-on experience with:

* Designing effective prompts for structured extraction tasks
* Evaluating LLM outputs quantitatively
* Working with API limitations and model reasoning behavior
* Improving NLP workflows through iterative experimentation
* Understanding the tradeoffs between precision and recall in information extraction systems

---

# Recruiter / Reviewer Guide

### View the Full Source Code

The complete implementation, prompt engineering workflow, and evaluation pipeline can be viewed here:

👉 https://github.com/neysap/LM-Powered-Structured-Data-Extraction-Evaluation-Zero-Shot-vs-Few-Shot-/blob/main/Exploring_GPT.ipynb

---

To run the notebook interactively in Google Colab:

Open the notebook link above
Click the “Open in Colab” button at the top of the notebook

👉 <img width="150" height="41" alt="image" src="https://github.com/user-attachments/assets/45d0c083-ab3f-4e76-89af-38b9fda0416e" />


---

# Future Improvements

Potential future enhancements include:

* Fine-tuning extraction prompts for higher recall
* Adding JSON schema validation
* Implementing automated post-processing and normalization
* Comparing multiple LLM architectures
* Deploying the extraction pipeline as an API or web application
* Adding named entity recognition (NER) comparisons using traditional NLP models

---

# Why This Project Matters

Structured data extraction is a core challenge in modern NLP systems used across:

* Search engines
* Knowledge graphs
* AI assistants
* Resume parsing systems
* Healthcare NLP
* Financial document processing
* Enterprise automation pipelines

This project demonstrates practical experience working with LLM-driven information extraction systems and evaluating their performance using measurable metrics.

---

# Author

Neysa Porter
Master of Computer & Information Technology (MCIT)
University of Pennsylvania
