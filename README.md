# GLAUCOMA DETECTION USING DEEP LEARNING

Glaucoma are the leading cause of blindness in the working age population all over the world. Glaucoma through colour fundus images requires experienced clinicians to identify the presence and signiﬁcance of many small features which, along with complex grading system, makes this difﬁcult and time consuming task. Here we propose a CNN approach to diagnosing Glaucoma from fundus images and accurately classifying its severity. We develop a network with Convolutional Neural Network(CNN) architecture and data augmentation which can identify the intricate features involved in the classiﬁcation task such as micro aneurysms, exudate and haemorrhages on the retina. We train this network using a high-end graphics processor unit (GPU). An open source Kaggle dataset is used as an input for DRand RIGA dataset is used as an input for Glaucoma. Total number of 25000 images are used for diabetic retinopathy and the testing accuracy for DR is 86%. Total number of 2664 images are used in glaucoma and the testing accuracy for glaucoma is 94%.

# The architecture consists of
	Data Pre-processing
	Data Augmentation
	Model trained using CNN
	Class Prediction
	
# Datasets

The Dataset for Glaucoma contains 2 classes. A total number of 2664 images are used for glaucoma.

class 0 for Non Glaucoma ( 1488 images )
class 1 for Glaucoma ( 1176 images )

# Data Pre-processing:
	Conversion of RGB images to Grayscale images. Conversion to grayscale images are done to improvement in testing accuracy.

# Data Augmentation : 
	Rotation, Zooming, Shearing, Horizontal and Vertical Flip are done on images of all classes.
	Data augmentation is done for balancing the classes with equal number of images .
# Model trained using CNN:
	Training the model by using CNN layers.
	We have used 3 convolutoinal & max pooling layer, A dropout, Dense and a Fully Connected Layer.

# The program runs in Google Colab.

Upload the source file and the datasets to the Google Drive.
Open the project.ipynb file using Google Colab web app.
Run all the cells in the given order.
Output for Glaucoma is a binary classification. Output will be either glaucoma or Not glaucoma. .
