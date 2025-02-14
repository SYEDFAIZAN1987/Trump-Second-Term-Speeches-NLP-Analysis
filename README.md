## President Donald J. Trump Second Term Speeches: A Natural Language Processing Based Analysis

### Overview
This repository contains an **NLP-based analysis** of **President Donald J. Trump's second-term speeches** using **NLTK, Scikit-Learn, and BERT Transformers**. The project aims to extract key linguistic patterns, topic distributions, sentiment analysis, and named entity recognition from his speeches.

### The source of the Data
The source of the speeches was 'The American Presidency Project' maintained by the University of Santa Barbara. The speeches and addresses used were of the following categories:
1. Interviews
2. News Conferences
3. Spoken Addresses and Remarks
4. Farewell Addresses
5. Inaugural Addresses
   The pool reports were not included as they are mediated via reportage.

### 🔍 Objectives of the Analysis
- **Sentiment Analysis** using **BERT Transformer Model**
- **N-gram Analysis** (Bigrams & Quadgrams)
- **Topic Modeling** using **NMF (Non-Negative Matrix Factorization)**
- **Named Entity Recognition** for frequently mentioned **leaders, cabinet members, and countries**
- **Word Cloud Analysis** of frequently used **adjectives, nouns, and verbs**
- **Speech Engagement Analysis** (Applause & Laughter frequency)
- **Immigration-Related Word Cloud Analysis**

---

## 📊 Results & Visualizations

### 1️⃣ BERT Sentiment Analysis
![BERT Sentiment Analysis](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/BERTpic.png)

- Majority of the sentences in the speeches have **positive sentiment**, with a significant number of **negative** statements as well.
- Sentiment Distribution: 'Positive sentences': 2921, 'Negative sentences': 1923, 'Neutral': 0

### 2️⃣ Bigrams Analysis
![Bigrams](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/Bigrams.png)

- Frequent bigrams include **"thank much", "united state", "president well"**, showcasing key phrases in his speeches.

### 3️⃣ NMF-Based Topic Modeling
![NMF Topic Analysis](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/NMF.png)

- Extracted **5 key topics** from the speeches, including themes on **governance, national security, economy, and audience interaction**.

### 4️⃣ Quadgrams Analysis
![Quadgrams](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/Quadgrams.png)

- Four-word phrases reveal structured patterns in **policy discussions and rally rhetoric**. The motto of the Trump campaigh 'Make America Great again', as expected is represented as the most frequent quadgram.

### 5️⃣ Speech Engagement: Applause & Laughter
![Applause & Laughter](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/applause.png)

- Shows where audience **engagement is highest**, analyzing **"applause" and "laughter" frequency**.
- Total words spoken in official speeches since inauguration were 23981: Interrupted by applause every 147 words and by laughter every 184 words

### 6️⃣ Most Frequently Mentioned Cabinet Members
![Cabinet Mentions](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/cabinet.png)

- Highlights **Trump's second-term cabinet picks** with highest mentions. Elon Musk is mentioned most.

### 7️⃣ Most Frequently Mentioned Countries
![Countries Mentioned](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/countries.png)

- **America, China, Israel, Canada, Iran, Ukraine, Russia** are the most frequently mentioned countries in speeches.

### 8️⃣ Most Mentioned World Leaders
![Leaders Mentioned](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/leaders.png)

- **Joe Biden, Benjamin Netanyahu, Vladimir Putin, Justin Trudeau** lead the mentions in Trump's speeches.

### 9️⃣ Immigration-Related Word Cloud
![Immigration Word Cloud](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/immigrationrefined.png)

- Frequent words include **"border, southern, invasion, security, wall"**, indicating major speech themes.
- Remarkable that the word 'immigrant' makes no apprearence in any speech,whereas 'illegal', 'alien' and 'immigration' are found.

### 🔟 Most Frequent Nouns Used
![Nouns Analysis](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/nouns.png)

- Shows **key entities** (places, policies, events) focused on in speeches.

### 1️⃣1️⃣ Most Frequent Topics Mentioned
![Topics](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/topics.png)

- Major **policy themes** extracted from speeches.

### 1️⃣2️⃣ Most Frequent Verbs Used
![Verbs Analysis](https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis/blob/main/verbs.png)

- Frequently used **action words** indicating key **speech intentions**.

---

## 🔧 Technologies Used
- **Python** (for text processing & NLP)
- **NLTK** (Natural Language Toolkit)
- **Scikit-Learn** (TF-IDF & NMF topic modeling)
- **Hugging Face Transformers** (BERT Sentiment Analysis)
- **Matplotlib & Seaborn** (for visualizations)

---

## 📌 How to Run the Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/SYEDFAIZAN1987/Trump-Second-Term-Speeches-NLP-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Trump Speeches NLP Analysis.ipynb"
   ```

---

## 📬 Contact
For any questions or collaborations, feel free to reach out:
- **Author:** Syed Faizan
- **Email:** faizan.s@northeastern.edu
- **GitHub:** [SYEDFAIZAN1987](https://github.com/SYEDFAIZAN1987)

---

## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify it!

---

### ⭐ If you found this project useful, give it a star on GitHub! ⭐

