states_babies = pd.read_csv('state_baby_names.csv')
states_babies ['Year'] == 2014
states_babies_2014 = states_babies.loc[states_babies['Year'] == 2014, :]
states_babies_2014 ['State'] == 'CA'
states_babies_2014_CA_sorted = states_babies_2014_CA.sort_values ('Count', ascending = False)
states_babies_2014_CA_sorted
states_babies_2014_CA_sorted.iloc[0:5]

