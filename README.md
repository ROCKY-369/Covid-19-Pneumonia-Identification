# Covid-19-Pneumonia-Identification
To identify covid-19 and other pneumonia based on chest x-ray used Convolutional Neural Network in TensorFlow and Keras based Covid-19 pneumonia classification. the proposed system based on CNN using Pneumonia images to classifying the Covid-19, normal, pneumonia this system using CNN model. It is predicted that the success of the obtained results will increase if the CNN method is supported by adding extra feature extraction methods and classify successfully covid-19&pneumonia.

Proposed System:  recognition framework based on the structured two dimensional convolutional neural networks (CNNs) type of AlexNet to classify the Covid-19&Pneumonia and improve the accuracy of workflow.  
The proposed method for this project is to train a Deep Learning algorithm capable of classifying Covid-19&Pneumonia images and data preprocessing  and visualizing the image then feature extracting to build AlexNet CNN using Covid-19&Pneumonia image dataset  we classify it  such as Covid-19,normal,pnemonia this system using CNN model. 

Deep learning algorithms are constructed with connected layers.   
• The first layer is called the Input Layer   
• The last layer is called the Output Layer   
• All layers in between are called Hidden Layers.
Input Layer: Input layer in CNN contain image data. Image data is represented by three dimensional matrixes. It needs to reshape it into a single column.
Convo Layer: Convo layer is sometimes called feature extractor layer because features of the image are get extracted within this layer. First of all, a part of image is connected to Convo layer to perform convolution operation as we saw earlier and calculating the dot product between receptive fields (it is a local region of the input image that has the same size as that of filter) and the filter.
Pooling Layer: Pooling layer is used to reduce the spatial volume of input image after convolution. It is used between two convolution layers. If it applies FC after Convo layer without applying pooling or max pooling, then it will be computationally expensive.
Fully Connected Layer (FC): Fully connected layer involves weights, biases, and neurons. It connects neurons in one layer to neurons in another layer. It is used to classify images between different categories by training.   
Logistic Layer: Logistic layer is the last layer of CNN. It resides at the end of FC layer. Logistic is used for binary classification and softmax is for multi-classification.
Output Layer: Output layer contains the label which is in the form of one-hot encoded. Now you have a good understanding of CNN.

Architecture
![image](https://github.com/user-attachments/assets/1db390e4-b85c-4674-bcf0-70ae973f0065)

Data set
![image](https://github.com/user-attachments/assets/77c9ff48-73d7-4a21-a058-5782f53b3eaf)

input
![image](https://github.com/user-attachments/assets/fac05e83-b5ad-48b4-abb2-620142f1ae39)

output
![image](https://github.com/user-attachments/assets/92c4dcb7-3009-4f58-8e59-438b9a3f803a)

Accuracy and Loss Graph
![image](https://github.com/user-attachments/assets/8dac59e7-0b36-40a0-8e95-d2d3ee8dbbe7)




