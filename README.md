## Self Driving 
### Problem Statement: 
#### Given frames of images for video we should predict the steering angle in proper direction
#### Based on Research paper : [PAPER](https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf)

###  Dataset:
####    Refer :[DatasetLink](https://github.com/SullyChen/driving-datasets)  or [DatasetLink](https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view)

#### I have used Keras functional API for Model Building and Keras Sequence API for Batch Data Generation.
#### For Training the model 
```bash
$ python train.py
```
#### for predicting 
```bash
$ python drive_car(run).py
``` 
#### if you want to see the results you can directly run drive_car(run).py without training,which uses testing_model which has been trained
