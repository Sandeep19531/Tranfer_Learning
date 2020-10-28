# Transfer Learning using VGG16
_________________________________________________________________________________________________________________
# About:  
### This is a **deep learning project** based on transfer learning. Here i have used VGG16 as a pre-trained model and trained a dataset of flower_images on it.  
_________________________________________________________________________________________________________________
# Motive:  
### Motive behind this project was to improve the accuracy of the model by implementing transfer learning technique.
_________________________________________________________________________________________________________________
# Libraries Used:  
   **Numpy**  
   **Keras**  
   **Tensorflow**  
   **Matplotlib**  
   **glob**  
_________________________________________________________________________________________________________________
# Process:  
### I re-trained the last layer of VGG16 model with training data consisting of flower images.  
![9818247_e2eac18894](https://user-images.githubusercontent.com/61156183/97415095-cb982a00-192a-11eb-8ca5-55b857c5c3e4.jpg)
 ![864957037_c75373d1c5](https://user-images.githubusercontent.com/61156183/97415236-f8e4d800-192a-11eb-904e-6c92a61aed0f.jpg)
  
### The model was re-trained on google colab's gpu and is giving an accuracy of > 80% in just 5 epochs. Given this data set also consisits of landscapes and garbage images , it is a massive improvement, further training couldn't be done due to lack of better hardware.
_________________________________________________________________________________________________________________
# About the dataset:
### It is a subset of 102flower data set provide by Oxford.
_________________________________________________________________________________________________________________
# Biblography:
1. Blogs:  [Aqeel Anwar](https://towardsdatascience.com/the-w3h-of-alexnet-vggnet-resnet-and-inception-7baaaecccc96)  [Jason Brownlee](https://machinelearningmastery.com/how-to-improve-performance-with-transfer-learning-for-deep-learning-neural-networks/)  
2. Youtube: [Krish Naik](https://www.youtube.com/watch?v=zBOavqh3kWU&t=758s)  [Deeplearning.ai](https://www.youtube.com/channel/UCcIXc5mJsHVYTZR1maL5l9w)  
**Special** thanks for Krish Naik who help me clear the concept and also provide a generic code [template](https://github.com/krishnaik06/Transfer-Learning) that is applicable for all transfer learning projects.  
