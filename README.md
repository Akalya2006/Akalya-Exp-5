# Akalya-Exp-5
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\sheri\Downloads\abalone.csv')
print(series.head())
series.plot()
pyplot.show()
![Screenshot (80)](https://github.com/user-attachments/assets/1c7e8a03-552a-4c13-aed7-84306b2b0975)
series.plot(style='-.')
pyplot.show()
![Screenshot (81)](https://github.com/user-attachments/assets/f9d21a1f-e7d9-4d3d-bb21-d1ee1aa6488e)
series.hist()
pyplot.show()
![Screenshot (82)](https://github.com/user-attachments/assets/17251bff-7731-4cde-9ab9-a93aafe76d94)
series.plot(kind='kde')
pyplot.show()
![Screenshot (83)](https://github.com/user-attachments/assets/47224b6c-d889-437f-8177-1f38de87c6f6)
