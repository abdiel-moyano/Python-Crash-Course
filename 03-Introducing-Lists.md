# Introducing Lists
A list is a collection of items, in a certain order. It's index is counted from 0, for example, if you have a list with 10 items, your 10th item corresponds with the index 9. You can also reference the las item as -1, the previous one as -2 and so on.
## Basic Operations
- Create a list
```python
newList = ['value1' , 'value2' , 'value3']
```
- Show values
```python
print(newList)
['value1' , 'value2' , 'value3']
```
- Show values per index
```python
print(newList[0])
```
- Show last value
```python
print(newList[-1])
```
- Concatenate
```python
print ("The " + newList[0] + " is the first element in my list")
```
- Number of elements in your list
```python
list.len()
```
## Edit, Insert and delete
- Replace existing value per index
```python
newList[0] = "newValue"
```
- Insert new value
```python
newList.insert(0, "newValue")
# The rest of values are moved one place to the right.
```
- Delete per index
```python
del list[0]
# You can use it when you know the index of the value or item you want to delete.
```
- Delete per value
```python
list.remove(value1)
# You can use when you know the value, but not the index, it deletes only the first occurrence.
```
- Delete the last value and use it
```python
LastValueSaved = list.pop()
#Deletes the last value at the same time you can save its value.
```
- Delete a particular value and use it
```python
particularValueSaved = list.pop(0)
# It does the same as .pop(), but you can pick one value per its index.
```
## Organize
- Sort permanently
```python
list.sort()
#Alphabetically sorted, and you loose permanently the original order
```
- Sort temporarily
```python
sortedView = sorted(list)
# You can sort it temporarily and recover the original order inmediately
```
- Reverse sort
```python
messedList.sort(reverse=true)
```
- Reverse
```pyhthon
list.reverse()
# You reverse the order of your elements, but not alphabetically, and you can recover the original order by applying the reverse operation again.
```
