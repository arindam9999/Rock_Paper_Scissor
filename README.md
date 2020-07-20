# Rock_Paper_Scissor
This project is implemented by me for gaining practical experience and educating my self on the subtleties to multiclass classification using Pretrained networks and fine-tuning of such models.
In this project, the base-model used was MobileNetV2 from Keras Library pre-trained on Imagenet Dataset. Finetuned it to get a training accuracy of 88% and test accuracy of 85% using only 800 images(200 of each category). 
The model used Global Average Pooling layer and Softmax Cost function. No dense layer was used.
This model trained for 10 epochs with a learning rate equal to 0.0001 and batch size 64. 
Fine-tuning the results with greater precision and training the model with higher epochs could possibly improve the accuracy of the model. 
The project includes the all files , datasets, and pre-trained model weights. 
The model was trained on Google Colab and took 30mins to run 10 epochs.
