# Custom CNN Image Classification

This project implements and compares three convolutional neural network architectures for image classification: a custom-built CNN, VGG16 (transfer learning), and AlexNet (transfer learning). It is built using PyTorch and trained on a dataset with 19 image classes.

## Project Structure

- `Untitled12.ipynb` - Jupyter notebook containing the full implementation, training, evaluation, and prediction logic.
- `colab fix.pdf` - Visual report showing training progress, accuracy, and final outputs.

## Dataset

- Images organized using the `ImageFolder` format.
- Total samples:  
  - Training: 4570 images  
  - Testing: 1131 images  
- Number of classes: 19

## Models Implemented

1. **Custom CNN**  
   - Built from scratch using 4 convolutional blocks.
   - Accuracy on test data: 73.03%

2. **VGG16 (Transfer Learning)**  
   - Pretrained VGG16 with modified classifier layers.
   - Accuracy on test data: 90.72%

3. **AlexNet (Transfer Learning)**  
   - Pretrained AlexNet with customized output layer.
   - Accuracy on test data: ~90%

## Technologies Used

- Python
- PyTorch
- torchvision
- Google Colab
- PIL
- matplotlib

## Instructions to Run

1. Open the `Untitled12.ipynb` notebook in Google Colab.
2. Ensure dataset is mounted via Google Drive.
3. Run all cells sequentially to train and evaluate models.
4. Modify the prediction path to test with custom images.

## Author

Parth Hasolkar  
LinkedIn: https://www.linkedin.com/in/parth-p-h  
LeetCode: https://leetcode.com/u/parth_hasolkar/
Email: parthhasolkar09@gmail.com
