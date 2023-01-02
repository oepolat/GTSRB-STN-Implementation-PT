# GTSRB Dataset Spatial Transformer Network Implementation on PyTorch

Personal Experiments on Implementing a Spatial Transformer Network for identification of German traffic signs. Dataset used is the [German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) consisting of 43 different traffic sign types and 50000+ images. Experiments we're performed on Jupyter Notebook for ease of experimentation and visualization of results in real time.

# Spatial Transformer Networks
![STN](https://production-media.paperswithcode.com/methods/Screen_Shot_2020-07-19_at_5.48.34_PM_vFLk7jR.png)
Spatial transformer networks are a generalization of differentiable attention to any spatial transformation. Spatial transformer networks (STN for short) allow a neural network to learn how to perform spatial transformations on the input image in order to enhance the geometric invariance of the model.
In this personal experiment, it can be seen that the localization network learns to pick affine transformations that improve the main models accuracy.

Example transformation also shown on the experiment file:
![STN-Theta](https://i.postimg.cc/xdWjNtx6/STN-network.png)
