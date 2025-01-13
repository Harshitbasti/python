Feature	List	Tuple	Set	Dictionary
Definition	An ordered collection of items that can contain duplicates.	An ordered collection of items that cannot be changed (immutable).	An unordered collection of unique items.	An unordered collection of key-value pairs.
Syntax	my_list = [1, 2, 3]	my_tuple = (1, 2, 3)	my_set = {1, 2, 3}	my_dict = {'a': 1, 'b': 2}
Mutability	Mutable (can be changed)	Immutable (cannot be changed)	Mutable (can be changed)	Mutable (can be changed)
Duplicates	Allows duplicates	Allows duplicates	Does not allow duplicates	Keys must be unique; values can be duplicated.
Order	Ordered (maintains insertion order)	Ordered (maintains insertion order)	Unordered (no guaranteed order)	Unordered (no guaranteed order)
Indexing	Supports indexing (e.g., my_list[0])	Supports indexing (e.g., my_tuple[0])	Does not support indexing	Accessed via keys (e.g., my_dict['a'])
Performance	Slower for membership tests (O(n))	Faster for membership tests (O(n))	Faster for membership tests (O(1))	Fast for key lookups (O(1))
Common Methods	append(), extend(), insert(), remove(), pop(), sort(), reverse()	count(), index()	add(), remove(), discard(), pop(), clear(), union(), intersection()	get(), keys(), values(), items(), update(), pop(), popitem(), clear()
Use Cases	When you need an ordered collection of items that can change, such as a list of tasks.	When you need an ordered collection of items that should not change, such as coordinates.	When you need a collection of unique items, such as a set of unique user IDs.	When you need to associate keys with values, such as a phone book or a configuration.
![image](https://github.com/user-attachments/assets/76d6d251-8a16-46e7-a331-7d12a7bb53a0)
