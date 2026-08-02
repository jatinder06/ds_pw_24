# Python Data Types Quiz — 20th Aug '23

**Score:** 46 out of 50 correct

---

## 1. Which of the following is mutable in Python?

- [ ] Tuple
- [ ] String
- [x] List
- [ ] frozenset

**Explanation:** Lists in Python are mutable, meaning their elements can be changed after they are created.

---

## 2. Which of the following creates an empty set in Python?

- [ ] `set{}`
- [ ] `{}`
- [x] `set()`
- [ ] `[]`

**Explanation:** The `set()` function creates an empty set. `{}` creates an empty dictionary.

---

## 3. Which data type would you use to store key-value pairs?

- [ ] List
- [ ] Tuple
- [ ] Set
- [x] Dictionary

**Explanation:** Dictionaries in Python are used to store key-value pairs.

---

## 4. Which of the following is ordered in Python?

- [ ] Set
- [ ] Dictionary (as of Python 3.7)
- [ ] List
- [x] Both b and c

**Explanation:** As of Python 3.7, dictionaries maintain the order of items. Lists are also ordered.

---

## 5. Which of the following cannot contain duplicate elements?

- [ ] List
- [ ] Tuple
- [x] Set
- [ ] Dictionary (based on keys)

**Explanation:** Sets in Python do not allow duplicate elements.

---

## 6. Which data type is immutable?

- [ ] List
- [x] Tuple
- [ ] Set
- [ ] Dictionary

**Explanation:** Tuples are immutable, meaning their elements cannot be changed after they are created.

---

## 7. How do you add an element to a set in Python?

- [ ] `append()`
- [x] `add()`
- [ ] `insert()`
- [ ] `push()`

**Explanation:** The `add()` method is used to add an element to a set.

---

## 8. Which method would you use to get all keys from a dictionary?

- [ ] `getkeys()`
- [ ] `all_keys()`
- [x] `keys()`
- [ ] `fetch_keys()`

**Explanation:** The `keys()` method returns all keys from a dictionary.

---

## 9. Which of the following is used to create a tuple?

- [ ] `[]`
- [ ] `{}`
- [x] `()`
- [ ] `<>`

**Explanation:** Parentheses `()` are used to create tuples in Python.

---

## 10. How do you access the third element of a list named `my_list`?

- [x] `my_list[2]`
- [ ] `my_list[3]`
- [ ] `my_list(2)`
- [ ] `my_list{2}`

**Explanation:** In Python, indexing starts from 0. So, the third element is accessed using index 2.

---

## 11. Which method is used to remove a specific element from a set?

- [ ] `remove()`
- [ ] `delete()`
- [ ] `discard()`
- [x] Both a and c

**Explanation:** Both `remove()` and `discard()` methods can be used to remove a specific element from a set. However, `remove()` raises an error if the element is not found, while `discard()` does not.

---

## 12. Which of the following can be used as a dictionary key?

- [ ] List
- [x] Tuple
- [ ] Another dictionary
- [ ] Set

**Explanation:** Dictionary keys must be immutable. Tuples are immutable, so they can be used as dictionary keys.

---

## 13. Which method is used to add multiple items to a set?

- [ ] `add()`
- [ ] `append()`
- [ ] `insert()`
- [x] `update()`

**Explanation:** The `update()` method is used to add multiple items to a set.

---

## 14. What is the output of `type((1,2,3))`?

- [ ] `<class 'list'>`
- [ ] `<class 'set'>`
- [ ] `<class 'dict'>`
- [x] `<class 'tuple'>`

**Explanation:** `(1,2,3)` is a tuple, so its type is `<class 'tuple'>`.

---

## 15. Which method would you use to remove the last item from a list?

- [ ] `remove()`
- [ ] `discard()`
- [x] `pop()`
- [ ] `delete()`

**Explanation:** The `pop()` method removes the last item from a list if no index is provided.

---

## 16. How do you create a dictionary with keys as numbers from 1 to 3 and values as their squares?

- [x] `{1:1, 2:4, 3:9}`
- [ ] `dict(1=1, 2=4, 3=9)`
- [ ] `{1:2, 2:4, 3:6}`
- [ ] `dict(1:2, 2:4, 3:6)`

**Explanation:** Dictionaries are created using curly braces `{}` with key-value pairs separated by colons.

---

## 17. Which of the following methods returns a list of all values in a dictionary?

- [ ] `get_values()`
- [x] `values()`
- [ ] `all_values()`
- [ ] `fetch_values()`

**Explanation:** The `values()` method returns a list of all the values in a dictionary.

---

