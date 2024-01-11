

# RAG-LLM-Question-Answer Bot

[![alt text][image]][hyperlink]
[hyperlink]:https://docs.aws.amazon.com/images/sagemaker/latest/dg/images/jumpstart/jumpstart-fm-rag.jpg
[image]:
https://aws.amazon.com/what-is/retrieval-augmented-generation/
(tooltip)
ref: https://docs.aws.amazon.com/images/sagemaker/latest/dg/images/jumpstart/jumpstart-fm-rag.jpg

## Overview

This repository contains the solution for a case study focused on constructing a Retrieval-Augmented Generation (RAG) system or Language Model (LLM) system. The primary goal is to optimize the system's performance in a hypothetical exam scenario by answering questions correctly. The success metric is the percentage of questions answered correctly.

## Task Breakdown

### 1. Data Cleaning and Preparation

- **Dataset Loading:** The dataset is loaded using Python to kickstart the analysis.

- **Data Cleaning:** Various data cleaning steps are performed to ensure the dataset's integrity and reliability.

### 2. Exploratory Data Analysis (EDA)

- **Exploratory Analysis:** In-depth exploration of the dataset is conducted to gain insights into its characteristics and nuances.

### 3. Data Engineering

- **Feature Engineering:** The data is engineered to suit the intended pipeline, enhancing its quality for subsequent processing.

- **Rationale Explanation:** The decisions made during data engineering are explained to provide clarity on the thought process.

### 4. RAG / LLM Prototype

- **Technology Stack:** A prototype setup is created to simulate a hypothetical exam. Any relevant technology stack is employed, and the LLM may utilize retrieval, math problem-solving abilities, or toolchains.

- **Prompting Techniques:** The system may employ various prompting techniques or chained prompts to optimize question-answering accuracy.

### 5. Interpretation & Future Work

- **Accuracy Determination:** A method to determine the accuracy of the prototype is outlined.

- **Improvement Suggestions:** Recommendations for future improvements are provided, suggesting ways to enhance the accuracy of the system.

## Repository Structure

- **`data/`:** Directory containing the dataset.

- **`results/`:** Directory for storing any additional files or resources generated during the assignment.

- **`EDA.ipynb`:** Jupyter Notebook for the Exploratory Data Analysis phase.

- **`LLM_RAG_Inference.ipynb`:** Jupyter Notebook detailing the implementation of the RAG / LLM prototype.

- **`LLM_finetuning_with_PEFT.ipynb`:** Jupyter Notebook focusing on finetuning the Language Model with additional techniques.

- **`LLM_finetuning_without_PEFT.ipynb`:** Jupyter Notebook for finetuning the Language Model without additional techniques.

- **`inference_gpt3.ipynb`:** Jupyter Notebook exploring inference using the GPT-3 model.

- **`LICENSE`:** MIT license file for the repository.

- **`README.md`:** This documentation providing an overview, task breakdown, repository structure, and evaluation criteria.



Feel free to explore the notebooks and directories for a detailed walkthrough of the process and outcomes of the RAG / LLM system construction.

