Joy Maurya  joymaurya1800@gmail.com

Fine-Tuned BERT for Question Answering on SQuAD

Overview
This document is about fine-tuning BERT model for the question-answering task on the SQuAD (Stanford Question Answering Dataset) dataset.



Model Details
Model Architecture: BERT
Dataset: SQuAD (Stanford Question Answering Dataset)
Fine-Tuning Approach: 3 epochs , whole training_dataset(80000 rows),learning_rate=2e-5,weight_decay=0.01

Training Duration: 2hr 11min with GPU

![Alt text](/1.png)

Usage Instructions

Requirements

Make sure you have the following dependencies installed:

transformers

accelerate

datasets

AutoTokenizer

AutoModelForQuestionAnswering

pipeline 


User Interface:
Didn't Used any web interface due to time constraints

Training Scores : {'exact_match': 40.0, 'f1': 61.32333333333336} for 250 samples


![Alt text](/3.png)


Used Model On own Example  Use__BERT can be used for user interface and handles the output if model is uncertain

![Alt text](/4.png)
