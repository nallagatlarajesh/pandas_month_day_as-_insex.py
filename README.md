# pandas_month_day_as-_insex.py
import pandas as pd
import numpy as np
#monthsdays ,from anumpy array
#having the number of days in the 12 months of a yesr .the labels 
# should be the month numbers from 1 to 12
days =np.array([31,28,31,30,30,31,31,31,30,31])
Monthdays=pd.Series(days,index=[1,2,3,4,5,6,7,8,9,10])
print(Monthdays)
print(Monthdays[2:7])
print(Monthdays[::-1])
