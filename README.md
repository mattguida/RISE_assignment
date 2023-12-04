# RISE_assignment

# NER Model Fine-Tuning with BERT

## Overview

This repository contains code for fine-tuning BERT-based models for Named Entity Recognition (NER) using the Hugging Face Transformers library. 
Two systems are created (A and B), following the received information. The chosen architecture for this task is bert-base-cased (https://huggingface.co/bert-base-cased).

We employed seqeval as evaluation metric (https://huggingface.co/spaces/evaluate-metric/seqeval), specifically designed for sequence labeling tasks, such as NER,
displaying accuracy, precision, recall and F1 for each entity of the test set.

## Requirements

- Python 3.x
- [Hugging Face Transformers](https://github.com/huggingface/transformers) library
- [Datasets](https://github.com/huggingface/datasets) library
- [scikit-learn](https://scikit-learn.org/stable/index.html)
- [WandB](https://wandb.ai/site) --> you might be prompted to insert an API key from WandB upon training
- PyTorch

Check the requirements.txt for information about needed dependencies. 

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/RISE_assignment.git
   cd RISE_assignment

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Run notebook:

   ```bash
   jupyter nbconvert --execute rise-assignment-matteoguida.ipynb --to pdf

or

     ```bash
     jupyter nbconvert --execute rise-assignment-matteoguida.ipynb --to notebook
   



