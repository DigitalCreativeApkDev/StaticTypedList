# StaticTypedList

StaticTypedList is a data type supporting a list of one type of element (and its subtypes) like Java List objects.

# Installation

pip install StaticTypedList

# Usage

To use the library install it using the command shown in "Installation" section. 
Then, read the instructions below regarding how to use operations with StaticTypedList.

# Length

'len()' function can be called with a StaticTypedList as the parameter. It gets the number of elements in the 
StaticTypedList.

Input: len(StaticTypedList([4, 5, 3]))
Output: 3

# Contains

Input: 5 in StaticTypedList([5, 6, 2])
Output: True

# Get Item at Index

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
print(a[1])

Output: 6

# Set Item at Index

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
a[1] = 1 
print(a)

Output: [5, 1, 2]

# Append Element

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
a.append(1)
print(a)

Output: [5, 6, 2, 1]

# Insert Element

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
a.insert(1, 3)
print(a)

Output: [5, 3, 6, 2]

# Remove Element

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
a.remove(6)
print(a)

Output: [5, 2]

# Pop Element

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
a.pop(1)
print(a)

Output: [5, 2]

# Extend Lists

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2])
b: StaticTypedList = StaticTypedList([2, 7])
a.extend(b)
print(a)

Output: [5, 6, 2, 2, 7]

# Count Number of Occurrences of Element

Input:

a: StaticTypedList = StaticTypedList([5, 6, 2, 7, 2, 3, 2])
print(a.count(2))

Output: 3

# Get Index of Element

Input:

a: StaticTypedList = StaticTypedList([1, 7, 3, 7, 5])
print(a.index(3))

Output: 2

# Sort

Input:

a: StaticTypedList = StaticTypedList([3, 2, 6, 7, 1])
a.sort()
print(a)

Output: [1, 2, 3, 6, 7]

# Clear

Input:

a: StaticTypedList = StaticTypedList([3, 2, 6, 7, 1])
a.clear()
print(a)

Output: []

# Checking for Equality

Input: StaticTypedList([2, 6, 7, 3]) == [2, 6, 7, 3]
Output: True
