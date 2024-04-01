# Predictive Modeling of Energy Consumption using Machine Learning (ML)


Abstract:
This study aimed to forecast energy consumption using data from Finland's transmission system operator. The project explored the feasibility of employing machine learning models for accurate energy forecasting, particularly focusing on a univariate time series dataset spanning 6 years of hourly electrical consumption in Finland. Leveraging a Long Short-Term Memory (LSTM) model, the research assessed the model's performance using Root Mean Squared Error (RMSE). Results indicated the potential of machine learning algorithms in predicting electricity consumption, enabling strategic deployment of renewable energy sources, optimizing energy management on high/low load days, and minimizing wastage from backup power generation.

Model Implementation:
Data sourced from Finland's transmission system operator were processed as a CSV file and subsequently stored in a GitHub repository. With 52965 observations and 5 variables, the dataset exhibited no missing values. Statistical analysis revealed a minimum load volume of 5341 MWh, a maximum load volume of 15105 MWh, and an average volume of 9488.75 MWh. The univariate time series data required conversion to daily frequency for predicting daily consumption. The LSTM model was trained using a training set, with validation data used for assessing model performance. The training involved iterating through the dataset 60 times (Epoch), with model weights updated after each batch, utilizing a batch size of 20.

References:
1. https://en.wikipedia.org/wiki/Long_short-term_memory
2. https://www.analyticsvidhya.com/blog/2021/03/introduction-to-long-short-term-memory-lstm/
3. https://github.com/MohamadNach/Machine-Learning-to-Predict-Energy-Consumption
