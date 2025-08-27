# ENG2112 PA1

Alphabet Soup: Creates a function that arranges a given word in alphabetical order.

```python
"".join () #joins elements of the list into a single string ('') shows that it will function with no spaces.
sorted() #sorts the elements of the given word in its alphabetical order based on the letter's ASCII value.
```

Emoticon Problem: Creates a function that replaces specific words with emoticons.

```python
emoticon ={} #a dictionary function that can set a certain string into an emoticon of your choosing.
for word, emoticon in emoticons.items() #a loop that iterates every item in the emoticons dictionary.
string = string.replace(word, emoticon) #replaces the words input in the emoticon dictionary with its set of emoticons
```

Unpacking List Problem: Unpacks the given list into its first, middle, and last segments.

```python
unpacking_list_slicing() #the function where the unpacking is made.
first = input[0] #gets the first element
middle = input[1:-1] #gets the elements between the first and the last.
last = input[-1] #gets the last element.
```
