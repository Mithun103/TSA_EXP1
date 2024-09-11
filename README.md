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

![image](https://github.com/user-attachments/assets/9431ba29-0a27-4f72-ad64-e7cf465a21b9)





# RESULT:
Thus we have created the python code for plotting the time series of given data.
