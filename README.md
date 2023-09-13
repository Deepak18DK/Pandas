# Pandas
Introduction day-1

We import pandas as [import pandas as pd]

df=pd.read_csv("D:\Excel\Weather_Prediction.csv") ->To read the csv file
To see maximum temperature -> df["Temperature"].max()
To show dates when are the events are rain -> df['EST'][df['Events']=="Rain"]
To show dates when temperature are greater than 35 -> df['EST'][df['Temperature']>35]
To replace the na values with 0 ->df.fillna(0,inplace=True)
To find the mean of WindSpeedMPH -> df["WindSpeedMPH"].mean()
