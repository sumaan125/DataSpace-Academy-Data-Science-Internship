# Rice Image Classification using CNN

**Notebook:** [Rice_Image_Classification.ipynb](Rice_Image_Classification.ipynb)

## Dataset
[Rice Image Dataset (Kaggle)](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset). It is large and not stored in this repository.

## Workflow
1. Mount Google Drive in Colab and unzip the dataset
2. Split into train / validation / test folders with `splitfolders`
3. Load images with `ImageDataGenerator` at 160x160x3
4. Model: Conv2D(32), Conv2D(64), pooling, Dense(320, ReLU), Dense(5, softmax)
5. Compile with Adam and categorical cross-entropy; train 5 epochs (training accuracy about 99%)
6. Evaluate with confusion matrix and classification report (**~99% accuracy** on 11,250 test images)
7. Predict on single images
