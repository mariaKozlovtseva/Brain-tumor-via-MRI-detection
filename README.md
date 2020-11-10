# Brain-tumor-via-MRI-detection
Based on patient's brain MRI detect whether he has or not brain tumor and if he has - produce location of this tumor
This project is my 1st experience with Image segmentation problem. I hope that I did good job.<br>In this task we're going to build 2 models and solve <b>2 problems</b>:<br>
<b>The 1st one will be responsible for classification</b> (whether patient has brain tumor or not). This model is build via <b>transfer learning</b>, exactly <b>ResNet50</b> with Fine tuning. The <b>results</b> are impressive (accuracy 0.989, recall 0.99 and precission 0.98).<br>
<b>The 2nd model will detect location</b> of brain tumor for those patients who has it. This model is build via <b>ResUnet</b> architecture, uses <b>Tversky loss</b> function and metric. Results of the model were great: all <b>rates have +-99% (including recall and precision)</b>. <br>In the end you can see final visualisations of model's results and useful links.<br>
This project is a part of course on Udemy.com.
