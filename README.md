# traffic-sign-classification
A colab notebook for training a deep neural network for classifying traffic signs in the test set of Chinese Traffic Sign Database.

A pre-trained model for testing:https://drive.google.com/file/d/1z9oAwv2clwXN8Jdg7NMSaneaP97Fa84b/view?usp=sharing

Dataset used:http://www.nlpr.ia.ac.cn/pal/trafficdata/recognition.html

Link to view only colab notebook:https://colab.research.google.com/drive/1wqN89NYQ_Z0nha1EIrqupeTR4k0TPh1o

Mobilenet-V2 is used as the base network. First 100 layers are freezed. Used dropout at bottleneck. Callback monitors validation loss.

Test accuracy:0.5396188497543335

Test loss:4.979988098144531

# To-do

Code for prediction.
