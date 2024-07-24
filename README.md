# my_list = []

# Append elements to the list
my_list.append(10)          # Number
my_list.append(20)          # Number
my_list.append(30)          # Number
my_list.append(40)          # Number

# Insert the value 15 at the second position (index 1) in the list
my_list.insert(1, 15)       # Number

# Extend the list with another list, including hobbies and skills
my_list.extend([50, 60, 70]) # More numbers
my_list.extend(['Reading', 'Coding', 'Photography'])  # Hobbies
my_list.extend(['Python', 'Data Analysis', 'Machine Learning'])  # Skills

# Remove the last element from the list
my_list.pop()

# Sort the list in ascending order
# Sorting will work correctly only for numbers, strings will be sorted in lexicographical order.
my_list.sort()

# Find and print the index of the value 30 in the list
# Note: Sorting might affect the index of 30, so make sure it exists before finding its index
if 30 in my_list:
    index_of_30 = my_list.index(30)
    print(index_of_30)
else:
    print("30 is not in the list")
