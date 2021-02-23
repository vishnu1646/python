lst = []
num = int(input('How many numbers: '))
total=0
for n in range(num):
    numbers = int(input('Enter number '))
    lst.append(numbers)

for ele in range(num):
       total=total+lst[ele]
       
print("Sum of elements in given list is :", total)