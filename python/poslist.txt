s=input("Enter the list of integers  :")
li=[int(i)  for i in s.split()]
pos=[i for i in li if i>0]
print("The list input from the user is   :",li)
print("The list of positive integers is   :",pos)
