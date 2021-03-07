keys=input("enter the keys in the first dictionary").split()
values=input("Enter the values corresponding to the keys in the dictionary").split()
dictionary1=dict()
dictionary2=dict()
j=0
for i in keys:
	dictionary1[i]=values[j]
	j+=1
keys=input("Enter the keys in the second dictionary").split()
values=input("Enter the values corresponding to the keys in the dictionary").split()
j=0
for i in keys:
	dictionary2[i]=values[j]
	j+=1
for key,value in dictionary2.items():
	if key in dictionary1.keys():
	    dictionary1[key]=int(dictionary1[key])+int(dictionary2[key])
	else:
	    dictionary1[key]=value
print("Merged Dictionary",dictionary1)
