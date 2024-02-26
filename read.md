## something python 

### slicing principle
- string, list, tuple and dictionary has the common slicing principle: [first : last : step] with defautl the first = 0 and the last = length of the container -> so the last is not include to print on the screen.
### string
- all variable declared in the code are considered as string -> so if you want to use it in another data types, you need to cast it into another type
- sicing method in python:
1. head : tail : step ( in this method, we print the string from head to tail with step = step, but not include the character with the tail index)
2. the first character of the string has the index = 1, so the last index has the index = length of the string minus 1 ( len(a) -1 ) or it can has the index = -1 and the front character has the index = -2.
3. reverse the string: ::-1

### range function
- rang ( first, last, step)
- by default, the first = 0, step = 1, so when we have "i in range(10)", it means i start with 0, finish when i = 10, and the step = 1.

### list 
- declare:
1. a = list() -> built-in function
2. a = [] -> using quote
- get length of the list: len(list_name)
- checking an item in the list: "item" in "list"
- adding an item to a list: list_name.append("item")
- deleting an item from a list: list_name.remove("item")
- removing the last item: list_name.pop()
- removing through del: del list_name[index]
- deleting the list: del list_name
- clearing all the elements of a list: list_name.clear()
- copying the list A into list B: B = A.copy()
- Joining listA with listB: listA + ListB or listA.extend(listB)
- counting the item in a list: list_name(count) -> return the number of item in a list
- finding index of an item in a list: list_name.index("item")
- reversing the list: list_name.reverse()
- sorting the list: list_name.sort()


### tuple 
- declare:
1. a = tuple() 
2. a =()
- tuple can not change the element after assign it
- tuple is faster than the list
- tuple's element can not be deleted

- get length of the tuple: len(tuple_name)
- change the tuple into the list -> new_list = list ( tuple_name ) -> otherwise: new_tuple = tuple( list_name )
- check an item whether it is in the tuple: "item_name" in "tuple_name"
- joining two tuple: operator + 
- it is not impossible to remove an element in a tuple so you only can remove | delete all the tuple: del tuple_name

### set 
- declare:
1. a = set()
2. a = {"item1", "item2"...} force to init with at least one elment
- set is the collection of different elements and all of them are sorted increasely
- get length of a set: len( set_name )
- checking a item in the set: "item_name" in "set_name"
- adding an item: set_name.add( "item" )
- the method update add more than one item into the set -> adding a list to the set: set_name.update( list )
- remove an item from the set -> set_name.remove( "item" ) else we can remove the last element through set_name.pop()
- clearing the set: set_name.clear()
- deleting the set: del set_name 
- coverting the set into list: we have listA and setB so we can convert follow this instruction: setB = set( listA )
- we can join two set through union method: setC = setA.union( setB )
- or we can use the update() method
- the subset and the superset: we have two set -> setA include ( 1, 2, 3, 4, 5, 6) and the setB include ( 1, 2, 3) -> consider setA is the superset of the setB and the setB is the subset of the setA
1. setA.issuperset( setB ) -> return true
2. setB.issubset ( setA ) -> return true


### dictionary




