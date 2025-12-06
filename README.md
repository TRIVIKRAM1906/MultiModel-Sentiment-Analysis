# MultiModel-Sentiment-Analysis
Absolutely — here is your content **perfectly formatted in clean GitHub-ready Markdown!**
Just copy–paste this into your `README.md` 🚀🔥

---

```markdown
# 🍽️ Sentiment Analysis on Amazon Fine Food Reviews using VADER & RoBERTa

This project explores **Natural Language Processing (NLP)** techniques to analyze sentiment from the popular **Amazon Fine Food Reviews** dataset.  
We compare a traditional lexicon-based model (**VADER**) with a modern deep-learning transformer (**RoBERTa**) to evaluate performance differences on real-world customer reviews.

---

## 📂 Dataset

This project uses the **Amazon Fine Food Reviews** dataset from Kaggle:

➡️ **Dataset link:** https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews  
➡️ **Kaggle path used in notebook:**
```

/kaggle/input/amazon-fine-food-reviews

```

⚠️ The dataset is **~300MB+**, so it is **NOT uploaded to GitHub** to avoid large file size.  
Instead, instructions are included for downloading it from Kaggle before running the project.

---

## 🧠 Techniques Used

### 1️⃣ VADER (Rule-based Lexicon Approach)
- Great for social-media style text  
- Fast, lightweight, and requires no GPU  
- Performs well on short reviews  

### 2️⃣ RoBERTa (Transformer-Based Model via HuggingFace)
- Context-aware sentiment understanding  
- Uses the pre-trained **roberta-base** sentiment model  
- Higher accuracy on nuanced and longer reviews  

### 3️⃣ HuggingFace Pipeline
- Simplified wrapper for quick inference  
- Supports easy plug-and-play model testing  

---

## 🏗️ Project Structure

```

📁 FoodSentimentX
├── sentiment_vader.py
├── sentiment_roberta.py
├── notebook.ipynb
├── README.md
└── requirements.txt

````

---

## ▶️ How to Run

### **1. Install Dependencies**
```bash
pip install -r requirements.txt
````

### **2. Download Dataset from Kaggle**

You must download the dataset manually (not included in GitHub):

```bash
kaggle datasets download -d snap/amazon-fine-food-reviews
```

Unzip it and place the CSV file in your project directory.

### **3. Run the Notebook / Scripts**

```bash
jupyter notebook
```

Or run Python scripts directly:

```bash
python sentiment_vader.py
python sentiment_roberta.py
```

---

## 📊 Goals of the Project

* Compare rule-based vs. transformer-based sentiment models
* Evaluate accuracy, speed, and limitations
* Understand real-world review sentiment patterns
* Visualize review distribution, polarity, and predictions

```
