# 😊Emotion_Detection Using CNN & Bi-LSTM with Word2Vec

This project focuses on emotion classification from text using a hybrid deep learning architecture that combines Convolutional Neural Networks (CNN) and Bidirectional Long Short-Term Memory (BiLSTM). It leverages Word2Vec embeddings to transform words into dense vector representations that preserve semantic relationships.

🔍 Objective
To build an intelligent system that can accurately identify emotions expressed in text, such as joy, anger, sadness, fear, love, and surprise, enabling applications like sentiment monitoring, conversational agents, and mental health analysis.

🧠 Key Features
Text Preprocessing: Cleaning, tokenization, stop-word removal, and padding.

Word Embeddings: Integration of pre-trained Word2Vec to capture semantic word relationships.

CNN Layer: Detects local patterns and n-gram features from text.

BiLSTM Layer: Captures long-range dependencies and contextual meaning from both directions.

Class Imbalance Handling: Addressed using class weights to improve performance on underrepresented classes.

Model Evaluation: Includes accuracy, loss visualization, and performance metrics.

🛠️ Technologies Used
Python

TensorFlow / Keras

NumPy, Matplotlib

Word2Vec (Gensim / Pre-trained vectors)

Jupyter Notebook

📊 Results
Achieved high accuracy (~93.75%) on multi-class emotion classification.

Demonstrated the effectiveness of combining CNN for feature extraction with BiLSTM for temporal understanding.
