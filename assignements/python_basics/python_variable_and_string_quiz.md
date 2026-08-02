# Python Variables and Strings Quiz

## 1. What will be the value of the variable `x` after the following code is executed in Python?

```python
x = 10
x = x + 5
```

- [ ] 10
- [x] 15
- [ ] 5
- [ ] 20

**Explanation:** The initial value of `x` is 10. Then, `x` is updated by adding 5 to its current value. Therefore, the value of `x` becomes 15.

---

## 2. Which of the following is a valid variable name in Python?

- [x] `my_var`
- [ ] `123var`
- [ ] `_var-abc`
- [ ] `$var`

**Explanation:** Variable names in Python can consist of letters, numbers, and underscores, but they cannot start with a number or contain special characters like hyphens or dollar signs.

---

## 3. What is the purpose of using the `input()` function in Python?

- [ ] To perform mathematical calculations
- [ ] To print output to the console
- [x] To take user input
- [ ] To define variables

**Explanation:** The `input()` function is used to receive input from the user during program execution.

---

## 4. Which of the following is the correct way to concatenate two strings in Python?

- [ ] `string1 . string2`
- [x] `string1 + string2`
- [ ] `string1 : string2`
- [ ] `string1 - string2`

**Explanation:** In Python, the `+` operator is used to concatenate strings.

---

## 5. What will be the output of the following code in Python?

```python
name = "John"
age = 25
print("My name is", name, "and I am", age, "years old.")
```

- [x] My name is John and I am 25 years old.
- [ ] My name is name and I am age years old.
- [ ] My name is "John" and I am 25 years old.
- [ ] Error: Undefined variable name

**Explanation:** The variables `name` and `age` are properly substituted into the string using the `print()` function.

---

## 6. What will the following code snippet output?

```python
word = "Python"
print(word[2])
```

- [x] t
- [ ] h
- [ ] o
- [ ] y

**Explanation:** In Python, string indexing starts from 0. So, `word[2]` refers to the third character in the string, which is "t".

---

## 7. Which of the following is the correct way to get the length of a string?

- [ ] `_length(string)`
- [ ] `string.len()`
- [x] `len(string)`
- [ ] `string.length()`

**Explanation:** The `len()` function is used to get the length of a string.

---

## 8. What does the `str.upper()` method do in Python?

- [x] Converts a string to uppercase
- [ ] Converts a string to lowercase
- [ ] Removes leading and trailing spaces from a string
- [ ] Reverses the characters in a string

**Explanation:** The `str.upper()` method converts all characters in a string to uppercase.

---

## 9. Which of the following is the correct way to check if a string contains a specific substring?

- [ ] `string.contains(substring)`
- [x] `substring in string`
- [ ] `string.includes(substring)`
- [ ] `string.indexOf(substring)`

**Explanation:** The `in` keyword is used to check if a substring is present in a string.

---

## 10. What will be the output of the following code?

```python
text = "Hello, World!"
print(text[7:12])
```

- [ ] Hello
- [x] World
- [ ] Wor
- [ ] llo, W

**Explanation:** The slice `[7:12]` extracts characters from index 7 to index 11 (inclusive), which corresponds to the substring "World".

---

## 11. What will be the output of the following code?

```python
phrase = "Python is fun!"
new_phrase = phrase.replace("fun", "awesome")
print(new_phrase)
```

- [ ] Python is fun!
- [x] Python is awesome!
- [ ] Python awesome!
- [ ] Python is

**Explanation:** The `replace()` method replaces occurrences of a substring in a string with another substring.

---

## 12. Which of the following is an example of a valid string declaration?

- [ ] `'Hello, World!"`
- [ ] `"Hello, World!`
- [x] `'Hello, World!'`
- [ ] `Hello, World!"`

**Explanation:** Strings in Python can be defined using either single quotes or double quotes. The correct option uses matching single quotes, which is valid.

---

## 13. What will be the output of the following code?

```python
string1 = "Python"
string2 = "Programming"
result = string1 + " " + string2
print(result)
```

- [x] Python Programming
- [ ] PythonProgramming
- [ ] Python + Programming
- [ ] PythonProgramming

**Explanation:** The `+` operator is used to concatenate strings. Here, a space is added between `string1` and `string2` to create the desired output.

---

## 14. Which of the following is the correct way to declare a multi-line string in Python?

- [ ] `string = "This is a multi-line string."`
- [ ] `string = 'This is a multi-line string.'`
- [x] `string = """This is a multi-line string."""`
- [ ] `string = "This is a multi-line string.`

**Explanation:** Triple quotes (`"""` or `'''`) are used to define multi-line strings in Python.

---

## 15. What will be the output of the following code?

```python
word = "Python"
repeated_word = word * 3
print(repeated_word)
```

- [ ] Python
- [x] PythonPythonPython
- [ ] 3Python
- [ ] 3

**Explanation:** The `*` operator is used to repeat a string a certain number of times. In this case, the string "Python" is repeated three times.

---

## 16. Which of the following is a valid way to convert an integer to a string in Python?

- [x] `str(number)`
- [ ] `number.to_string()`
- [ ] `string(number)`
- [ ] `number.toString()`

**Explanation:** The `str()` function is used to convert data types to strings, including integers.

---

## 17. What will be the output of the following code?

```python
message = "Hello, World!"
print(message[-6:-1])
```

- [ ] Hello
- [x] World
- [ ] ,Wor
- [ ] World!

**Explanation:** Negative indices count from the end of the string. So, `message[-6:-1]` extracts characters from index -6 to index -2, which corresponds to the substring "World".

---

## 18. What will be the output of the following code?

```python
word = "python"
capitalized_word = word.capitalize()
print(capitalized_word)
```

- [x] Python
- [ ] PYTHON
- [ ] pYTHON
- [ ] python

**Explanation:** The `capitalize()` method capitalizes the first character of a string.

---

## 19. What will be the output of the following code?

```python
text = "   Hello, World!   "
trimmed_text = text.strip()
print(trimmed_text)
```

- [x] Hello, World!
- [ ] "  Hello, World!"
- [ ] " Hello, World! "
- [ ] Hello, World! (with trailing spaces)

**Explanation:** The `strip()` method removes leading and trailing spaces from a string.

---

## 20. Which of the following methods can be used to convert a string to lowercase in Python?

- [x] `string.lower()`
- [ ] `string.upper()`
- [ ] `string.toLower()`
- [ ] `string.casefold()`

**Explanation:** The `lower()` method is used to convert a string to lowercase in Python.
