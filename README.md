# ENG2112 PA1

This problem assignment was the basics of Python and applications of it


# Alphabet Soup

This task made us create a function that arranges a given word in alphabetical order.

First is to set up the function itself using def *function*():
```python
def alphabet_soup() #name of the function that will be used
```

string.replace("", "") #replaces the words from their original form with the alphabetical one.
sorted(...) #takes the string and converts it into a sorted list based on the letter's ASCII values.
"".join(...) #takes the list of sorted letters and joins them back together into a single string.
```

Emoticon Problem: Creates a function that replaces specific words with emoticons.

```python
emoticon ={} #a dictionary function that can set a certain string into an emoticon of your choosing.
for word, emoticon in emoticons.items() #a loop that iterates every item in the emoticons dictionary.
string = string.replace(word, emoticon) #replaces the words in the input with their set of emoticons.
```

Unpacking List Problem: Unpacks the given list into its first, middle, and last segments.

```python
unpacking_list_slicing() #the function where the unpacking is made.
first = input[0] #gets the first element.
middle = input[1:-1] #gets the elements between the first and the last.
last = input[-1] #gets the last element..
```
