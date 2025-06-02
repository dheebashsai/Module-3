# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(string, n):
    a = ''
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

# Read input from user
input_str = input("Enter a string: ")
index = int(input("Enter the index of the character to remove: "))

# Function call and output
result = remove(input_str, index)
print("String after removing character at index", index, ":", result)


## Output
Enter a string: python
Enter the index of the character to remove: 3
String after removing character at index 3 : pyton


## Result
 The program successfully removes the character at the specified index from the input string.
