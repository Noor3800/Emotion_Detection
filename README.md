# 😄😢 EMOTION DETECTION - CNN + BiLSTM + Word2Vec 💬🧠  
🔍 *Can a machine understand human emotions from just a sentence? Let’s find out!*

Welcome to **Emotion Detection**, a powerful deep learning project that uses a hybrid model of **CNN** and **BiLSTM** to detect emotions from text with high accuracy! It’s trained on labeled text data and powered by **Word2Vec** embeddings to truly *feel* the meaning of your words.

---

## 💡 What It Does  
📘 **Input:** A sentence like _“I just got promoted!”_  
🎯 **Output:** An emotion label like `joy`, `anger`, `sadness`, `fear`, `love`, or `surprise`

🧠 The model processes your sentence in smart steps:
- 📍 **CNN** captures local patterns (e.g., "not happy")
- 🔁 **BiLSTM** understands word order & context
- 🧾 **Word2Vec** maps words into meaningful vector space

---

## ⚙️ How It Works  
### 🧪 Neural Network Pipeline:
- 🧱 **Embedding Layer:** Uses pre-trained **Word2Vec** vectors  
- 🔎 **CNN Layer:** Detects patterns (like n-grams)  
- 🔁 **BiLSTM Layer:** Reads text in both directions for better context  
- 🧠 **Dense Layers:** Final emotion prediction (6-class classification)

---

## 🔬 Emotions It Can Detect

| Emotion      | Example Sentence                    |
|--------------|-------------------------------------|
| 😄 Joy       | “This is the best day ever!”        |
| 😡 Anger     | “I can’t believe this happened!”    |
| 😢 Sadness   | “I miss my old friends.”            |
| 😨 Fear      | “I’m scared of the dark.”           |
| 😍 Love      | “I love you so much!”               |
| 😲 Surprise  | “Whoa, I didn’t expect that!”       |

---

## 📁 Project Structure

