# Deep Learning Assignment for DATA2040

### Mini Project 1: Using ConvNets to Distinguish Trains vs. Cars

Medium Blog Post Link: https://medium.com/training-convnet-on-small-binary-classified/training-a-convnet-with-limited-image-data-59b7f36e281a

Relevant Notebooks: p1-ConvNets_trains_vs_cars.ipynb

### Mini Project 2: NLP with Embedding and RNN's using the Yelp Dataset
Medium Blog Post Link: https://medium.com/training-convnet-on-small-binary-classified/using-word-embeddings-and-recurrent-neural-networks-to-predict-rating-scores-from-text-93ba0a48bf82

Relevant Notebooks: p2-category_yelp.ipynb, p2-binary_yelp.ipynb

### Mini Project 3: Neural Style Transfer with VGG16, VGG19, and ResNet50
Medium Blog Post Link: https://medium.com/training-convnet-on-small-binary-classified/image-style-transfer-using-pre-trained-convnets-1c750c0cb458

Relevant Notebooks: p3-neural_style_transfer.ipynb

### Additional Info

The majority of the code was run on an AWS EC2 p2.xlarge instance (Python 3.6 and Keras 2.0.8). The public DNS of this instance is ec2-18-219-45-93.us-east-2.compute.amazonaws.com.

### Instructions to Run EC2 Instance:
1. SSH into the instance.
```
ssh -i "data2040-dl.pem" ubuntu@ec2-18-219-45-93.us-east-2.compute.amazonaws.com
```
2. CD into the git repo and run jupyter notebook.
```
cd DATA2040-DLPython
jupyter notebook
```
3. Go to the address below and ignore the warning by clicking advanced, then continue.
```
https://ec2-18-219-45-93.us-east-2.compute.amazonaws.com:8888
```

Based on Jupyter Notebooks from https://github.com/fchollet/deep-learning-with-python-notebooks
