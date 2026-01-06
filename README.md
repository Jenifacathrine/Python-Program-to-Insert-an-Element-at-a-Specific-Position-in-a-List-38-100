# Python-Program-to-Insert-an-Element-at-a-Specific-Position-in-a-List-38-100
numbers = [3, 4, 1, 9, 6, 2, 8]
print("Original list:", numbers)

x = int(input("Enter the number to be inserted: "))
y = int(input("Enter the position: "))

numbers.insert(y, x)
print("Updated list:", numbers)

Original list: [3, 4, 1, 9, 6, 2, 8]
Enter the number to be inserted: 7
Enter the position: 3
Updated list: [3, 4, 1, 7, 9, 6, 2, 8]

