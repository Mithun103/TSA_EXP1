# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('ECOMM DATA.csv')
plt.plot(df['Ship Date'], df['Sales'])
plt.xlabel("ship date")
plt.ylabel("sales")
plt.title("Student Study Hours")
plt.show()
```


# OUTPUT:

![image](https://github.com/user-attachments/assets/a9568443-3d72-4bc1-a8b2-f3989d0baf70)




# RESULT:
Thus we have created the python code for plotting the time series of given data.
