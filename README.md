# Driver-Behaviour-Monitoring
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
<pre>
python main.py
</pre> 
<br/>
## To enable Seatbelt & Distraction detection
<b>Step 3.</b> Clone this repository: https://github.com/nicknochnack/TFODCourse
<br/><br/>
<b>Step 3.</b> Create a new virtual environment 
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 4.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 5.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>
<b>Step 6.</b> Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders. <br/>
\TFODCourse\Tensorflow\workspace\images\train<br />
\TFODCourse\Tensorflow\workspace\images\test
<br/><br/>
<b>Step 7.</b> Begin training process by opening <a href="https://github.com/MostafaAhmedZaki/Driver-Behaviour-Monitoring/blob/main/ObjectDetection_TensorFlow.ipynb">2. Training and Detection.ipynb</a>, this notebook will walk you through installing Tensorflow Object Detection, making detections, saving and exporting your model. 
<br /><br/>
<b>Step 8.</b> You can optionally evaluate your model inside of Tensorboard. Once the model has been trained and you have run the evaluation command under Step 7. Navigate to the evaluation folder for your trained model e.g. 
<pre> cd Tensorlfow/workspace/models/my_ssd_mobnet/eval</pre> 
and open Tensorboard with the following command
<pre>tensorboard --logdir=. </pre>
Tensorboard will be accessible through your browser and you will be able to see metrics including mAP - mean Average Precision, and Recall.
<br />
