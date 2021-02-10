# train_delay_prediction

I was trying to make LSTM work as it is a strong candidate ML model that can model the temporal structure as we have in this case.
MSE metric was used with Adam optimizer. 
I have chosen the following features:

 0   runDate   :   
 1   stations  :   labelencoded it
 2   trainCode :   labelencoded it 
 3   scheduledArrival  : converted into just time data (24 hour format) 
 4   scheduledDeparture: converted into just time data (24 hour format)
 5   distance          : 
 6   dayCount          : 
 7  previous ArrivalDelay    
 8  previous DepartureDelay 


Improvements:
One feature I need to add is distance between the successive stations
Further feature engineering and hyper parameter tuning needs to be done. 

