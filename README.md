# 😊EMOTION DETECTION - CNN + BiLSTM + Word2Vec 💬🧠  
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
### 🧪 Hybrid Neural Network Model:
- 🧱 **Embedding Layer:** Uses pre-trained **Word2Vec** vectors and turns words into semantic vectors
- 🔎 **CNN Layer:** Extracts local text features (n-grams, patterns) 
- 🔁 **BiLSTM Layer:** Reads text in both directions for better context  
- 🧠 **Dense Layers:** Final emotion prediction (6-class classification)

📊 Trained with:

Balanced class weights

Categorical cross-entropy loss

Accuracy & loss tracked over epochs


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


## 📊 Results
✅ **Accuracy:** ~93.75%  
📉 **Loss:** Significantly reduced with training  
📈 **Visualization:** Accuracy & loss curves included

---

## 🚀 How to Run

```bash
# 1. Clone this repository
git clone https://github.com/Noor3800/Emotion_Detection.git
cd EmotionDetection

# 2. Install requirements
pip install -r requirements.txt

# 3. Run the training notebook
jupyter notebook train_evaluate.ipynb

---

🧠 FUN FACT
The model doesn’t just memorize — it learns the feelings behind words, even understanding sarcasm and negation with enough data!

