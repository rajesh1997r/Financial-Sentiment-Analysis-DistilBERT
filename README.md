# Financial Sentiment Analysis using DistilBERT

This project fine-tunes a pre-trained DistilBERT model to classify financial news text into
**Negative**, **Neutral**, or **Positive** sentiment using the Financial PhraseBank dataset.

---

## Video Walkthrough

A complete video walkthrough explaining the approach, implementation, results, hyperparameter tuning, 
and live inference demonstration is available here:

🔗 https://www.youtube.com/watch?v=tdFPauA4A0Q

(The video is unlisted and accessible via the link.)

---

## Dataset
- **Financial PhraseBank (Kaggle)**
- Human-annotated financial news sentences
- 3 sentiment classes: Negative, Neutral, Positive
- Stratified Train / Validation / Test split (70/15/15)

---

## Model
- Base model: `distilbert-base-uncased`
- Framework: Hugging Face Transformers + PyTorch
- Fine-tuned for multi-class sentiment classification

---

## Results
- Test Accuracy: **~85%**
- Macro F1-score: **~0.83**
- Significant improvement over baseline (pre-trained model without fine-tuning)

---

## Inference
The trained model can predict sentiment for unseen financial statements using the Hugging Face
`pipeline`, returning both the predicted label and a confidence score.

---

## Prerequisites & Reproducibility Notes

To run this Jupyter Notebook on any machine, the following setup is required:

### Environment
- Python **3.9 or higher**
- Jupyter Notebook or JupyterLab

### Required Libraries
- numpy  
- pandas  
- torch  
- transformers  
- datasets  
- scikit-learn  
- matplotlib  

### Installation
All required libraries can be installed using:

```bash
pip install numpy pandas torch transformers datasets scikit-learn matplotlib

### LICENSE
MIT License
