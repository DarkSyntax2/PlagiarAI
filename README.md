# PlagiarAI - AI-Powered Plagiarism Checker  

**PlagiarAI** is a web-based plagiarism checker built with **Flask**, **Python**, and **scikit-learn**. It analyzes the similarity between two text samples and provides a plagiarism percentage using advanced NLP techniques.  

## 🔹 Features  
- Compares two text inputs and detects plagiarism.  
- Utilizes **TF-IDF Vectorization** and **Cosine Similarity** for precise results.  
- Displays similarity percentage with an intuitive UI.  
- Mobile-friendly and responsive design.  

## 🔹 Technologies Used  
- **Flask**: Lightweight Python web framework.  
- **scikit-learn**: Implements **TF-IDF** and **Cosine Similarity**.  
- **HTML, CSS, JavaScript**: For frontend development.  
- **Python**: Backend processing and text analysis.  

## 🚀 Setup Instructions  

### Prerequisites  
1. **Python** (>= 3.6)  
2. **Flask** and **scikit-learn** installed (see steps below)  

### 🔧 Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/DarkSyntax2/PlagiarAI.git
   cd PlagiarAI
   ```
2. Create and activate a virtual environment:  
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: `venv\Scripts\activate`
   ```
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
   *If `requirements.txt` is missing, install manually:*  
   ```bash
   pip install flask scikit-learn
   ```

4. Run the Flask app:  
   ```bash
   python app.py
   ```  
   The app will be available at **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**.  

## 🛠 Usage  

1. Open your browser and go to **http://127.0.0.1:5000/**.  
2. Enter two text samples in the input fields.  
3. Click **Check Similarity**.  
4. The app will compute and display the plagiarism percentage.  

### 📌 Example  

#### **Input 1:**  
```
The quick brown fox jumps over the lazy dog.
```
#### **Input 2:**  
```
A fast brown fox leaps over a lazy dog.
```
#### **Output:**  
```
Plagiarism Similarity: 72.34%
```

## 📂 Folder Structure  

```
/PlagiarAI
    /static
        styles.css
        script.js
    /templates
        index.html
    app.py
    requirements.txt
    README.md
``
