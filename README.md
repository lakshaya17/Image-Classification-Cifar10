# Image Classification for Cifar10 Dataset

## This assignment was done as a part for course Applied Artificial Intelligence

### Process include:

1. Used the following source: keras.datasets.cifar10
2. Different number of neurons are tested (efficient code requires low computational cost (less number of neurons with higher accuracy))
3. Almost 30 CNN architectures are tested and out of which, 3 models are chosen to make the comparisons for 
   * Accuracy of the model -- Both on training and tesing dataset
   * Prediction performance
4. Out of which, one best model is selected based on the validation accuracy. 
5. With that model, different types of optimizers are applied including
  * Adam
  * SGD
  * AdaDelta
6. Plots for training loss, training accuracy, validation loss, and validation accuracy are visualized

7. An *EarlyStopping* is implementd and the model is a saved at a *checkpoint* ,
   - to implement EarlyStopping and save model at a checkpoint when
      - no progress has been acheived and/or
      - overfitting has been observed.
8. Model is saved and restored.
9. Various metrics are displayed that can be helpful to the customer/reader.


## Result:
* Best accuracy is provided by Optimizer - SGD for the best model with ~83% accuracy.
