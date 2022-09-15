# Print population by region
print('### Korean Population by Region')
print('* Total population:', sum_people)
print() # Print an empty line
print('| Region | Population | Ratio (%) |')
print('| ------ | ---------- | --------- |')
for idx, pop in enumerate(n_people):
    ratio =n_people[idx]/sum_people*100 # TODO: The ratio of new cases to the total
    print('| %s | %d | %.1f |' % (regions[idx], pop, ratio))
print()
 
# TODO: Print COVID-19 new cases by region
print('### Korean COVID-19 New Cases by Region')
print('* Total new cases:',sum_covid)
print() # Print an empty line
print('| Region | New Cases  | Ratio (%) |New Cases/1M')
print('| ------ | ---------- | --------- | ---------- ') 
for idx, pop in enumerate(n_people):
    ratio=n_covid[idx]/sum_covid*100
    newcases =n_covid[idx]/n_people[idx]*1000000 # TODO: The ratio of new cases to the total
    print('| %s | %d | %.1f | %.1f |' % (regions[idx], pop, ratio,newcases))
print()