## 18. Which of the following is not a valid way to create a set in Python?

- [ ] `set([1,2,3])`
- [ ] `{1,2,3}`
- [x] `set{1,2,3}`
- [ ] `set()`

**Explanation:** The correct syntax to create a set using the `set()` function is `set([1,2,3])`. `set{1,2,3}` is invalid syntax.

---

## 19. Which of the following will create a tuple with a single element?

- [ ] `(1)`
- [ ] `1,`
- [x] `(1,)`
- [ ] `tuple(1)`

**Explanation:** A tuple with a single element is defined by placing a comma after the element.

---

## 20. Which method is used to get the value of a key in a dictionary?

- [x] `get()`
- [ ] `fetch()`
- [ ] `retrieve()`
- [ ] `value()`

**Explanation:** The `get()` method is used to retrieve the value of a given key in a dictionary.

---

## 21. Which of the following will create an empty list?

- [ ] `list{}`
- [x] `[]`
- [ ] `list()`
- [ ] `list[]`

**Explanation:** Square brackets `[]` are used to create an empty list.

---

## 22. Which of the following is not a valid dictionary?

- [ ] `{1: 'one', 2: 'two'}`
- [ ] `{'key1': 'value1', 'key2': 'value2'}`
- [x] `{[1,2,3]: 'list'}`
- [ ] `{'key': (1,2,3)}`

**Explanation:** Dictionary keys must be immutable. Lists are mutable and cannot be used as dictionary keys.

---

## 23. How do you create a list with numbers from 1 to 5?

- [ ] `list(1,2,3,4,5)`
- [x] `[1,2,3,4,5]`
- [ ] `list[1,2,3,4,5]`
- [ ] `list{1:5}`

**Explanation:** Lists are created using square brackets `[]` with elements separated by commas.

---

## 24. Which of the following methods will add an element to the end of a list?

- [ ] `push()`
- [ ] `add()`
- [x] `append()`
- [ ] `insert()`

**Explanation:** The `append()` method adds an element to the end of a list.

---

## 25. Which of the following will create a tuple with elements 1, 2, and 3?

- [ ] `tuple(1,2,3)`
- [ ] `(1 2 3)`
- [x] `(1,2,3)`
- [ ] `tuple[1,2,3]`

**Explanation:** Tuples are created using parentheses `()` with elements separated by commas.

---

## 26. Which method is used to remove a specific value from a list?

- [ ] `discarditem()`
- [ ] `delete()`
- [x] `remove()`
- [ ] `pop()`

**Explanation:** The `remove()` method removes the first occurrence of a value from a list.

---

## 27. How do you access the value associated with the key 'name' in a dictionary named `my_dict`?

- [ ] `my_dict.name`
- [x] `my_dict['name']`
- [ ] `my_dict.getname()`
- [ ] `my_dict{name}`

**Explanation:** Dictionary values are accessed using their keys inside square brackets.

---

## 28. Which of the following methods returns a list of all keys in a dictionary?

- [ ] `get_keys()`
- [x] `keys()`
- [ ] `all_keys()`
- [ ] `fetch_keys()`

**Explanation:** The `keys()` method returns a list of all the keys in a dictionary.

---

## 29. Which of the following is not a valid way to create a list in Python?

- [ ] `list()`
- [ ] `[]`
- [x] `list{}`
- [ ] `[1,2,3]`

**Explanation:** The correct syntax to create a list using the `list()` function is `list([1,2,3])`. `list{}` is invalid syntax.

---

## 30. Which of the following methods will add multiple items to a list?

- [ ] `append()`
- [x] `extend()`
- [ ] `add()`
- [ ] `push()`

**Explanation:** The `extend()` method adds multiple items to a list.

---

## 31. Which of the following will create a set with elements 1, 2, and 3?

- [ ] `set(1,2,3)`
- [ ] `{1 2 3}`
- [x] `{1,2,3}`
- [ ] `set[1,2,3]`

**Explanation:** Sets are created using curly braces `{}` with elements separated by commas.

---

## 32. Which of the following methods will remove all items from a set?

- [x] `clear()`
- [ ] `empty()`
- [ ] `remove_all()`
- [ ] `discard_all()`

**Explanation:** The `clear()` method removes all items from a set.

---

## 33. Which of the following methods will add a key-value pair to a dictionary?

- [ ] `add()`
- [ ] `append()`
- [ ] `insert()`
- [x] None of the above

**Explanation:** Key-value pairs are added to dictionaries by assigning a value to a key using the assignment operator (e.g. `my_dict['key'] = 'value'`), not via a method.

---

## 34. Which of the following is not a valid way to create a tuple in Python?

