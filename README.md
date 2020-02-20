# Image Classifier Project

Taken from the Udacity course for AI Programming in Python, herein lies the code for an Image Classifier that is used on plants. 

## Project Goal

The given intention was to take a pre-trained CNN and feed it images of plants and a list of species for reference. The hopeful goal was an accuracy rate of >70%. 

Each .py has it's purpose listed below:

+ train.py uses the pre-trained VGG CNN from pytorch's torchvision module to differentiate the different species of plants listed in the .json file. After running a number of epochs (approx 8) determinted by the user, the file saves a checkpoint to be used as reference later.
+ predict.py takes the checkpoint as input, and randomly selects an image, providing the top 5 species names that most match said image. The value is a percentage. 
+ utils.py provides the functions to save and load a checkpoint. 
+ workspace-utils.py was provided by the course to keep environment active while waiting for the epochs to run. 
