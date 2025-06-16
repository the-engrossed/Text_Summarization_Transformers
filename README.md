# Text_Summarization_Transformers

## Tools Used - Python, PyTorch, Trasformers, Flask API, Docker, GCP (Compute Engine), Git Hub workflows

## Table of Contents
1.  [Project Objective](#project-objective)
2.  [Transformers](#text_summarization_transformers)






## Project Objective
Given a text/paragraph identify the most important information from the text and present the abriged version of it.
1. Load the news data.
2. Loading hugging face model along with specific tokenizer using Transformers.
    1. T5 -model ( https://huggingface.co/t5-base , https://huggingface.co/t5-small)
    2. BERT(https://huggingface.co/mrm8488/bert-small2bert-small-finetuned-cnn_daily_mail-summarization)
    3. Pegasus(https://huggingface.co/google/pegasus-large)
3. Fine Tuning the model with our data set.