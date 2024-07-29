# FinNERBERT
Training BERT for NER on financial entities using the RealKIE datasets.

# Datasets

Using the RealKie (https://arxiv.org/abs/2403.20101) datsets for enttiy extraction. `data.ipynb` is used to transfom these datasets into the NER format of IOB (Inside Out Beginning) tagging. Also used the BERT tokenizer to process the data. However manually implmented parts such as token_ids, attention masks and paddings to learn more about how BERT works, even though `transformers` library from HuggingFace can do most of this.

The RealKIE datasets have 5 sub datasets within them, each with their own annotated entities, many of these entites have been selected and combined to train the model on identifying 4 entites.

- ORG: Organisations
- PER: Person
- DAT: Dates
- FIN: Financial Amounts (monetary values).

# Training

Up next.

# Deployment

Planning to deploy model to be used for inference.