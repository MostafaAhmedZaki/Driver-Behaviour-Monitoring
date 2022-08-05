# Driver-Behaviour-Monitoring

## Tensorflow Object Detection Walkthrough
<p>This repo includes the source code of a Driver Behaviour Monitoring System 

<img src="file:///C:/Users/Mostafa/Desktop/1.png">

## Steps
<br/>
<b>Step 1.</b> Install requirments 
<pre>
pip install -r requirments.txt
</pre> 
<br/>

## To enable Face Recognition System

<br/>
<b>Step 1.</b> Go to Face_Recognition 
<pre>
cd Face_Recognition
</pre> 
<b>Step 2.</b> Run the script 
<pre>
python main.py
</pre> 
<br/>

## To enable Seatbelt & Distraction detection

<br/>
<b>Step 1.</b> Create a new virtual environment 
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 2.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 3.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>
<b>Step 4.</b> Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders. <br/>
\TFODCourse\Tensorflow\workspace\images\train<br />
\TFODCourse\Tensorflow\workspace\images\test
<br/><br/>
<b>Step 5.</b> Begin testing on an Image or on a Webcam by opening <a href="https://github.com/MostafaAhmedZaki/Driver-Behaviour-Monitoring/blob/main/ObjectDetection_TensorFlow.ipynb">1. ObjectDetection_TensorFlow.ipynb</a> 
<br /><br/>