- [ ] `tuple()`
- [ ] `()`
- [x] `tuple{}`
- [ ] `(1,2,3)`

**Explanation:** The correct syntax to create a tuple using the `tuple()` function is `tuple((1,2,3))`. `tuple{}` is invalid syntax.

---

## 35. Which of the following methods will remove a key-value pair from a dictionary?

- [ ] `discard()`
- [ ] `delete()`
- [ ] `remove()`
- [x] `pop()`

**Explanation:** The `pop()` method removes a key-value pair from a dictionary using the key.

---

## 36. Which of the following methods will check if a key exists in a dictionary?

- [ ] `exists()`
- [ ] `contains()`
- [ ] `has_key()`
- [x] None of the above

**Explanation:** To check if a key exists in a dictionary, you can use the `in` keyword.

---

## 37. Which of the following methods will return a list of all values in a dictionary?

- [ ] `get_values()`
- [x] `values()`
- [ ] `all_values()`
- [ ] `fetch_values()`

**Explanation:** The `values()` method returns a list of all the values in a dictionary.

---

## 38. Which of the following is not a valid way to create a dictionary in Python?

- [ ] `dict()`
- [ ] `{}`
- [x] `dict[]`
- [ ] `{'key': 'value'}`

**Explanation:** The correct syntax to create a dictionary using the `dict()` function is `dict(key='value')`. `dict[]` is invalid syntax.

---

## 39. Which of the following methods will add an element to a tuple?

- [ ] `append()`
- [ ] `add()`
- [ ] `insert()`
- [x] None of the above

**Explanation:** Tuples are immutable, so you cannot add elements to them.

---

## 40. Which of the following methods will remove an element from a tuple?

- [ ] `remove()`
- [ ] `discard()`
- [ ] `pop()`
- [x] None of the above

**Explanation:** Tuples are immutable, so you cannot remove elements from them.

---

## 41. Which of the following methods will add multiple key-value pairs to a dictionary?

- [ ] `append()`
- [ ] `extend()`
- [ ] `add()`
- [x] `update()`

**Explanation:** The `update()` method adds multiple key-value pairs to a dictionary.

---

## 42. Which of the following methods will return a list of all keys in a dictionary?

- [ ] `get_keys()`
- [x] `keys()`
- [ ] `all_keys()`
- [ ] `fetch_keys()`

**Explanation:** The `keys()` method returns a list of all the keys in a dictionary.

---

## 43. Which of the following methods will check if a value exists in a dictionary?

- [ ] `exists()`
- [ ] `contains()`
- [ ] `has_value()`
- [x] None of the above

**Explanation:** To check if a value exists in a dictionary, you can use the `in` keyword with the `values()` method.

---

## 44. Which of the following methods will return a list of all items in a dictionary?

- [ ] `get_items()`
- [x] `items()`
- [ ] `all_items()`
- [ ] `fetch_items()`

**Explanation:** The `items()` method returns a list of all the key-value pairs (as tuples) in a dictionary.

---

## 45. Which of the following methods will remove a key-value pair from a dictionary using the value?

- [ ] `remove_by_value()`
- [ ] `discard_by_value()`
- [ ] `pop_by_value()`
- [x] None of the above

**Explanation:** There is no built-in method to remove a key-value pair from a dictionary using the value. You would need to iterate through the dictionary and find the key associated with the value to remove it.

---

## 46. Which of the following methods will add an element to a set?

- [x] `add()`
- [ ] `append()`
- [ ] `insert()`
- [ ] `push()`

**Explanation:** The `add()` method adds an element to a set.

---

## 47. Which of the following attributes is not applicable to a set?

- [ ] `remove()`
- [ ] `discard()`
- [ ] `pop()`
- [x] `delete()`

**Explanation:** The `set` object has no attribute `delete`; calling it raises an `AttributeError`.

---

## 48. Which of the following methods will check if an element exists in a set?

- [ ] `exists()`
- [ ] `contains()`
- [ ] `has_element()`
- [x] None of the above

**Explanation:** To check if an element exists in a set, you can use the `in` keyword.

---

## 49. Which of the following methods will return a list of all elements in a set?

- [ ] `get_elements()`
- [ ] `elements()`
- [ ] `all_elements()`
- [x] None of the above

**Explanation:** Sets do not have a method to return a list of all elements. You can simply iterate through the set or convert it to a list using the `list()` function.

---

## 50. Which of the following methods will add multiple elements to a set?

- [ ] `add()`
- [ ] `append()`
- [ ] `insert()`
- [x] `update()`

**Explanation:** The `update()` method adds multiple elements to a set.