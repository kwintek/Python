# Python
#List Sorting with if & else conditions- user needs to end "Sort" for the list to get sorted

lst = [5, 3, 1, 2, 4]
print("Unsorted List:",(lst))
comand = "Sort"
comand=(input("Type 'Sort' to sort the numbers:"))
if comand == "Sort":
    lst.sort()
    print("Sorted list:",(lst))  # outputs: [1, 2, 3, 4, 5]
else:
    print("Error")

