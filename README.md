# Brain-tumor-via-MRI-detection
Based on patient's brain MRI detect whether he has or not brain tumor and if he has - produce location of this tumor
This project is my 1st experience with Image segmentation problem. I hope that I did good job.<br>In this task we're going to build 2 models and solve 2 problems:<br>
The 1st one will be responsible for classification (whether patient has brain tumor or not). This model is build via transfer learning, exactly ResNet50 with Fine tuning. The results are impressive (accuracy 0.989, recall 0.99 and precission 0.98).<br>
The 2nd model will detect location of brain tumor for those patients who has it. This model is build via ResUnet architecture, uses Tversky loss function and metric. Results of the model were great: all rates have +-99% (including recall and precission). In the end you can see final visialusations of model's results and usefull links.<br>
This project is a part of course on Udemy.com.
