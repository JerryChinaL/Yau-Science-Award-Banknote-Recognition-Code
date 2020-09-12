# Yau-Science-Award-Banknote-Recognition-Code
Authors: Hangyu Liu, Haoyang Cai
## Project Dependencies:
We are writing this program in python 3.7.6 with the following libraries:
* Pytorch: 1.5.1
* Torchvision: 0.6.1
* Pandas: 0.24.2
* Skimage: 0.15.0
* Numpy: 1.16.4
* Matplotlib: 3.1.0
* cv2: 3.4.1
* Sklearn: 0.21.2
* Augmentor: 0.2.8
      
## File Structure:
* `CNN-Mobilenet.ipynb`: Naive trained CNN model using Mobilenet architecture
* `Adv_training-Mobilenet.ipynb`: Targeted and Non-targeted FGSM attack on the previous model and adversarial training using perturbed images
* `Data_Augmentation.ipynb`: 30x Data augmentation on the training set using augmentor
* `Data_Labeling.ipynb`: Convert labels of images to one-hot encoding format by their folder name, output as .csv
