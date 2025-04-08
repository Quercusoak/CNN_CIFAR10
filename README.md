# CNN for CIFAR10
Exercise in cnn hyperparameter tuning: explores different CNN architectures, regularization techniques, and optimizers to build a model for image classification on the CIFAR-10 dataset.
It aims to find the best model configuration that maximizes accuracy and minimizes overfitting.

### Overview
1. **Data Preparation:**

   The CIFAR-10 dataset is loaded, normalized using transforms, and split into training and testing sets using DataLoader.

2. **CNN Architecture and Hyperparameter Tuning:**

   Experiment with various hyperparameters such as the number of layers, kernel sizes, padding, activation functions, optimizers (Adam and SGD), learning rates, batch sizes, and regularization techniques (dropout and weight decay).
  
3. **Evaluation Metrics:**
  
   Accuracy on the test set and loss functions (training and validation) are used to evaluate model performance.

4. **Visualization:**

   Training and validation loss are plotted to assess overfitting/underfitting.

5. **Results:**

   The results of each experiment are summarized, including accuracy and bias/variance analysis.

6. **Final Model:**

    The notebook identifies a final model architecture based on the experimental results.
