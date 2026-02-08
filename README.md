# Financial Sentiment Analysis using DistilBERT

This project fine-tunes a pre-trained DistilBERT model to classify financial news text into
Negative, Neutral, or Positive sentiment.

## Dataset
- Financial PhraseBank (Kaggle)
- Human-annotated financial news sentences
- 3 sentiment classes

## Model
- distilbert-base-uncased (Hugging Face)
- Fine-tuned using PyTorch and Transformers

## Results
- Test Accuracy ≈ 85%
- Macro F1-score ≈ 0.83

## Inference
The trained model can predict sentiment for unseen financial statements using the Hugging Face pipeline.

## Tools
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn

## License
MIT License
