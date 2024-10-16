# Clean-Dirty plates images classification.

Here is breaf approach to accomplish the task of classification clead and dirty images of plates from Kaggle competition. <br />

I used a combination of transfer learning and active learning to classify images of clean and dirty plates from a Kaggle competition. The process involved several key steps:
<br />
1. Preprocessing: I removed backgrounds and applied various image transformation techniques to augment the training set.
<br />
2. Model Training: After training the neural network, I made predictions on the test set. I labeled the images based on the assumption that dirty images should have a probability of being classified as dirty greater than or equal to 0.99, while clean images should have a probability less than or equal to 0.01.
<br />
3. Pseudo-Labeling: This approach resulted in a new pseudo-labeled dataset for further training.
<br />
4. Second Training: I trained the model again with the updated dataset and then made predictions on the test set once more, creating a submission file.
<br />
5. Performance: The final score I achieved was 0.85.

Now, I’m excited to test the model on real photos to see how it performs in practical scenarios!


<img width="603" alt="Result_image_1" src="https://github.com/user-attachments/assets/d5374989-8317-43c2-a74d-cd73c36ded33">
<img width="550" alt="Result_image_3" src="https://github.com/user-attachments/assets/0492472e-92c7-47bb-a7ad-b41aa61d8f62">
<img width="550" alt="Result_image_2" src="https://github.com/user-attachments/assets/b6a4d8fa-9802-4968-a40f-b77fd3030e26">
