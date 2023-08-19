#### Inbuilt investigation of Spatial and Spectral features of 

Hyperspectral Image Classification through Res2DCLSTM
# Illustration
We combined 2DCNN with Batch Normalization and shortcut 2D CNN connection, Resnet and LSTM model added and they helped to overcome all the challenges which are faced during exclusively and severally applying all the supervised models at the time of Hyperspectral image classification.


## Prerequisites
We have implemented this method on Google Colab. The version of Keras is 2.4.3, version of Python is 3.6.9 and version of Tensor flow is 2.3.1.
## How to run the code
* At first we need to import some libraries of Google credentials.
* After that we have to get the permission granted from the Gmail account to access any files from the Google Drive. Then we need to copy that generated link from the Gmail account and paste it on google colab.
* Each and every file has a unique id and that id can be obtained from google drive. If we want to have an access to a particular data set we
need to copy that id from google drive and subsequently paste it on google colab.
* In the next phase we have defined some functions like split of training testing ratio, dimension reduction technique and creating image cubes.
* After that we have to fix some hyperparameters namely window size; number of bands; training ratio and testing ratio.
* Afterwards we trained our ResnetConvLstm model.
* Finally we obtained the accuracy of our model and to visualize the predicted image and the ground truth image of that data set.
# DATA SOURCE
We got three different types of hyperspectral datasets namely Indian Pines, Pavia University and Botswana.
from the site: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes  

## Cite: Please cite the original publication if you utilize Res2DCLSTM and HSI-Survey code in your research.
Banerjee, Anasua, and Debajyoty Banik. "Resnet Based Hybrid Convolution LSTM for Hyperspectral Image Classification" Multimedia Tools and Applications (2023).
