**Project Overview**

This project involves training a deep learning model on the COCO dataset using Bahdanau Attention. The implementation leverages TensorFlow and Keras to process image data and generate captions or predictions based on the dataset. The COCO dataset is used for object detection, segmentation, and captioning tasks.

**Dataset**

Dataset Used: COCO 2017

Data Location: coco2017/train2017 for images and coco2017/annotations/person_keypoints_train2017.json for annotations.

Dataset Library: pycocotools

**Installation**

To set up the environment for this project, install the required dependencies:

pip install tensorflow numpy matplotlib pycocotools pillow

**How to Run**

Clone this repository and navigate to the project folder:

git clone <repository_url>
cd <project_folder>

Ensure the COCO dataset is placed correctly within the specified directory structure.

Open the Jupyter Notebook and run the cells step by step:

jupyter notebook Sanika_Assignment_7.ipynb

**Model Details**

Base Model: VGG16

Attention Mechanism: Bahdanau Attention

Optimizer: RMSprop

Loss Function: Categorical Cross-Entropy

**Results**

The model processes COCO dataset images and applies Bahdanau Attention for enhanced feature extraction. Performance evaluation and visualization steps are included in the notebook.


