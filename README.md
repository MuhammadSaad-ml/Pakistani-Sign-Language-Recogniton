 <img src="https://img.shields.io/badge/-Sign Language-pink"><img src =https://img.shields.io/badge/Build_with-Python-yellow> <img src="https://img.shields.io/badge/-Tensorflow-orange"> <img src="https://img.shields.io/badge/-Python 3.7-blue"><img src="https://img.shields.io/badge/-API-blueviolet"> <img src="https://img.shields.io/badge/Framework-VS_Code-red"> <img src="https://img.shields.io/badge/-Machine learning-green"> <img src="https://img.shields.io/badge/-Object Detection-purple"> <img src="https://img.shields.io/badge/-SSD Model-brown">





# Pakistani Sign Langauge Detection Using Tensor Flow Object Detection API(With Trained Checkpoints)
<p>This set of repository provide a complete guide how to run or train object detection model following repository have  four files which includes trained checkpoints (Means person dont have to train the model can run and detect signs using PSL)

<img src =https://i.imgur.com/SaU66RC.png>


<pre>
1.Object detection.py(used to detect object in real time)
2.Image detection.py(used to detect object in images )
3.Images using camera.ipynb(Capturing images using OpenCV)
4.Training the model.ipynb(used for training the model)
5.Install Object Detection.ipynb(Used for installing tf object detection API)
</pre>

## Steps

<b>Step 1.</b> Create a new virtual environment using Anaconda  
<pre>
conda create --name object detection python=3.8
</pre> 
<br/>
<b>Step 2.</b> Activate your virtual environment
<pre>
conda activate object detection
</pre>
<br/>

<b>Step 3.</b> Collect images using the file file no 3 take images using camera

<br/>
<b>Step 4.</b> Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders. <br/>
\PSLD\Tensorflow\workspace\images\train<br />
\PSLD\Tensorflow\workspace\images\test
<br/><br/>
<b>Step 5.</b>Install TF object detection API using install object detection file no 5
<img src=https://i.imgur.com/fADvaOv.png>
After sucessfully installing by running verfication script will display the following 
<br><br/>

<b>Step 5.</b> Begin training process by opening. Training the model.ipynb</a>, this notebook will walk you through training the model
