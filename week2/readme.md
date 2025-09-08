🗑️ Garbage Classification – Stage 1 (30% Completion)
📌 Project Summary

This project aims to build a Convolutional Neural Network (CNN) for automated garbage classification.
The internship work is divided into progressive milestones:

Stage 1 (30%) – Week 1: Dataset setup, preprocessing, and exploratory checks.

Stage 2 (60%) – Week 2: CNN architecture design and training.

Stage 3 (100%) – Week 3: Final tuning, evaluation, and conclusion.

This folder documents the 30% completion milestone (Week 1).

📂 Dataset Details

Dataset Source: Kaggle – Garbage Classification Dataset

Number of Classes: 10 types of waste items

Image Count: ~20,000 total images

Split Used: 70% training, 30% validation (via Keras ImageDataGenerator)

🛠️ Preprocessing Workflow

Imported the dataset from Kaggle environment.

Verified dataset health using Pandas (info(), describe(), null value check).

Reviewed and confirmed class distribution across categories.

Applied preprocessing pipeline:

Rescaling pixel values → [0,1] range

Validation split of 0.3 for train/val separation

Confirmed final split sizes:

Training set: ~15.8k images

Validation set: ~4.0k images

📊 Exploratory Insights

No missing or corrupt samples detected ✅

Bar plot created to show class-wise image distribution.

Inspected random image samples for quality check.

📑 Progress at 30%

Train and validation data generators successfully created.

Dataset is standardized, normalized, and ready for CNN training in Stage 2.

✅ Plan for Next Stage (60%)

Implement baseline CNN with convolution + pooling layers.

Train for multiple epochs and log accuracy/loss.

Experiment with data augmentation and dropout.

🚀 Reproducibility

Open notebook: Week-1_Project_Submission.ipynb

Set dataset path as:

dataset_dir = "/kaggle/input/garbage-classification-v2/garbage-dataset"


Run all cells → preprocessing and EDA will be reproduced.
