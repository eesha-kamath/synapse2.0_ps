# **Food Allergy Detection System**

## **Overview**
This system helps users detect potential allergens in food items based on their dietary restrictions. By analyzing food labels,  or ingredient lists, the system warns users about allergens and suggests safe alternatives.

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
