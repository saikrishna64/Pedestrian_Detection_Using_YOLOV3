<!DOCTYPE html>
<html>
<head>
	<title>Pedestrian Detections using YOLOv3</title>
</head>
<body>
	<h1>Pedestrian Detections using YOLOv3</h1>
  <p>This project aims to detect pedestrians in images using the YOLOv3 object detection algorithm.</p>

<h2>Dataset</h2>

<p>The dataset used in this project contains a collection of images of pedestrians in various settings. It includes both daytime and nighttime images, as well as images with varying weather conditions and pedestrian densities.</p>

<h2>Requirements</h2>

<ul>
	<li>Python 3.6 or higher</li>
	<li>OpenCV</li>
	<li>numpy</li>
	<li>matplotlib</li>
</ul>

<h2>Getting Started</h2>

<pre>
	git clone https://github.com/&lt;username&gt;/pedestrian-detections.git
</pre>

<li>Download the pre-trained weights for YOLOv3:</li>

<pre>
	wget https://pjreddie.com/media/files/yolov3.weights
</pre>

<li>Run the script to perform pedestrian detections:</li>

<pre>
	python pedestrian_detections.py --image &lt;path_to_image&gt;
</pre>

<p>The script will output an annotated image with bounding boxes around the detected pedestrians.</p>

<h2>Customization</h2>

<p>You can customize the detection parameters by modifying the <code>pedestrian_detections.py</code> script. The following parameters can be adjusted:</p>

<ul>
	<li><code>CONFIDENCE_THRESHOLD</code>: Confidence threshold for detection (default: 0.5)</li>
	<li><code>NMS_THRESHOLD</code>: Non-maximum suppression threshold (default: 0.4)</li>
	<li><code>YOLOV3_CONFIG_PATH</code>: Path to YOLOv3 configuration file (default: yolov3.cfg)</li>
	<li><code>YOLOV3_WEIGHTS_PATH</code>: Path to YOLOv3 weights file (default: yolov3.weights)</li>
</ul>

<p>You can also experiment with different object detection algorithms or train your own model to improve the accuracy of the detections.</p>

</body>
</html>
