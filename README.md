#### friendly-waffle-snowy

# **Dog Breed Identification**

##### Determine breed of Dog in an Image

Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have *all* the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?

In this project, we have a strictly canine subset of ImageNet in order to practice fine-grained image categorization. How well can we differentiate Norfolk Terriers from Norwich Terriers? With 120 breeds of dogs and a limited number training images per class, the problem was more, err, ruff than I anticipated.

### **Data Description**

The dataset consists of a training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal of the competition is to create a classifier capable of determining a dog's breed from a photo.

### **File descriptions**

- ```train.zip``` - the training set, you are provided the breed for these dogs
- ```test.zip``` - the test set, you must predict the probability of each breed for each image
- ```sample_submission.csv``` - a sample submission file in the correct format
- ```labels.csv``` - the breeds for the images in the train set

Use Kaggle API to download [dataset](https://www.kaggle.com/competitions/dog-breed-identification/data):
```console
kaggle competitions download -c dog-breed-identification
```
