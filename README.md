# ECG Proof of Concept

This project was see if I am able to predict ECG data using an LSTM. This is still a work on progress, as there still a lot of improvements that need to be done. 

## Versions

[Version 3](#version-3-nodebook3---training-with-21891-data-points)

[Version 2](#version-2-notebook2---training-with-1000-data-points)

[Version 1](#version-1-notebook)

## Plans / Work That Needs to be Done

- [ ] Fix the training data
- [ ] See how far we can predict the ECG data
- [ ] Mess around how much data we need
- [ ] Fine-tune the model

## Future Plans

- [ ] Have another model that uses the ECG data and the predicted ECG and predicts that type of data it came from 


## Version 3 (Nodebook3) - Training With 21891 data points

### Training

![](images/Notebook_3_Training.png)

![](images/Training_3.png)

### Prediction

![](images/ECG_Prediction_3.png)

model is saved under models/model3 - took 2.5 hours to train

## Version 2 (Notebook2) - Training With 1000 data points

### Training

![](images/Training_2.png)

### Prediction 

![](images/ECG_Prediction_2.png)


## Version 1 (Notebook)

### Training

![](images/Training.png)

### Prediction

![](images/ECG_Prediction.png)

## Resources that I used: 

https://curiousily.com/posts/time-series-forecasting-with-lstms-using-tensorflow-2-and-keras-in-python

https://www.kaggle.com/shayanfazeli/heartbeat

https://www.kaggle.com/gregoiredc/arrhythmia-on-ecg-classification-using-cnn

