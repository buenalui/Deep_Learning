# Deep Learning Stock Predictor

## Which model has a lower loss?
The Closing predictor had a much lower loss than the FNG predictor, almost over 5% less of a loss
<br>-Closing</br>
- <img src="Pictures/predictor_closing_loss
.PNG">

<br>-FNG</br>
- <img src="Pictures/predictor_fng_loss
.PNG">


## Which model tracks the actual values better over time?
Closing predictor is better at tracking BTC actual values over time

<br>-Closing</br>
- <img src="Pictures/closing_hvplot
.PNG">

<br>-FNG</br>
- <img src="Pictures/fng_hvplot
.PNG">


## Which window size works best for the model?

when I set the batch size to 2, I had the lowest loss at .008
<img src="Pictures/window_2
.PNG">
