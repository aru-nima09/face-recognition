# Face Recognition using PCA and kNN

## Project Description

This project implements an efficient **Face Recognition System using Principal Component Analysis (PCA)** for dimensionality reduction and **k-Nearest Neighbor (kNN)** for classification. The system is trained and tested using the **ORL Face Dataset** and evaluated based on recognition accuracy and computational performance.

---

## Dataset

**ORL Face Dataset (AT&T Database of Faces)**

* Total Subjects: 40
* Images per Subject: 10
* Total Images: 400
* Image Size: 92 × 112 (grayscale)

Dataset structure:

```
s1, s2, s3, ..., s40
(each folder contains 10 face images)
```

---

## Technologies Used

* Python
* Google Colab
* NumPy
* OpenCV
* Scikit-learn
* Matplotlib
* Pandas

---

## Workflow

1. Load and preprocess images
2. Convert images to grayscale and resize
3. Flatten image matrices into vectors
4. Apply PCA for dimensionality reduction
5. Train kNN classifier
6. Test model and evaluate performance
7. Compare results for different PCA components

---

## How to Run

### 1️. Clone the Repository

```bash
git clone https://github.com/your-username/face-recognition-pca-knn.git
cd face-recognition-pca-knn
```

---

### 2️. Install Required Libraries

```bash
pip install numpy opencv-python scikit-learn matplotlib pandas
```

---

### 3️. Upload Dataset

Place the ORL dataset folders (`s1` to `s40`) inside the project directory.

---

### 4️. Run the Notebook

Open and run:

```
Face_Recognition_PCA_kNN.ipynb
```

---

## 📊 Results

| PCA Components | Accuracy |
| -------------- | -------- |
| 50             | ~90%     |
| 100            | ~90%     |
| 150            | ~88.33%  |

> Best trade-off between accuracy and speed is achieved at **100 PCA components**.

---

## Output

* Classification accuracy
* Explained variance graph
* Training and testing time comparison

---

## Applications

* Biometric authentication
* Attendance systems
* Surveillance
* Access control systems

---

## Authors

* Arunima Nithin Nair
* Gayathri S Menon
* Jania Jose
* Joel Santhosh

---

## License

This project is for **academic and educational use only**.

---
