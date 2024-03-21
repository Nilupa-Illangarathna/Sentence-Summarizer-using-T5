# Sentence Summarizer using T5-base

[![T5 Model](https://img.shields.io/badge/T5_Model-Transformers-orange)](https://huggingface.co/transformers/model_doc/t5.html)
[![Summarization](https://img.shields.io/badge/Summarization-Sequence--to--Sequence-blue)](https://huggingface.co/transformers/model_doc/t5.html)

Hotel Review Summarizer is a Python script that utilizes the T5-base model for sequence-to-sequence learning to summarize hotel reviews. The script processes a dataset of hotel reviews, partitions the data by hotel names, concatenates negative reviews within each group, generates summaries using the T5-base model, and writes the results to an output CSV file. It includes functions for file management, time calculation, and progress monitoring, and executes data processing in batches to handle large datasets efficiently.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hotel-review-summarizer.git
