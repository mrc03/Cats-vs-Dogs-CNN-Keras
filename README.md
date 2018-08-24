/*
   Author:: Raj Mehrotra
   Date:: 25-08-2018
   
 */
 
The famous Cats-vs-Dogs dataset. 

I have used a self laid ConvNet to classify the image into 2 classes either a Dog or a Cat. 

The images used are of 100*100 pixels each. The images are first converted to the numpy array of pixel values using the python ZipFile module. The images are then divided into the training ,cross-validation,testing set containing 20000 , 5000 , 12500 images respectively. Also I have used data augmentation technique to avoid chances of overfitting the model.

Finally I achieved a decent accuracy of about 88 % on the validation set.
