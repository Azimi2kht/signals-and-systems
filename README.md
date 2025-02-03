# 🎵 Signals and Systems Course Project  

## 📌 Project Overview  
This project focuses on **signal processing techniques** applied to **musical notes analysis** and **classification using K-Nearest Neighbors (KNN)**. It consists of two main sections:  

1. **Musical Note Analysis and Sound File Generation**  
2. **KNN-Based Classification of Musical Notes**  

The objective of the project is to analyze **musical notes**, extract their **dominant frequencies**, and classify them using **machine learning techniques**. Additionally, we construct an **audio file of "Happy Birthday" in Farsi** based on extracted note sequences.  

---

## 📁 Project Structure  
- `data/` → Directory containing project data files  
  - `Happy_Birthday_Farsi.mp3` → Audio file of "Happy Birthday" in Farsi  
  - `project_document.pdf` → Documentation file for the project  
  - `project_report.pdf` → Report detailing the project findings  
  - `project.ipynb` → Jupyter Notebook for signal analysis and classification  

---

## 🎼 Section 1: Musical Note Analysis  
This section involves **extracting fundamental frequencies** from **musical notes** and constructing a complete **Happy Birthday melody** using signal processing techniques.  

### **Key Steps:**  
1. **Extracting dominant frequencies** from individual note audio samples  
2. **Building a dataset** of musical notes from recorded sound files  
3. **Constructing the "Happy Birthday" melody** by sequencing the notes  
4. **Processing the recorded sound files** (stereo to mono conversion)  
5. **Validating the generated song** to ensure accuracy in pitch and duration  

---

## 🤖 Section 2: Musical Note Classification using KNN  
The second part of the project applies **K-Nearest Neighbors (KNN)** to classify musical notes based on their **extracted frequency components**.  

### **Key Steps:**  
1. **Creating labeled datasets**: 16 musical notes with known frequencies  
2. **Feature Extraction**: Computing dominant frequencies using **FFT (Fast Fourier Transform)**  
3. **Applying KNN classification** to categorize notes in the test dataset  
4. **Evaluating classification performance** with different values of **K**  
5. **Optimizing K**: Determining the best **K-value** for classification accuracy  

The best **K-value** was found to be **4**, balancing classification accuracy and computational efficiency.  

---

## 🛠 Installation & Usage  
### **1⃣ Clone the Repository**  
```bash  
git clone https://github.com/your_username/signals-systems-project.git  
cd signals-systems-project  
```

### **2⃣ Install Dependencies**  
```bash  
pip install -r requirements.txt  
```

### **3⃣ Run the Scripts**  
- To analyze and generate musical notes:  
  ```bash  
  python scripts/note_analysis.py  
  ```  
- To run the KNN classification:  
  ```bash  
  python scripts/knn_classifier.py  
  ```  

---

## 📊 Results & Findings  
- **Accurate frequency extraction** was achieved using FFT.  
- **Successful classification** of musical notes using KNN.  
- **Optimized K-value** was determined to be **4**, maintaining high classification accuracy.  
- **Generated "Happy Birthday" melody** using extracted musical notes.  

---

## 🔗 References  
- Signals and Systems course materials  
- Python libraries: `numpy`, `scipy`, `librosa`, `matplotlib`, `sklearn`, `pydub`  

---

## 🐜 License  
This project is licensed under the **MIT License**.  

---

## ✨ Author  
👤 **SeyyedHamid Azimidokht**  

Feel free to contribute or reach out for collaboration! 🚀


