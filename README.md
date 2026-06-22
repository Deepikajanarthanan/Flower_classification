<div align="center">

# 🌸 Flower Classification using Data Science 🌸

### *Image Preprocessing for Flower Classification using Python*

<img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/>
<img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pillow-Image%20Processing-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter"/>
<img src="https://img.shields.io/badge/VS%20Code-Editor-blue?style=for-the-badge&logo=visualstudiocode"/>

---

### ⭐ A beginner-friendly Data Science project demonstrating complete image preprocessing for flower classification.

</div>

---

# 📌 Project Overview

This project demonstrates the **complete image preprocessing pipeline** required before building Machine Learning or Deep Learning models.

The project focuses on preparing flower images for classification through various preprocessing techniques.

---

# 🌼 Flower Categories

| Flower | Emoji |
|---------|-------|
| Daisy | 🌼 |
| Dandelion | 🌻 |
| Roses | 🌹 |
| Sunflowers | 🌻 |
| Tulips | 🌷 |

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Programming Language |
| 🔢 NumPy | Numerical Computing |
| 📊 Matplotlib | Data Visualization |
| 🖼 Pillow (PIL) | Image Processing |
| 🤖 Scikit-learn | Dataset Splitting |
| 📒 Jupyter Notebook | Development Environment |
| 💻 Visual Studio Code | Code Editor |

---

# 📂 Dataset

The dataset consists of five categories of flower images.

```
flower_photos
│
├── 🌼 daisy
├── 🌻 dandelion
├── 🌹 roses
├── 🌻 sunflowers
└── 🌷 tulips
```

---

# 🚀 Project Workflow

```text
                        🌸 FLOWER CLASSIFICATION 🌸

                                │
                                ▼

                     📂 Load Flower Dataset

                                │
                                ▼

                    🔍 Explore the Dataset

                                │
                                ▼

                  🖼 Display Sample Images

                                │
                                ▼

                  📏 Resize All Images
                    (180 × 180 Pixels)

                                │
                                ▼

              🔢 Convert Images to NumPy Arrays

                                │
                                ▼

              ⚡ Normalize Pixel Values (0-255 → 0-1)

                                │
                                ▼

          ✂ Split Dataset (80% Train | 20% Test)

                                │
                                ▼

          📊 Feature Extraction (Flatten Images)

                                │
                                ▼

                 ✅ Dataset Ready for ML / DL
```

---

# 📖 Project Steps

## ✅ Step 1 : Import Required Libraries

Import all the required Python libraries for image processing and visualization.

---

## ✅ Step 2 : Load the Dataset

Load the flower image dataset from the project directory.

---

## ✅ Step 3 : Explore the Dataset

Display folder names and verify dataset organization.

---

## ✅ Step 4 : Display Flower Images

Visualize sample images from each flower category.

---

## ✅ Step 5 : Count Images

Calculate the number of images available in every flower category.

---

## ✅ Step 6 : Resize Images

Resize every image to:

```
180 × 180 Pixels
```

This ensures that every image has the same dimensions.

---

## ✅ Step 7 : Convert Images into NumPy Arrays

Convert images into numerical arrays.

Example:

```
Original Image

🌹

↓

NumPy Array

[[23 45 66]
 [12 78 98]
 [44 23 89]
      ...
]
```

---

## ✅ Step 8 : Normalize Images

Pixel Values

```
Before

0 ---------------------- 255

↓

After

0.0 -------------------- 1.0
```

Normalization improves computational efficiency and prepares the dataset for Machine Learning.

---

## ✅ Step 9 : Train-Test Split

Dataset Split

```
Entire Dataset

████████████████████████████

↓

Training Set

████████████████████

80%

↓

Testing Set

█████

20%
```

---

## ✅ Step 10 : Feature Extraction

Flatten every image.

```
Original Shape

(180 × 180 × 3)

↓

Flatten

(97200,)
```

The image becomes a one-dimensional feature vector.

---

# 📁 Project Structure

```
Flower_Classification
│
├── 📒 Flower_Classification.ipynb
├── 📄 README.md
├── 📄 requirements.txt
├── 📁 flower_photos
│      ├── 🌼 daisy
│      ├── 🌻 dandelion
│      ├── 🌹 roses
│      ├── 🌻 sunflowers
│      └── 🌷 tulips
│
└── 📁 Images
```

---

# 🎯 Learning Outcomes

✔ Image Loading

✔ Image Visualization

✔ Image Resizing

✔ NumPy Conversion

✔ Image Normalization

✔ Train-Test Split

✔ Feature Extraction

✔ Dataset Preparation

---

# 🚀 Future Scope

- 🌟 Apply Machine Learning algorithms

- 🌟 Build CNN models

- 🌟 Improve prediction accuracy

- 🌟 Deploy as a Web Application

- 🌟 Develop a Mobile Application

---

# 📈 Project Summary

| Task | Status |
|------|--------|
| Import Libraries | ✅ |
| Load Dataset | ✅ |
| Explore Dataset | ✅ |
| Display Images | ✅ |
| Resize Images | ✅ |
| NumPy Conversion | ✅ |
| Normalization | ✅ |
| Train-Test Split | ✅ |
| Feature Extraction | ✅ |

---

# 💡 Conclusion

This project demonstrates the complete image preprocessing workflow for flower classification.

The processed dataset is fully prepared for future Machine Learning and Deep Learning models.

This project helped me understand:

- Image preprocessing
- Data visualization
- Image normalization
- Feature extraction
- Dataset preparation
- Image-based Data Science workflow

---

<div align="center">

## 👩‍💻 Author

### **Deepika J**

⭐ If you found this project helpful, don't forget to **Star** this repository!

🚀 Happy Coding!

</div>
