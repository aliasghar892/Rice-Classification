# Rice Image Classification using PyTorch

dataset contains 75000 images from 5 diffrent type of rices :

1. Arborio
2. Basmati
3. Ipsala
4. Jasmine
5. Karacadag

15000 images for each class of rice

dataset : https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset

## Results (they may differ in model layers and some settings like number of epoches and learning rate)

1. simple nn with cuda resulted in 97.6% acc in 10 minutes, 5 epoches, 1e-3 learning rate
2. nn with PCA transformation (250 components) resulted in 97.8% acc in 18 minutes, 4 epoches, 1e-2 learning rate, using dropouts
