Mental Health Text Classifier (QLoRA, BERT)
This is a small and efficient model built with bert-base-uncased and fine-tuned under Quantized Low Rank Adaptation. It classifies mental health-related text into categories like Anxiety, Depression, etc.



DistilBert Info

Type: Natural Language text sentiment classifier using Google BERT + QLoRA adapters
Purpose: Detect mental health sentiments througgh short text
Uses: Social media, forums, research, screening

============================
Originally prototyped for community health project as a Fairfax County Public Youth Health Ambassador
============================

Not for Medical diagnosis or treatment


Details
Created by: Bhavesh Adivi
Data: "Kaggle mental health sentiment dataset"
Hardware: Trained on Nvidia Tesla 4 GPU - Access provided by Google Colab
License: Apache 2.0


Usage & Inference:
Can be used to (experimentally) classify user posts or comments for mental health signs
Use in apps for (experimental) mental health monitoring or (experimental only) early alerts
Can be further fine-tuned for better results or distinct cohorts


Important Notes to consider:
This is NOT meant for immediate diagnosis or replacing health professionals
Bias risk included: Potential data biases may affect results from datasets
Some Limitations might include missing indirect or subtle cues such as sarcasm or critical context
Make sure to always involve human judgment and privacy protections


Model is hosted on Hugging Face for inference:
https://huggingface.co/spaces/bhaveshadivi/distilMind
