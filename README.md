# indoor-scene-recognition
Image Classification Model in PyTorch for Indoor Scene Recognition.
<br><br>
This is a Google Colab Notebook. The notebook can also be found here :https://colab.research.google.com/drive/1ALGzKj3cafL0MPUNtbUNXzRc8S_C_lqM <br><br>
The MIT-67 Indoor Scene Recognition Dataset is used here. The dataset has 15620 images in total distributed amongst 67 classes consiting of airport,trainstation,kitchen,library,etc. Link: http://web.mit.edu/torralba/www/indoor.html 
<br><br>
The model used is Resnext101_32x16d . Link:https://github.com/facebookresearch/ResNeXt .
<br><br>
Transfer Learning was used in this task. Pre-trained weights of the model on the ImageNet dataset was used.
<br>
Along with transfer learning, data-augmentation, learning rate annealing, early stopping,etc. were also used in the training process.
<br><br>
This model was originally created for the kaggle challenge (https://www.kaggle.com/c/qstp-deep-learning-2019/leaderboard) . The model acheived 3rd rank in the contest amongst 30 participants(Top 1 %). 
