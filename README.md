# **Food Allergy Detection System**

## **Overview**
This system helps users detect potential allergens in food items based on their dietary restrictions. By analyzing food labels,  or ingredient lists, the system warns users about allergens and suggests safe alternatives.

---

## 🎬 Project Demo & Presentation

**Watch the Prototype Demo**  
[![Watch Video](https://img.shields.io/badge/Demo-YouTube-red?logo=youtube)](https://youtu.be/Sf8cmyAvRhA)

**View Project PPT**  
[📎 Download Presentation (PPT)](https://docs.google.com/presentation/d/18UyDO1mgryYWV6AzRmfTa0WHv_ZQ8T_4/edit?usp=sharing&ouid=108039171078965053470&rtpof=true&sd=true)

---

## **Features**
✅ Image-to-text conversion for ingredient extraction  
✅ NLP-based ingredient recognition and allergen detection  
✅ Multilingual support for ingredient recognition  
✅ Alternative food suggestions for safer consumption  

---

## **Datasets Used**
1. **Hugging Face Dataset** – For NLP model fine-tuning and ingredient classification  
2. **Kaggle Dataset** – Comprehensive ingredient and allergen mapping  
3. **Curated Dataset** – Includes local cuisines, alternative names, and cultural variations  

---

## **Tech Stack**
- **Python** (Primary language)
- **OpenCV** (Image preprocessing)
- **PaddleOCR** / **Tesseract OCR** (Text extraction)
- **Hugging Face's `distilBERT` or `RoBERTa`** (Ingredient recognition)
- **pandas**, **NumPy** (Data handling)
- **Flask** / **FastAPI** (Web interface for user interaction)

---

## **Setup Instructions**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/food-allergy-detection.git
   cd food-allergy-detection
