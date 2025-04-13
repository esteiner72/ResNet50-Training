# Colorado Plants/Flora Image Classifier using ResNet50

This project uses transfer learning to train a ResNet50 convolutional neural network for image classification. It is trained using an A100 GPU in a Google Colab environment on a custom dataset containing Colorado plants.

## Dataset Summary
- Raw data processed into TFRecord file
- 434 classes (plant species)
- 180710 features (images)
- Between 400 and 600 features per class
- Created using iNaturalist API
- Dataset available at https://drive.google.com/file/d/12WH9Kp7oSqrNHlAMNzbqWIKY8AX1QNBP/view?usp=sharing
- **Note:** iNaturalist terms of use must be followed. Use of this dataset for commerical AI training or other use is strictly prohibited. Full terms of use available here: https://www.inaturalist.org/pages/terms

## Model Summary
- Final validation accuracy: **0.9223 (92.2%)**
- Final validation loss: **0.3364**
- Model implemented in academic capstone team project "LeafQuest"

## Result Plots
![accuracy_plot](https://github.com/user-attachments/assets/7fe27eea-c295-4913-a6ea-641446a06842)
![loss_plot](https://github.com/user-attachments/assets/3d679bfb-fbc8-42f4-b2ce-518d4fca2d44)
