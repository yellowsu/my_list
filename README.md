# my_list
Create an empty list called my_list.
Append the following elements to my_list: 10, 20, 30, 40.
Insert the value 15 at the second position in the list.
Extend my_list with another list: [50, 60, 70].
Remove the last element from my_list.
Sort my_list in ascending order.
Find and print the index of the value 30 in my_list.



#empty list
my_list=[]

#append elements to the list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

print(my_list)
#insert
my_list.insert(1,15)
print("Updated set 1:",my_list)

#extend list with another list
my_list.extend([50,60,70])
print("set 2:",my_list)

#remove the last element
my_list.pop()
print("set 3:",my_list)
#sort the list ascending order
my_list.sort()
print("ascending order:",my_list)

#find the index of 30
index_of_30 =my_list.index(30)
print("index of 30:",index_of_30)


