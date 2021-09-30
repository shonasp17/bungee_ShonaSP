import pandas as pd
import numpy as np
p=pd.read_csv("https://github.com/Bungeetech/internship-test2/blob/master/input/question-1/main.csv")
for year in p:
  if p.year%10==0:
    print(p.year)
