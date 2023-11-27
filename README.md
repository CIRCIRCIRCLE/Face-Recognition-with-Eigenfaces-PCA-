# Face Recognition with Eigenfaces PCA   
## 1.	Overview—Define Problem  
Using principal component analysis (PCA) features to get eigenfaces and implement the function of face recognition (MLE, KNN included).   
## 2.	Data Description  
We obtain the dataset from the Yale face database which consists of a set of 15 grayscale face images. Each image is of dimension 195*231 pixels and each pixel uses 8 bits for grayscale.  
The training set consists of normal faces of 15 people and the test set consists of images of the same 15 people with different expressions or under different lighting.  
## 3.	Project Process  
This project is based on the lecture of principal component analysis.  
For training images: Use the training images to produce a set of eigenfaces. Use Euclidean distance as distance measure for computing 𝑑𝑖. Choose the threshold T that produce the proper results.  
For each test image: the image after subtracting the mean face, its PCA coefficients, the reconstructed face image, distances 𝑑𝑖, and classification result.  
## 4.	Steps and Results(details can be seen in the .docx file)  
  1) read images  
  2) get mean&normalized faces  
  3) use PCA to generate eigenmatrix  
  4) extract pricipal components  
  5) recognize test images  
