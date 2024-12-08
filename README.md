# Wild-life-detection
## Team members: <br>
Radhika Raghuwanshi - G32395729 Github username: GWRAD <br>
Divya Sree Vadlamudi - G48698217 Github username: DivyaSreeVadlamudi <br>
# Object Detection on Animal Dataset <br>
This project outlines the process of training and evaluating a YOLOv8 model for object detection using an animal dataset. The goal is to recognize and classify objects (animals) in images. The training involved using annotated images with bounding boxes, which are crucial for teaching the model to localize objects within an image. Bounding boxes are drawn around the objects (animals) in the dataset images, and these serve as ground truth for the model to learn object localization.

To enhance training efficiency, a pre-trained YOLOv8 model was used as a starting point. Transfer learning with a pre-trained model allows the model to leverage previously learned features from a large dataset (e.g., COCO dataset) and fine-tune on the specific animal dataset, improving performance and reducing the amount of time and data required for training.

## Objectives: <br>
1. Detect and Localize Animals. <br>
2. Use a CNN-based object detection model to detect animals in wildlife images , drawing bounding boxes around them. <br>
3. Improve Accuracy through Pre-trained Models. <br>
4. Leverage transfer learning from pre-trained object detection models YOLO to improve accuracy. <br>
## Evaluate Performance on Wildlife Data: <br>
Use standard evaluation metrics such as  precision, and recall for bounding box predictions. <br>

# Dataset Overview: <br>
## 1. Dataset Source <br>
    This dataset is available on Kaggle, contributed by Antoreep Jana. 
    It is publicly accessible and can be downloaded for educational and research purposes. 
    Link :https://www.kaggle.com/datasets/antoreepjana/animals-detection-images-dataset  
## 2. Dataset Composition <br>
    80 Unique Classes: Each class corresponds to a specific animal species or category.
    Class Selection: Due to the large size of the dataset, we have selected only 5 classes ('Cheetah', 'Fox', 'Jaguar', 'Lion', 'Tiger') for training. This decision was made to simplify the training process and reduce the computational resources required. By focusing on a smaller subset of classes, the model can be trained efficiently
    Images: Each subclass contains multiple images representing a particular animal. 
    Labels : Each subclass contains labels of their corresponding images. 

  # Result Folder: <br>
  Google drive link - <a>https://drive.google.com/drive/folders/1w_7c4IsCJT0zRTi4rOQc7xvKfXmP7Hz0?usp=sharing <a>

 # Colab Notebook: <br>
 link: https://colab.research.google.com/drive/1kgJs7EbkJG5AUDidbtHBD3ypGIJQag4d?usp=sharing
