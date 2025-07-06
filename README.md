# 🧠 AI-Powered Medical Image Captioning

## Detection of Pneumonia, Cardiomegaly, and Rib Fracture from Chest X-Rays

### 🔬 Project Overview

This project implements an AI-powered system that automatically analyzes chest X-ray images to detect and describe the presence of **Pneumonia**, **Cardiomegaly**, and **Rib Fracture** using image captioning and classification models. It combines deep learning techniques in computer vision (CNNs) with natural language generation (image captioning) to provide interpretable and accurate descriptions of medical conditions.

---

### 📌 Features

* ✅ Upload and analyze chest X-ray images.
* 🧠 Deep learning-based detection of:

  * Pneumonia
  * Cardiomegaly
  * Rib Fracture
* 📄 Automatic image captioning with clinical terminology.
* 📊 Visualization of predictions and attention maps.
* 🌐 User-friendly web interface (optional if web frontend is included).

---

### 🖼️ Sample Output

> **Input:** Chest X-ray Image
> **Output Caption:** *"The X-ray shows signs of cardiomegaly with no evidence of rib fracture. Mild patchy opacity suggests possible pneumonia."*

---

### ⚙️ Technologies Used

* **Python**
* **TensorFlow / PyTorch**
* **CNN Architectures (e.g., ResNet, DenseNet)**
* **LSTM / Transformer for Captioning**
* **Flask / Django / FastAPI** (for backend)
* **React / HTML-CSS-JS** (if frontend is used)
* **OpenCV, PIL** for image handling
* **Matplotlib / Seaborn** for visualization

---

### 🗃️ Dataset

The model is trained and evaluated on publicly available medical image datasets:

* **NIH Chest X-ray Dataset**
* **RSNA Pneumonia Detection Challenge**
* **MIMIC-CXR** (if used)

> 📝 Ensure compliance with dataset licenses when distributing or deploying the app.

---

### 🚀 Installation & Setup

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-medical-image-captioning.git
cd ai-medical-image-captioning
```

#### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

#### 3. Install Requirements

```bash
pip install -r requirements.txt
```

#### 4. Prepare Dataset

* Download and preprocess X-ray images.
* Update dataset path in config files or training script.

#### 5. Train Model (if not using pretrained)

```bash
python train.py
```

#### 6. Run Inference or Start Web App

```bash
python app.py   # For Flask/Django backend
```

---

### 🧪 Model Architecture

* **Encoder:** Convolutional Neural Network (CNN) extracts features from X-ray.
* **Decoder:** RNN (LSTM) or Transformer generates textual description.
* **Classifier Head:** Predicts disease class probabilities.

---

### 📈 Evaluation Metrics

* **Classification Accuracy / Precision / Recall / F1-score**
* **BLEU / METEOR / ROUGE / CIDEr** for caption quality
* **Confusion matrix** for disease classification
* **Attention maps** for interpretability (Grad-CAM)

---

### 💡 Use Cases

* Assist radiologists in detecting multiple thoracic conditions.
* Provide explainable AI reports for X-ray scans.
* Improve diagnostic efficiency in low-resource hospitals.

---

### ⚠️ Disclaimer

This project is for **educational and research purposes only**. It is not approved for clinical use. Always consult a licensed medical professional for diagnosis and treatment.

---

### 👨‍💻 Author

**oluwatomisin oluwapelumi**
\[LinkedIn Profile] | \[GitHub Profile] | \[pelumit61@gmail.com]

---

### 📜 License

This project is licensed under the MIT License. See `LICENSE` file for more information.

---

### 📚 References

* [NIH Chest X-rays Dataset](https://www.kaggle.com/datasets/nih-chest-xrays)
* [RSNA Pneumonia Challenge](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge)
* [MIMIC-CXR Database](https://physionet.org/content/mimic-cxr/)
