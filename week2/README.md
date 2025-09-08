🗑️ Garbage Classification — Week 2

This repository documents Week 2 progress of the Garbage Classification project for the AICTE Edunet Internship (AI/ML track).
Focus this week: Convolutional Neural Network (CNN) model building, training, and performance improvement.

📂 Dataset

Source: Kaggle Garbage Classification Dataset (~20,000 images across 10 categories).

Classes include: cardboard, glass, metal, paper, plastic, trash, biological, battery, clothes, shoes.

Train/validation split: 70% train (~17.5k images), 30% validation (~7.5k images).

🧠 Model Development
1. CNN Architecture

Input layer: 32×32 RGB images

2 Convolutional layers with ReLU + MaxPooling

Flatten + Dense hidden layers

Dropout layer (0.5) to reduce overfitting

Output layer: Softmax with 10 classes

2. Data Augmentation

Rotation (±20°)

Horizontal flip

Zoom, width/height shift

Rescale factor = 1/255

3. Training Setup

Optimizer: Adam (learning rate = 0.001)

Loss: Categorical Crossentropy

Batch size = 32

Epochs = 10

📊 Results

Training Accuracy: ~92%

Validation Accuracy: ~87%

Accuracy/Loss curves showed good learning with minimal overfitting.

Confusion Matrix indicated strong performance across all 10 classes.

⚡ Key Improvements (vs Week-1 Baseline)

CNN improved accuracy drastically compared to Logistic Regression baseline (~32%).

Data augmentation helped in better generalization.

Dropout layer reduced overfitting.

Plots of training vs validation metrics confirmed stability.

🚀 Next Steps (Week 3 Preview)

Fine-tune CNN hyperparameters (layers, learning rate, epochs).

Compare different optimizers (Adam, RMSprop, SGD).

Document results in Week-3 PPT Template.

Prepare for deployment-oriented report.

▶️ How to Run

Open the notebook Week-2_Project_Submission.ipynb.

Ensure dataset path is correct:

dataset_dir = "/kaggle/input/garbage-classification-v2/garbage-dataset"


Run all cells to reproduce preprocessing, model training, evaluation, and plots.

👨‍💻 Contributors

SURAJ KUMAR SHARMA — AICTE Edunet Intern

(End of Week 2 log)
