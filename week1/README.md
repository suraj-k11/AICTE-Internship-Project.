#  Garbage Classification — Week 1 Progress

This is **Week 1** deliverable for the Garbage Classification project under the AICTE Edunet Internship (AI/ML track).  
Focus this week: importing dataset, preprocessing images, and preparing data pipeline for CNN training.

---

## Dataset Overview

- **Source**: Kaggle Garbage Classification Dataset (~20,000 images across 10 categories)  
- **Classes** include: cardboard, glass, metal, paper, plastic, trash, etc.  
- **Train/Validation Split**: 70% train (~15,800 images), 30% validation (~4,200 images) via `ImageDataGenerator`.

---

## Preprocessing Workflow (Week 1)

1. **Data Inspection**
   - Loaded dataset structure and verified counts per class.  
   - Checked for missing files or format issues (none found).  
2. **Normalization & Splitting**
   - Rescaled pixel values using `rescale=1./255`.  
   - Defined `validation_split=0.3` to partition data automatically.  
3. **Data Pipeline Setup**
   - Created `train_generator` and `val_generator` using `flow_from_directory`.  
   - Verified classes and sample batches loaded correctly.

---

## Status Update (Current Output)

- Data generators initialized successfully.  
- Data is clean, normalized, and ready for CNN training.

---

## What’s Next (Week 2 Roadmap)

- Design and train a **CNN model** (2–3 convolutional + pooling layers).  
- Visualize performance: training vs validation accuracy/loss curves.  
- Optimize with **data augmentation**, dropout, or learning rate adjustments.  
- Compare results with Week 1 baseline to show improvement.

---

## How to Reproduce (Run Instructions)

1. Open the notebook: `Week-1_Project_Submission.ipynb` in Kaggle or Colab.  
2. Modify dataset path if needed:
   ```python
   dataset_dir = "/kaggle/input/garbage-classification-v2/garbage-dataset"

