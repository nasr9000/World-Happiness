# World-Happiness

Intro: I chose this to be my very first solo project because we currently face a mental health crises aroud the world and I am looking to understand just exactly what are the most important factors that contribute to a coutnry's overall happiness. I started by choosing this dataset as it had an abundance of coutnries to choose from as well as important varibales that correlate heavily with an individuals wellbeing wherever they reside. I started off by importning my dependencies and cleaning my dataframes to rid of any metrics that I was not interested in measuring for the project. 

#drop columns and clean data from Happiness_df
new_df = clean_df.copy()
new_df = clean_df.drop(columns=['Lower Confidence Interval', 'Upper Confidence Interval', 'Family', 'Dystopia Residual'])
new_df
