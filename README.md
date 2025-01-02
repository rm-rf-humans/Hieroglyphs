# Hieroglyph Symbol Detection using YOLOv8

This repository provides an end-to-end solution for detecting hieroglyph symbols using YOLOv8, trained from scratch on a custom dataset. The primary goal is to build a lightweight, efficient, and deployable model for hieroglyph detection, with the added flexibility of converting the trained model to TensorFlow.js for web-based applications.

# Features
	
 - **YOLOv8 Training from Scratch**
 	- Trained on a hieroglyph dataset with symbols size.
 - **Custom Dataset Integration**
	- Dataset: COTA COCO 50.
 - **TensorFlow.js Conversion**
   	- Enables easy deployment in web environments.

## Dataset

The dataset used for this project is COTA COCO 50, sourced from Roboflow. It contains annotated hieroglyph images optimized for training and evaluation.

### Dataset Overview
	-	Annotation Format: COCO.
	-	Classes: Various hieroglyphic symbols.

### To access the dataset:
	1.	Visit COTA COCO 50 on Roboflow.
	2.	Download the dataset in COCO format.

## Setup and Installation

### Prerequisites
	-	Python 3.8 or above
	-	PyTorch
	-	YOLOv8 dependencies

### Steps
	1.	Clone this repository:

	git clone https://github.com/rm-rf-humans/Hieroglyphs.git  
	cd Hieroglyphs  


	2.    Download the dataset from Roboflow and place it in the data/ directory:

data/  
├── train/  
├── val/  
└── test/  


## Model Conversion to TensorFlow.js

Once training is complete, convert the YOLOv8 model to TensorFlow.js for deployment.

### Results
	- **Evaluation metrics (mAP, precision, recall) are logged after each training epoch.**
		- Performance details can be found in the results/ folder.

Contributions

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

Acknowledgments
	- 	Roboflow for providing the dataset.
	-	Ultralytics for the YOLOv8 framework.

For questions or suggestions, please open an issue in the repository.
