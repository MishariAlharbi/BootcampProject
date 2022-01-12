# Summary
The goal was to predict if the flight was going to be delayed or not. The data was downloaded from Kaggles, contains 5.8M rows with 31 features. Made my own columns to simplify the work based on feature calculations/merging.You can find the summariezed results and findings in the powerpoint presentation.

# Design
Becuase 19% of flights worldwide get delayed, I decided that I would like to present a model that is good enough to predict flights delay based only on its history. 

# Data
The dataset contains 5.8M rows , with 31 features. I ended up with 12 features after cleaning/preprocessing,

'AIRLINE', 'ORIGIN_AIRPORT', 'DESTINATION_AIRPORT','SCHEDULED_DEPARTURE', 'DEPARTURE_TIME', 'DEPARTURE_DELAY','SCHEDULED_ARRIVAL', 'ARRIVAL_TIME', 'ARRIVAL_DELAY', 'SCHEDULED_TIME','ELAPSED_TIME', 'DELAY_LEVEL'

# Algorithms
Model:
I used linear regression as the data was numeric and needs projection of the near future.


Mean Squared Error = 53.74%


We can explain why MSE is a bit high due to the overall inconsistency for flights to be delayed. There are so many factors affecting flights to be delayed as well as our data wasn't consistant, If we want to predict January flights, We need to give the model similar data to work on, such as same month but next year.

# Tools
Numpy and Pandas.

Sklearn for modeling.

Matplotlib and Seaborn for plotting.


# Communication
You can find the project powerpoint presentation in the main rep

