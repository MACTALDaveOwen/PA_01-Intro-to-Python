# PA_01-Intro-to-Python

Alphabet Soup Problem: This function arranges the letts of the word in alphabetical order (from A to Z).

```
list()    - converts the string in alist of individual characters
sort()    - arranges the list of characters in an alphabetical order
"".join   - combines the sorted list back in a single string.
```

Emoticon Problem: This function converts word equivalent to its emoji

```
emoji = {}              - declaration of a dectionary
for word in emoji:      - loop which replaces the word into its equivalent emoji
word.capitalize         - enables the function to read the word when user input capitalize the word
word.upper              - enables the function to read the word when user input capitalizes the first letter of the word
```

Unpacking List Problem: This Function unpacks the list or a group that the user inputs into first, middle, and last.

```
user_list = input()  - allows user to input their list
user_list.split()    - splits the user's list in a single element
first, last          - unpacks the list by setting the first element of the list in the first, then last element in last.
*middle              - the * in middle means it will take everything in between of the first and last unpacking.
```
