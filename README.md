# CanSat Picture-Segmentation

Object-Segmentation model created for Project Trailblazer’s project in 2019/2020 CanSat competition. Program divides pictures taken by our probe into categories like forest, grass, sand. 

In this project we used solutions such as: NumPy, PIL, PyTorch, TensorFlow
## Folder structure
We created two different models, each using different machine learning solutions.
### Both projects contain
 - #### Data
 Folder containing photos used for training our models.
 - #### DataPreparation.ipynb
We needed to create a dataset containing substantial amount of photos. Therefore, we created a simple program that loads a large picture, resizes it to 
a multiplicity of 224 and cuts it into smaller pictures (224x224px)
 - #### App.ipynb
 - 
Program that loads photos made by probe and 
pre-trained weights to generate final output of this branch of project.
 - #### Test.png
 Photo to test both models.
 ### Project A
 - #### Model.ipynb
Program that loads photos from data folder and uses RandomForestClassifier to generate weights for the machine-learning model.
 ### Project B
 
 - #### ResNet18.ipynb
 Program that loads photos form data folder and 
 pre-trained ResNet18 model. We have had the dense layer cut and replaced it with our own one. Then it saves generated weights

 

## Example
jdjdjd
## Author

**Adam Kaniasty** as a member of [Project Trailblazer](http://www.project-trailblazer.pl/) Team.

