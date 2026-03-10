# Chest X-ray Pneumonia Detection

## Project Description
This project classifies chest X-ray images as **Normal** or **Pneumonia** using a **pretrained ResNet50** model.  
It includes **data preprocessing, augmentation, model training, evaluation, and visualization**.

**Dataset:** [Chest X-ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) (Kaggle)

**Goal:** Predict whether a patient has pneumonia from X-ray images.

---


## Repository Structure
Chest_XRay_Classification/
│

├─ Chest_XRay_Classification.ipynb # Notebook with code + outputs

├─ best_model.pth # Saved model (or link if too big)

├─ test_metrics.csv # Metrics table

├─ confusion_matrix.png # Confusion matrix image

├─ requirements.txt # Python dependencies

└─ README.md # Project description



---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Chest_XRay_Classification.git
cd Chest_XRay_Classification
 ```

2. Install dependencies:
   
pip install -r requirements.txt

## Usage

Open the notebook in **Google Colab** or **Jupyter Notebook**:
Chest_XRay_Classification.ipynb


Run the cells **from top to bottom** in the following order:

1. **Dataset loading & augmentation** – Prepare and normalize the X-ray images.  
2. **Model definition (ResNet50)** – Load the pretrained ResNet50 and set up the classifier.  
3. **Training** – Fine-tune the model on your dataset.  
4. **Evaluation** – Compute accuracy, precision, recall, F1 score, ROC-AUC, and confusion matrix.  
5. **Visualizations** – Display sample predictions and generate plots (confusion matrix, sample X-rays).
