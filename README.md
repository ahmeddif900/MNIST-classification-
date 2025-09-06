# MNIST Handwritten Digit Classification

This project demonstrates a simple **Machine Learning pipeline** for classifying handwritten digits (0–9) using the **MNIST dataset**.  
It compares a traditional **Logistic Regression model** with a simple **Convolutional Neural Network (CNN)**.

---

## Project Structure
- `MNIST_classification.ipynb` → Jupyter Notebook with full pipeline
- `README.md` → Project description & usage instructions

---

##  Dataset
The project uses the **MNIST dataset** (60,000 training images + 10,000 test images), which is available as a **built-in dataset** in TensorFlow/Keras.  
No manual download is required.

---

## Requirements
Make sure you have Python 3.8+ installed. Then install the dependencies:

```bash
pip install tensorflow scikit-learn matplotlib seaborn numpy
```
## Running the Notebook

Start Jupyter Notebook:
- Open ai_ml_assignment.ipynb and run all cells.

---
## Results

- Logistic Regression: ~92–94% accuracy
- CNN: ~98–99% accuracy

Visualizations include:

- Confusion matrices
- Model comparison bar chart
- CNN training curves (loss & accuracy)

## Ethics & Reflection

- AI models can make mistakes due to noisy or biased data.
- In real-world use (e.g., postal services, banking), misclassification may cause serious issues.
- Fairness and reliability must be considered during deployment.
- Human oversight should always be included in critical applications.
