Open experiment.ipynb in Google Colab and choose Runtime → Run all on a CPU runtime. The notebook downloads KBLab's public Swedish BERT from Hugging Face. No credentials, training or GPU are required. The final cell writes results relative to the current directory.


results/predictions.csv records every held-out decision. Positive margin means that en has the higher logit. On regression items, prediction is over the entire vocabulary. Gold log probability is always over the entire vocabulary.
AI-usage.md describes the work performed with AI.
