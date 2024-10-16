# Clean-Dirty plates images classification.

Here is breaf approach to accomplish the task of classification clead and dirty images of plates from Kaggle competition. <br />

I used transfer learning and active lerning aproches for this task. As logn with some preprocessing of images such us background removing and many features for image transformation in order to generate augmented images for train set. <br />

After training of neuron network and make a prediction for test set I labled images with assumption that dirty images must have probability of being dirty >= 0.99 and cleand must have probability of being dirty <= 0.01. <br />

I resived a new pseudo labled data set for next training. <br />

After second training I made a prediction for test set again and created a submition file. <br />

Resived score is 0.85 <br />

But lets try model on real photos) <br />

<img width="603" alt="Result_image_1" src="https://github.com/user-attachments/assets/d5374989-8317-43c2-a74d-cd73c36ded33">
<img width="550" alt="Result_image_3" src="https://github.com/user-attachments/assets/0492472e-92c7-47bb-a7ad-b41aa61d8f62">
<img width="550" alt="Result_image_2" src="https://github.com/user-attachments/assets/b6a4d8fa-9802-4968-a40f-b77fd3030e26">
