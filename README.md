📘 IMDB Movie Review Sentiment Analysis using LSTM

🔍 Objective
To build a deep learning model using LSTM (Long Short-Term Memory) to classify IMDB movie reviews as positive or negative based on the textual content.

📁 Dataset
Dataset Name: IMDB Movie Review Dataset

Source: Keras Datasets

Description: 50,000 movie reviews from IMDB, labeled as:

1 → Positive

0 → Negative

Split:

25,000 reviews for training

25,000 reviews for testing

⚙️ Tech Stack
Language: Python
Libraries:
TensorFlow / Keras
NumPy

Matplotlib / Seaborn (for visualization)

📊 Results
Accuracy Achieved: ~85–88% (varies slightly depending on parameters and random seed)
Loss Function: Binary Crossentropy
Optimizer: Adam

📈 Visualizations (Optional)
Plot training vs validation accuracy and loss using Matplotlib to observe overfitting or underfitting.

✅ Conclusion

LSTM is effective for handling sequential text data like movie reviews.

Proper padding, embedding, and dropout prevent overfitting and improve generalization.

This approach can be further improved using Bidirectional LSTM, GRU, or pretrained embeddings (like GloVe).

🚀 Future Enhancements

Use pre-trained word embeddings (GloVe, Word2Vec)
Try Bidirectional LSTM or GRU
Add attention mechanism
Use transformers (BERT)
