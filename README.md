# human-and-machine-confidence-in-truthfulness
repository for the JDIQ paper "Combining Human and Machine Confidence in Truthfulness Assessment" 


# Overview
- to be added

# Deep Learning Models
The models used in the work are the following:
- https://huggingface.co/kevinr/Confidence-bert-base-uncased-Loss_CrossEntropy-Bin_0-12345
- https://huggingface.co/kevinr/Confidence-bert-base-uncased-Loss_CrossEntropy-Bin_01-2345
- https://huggingface.co/kevinr/Confidence-bert-base-uncased-Loss_CrossEntropy-Bin_012-345 
- https://huggingface.co/kevinr/Confidence-bert-base-uncased-Loss_CrossEntropy-Bin_0123-45
- https://huggingface.co/kevinr/Confidence-bert-base-uncased-Loss_CrossEntropy-Bin_01234-5
- https://huggingface.co/kevinr/Confidence-bert-base-uncased-Loss_CrossEntropy-Bin_Nobin

each model can be used as follows (example provided for the last model):

```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification
tokenizer = AutoTokenizer.from_pretrained("kevinr/Confidence-bert-base-uncased-Loss_MSE-Bin_Nobin")
model = AutoModelForSequenceClassification.from_pretrained("kevinr/Confidence-bert-base-uncased-Loss_MSE-Bin_Nobin")
```

# Data
 to be added.

