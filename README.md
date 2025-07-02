# 👔👗 Fashion Outfit Recommendation Chatbot

A smart, multimodal AI chatbot that recommends fashion outfits based on text queries. This project combines computer vision and natural language processing to provide intelligent, personalized clothing suggestions.

---

## 📌 Project Features

- 🧠 **Chatbot Interface** for natural interactions  
- 🔍 **Text-to-Image Retrieval** — search using descriptive fashion terms
- 🧠 Uses **BERT** for understanding user fashion descriptions  
- 🔄 **Multimodal Fusion** — combine text + image inputs for better results  
- 📚 Powered by pretrained models and a custom-trained fashion dataset

---

## 🛠️ Tech Stack

| Area            | Technologies Used                            |
|-----------------|-----------------------------------------------|
| Notebook        | Jupyter Notebook                              |
| Backend         | Python                                        |
| CV Model        | ResNet50 (via torchvision)                    |
| NLP Model       | BERT (via Hugging Face Transformers)          |
| AI/ML Models    | ResNet50 (CV), BERT (NLP), FAISS, PCA         |
| Dataset         | DeepFashion or custom folder-based images     |
| Others          | OpenCV, NumPy, Pandas                         |

---

## ⚙️ Installation & Setup

1. **Clone the repo:**
   ```bash
   git clone https://github.com/rishi2100/fashion-outfit-recommendation-chatbot.git
   cd fashion-outfit-recommendation-chatbot
2. **Create a virtual environment & activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # for macOS/Linux
   venv\Scripts\activate     # for Windows
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
4. **launch the notenook:**
   ```bash
   jupyter notebook
4. **Open & Run the notenook:**
   Locate and open fashion-outfit-recommendation-chatbot.ipynb
   Run the cells step-by-step to test text- or image-based outfit recommendations

## ⏳ Coming Features (STAY TUNED):
   - Chatbot UI
   - 🖼️ Image Upload Support— to get outfit recommendations by uploading a picture & RestNet model for extracting visual features from clothing images.

