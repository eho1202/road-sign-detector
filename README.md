# Road Sign Recognition
The project involves creating an application that uses a mobile phone camera or any other camera to recognize road signs in Ontario. The purpose of traffic sign recognition is to allow autonomous vehicles to recognize and respond accordingly to road signs. This helps improve road safety, compliance with traffic laws and driving comfort.  

This repository contains the trained model optimized for recognizing road signs in Ontario, as well as an installation guide detailing the steps we followed to train the model. 

## Installation Guide
1. If you have a [compatible Nvidia graphics card](https://developer.nvidia.com/cuda-gpus), download [CUDA Toolkit 12.4](https://developer.nvidia.com/cuda-12-4-0-download-archive). If you do not have an Nvidia graphics card, ignore this step.
2. Ensure Python is installed and the version is between ```3.8``` and ```3.12```.
3. Install all necessary libraries using ```pip install -r requirements.txt```.
4. You are now ready to train your own model!

## Training the Model
1. Head to ```main.ipynb```
   1. If you have an Nvidia graphics card, just run the notebook normally
   2. If you do not have an Nvidia graphics card, remove the code ```model.to('cuda')``` inside the second codeblock.
2. Wait and once the program finishes training, you will be able to see the results.

## Some Infomation on the Dataset
The dataset includes 20 classes, they are:
- 10km
- 20km
- 30km
- 40km
- 50km
- 60km
- 70km
- 80km
- 90km
- 100km
- 110km
- keep_right_of_mediam
- no_left_turn
- no_right_turn
- no_u_turn
- one_way_left
- one_way_right
- school_zone
- stop
- yield

The roboflow dataset can be found [here](https://universe.roboflow.com/cps843-o3qp2/road-sign-recognition-g1lfe/dataset/1).

## Collaboration
This assignment was completed in collaboration with:  
[Anthony Thanpoovong](https://github.com/anthonythanpoovong)  
[Caleb Lam](https://github.com/ClamEater14)  
[Jerome Magpantay](https://github.com/JeromeMagpantay)  
[Ryan Le](https://github.com/ryan1le)
