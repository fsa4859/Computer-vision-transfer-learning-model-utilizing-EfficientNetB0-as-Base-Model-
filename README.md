# Computer-vision-transfer-learning-model-using-EfficientNetB0-as-Base-Model-
This project presents the development of a computer vision model in Tensorflow using transfer learning with base model EfficientNetB0 and fine tuning. The model achieved 80% validation accuracy compared to 70% presented in Food vision paper

- This model utilizes mixed precision to enhance the training speed (Mixed precision means the switching between float16 and float32 in model training and storing of weights)

**Tensorflow Datasets**
- Tensor flow datasets will be used to download the foodvision 101 dataset which contains 101 classes of food data.

![image](https://user-images.githubusercontent.com/69100847/178313981-3e339f6a-6811-4907-be58-bc8992972a7d.png)
![image](https://user-images.githubusercontent.com/69100847/178314017-e4999b24-c9fe-492a-879f-eafaac2d939b.png)

**Understanding and visualizing the data**

![image](https://user-images.githubusercontent.com/69100847/178314960-e9a01e3e-a291-485e-abe3-f29cd37e55d0.png)
![image](https://user-images.githubusercontent.com/69100847/178315013-961849dd-6a07-40de-86a1-c8235cbec584.png)


**Checking the number of training and testing data**

![image](https://user-images.githubusercontent.com/69100847/178315400-67726cb6-6dea-4a48-863e-1a7b2bb19b21.png)

**Defining a preprocessing function**

- The preprocessing function prepares the images to be in the shape of (224,224,3)

![image](https://user-images.githubusercontent.com/69100847/178315908-8fb4da3e-9aed-4988-af19-d8bdb69d7d93.png)

- Now checking the image after being passed to the pre-processing function

![image](https://user-images.githubusercontent.com/69100847/178316034-4f1e8464-2549-4602-8510-fc8163bcabaa.png)


