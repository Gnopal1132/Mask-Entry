# Mask-Entry
You are only allowed to enter the building if your are wearing mask and in right way
Mask-Entry is an Deep learning Object detection model used for checking whether you are wearing mask or not and that too in right order.

There are total three classes:
* Wearing a mask : Wearing right mask and in right order
![Download](https://user-images.githubusercontent.com/51056214/139663753-c15f9199-37fa-4c76-9f88-c22d59e215da.png)
* Wrong mask : Wearing mask but not in right order.
![Download (1)](https://user-images.githubusercontent.com/51056214/139663790-cd2084f6-85de-4f47-a060-0cbbac91060b.png)
* No mask : Wearing no mask
![Download (2)](https://user-images.githubusercontent.com/51056214/139663836-31718b8a-a74c-47d9-b04c-31f4099ecae2.png)


The file has two Scripts.

Getting and Preprocessing dataset: This file simply takes the image as webcam and manually requires annotation using the Label Image annotator

Training and Validating: Will load the Tensorflow Object Detection API,install all the protobuffers and then given our dataset from above,the model will be trained. For music player you need to manually put songs in different categories defined.
Network Used to train the Model: MobileNetwork for real time object detection.

Process to get started:

Step 1: Install basics like Python Interpreter and clone the repository.

Step 2: Create your Environment: Creating an environment will create a seperate room for your project and the libraries installed will be seperate from your installed one.
```
python -m venv {NAME_OF_YOUR_ENVIRONMENT} or conda create -n {NAME_OF_YOUR_ENVIRONMENT}
```
Step 3: Activation of Your Environment.
```
.\ENVIRONMENTNAME\Scripts\activate  or conda activate {NAME_OF_YOUR_ENVIRONMENT}
```
Step 4: Install IpyKernel so that you can attach the environment with Jupyter notebook

```
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=EnvironmentName
```

In conda:
```
conda install -n EnvironmentName pip  # This will install pip in our environment
conda install ipykernel
python -m ipykernel install --user --name=EnvironmentName
```
Step 5: Open the Jupyter notebook Click Your Environment in the Corner and Select it. 

We are using object detection api. To be specific Mobile Net 320x320.
![120103075-340fe980-c14e-11eb-9397-a5fda5bf4119](https://user-images.githubusercontent.com/51056214/139664126-28fb6592-cef3-4b52-aa5b-a56e30194f10.png)


Reference and Big Help From :[Nicholas Renotte](https://github.com/nicknochnack/)
