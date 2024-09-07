from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\sheri\Downloads\auto_imports.csv')
print(series.head())
series.plot()
pyplot.show()
![Screenshot (73)](https://github.com/user-attachments/assets/372bf3a6-8cac-47f0-85f7-20f5e08d45a0)
series.plot(style='-.')
pyplot.show
![Screenshot (74)](https://github.com/user-attachments/assets/59fa975f-26c6-4c24-ba13-f7da4492ceb6)
series.hist()
pyplot.show()
![Screenshot (76)](https://github.com/user-attachments/assets/4a2a6a5b-294c-428f-a7e8-14f954a35350)
series.plot(kind='kde')
pyplot.show()
![Screenshot (77)](https://github.com/user-attachments/assets/8012b0c2-33a5-47f3-90d6-f8d4aec99843)
