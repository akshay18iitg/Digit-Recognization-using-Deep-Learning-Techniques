# Digit-Recognization-using-Deep-Learning-Techniques

This project uses MNIST dataset. It consists of 60000 28X28 grayscale images of 10 digits and 10000 images in test dataset. So the input is 28X28 pixels of images and the output is array of size 10.

![image](https://user-images.githubusercontent.com/50731752/144897836-e1dd4721-81ee-485e-9bd2-387e523eb262.png)

First I implemented Fully connected neural networks Architecture. 
- I implemented neural network with 2 layers. 

![image](https://user-images.githubusercontent.com/50731752/144898841-d43d1a61-be3f-4389-b364-5f948a302940.png)

Using this network I achieved 96.83% on training dataset and 95% on testing dataset.

- Then I implemented neural network with 4 layers.

![image](https://user-images.githubusercontent.com/50731752/144899725-c4544708-5c62-44f9-b82c-b8a0035c911b.png)

Using this network I achieved 99.56% on training dataset and 96.04% on testing dataset.

- To make the model more robust I used batch normalization which increased the accuracy on test dataset.

![image](https://user-images.githubusercontent.com/50731752/144900488-ed8a31e9-1ea4-46f4-9292-fba787ae38af.png)

This increased the accuracy on training dataset to 99.98% and 97.24% on test dataset.

To take spatial information into consideration and reduce number of parameter I used CNN model. 

- I created my own CNN model from scratch.

![image](https://user-images.githubusercontent.com/50731752/144902699-092928b4-0480-42ac-9d07-2c8d74d41a28.png)

On just training for 10 epochs i achieved 98.75% accuracy on training dataset and 98.37% accuracy on testing dataset

I also tried data augmentation but it did'nt increase the accuracy. Maybe just using horizontal flip may increase the accuracy.
