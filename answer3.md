import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/Bungeetech/internship-test2/master/input/question-3/main.csv")

discipline = df[['Team', 'Yellow Cards', 'Red Cards']]
print(discipline)
discipline.sort_values(by=['Red Cards','Yellow Cards'],ascending=False)
