# YAR42-a-novel-modification-of-CNN-algorithm

## 3.3 Appendix

The application will allow the user to choose the network, delegate, and the number of threads used during inference. The camera will capture frames continuously during operation and provide them to the loaded model. Between the process of capturing and delivering frames to the network, the image must be appropriately processed. Primarily, it will undergo segmentation to separate the hand from the background. For this purpose, a method converting the color space from RGB to HSV will be applied. This method is effective because it is easier to separate skin tone colors in the HSV color space than in RGB. The modified image will be processed into grayscale and resized to fit the input layer of the neural network being used. The installed network will make predictions and provide feedback to the user in the form of text with the percentage prediction result.
