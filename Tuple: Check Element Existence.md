# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
    # Step 1: Define the tuple
    x = ('a', 'b', 'n', 1, 2, 8, 'z')
    
    # Step 2 & 3: Check for existence
    is_n_present = 'n' in x
    is_8_present = 8 in x
    
    # Step 4: Print results
    print("'n' is in the tuple:", is_n_present)
    print("8 is in the tuple:", is_8_present)


## Output
'n' is in the tuple: True
8 is in the tuple: True

## Result
The program successfully checks and confirms the existence of 'n' and 8 in the given tuple.


