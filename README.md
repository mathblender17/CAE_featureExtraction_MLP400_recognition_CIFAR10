# CAE_featureExtraction_MLP400_recognition_CIFAR10
## Here I have implemented feature extraction using CAE on CIFAR-10 and then using MLP-400 for recognition using keras and TensorFlow

### **MLP-400**
- An MLP is a type of feedforward artificial neural network that consists of multiple layers, including an input layer, one or more hidden layers, and an output layer.
- Hidden layers -400

### **CIFAR-10:**

- Contains **60,000 images of 32x32 pixels** belonging to *10 mutually exclusive* **classes**: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.
- Includes **50,000 training images** and **10,000 testing images**.
- https://paperswithcode.com/dataset/cifar-10 

### **Convolutional Autoencoder (CAE):**

A Convolutional Autoencoder (CAE) is a type of artificial neural network that learns to **compress and reconstruct** input data (often images) in a compressed, low-dimensional representation.

- CAEs are effective for **feature extraction**, as the latent space captures important features of the input data in a low-dimensional form.
- They can be used for dimensionality reduction, data compression, and anomaly detection.
- Compared to regular autoencoders, they are specifically designed for images and leverage the spatial structure of the data.

  ## Results:
  - 1st Approach:![image](https://github.com/mathblender17/CAE_featureExtraction_MLP400_recognition_CIFAR10/assets/114827353/abd63be0-e2fc-45ab-b390-b4f4e2738e22)

  - 2nd Approach:![image](https://github.com/mathblender17/CAE_featureExtraction_MLP400_recognition_CIFAR10/assets/114827353/e1091770-4848-46b4-8b48-f2464c47f803)
    ![image](https://github.com/mathblender17/CAE_featureExtraction_MLP400_recognition_CIFAR10/assets/114827353/dd0f9b50-d7bd-4501-a79a-fb02db54eee1)
    ![image](https://github.com/mathblender17/CAE_featureExtraction_MLP400_recognition_CIFAR10/assets/114827353/faf189d2-fcdf-4d4c-8883-eb86dd54cb94)
    



  ### For future reference: The loss is high and below average accuracy for the MLP400. 
  
