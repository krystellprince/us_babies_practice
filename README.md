http://localhost:8888/notebooks/US_Baby_Names_Practice.ipynb#

states_babies = pd.read_csv('state_baby_names.csv')
states_babies ['Year'] == 2014
states_babies_2014 = states_babies.loc[states_babies['Year'] == 2014, :]
states_babies_2014 ['State'] == 'CA'
states_babies_2014_CA_sorted = states_babies_2014_CA.sort_values ('Count', ascending = False)
states_babies_2014_CA_sorted
states_babies_2014_CA_sorted.iloc[0:5]

[US_Baby_Names_Practice.pdf](https://github.com/krystellprince/us_babies_practice/files/11696850/US_Baby_Names_Practice.pdf)
