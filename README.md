# Assignment-6
# Python program to create a list and demonstrate membership operators

# Creating a list
numbers = [10, 20, 30, 40, 50]

print("List:", numbers)

# Using 'in' operator
if 30 in numbers:
    print("30 is present in the list")
else:
    print("30 is not present in the list")

# Using 'not in' operator
if 60 not in numbers:
    print("60 is not present in the list")
else:
    print("60 is present in the list")


# Python program to demonstrate indexing, negative indexing, and slicing on a list

# Creating a list
numbers = [10, 20, 30, 40, 50, 60]

# Indexing
print("List:", numbers)
print("Element at index 0:", numbers[0])
print("Element at index 2:", numbers[2])

# Negative Indexing
print("Last element using negative indexing:", numbers[-1])
print("Second last element:", numbers[-2])

# Slicing
print("Elements from index 1 to 4:", numbers[1:5])
print("Elements from beginning to index 3:", numbers[:4])
print("Elements from index 2 to end:", numbers[2:])
print("Complete list using slicing:", numbers[:])

# Slicing with step
print("Elements with step 2:", numbers[::2])
