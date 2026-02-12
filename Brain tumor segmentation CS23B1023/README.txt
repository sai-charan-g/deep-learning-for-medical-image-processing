# Brain MRI Tumor Segmentation – Otsu vs Sauvola

This project compares two classical thresholding methods for brain tumor
segmentation using MRI images.

The segmentation performance is evaluated using Dice score and Jaccard index.

---

## Methods used

- Otsu global thresholding
- Sauvola adaptive thresholding

---

## Dataset

Brain Tumor Segmentation dataset (Kaggle)

Link:
https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation

---

## Evaluation metrics

- Dice score 
- Jaccard index (sklearn)

---

## How to run (Kaggle notebook only)

1. Open a new Kaggle notebook.

2. Add the dataset using the **Add data** button and select  
   **Brain Tumor Segmentation** dataset from the link above.

3. Upload the notebook file:

   Braintumor_Segmentation_.ipynb

4. Make sure the dataset path inside the notebook is:

```python
DATA_PATH = "/kaggle/input/brain-tumor-segmentation"
