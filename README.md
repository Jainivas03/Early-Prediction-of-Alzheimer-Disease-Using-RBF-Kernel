# Early Prediction of Alzheimer Disease And Classifier System Using SVM with RBF Kernel

This project aims to detect various stages of dementia using brain MRI images, focusing on classification into categories like Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented. The model utilizes a Support Vector Machine (SVM) with a Radial Basis Function (RBF) kernel to achieve non-linear classification, handling the complex nature of medical image data.

The project involves several stages, including data preprocessing, model training, evaluation, and visualization. Preprocessing includes resizing the brain MRI images to 256x256 pixels and normalizing them for consistent input to the model. The dataset is then split into training and testing sets.

The SVM model with an RBF kernel is chosen due to its ability to handle non-linear patterns by transforming data into higher dimensions. This helps in drawing more complex decision boundaries for accurate classification. Key metrics such as accuracy, precision, recall, and F1 score are used to evaluate the model's performance. The final model achieves a test accuracy of approximately 86%.

Additionally, the project includes visualization through a confusion matrix heatmap, providing insight into the model's classification performance for each dementia stage.

This project can serve as a foundation for building medical diagnostic systems, helping healthcare professionals detect dementia stages more effectively.
