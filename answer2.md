import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/Bungeetech/internship-test2/master/input/question-2/main.csv")

result = df.groupby('occupation').agg({'age': ['min', 'max']})

print(result)
