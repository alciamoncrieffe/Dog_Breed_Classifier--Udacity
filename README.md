## Dog Breed Classifier -- Udacity Project

Train a Convolutional Neural Network (CNN) to provide an estimate of the canine’s breed, given an user provided image of a dog.  If supplied an image of a human, the code will identify the resembling dog breed.

### Contents
0. Initial library setup
1. To retrain the CNNs -> Import Datasets
2. Detect Humans
3. Dog detector
3. Train a CNN to Classify Dog Breeds (from Scratch)
4. Train a CNN to Classify Dog Breeds (using Transfer Learning)
5. Use saved model to predict Dog Breeds

##### Initial setup
1. Download dog_classifier_app.ipynb.
2. Step 0 of the dog_classifier_app.ipynb contains the required libraries. Version Python 3.8.5. 
3. To retrain the model, either from scratch or applying transfer learning download the following datasets. 
    - Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
    - Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.

##### Usage
After the initial setup and import of the datasets in step 1, run the code from steps 2-3 for use in later steps. 
But to train a model that can be used to predict dog breeds ASAP skip step 3 and go to step 4 to train the model using transfer learning.
You can then use your own images to test the model, or get a prediction of the dog you closest resemble.

