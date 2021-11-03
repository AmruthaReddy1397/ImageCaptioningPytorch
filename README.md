# ImageCaptioningPytorch
This is a Image Captioning model  
The model comprises of an encoder and decoder  
The encoder part is built using a pretrained CNN model for Feature extraction. The decoder part is built using LSTM.  
The CNN model used for feature extraction is Inception_V3.  
The output from the CNN model is then embedded according to the input size of the LSTM using a Linear model
