# tuple
# Creating a tuple
fruits = ("apple", "banana", "cherry", "orange")

# Accessing elements
print(fruits[0])      # Output: "apple" (first element)
print(fruits[-1])     # Output: "orange" (last element)

# Slicing a tuple
print(fruits[1:3])    # Output: ("banana", "cherry")

# Length of tuple
print(len(fruits))    # Output: 4

# Looping through a tuple
for fruit in fruits:
    print(fruit)

# Checking if an item exists
if "banana" in fruits:
    print("Banana is in the tuple!")  # Output: True

# Tuple concatenation
more_fruits = ("grape", "kiwi")
all_fruits = fruits + more_fruits
print(all_fruits)  # Output: ("apple", "banana", "cherry", "orange", "grape", "kiwi")
