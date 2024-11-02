# BERT-Phishing-Classifier



This repository contains a Jupyter Notebook that demonstrates the fine-tuning of a pretrained transformer model for phishing classification. The notebook leverages Hugging Face's Transformers library to perform transfer learning on a dataset of phishing and benign URLs, enabling the model to distinguish between them effectively.

The fine-tuned model is available on Hugging Face and can be accessed [here](https://huggingface.co/dhruvyadav89300/BERT-phishing-classifier).

## Training Summary

- **Total Training Runtime**: 555.4381 seconds
- **Final Training Loss**: 0.3372
- **Train Samples per Second**: 75.616
- **Eval Accuracy (Best Epoch)**: 0.893 (Epoch 15)
- **Eval AUC (Best Epoch)**: 0.957 (Multiple Epochs)

## Dependencies

All dependencies are listed in the `requirements.txt` file. Install them using:
```bash
pip install -r requirements.txt
```
