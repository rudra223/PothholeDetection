# PothholeDetection
<br>
This project uses YOLOv8 to detect potholes in realtime. <br>
Evaluate model performance using metrics like F1-score, precision, recall, and confusion matrices.<br>
Used YOLOv8’s inbuilt augmentation techniques to enhance generalization.<br>

## Training Parameters 
Learning Rate: The initial learning rate is set to 0.0005.
Epochs: The model is trained for 150 epochs, a sufficient number of epochs to ensure the model converges without overfitting.
Optimizer: The Adam optimizer is used.
Dropout: A dropout rate of 0.5 is applied to the model to prevent overfitting by randomly dropping neurons during training, improving the model's generalization ability.
Early Stopping: A patience parameter of 15 epochs is used to monitor the validation performance. If no improvement is seen for 15 consecutive epochs, training stops early to avoid overfitting and reduce unnecessary training time.<br>



