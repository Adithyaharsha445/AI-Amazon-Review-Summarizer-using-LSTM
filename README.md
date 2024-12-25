Deep Learning Seq2Seq Text Summarization (LSTM)
Overview
This project leverages deep learning techniques to create an abstractive text summarization model using a Sequence-to-Sequence (Seq2Seq) architecture with Long Short-Term Memory (LSTM) layers and an Attention Mechanism. The model is trained to generate concise and contextually relevant summaries from long customer reviews, specifically from the Amazon Fine Food reviews dataset.

Key Features
Seq2Seq Model with Encoder-Decoder architecture
Attention Mechanism for improved focus on relevant input segments
Built using LSTM layers to capture long-term dependencies in the data
Optimized for summarizing positive sentiment reviews
Preprocessing techniques include tokenization, padding, and contraction mapping to handle real-world data complexities
Dataset
The dataset used for training consists of over 100,000 Amazon Fine Food reviews, containing both text and corresponding summaries. This data is used to train and evaluate the model for generating high-quality summaries.

Methodology
Data Preprocessing: Text cleaning, tokenization, padding, and rare word filtering.
Model Architecture:
Encoder: Embedding layer followed by multiple stacked LSTM layers.
Decoder: LSTM with attention mechanism for dynamic focus on input sequence parts.
Attention Mechanism: Dynamically assigns attention scores to different parts of the input sequence.
Training: The model is trained using RMSProp optimizer, with early stopping to prevent overfitting.
Results
The model effectively generates accurate summaries for simpler, positive reviews. However, it struggles with more complex and nuanced content, indicating areas for improvement.

Future Directions
Implement Bi-Directional LSTM for enhanced context understanding.
Integrate Pointer-Generator Networks to improve summary accuracy.
Explore Beam Search decoding to generate multiple candidate sequences.
Link to Final Project Report
For more detailed insights, you can access the full Final Project Report, which provides an in-depth explanation of the methodology, experiments, and results.
