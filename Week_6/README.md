CS5720: Neural Network Deep Learning: In Class Programming Assignment-5
Name: Alekhya Aluri
ID: 700773355 
Video Link: https://drive.google.com/file/d/1Av-nkW0X0pUnrudjVora76xJ8i46Jzju/view

Deep Learning Image Classification with CNN
Lesson Overview:
In this lesson, we are going to discuss Image classification with CNN.
Use Case Description:
Image Classification with CNN
1. Training the model
2. Evaluating the model
Programming elements:
1. About CNN
2. Hyperparameters of CNN
3. Image classification with CNN
In class programming:
1. Follow the instruction below and then report how the performance changed.(apply all at once)
• Convolutional input layer, 32 feature maps with a size of 3×3 and a rectifier activation function.
• Dropout layer at 20%.
• Convolutional layer, 32 feature maps with a size of 3×3 and a rectifier activation function.
• Max Pool layer with size 2×2.
• Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function.
• Dropout layer at 20%.
• Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function.
• Max Pool layer with size 2×2.
• Convolutional layer, 128 feature maps with a size of 3×3 and a rectifier activation function.
• Dropout layer at 20%.
• Convolutional layer,128 feature maps with a size of 3×3 and a rectifier activation function.
• Max Pool layer with size 2×2.
• Flatten layer
• Dropout layer at 20%.
• Fully connected layer with 1024 units and a rectifier activation function.
• Dropout layer at 20%.
• Fully connected layer with 512 units and a rectifier activation function.
• Dropout layer at 20%.
• Fully connected output layer with 10 units and a Softmax activation function
Did the performance change?
2. Predict the first 4 images of the test data using the above model. Then, compare with the actual label for those 4
images to check whether or not the model has predicted correctly.
3. Visualize Loss and Accuracy using the history object