# PothholeDetection
<br>
This project uses YOLOv8 to detect potholes in realtime. <br>
Evaluate model performance using metrics like F1-score, precision, recall, and confusion matrices.<br>
Used YOLOv8’s inbuilt augmentation techniques to enhance generalization.<br>

## Training Parameters 
Learning Rate: The initial learning rate is set to 0.0005.<br>
Epochs: The model is trained for 150 epochs, a sufficient number of epochs to ensure the model converges without overfitting.<br>
Optimizer: The Adam optimizer is used.<br>
Dropout: A dropout rate of 0.5 is applied to the model to prevent overfitting by randomly dropping neurons during training, improving the model's generalization ability.<br>
Early Stopping: A patience parameter of 15 epochs is used to monitor the validation performance. If no improvement is seen for 15 consecutive epochs, training stops early to avoid overfitting and reduce unnecessary training time.<br>

## Inference

Image Inference<br>
![image](https://github.com/user-attachments/assets/1992164d-fa41-4198-a6fe-9eb3520bb4bc)<br>

Video Inference<br>
![image](https://github.com/user-attachments/assets/c6a8947e-1ba7-4b9f-b665-5c6122e0418e)<br>

## Results
Metric	Value<br>
Precision	91%<br>
Recall	88%<br>
F1-Score	89%<br>
mAP@0.5	92%<br>
Fitness	90%<br>






