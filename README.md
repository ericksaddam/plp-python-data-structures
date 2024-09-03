# plp-python-data-structures
Week Two Assignment
Submit a github repo link for the assignment below


Create an empty list called my_list.
Append the following elements to my_list: 10, 20, 30, 40.
Insert the value 15 at the second position in the list.
Extend my_list with another list: [50, 60, 70].
Remove the last element from my_list.
Sort my_list in ascending order.
Find and print the index of the value 30 in my_list.

<h1>Code Solution</h1>
# 1. Create an empty list called my_list
my_list = []

# 2. Append the following elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print("Appended:", my_list)

# 3. Insert the value 15 at the second position in the list
my_list.insert(1, 15)
print("Insterted 15 at the second position in the list:", my_list)

# 4. Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])
print("Extended:", my_list)

# 5. Remove the last element from my_list
my_list.pop()
print("Removed last element:", my_list)

# 6. Sort my_list in ascending order
my_list.sort()
print("Sorted:", my_list)

# 7. Find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)