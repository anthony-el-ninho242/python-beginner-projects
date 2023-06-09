# python-beginner-projects
#This is my first upload on Github. This is basically a test trial.
#This file contains simple experiments with dictionaries

sample_dict={1:'coffee', 2:'tea', 3:'juice'}
print(sample_dict[1])
sample_dict[2]='mint tea'
print(sample_dict)
del sample_dict[3]
print(sample_dict)

my_d={1:'Test', 'Name':'Jim'}

print(my_d[1],my_d['Name'], end=' ')

my_d[2]='test 2'
print(my_d)

my_d={1:'Test', 'Name':'Jim', 2:'test 2'}

for key, value in my_d.items():
    print(key, ':', value)
