# MultiModel-Sentiment-Analysis
### Sentiment Analysis on Amazon Fine Food Reviews using VADER & RoBERTa

This project explores **Natural Language Processing (NLP)** techniques to analyze sentiment from the Amazon Fine Food Reviews dataset.  
We compare a rule-based model (**VADER**) and a transformer-based model (**RoBERTa**) to understand how each performs on real customer reviews.

---

## 📂 Dataset

This project uses the **Amazon Fine Food Reviews** dataset from Kaggle:

🔗 **Dataset:** https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews  
📁 **Path used in Kaggle notebooks:**
/kaggle/input/amazon-fine-food-reviews

yaml
Copy code

⚠️ **Note:**  
The dataset is **large (~300MB)**, so it is **NOT uploaded to GitHub**.  
Instead, instructions are provided to download it from Kaggle before running the project.

---

## 🧠 Techniques Used

### 1️⃣ VADER (Lexicon-Based)
- Fast and lightweight  
- Great for short texts  
- No GPU required  

### 2️⃣ RoBERTa (Transformer Model)
- Context-aware sentiment analysis  
- Uses pre-trained `roberta-base` model  
- Better performance on long and nuanced reviews  

### 3️⃣ HuggingFace Pipeline
- Simple high-level API  
- Allows quick testing of transformer models  

---

## 🏗️ Project Structure
📁 FoodSentimentX
├── sentiment_vader.py
├── sentiment_roberta.py
├── notebook.ipynb
├── README.md
└── requirements.txt

yaml
Copy code

---

## ▶️ How to Run

### 1. Install Dependencies
```bash
pip install -r requirements.txt
2. Download Dataset from Kaggle
bash
Copy code
kaggle datasets download -d snap/amazon-fine-food-reviews
Extract the zip file and place the CSV in your project folder.

3. Run the Notebook / Scripts
bash
Copy code
jupyter notebook
or

bash
Copy code
python sentiment_vader.py
python sentiment_roberta.py
📊 Project Goals
Compare traditional vs. modern NLP models

Visualize sentiment trends

Analyze review polarity

Measure accuracy + performance
