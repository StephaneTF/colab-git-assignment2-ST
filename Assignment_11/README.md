# Assignment 11 – Image Classification Using Random Forest

## Image Classification Using Random Forest

A Google Colab assignment that classifies flower images using Random Forest and compares its performance with SVM.

## Dataset and Workflow

- Dataset: TensorFlow Flowers, containing 3,670 images across five classes: daisy, dandelion, roses, sunflowers, and tulips.
- Resize images to 32 × 32, normalize pixels, and flatten them into feature vectors.
- Split the data into 80% training and 20% testing sets.
- Tune Random Forest and SVM using GridSearchCV.
- Compare accuracy, precision, recall, F1-score, and confusion matrices.
- Visualize the top 20 Random Forest feature importances.
- Predict the class of an uploaded flower image.

## Tools and Usage

Python, TensorFlow/Keras, scikit-learn, NumPy, pandas, Pillow, and Matplotlib. Open the notebook in Google Colab and run the cells in order. The dataset downloads automatically. Upload a JPG, JPEG, or PNG flower image when prompted.
