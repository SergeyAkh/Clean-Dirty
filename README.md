# Clean-Dirty plates images classification.

Here is breaf approach to accomplish the task of classification clead and dirty images of plates from Kaggle competition. <br />

I used transfer learning and active lerning aproches for this task. As logn with some preprocessing of images such us background removing and many features for image transformation in order to generate augmented images for train set. <br />

After training of neuron network and make a prediction for test set I labled images with assumption that dirty images must have probability of being dirty >= 0.99 and cleand must have probability of being dirty <= 0.01. <br />

I resived a new pseudo labled data set for next training. <br />

After second training I made a prediction for test set again and created a submition file. <br />

Resived score is 0.85 <br />

But lets try model on real photos) <br />
<img src="/Users/sergeiakhmadulin/My Drive/Clean-Dirty/Result_image_1.webp" width="350">
<br />
<img src="https://github.com/SergeyAkh/FlashCardGame_App/assets/57836225/e3faa6bf-c5ae-4863-affa-0746bcace11c" width="200" />
<br />
<img src="https://github.com/SergeyAkh/FlashCardGame_App/assets/57836225/b74e1fb2-ba29-4075-be2a-ef87501d1062" width="200" />
<br />
<img src="https://github.com/SergeyAkh/FlashCardGame_App/assets/57836225/306ef9a2-deec-4db0-b6c0-9105e075a36e" width="200" />
