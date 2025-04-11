# final-project-fda-
🧠 Gender and Age Prediction from Facial Images
This project aims to build a robust deep learning system that predicts gender and age from facial images using Convolutional Neural Networks (CNNs). The model is trained on the UTKFace dataset and built entirely using TensorFlow and Keras, without relying on high-level ML APIs like Scikit-learn.

📁 Dataset
UTKFace Dataset: 20,000+ facial images labeled with age, gender, and ethnicity.

Images are named using a format that encodes this metadata.

🔍 Project Pipeline
Data Acquisition

Collect facial images from the UTKFace dataset.

Data Preprocessing

Resize images to 200x200

Normalize pixel values

Extract age & gender labels from filenames

Train-test split

EDA (Exploratory Data Analysis)

Visualize age distribution

Check gender balance

Sample inspection & correlation analysis

Model Architecture

CNN with shared base layers

Dual outputs:

Gender: Binary classification (sigmoid)

Age: Regression (linear)

Optimized with binary cross-entropy & MSE

Training & Evaluation

Uses batch processing & callbacks

Evaluated with:

Accuracy (gender)

MAE (age)

Prediction & Visualization

Real-time inference on new images

Training curves and result analysis

🛠 Tech Stack
Python

TensorFlow & Keras

Pandas, NumPy, Matplotlib

📸 Sample Output
Model predicts:
👤 Gender: Male
🎂 Age: 26
(Visual output included in notebook)

📄 License
This project is open-source under the MIT License.
