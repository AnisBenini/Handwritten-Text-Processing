# Handwritten Text Processing & Segmentation


## 📋 Project Overview
This project was developed as part of the second practical work (TP2) in computer vision. The main objective was to segment handwritten characters from a scanned image using region-growing segmentation techniques, followed by post-processing for text recognition.

## 🚀 Features
- **Image Preprocessing:** Grayscale conversion, noise reduction, and contrast normalization.
- **Region-Growing Segmentation:** Isolating handwritten characters based on homogeneous regions.
- **Post-Processing:** Cleaning small noise regions and extracting sub-images for each character.
- **Advanced Work:**
  - **Word-by-Word Segmentation:** Implemented in `WordByWord.ipynb`.
  - **Arabic OCR:** Using `ArabicOCR.ipynb` for Arabic text recognition.

## 🛠️ Technologies Used
- **Python** 🐍
- **NumPy:** Matrix operations
- **Matplotlib:** Visualization
- **PIL:** Image loading and processing
- **OpenCV:** Advanced image processing
- **ArabicOcr:** Optical Character Recognition for Arabic texts

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/AnisBenini/Handwritten-Text-Processing-&-Segmentation.git

# Navigate to the project directory
cd Handwritten-Text-Processing-&-Segmentation

# Install required libraries
pip install numpy matplotlib pillow opencv-python arabic-ocr
```

## 🖼️ How to Use
1. Run the main segmentation notebook:
```bash
jupyter notebook Tp2-VA.ipynb
```
2. For Arabic OCR:
```bash
jupyter notebook ArabicOCR.ipynb
```
3. For word-by-word segmentation:
```bash
jupyter notebook WordByWord.ipynb
```

## 📊 Results & Analysis
- **Effective Segmentation:** Clear isolation of handwritten characters.
- **Word-by-Word Extraction:** Accurate splitting of text into individual letters.
- **Arabic OCR:** Successful recognition of Arabic text from images.

## ⚡ Challenges Faced
- Noise artifacts during region growing.
- Handling overlapping characters.
- OCR performance on complex Arabic scripts.

## 💡 Future Improvements
- Integrate deep learning models for better segmentation.
- Improve OCR accuracy with custom-trained models.
- Optimize region-growing algorithms for faster processing.

---

Made with ❤️ for Computer Vision & Text Processing & Segmentation enthusiasts!

