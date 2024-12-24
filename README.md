# *Using Pre-trained Models: Tokenization to Predictions*

### In this notebook, I explore the use of a pre-trained model (like BERT) step by step

#### Summary of Steps:
1. **Install Libraries:** Install Hugging Face and PyTorch.
2. **Import Libraries:** Import the necessary classes and functions.
3. **Load Pre-trained Tokenizer and Model:** Use AutoTokenizer and AutoModelForSequenceClassification.
4. **Tokenize Input Text:** Convert your text into token IDs that the model can understand.
5. **Make Predictions:** Use the model to generate logits (raw predictions).
6. **Convert Logits to Probabilities:** Use softmax to get probabilities and make predictions.
7. **Interpret Results:** Convert probabilities into class labels (e.g., positive/negative).
8. **Fine-Tuning (optional):** Adjust the model on your own dataset.
9. **Save and Load Model:** Store your model for later use







