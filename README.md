
# 📄 Resume Clustering using Machine Learning

This project automates the clustering of resumes based on textual similarity, making HR shortlisting more efficient by eliminating manual tagging. It leverages **TF-IDF** for vectorization, **KMeans** for unsupervised clustering, and provides an interactive **Streamlit** interface for visualization and download.

---

## 🚀 Features

- 🔍 **TF-IDF Vectorization** to extract textual features from resumes  
- 🤖 **KMeans Clustering** to group similar resumes together  
- 🌐 **Streamlit Web App** to upload, cluster, and download resumes  
- 📂 Supports bulk PDF uploads with real-time feedback  

---

## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- Streamlit  
- PyPDF2  
- Pandas  

---

## 📦 Installation

```bash
git clone https://github.com/vivekvarma-01/Resume-Clustering.git
cd Resume-Clustering
pip install -r requirements.txt
```

---

## 💻 Running the App

```bash
streamlit run app.py
```

---

## 📁 Usage

1. Launch the app using the command above.  
2. Upload multiple resume PDFs.  
3. Choose the number of clusters.  
4. View clustered resumes and download grouped results.  

---

## 📊 Sample Screenshot

<!-- Optional: Add an actual image in your repo and uncomment below -->
<!-- ![App Screenshot](./screenshot.png) -->

---

## 🧠 How It Works

- **Text Extraction:** Extracts text from PDFs using PyPDF2  
- **Vectorization:** Applies TF-IDF to convert raw text to numerical features  
- **Clustering:** Uses KMeans to group similar resumes  
- **Output:** Presents results by cluster and allows downloading clustered sets  

---

## 📌 TODO

- [ ] Add PDF preview in-app  
- [ ] Support DOCX resumes  
- [ ] Improve model with word embeddings  
