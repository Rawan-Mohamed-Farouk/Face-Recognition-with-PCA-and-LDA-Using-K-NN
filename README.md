Project Title: Face Recognition with PCA and LDA Using K-Nearest Neighbors

Project Description:
This project focuses on implementing face recognition using Principal Component Analysis (PCA) and Linear Discriminant Analysis (LDA) for dimensionality reduction and K-Nearest Neighbors (KNN) for classification. The dataset comprises images of faces from 40 different subjects, with each subject having 10 grayscale images. The project explores both PCA and LDA to reduce the dimensionality of the dataset, visualize eigenfaces, and classify the images using KNN. Additionally, it includes a comparison of the classifier performance on face and non-face images.

What I Have Learned:
    Image Processing:
        Reading and manipulating images using OpenCV and PIL libraries.
        Converting images into grayscale and flattening them into vectors.

    Data Handling:
        Managing datasets using Pandas DataFrame.
        Splitting datasets into training and testing sets.

    Dimensionality Reduction:
        Implementing PCA from scratch and using sklearn’s PCA.
        Visualizing eigenfaces to understand the principal components.
        Implementing LDA from scratch to maximize class separability.

    Machine Learning Algorithms:
        Using KNN for classification and tuning the classifier by varying the number of neighbors (k).
        Evaluating model performance using classification reports and accuracy scores.

    Data Visualization:
        Plotting images and results using Matplotlib.
        Creating scatter plots to visualize the accuracy of different models.

    Model Evaluation:
        Comparing the performance of PCA and LDA in face recognition.
        Testing the robustness of the classifier with non-face images and visualizing successful and failed classifications.
