# Brain-Tumor-Detection-using-CNN
BRAIN TUMOR DETECTION

The human brain is the focal point of the sensory system. It is a cluster of the white mass of cells. A brain tumor is an uncontrolled development of these cells strangely found in various pieces of the cerebrum, to be specific, Glial cells, neurons, lymphatic tissues, veins, pituitary organs, and different pieces of the cerebrum. A brain tumor is of three kinds: Benign, Malignant, and Premalignant. A benign tumor is not destructive and causes no risk. In actuality, a Malignant tumor is harmful and lethal. This tumor develops anomalously by augmentation of the cells, which would cause the death of the patient. The Discovery of a brain tumor at the starting stages is incredibly important yet tedious and tiresome. The programming division strategy by MRI is an approach to distinguish and recognize the tumor. In order to give an exact yield, a solid division strategy is required. These days, this innovation has gotten relatively progressed with different AI and deep learning algorithms. Clinical image processing is one of the premier requesting and promising fields these days. So as to recognize the brain tumor, I will consider the MRI pictures of a patient's mind. Here, the primary focus is to recognize the presence of a tumor. There are numerous bits of writing on distinguishing these sorts of brain tumors and improving the location exactnesses. The division, recognition, and extraction of the tumor territory from attractive reverberation (MR) pictures are the focal point of consideration. Be that as it may, they are repetitive and tedious, and their exactness relies upon the experience of the radiologist. Thus, the utilization of computer-aided tools turns out to be extremely important to beat these constraints. These instruments give a brisk and exact outcome. 

The main focus is to give an algorithm that ensures the presence of a tumor accurately using CNN. The focal point of this project is image extraction of the tumor and its portrayal in an easier structure with the end goal that it is understandable by everybody. People, in general, comprehend colored pictures easily as compared to grayscale. Subsequently, utilizing hues to make the portrayal less complex enough to be perceived by the patient alongside the clinical staff will solve the problem. The resultant picture will have the option to give data like size, measurement and position of the tumor, plotting shape and c-mark of the tumor and its limit furnishes us with data identified with the tumor that can demonstrate value for different cases, which will give a superior base to the staff to choose the relieving system. Many government or NGO-based medical facilities might not be able to afford to pay for it. The availability of this project as an open-source will help various medical organizations in improving their efficiency and thus, decreasing their death rate. The accuracy of finding a tumor will also be increased by using CNN.


Methodology: 

 The first part deals with the detection of the tumor from MRI images, and the second part contains the process of classification of tumor type (Benign, Malignant or Normal). A general system takes the given input MRI image which goes through several stages, which are pre-processing, segmentation and classification. For this we will have to first select a dataset which consists of MRI images which are good for representation of tumors. This dataset is then going to be categorized into yes and no forms. Yes, reveals that there is a tumor, and no means that there is no tumor. 
For the next step we will need to pre-process the basic images which will require different techniques such as image enhancement, scale changing, noise removal etc. The purpose of these steps is basically to improve the image and the image quality to get more surety and ease in detecting the tumor. 
After that segmentation of influenced mind tissues and ordinary tissues, for example, cerebrospinal liquid, grey matter, white matter and magnetic resonance images is done using a function extraction procedure, and convolution neural network classification. Segmentation of images is the process by which an image is broken down into small pieces. Segmentation is performed to allow analysis. 

CNN: 

The preprocessed images move through a multi-layer model. Images are fed to the input layer. Multiple features are identified that are useful in classifying MRI images into unique tumor types. Following can be the different layers present in the model:
 a) Convolution layer : Goal of the convolution layer is to take or extricate the highlights from the info [image]. 
b) Padding : Padding is fusing a zero layer outside the input volume so the information on outskirts won't be lost. 
c) Activation Function : A non- linear activation function ReLU (Rectifier Activation function) is utilized to give precise results than traditional sigmoid capacities. 
d) Pooling Layer : It is utilized for joining spatially close highlights. Max-pooling is commonly used to join highlights. It diminishes the component of info picture and powers over-fitting. 
e) Fully Connected Layer: At last Fully Connected layer gives the arranged picture depending on the dataset. Finally, the system will be able to tell if the tumor present is benign (non-cancerous, not harmful) or malignant (cancerous and harmful).



Timeline: 


WEEK
TASK
1,2,3
Collect the dataset
4
Study the different kinds of Brain tumor in detail
5,6,7
Improve Image Quality
8,9,10,11
Start Working on CNN
12,13,14
Perform efficient analysis
15
Finishing details

