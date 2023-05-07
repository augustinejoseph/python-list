# Python List Operations


This document describes common Python list operations, including adding and deleting elements, and concatenating lists.

## Adding Elements to a List
You can add elements to a Python list using the append() method to add an element to the end of the list, the insert() method to insert an element at a specific position, or the extend() method to add elements from another list.

### Adding to the End of a List
To add an element to the end of a list, use the append() method:

```ruby 
my_list = [1, 2, 3]
my_list.append(4)
print(my_list)  # Output: [1, 2, 3, 4]
```

### Inserting at a Specific Position
To insert an element at a specific position in a list, use the insert() method:

```ruby 
my_list = [1, 2, 3]
my_list.insert(1, 4)
print(my_list)  # Output: [1, 4, 2, 3]
```

This code inserts the value 4 at position 1 in the list my_list.

### Adding Elements from Another List
To add elements from another list to the end of a list, use the extend() method:

```ruby 
my_list = [1, 2, 3]
other_list = [4, 5, 6]
my_list.extend(other_list)
print(my_list)  # Output: [1, 2, 3, 4, 5, 6]
```

## Deleting Elements from a List
You can delete elements from a Python list using the pop() method to remove an element at a specific position, the remove() method to remove the first occurrence of a specific value, or the del statement to remove a slice of the list.

### Removing an Element at a Specific Position
To remove an element at a specific position in a list, use the pop() method:

```ruby 
my_list = [1, 2, 3, 4]
my_list.pop(1)
print(my_list)  # Output: [1, 3, 4]
```

This code removes the element at position 1 in the list my_list.

### Removing the First Occurrence of a Value
To remove the first occurrence of a specific value in a list, use the remove() method:

```ruby 
my_list = [1, 2, 3, 2]
my_list.remove(2)
print(my_list)  # Output: [1, 3, 2]
```

This code removes the first occurrence of the value 2 in the list my_list.

### Removing a Slice of a List
To remove a slice of a list, use the del statement:

```ruby 
my_list = [1, 2, 3, 4, 5]
del my_list[1:3]
print(my_list)  # Output: [1, 4, 5]
```

This code removes the elements from position 1 to 3 (exclusive) in the list my_list.

## Concatenating Lists
You can concatenate two or more Python lists using the + operator or the extend() method:

```ruby 
my_list = [1, 2, 3]
other_list = [4, 5, 6]
concatenated_list = my_list + other_list
print(concatenated_list)  # Output: [1, 2,3,4,5,6]
```