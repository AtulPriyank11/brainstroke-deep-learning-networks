# brainstroke-deep-learning-networks
Image Processing domain that integrates the use of some deep learning networks for the identification of brain stroke.
Code for Brain Stroke Detection using different deep learning networks with different optimizers. Deep learning networks are particularly accurate for computer vision applications like object categorization. VGG-16, VGG-19 and InceptionV3 has been used for the detection tasks. The dataset was shrink into 3 folders named training set, testing set and validation set.
According to that, some data pre-processing techniques were applied. Image folders are recognized and then by using ImageDataGenerator() method, the total number of images are shown where image cropping, horizontal shift and many more etc. is done at the backend. For Normalizing the data, Data Normalization techniques are used like resizing.

Then the pretrained weights of the model are called. Only last few layer’s changes are being done.
Then we train the model, find accuracy, loss etc. Model is evaluated and model’s classification report is taken out like precision, recall, f1-score, and confusion matrix. Then we test the model by passing a image that will rectify that the image contains stroke or Not Stroke aka Normal or Abnormal.
![Workflow Diagram for Detection of Brain Stroke](https://github.com/AtulPriyank11/brainstroke-deep-learning-networks/assets/134692859/c3ab9ad7-b410-4cf6-b081-0011ced2e090)
