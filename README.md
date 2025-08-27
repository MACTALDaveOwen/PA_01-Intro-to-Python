# PA_01-Intro-to-Python

Alphabet Soup Problem: This function arranges the letters of the word in alphabetical order (from A to Z).

This function converts the input string to a list of charaters, sorts the list in alphabetical order, and then joins the character back in a single string.

```
list()    - converts the string in alist of individual characters
sort()    - arranges the list of characters in an alphabetical order
"".join   - combines the sorted list back in a single string.
```

Emoticon Problem: This function converts word equivalent to its emoji

This function uses a loop to replace words in the user's input with their corresponding emoji which handles various capitalization styles.

```
emoji = {}              - declaration of a dectionary
for word in emoji:      - loop which replaces the word into its equivalent emoji
word.capitalize         - enables the function to read the word when user input capitalize the word
word.upper              - enables the function to read the word when user input capitalizes the first letter of the word
```

Unpacking List Problem: This Function unpacks the list or a group that the user inputs into first, middle, and last.

This takes a string input from the user, then splits it in al ist of elements, and uses an unpacking assignment to assign the first, middle, and last elements to separate variables.

```
user_list = input()  - allows user to input their list
user_list.split()    - splits the user's list in a single element
first, last          - unpacks the list by setting the first element of the list in the first, then last element in last.
*middle              - the * in middle means it will take everything in between of the first and last unpacking.
```
