## Support Vector Machine for Cat and Dog Image Classification

**Objective:**
To classify images of cats and dogs using a Support Vector Machine (SVM) on a Kaggle dataset.

**Description:**
This project involves implementing a Support Vector Machine (SVM) to classify images of cats and dogs. The dataset used for this project contains images of cats and dogs stored in separate folders. The primary objective is to preprocess the images, train an SVM model, and evaluate its performance.

**Steps Involved:**

1. **Data Loading and Preprocessing:**
   - Images from the dataset were loaded and resized to a uniform size of 128x128 pixels.
   - The images were converted to arrays and labeled, with cat images labeled as 0 and dog images as 1.
   - The image data was split into training and testing sets with an 80-20 split.
   - The images were flattened and normalized to prepare them for the SVM model.

2. **Model Training:**
   - A Support Vector Machine (SVM) with a linear kernel was trained on the training data.
   - The model aimed to learn the distinct features of cat and dog images for accurate classification.

3. **Model Evaluation:**
   - The trained SVM model was used to predict labels for the test set.
   - The model's performance was evaluated using accuracy as the metric, achieving an accuracy of 65.53%.

**Conclusion:**
The project successfully implemented an SVM for image classification, demonstrating the importance of data preprocessing and normalization in achieving effective classification results. Future improvements could involve experimenting with different kernels, hyperparameter tuning, and exploring advanced image processing techniques to enhance the model's performance.

**Dataset Link -** https://www.kaggle.com/c/dogs-vs-cats/data
