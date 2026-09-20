# ECE 2112: Python Practice Projects

A repository containing my introductory Python scripts, focusing on core data structures, loop control flow, and syntax fundamentals. 

---

# FOR MODULE 1:
📝 **[click here for reviewer](./mod%201%20reviewer.ipynb)**

---

## Practice Problem 1: string manipulation and input filtering

**Description:** 
Write a script that captures a user's sentence using _input()_

---

## Practice Problem 2: word rotation problem

**Description:** 
Create a function named rotate_word() that accepts a non-empty string. Move the first character of the string to the end while keeping all remaining characters in their original order. Preserve the capitalization of every character.

---

## Practice Problem 3: laptop dictionary

**Description:** 
A script that utilizes a Python Dictionary to store, modify, and delete hardware specifications for a laptop, simulating a hardware upgrade process.

---

## Practice Problem 4: USERNAME BUILDER PROBLEM

**Description:** 
Create a function named make_username() that accepts two strings: first name and last name. The function must:
1. convert all letters to lowercase.
2. remove all spaces from the first name.
3. remove all spaces from the last name.
4. join the processed first and last names using one period (.).

**Function format:** make_username(first_name, last_name)

**Examples:**
* make_username("Ada", "Lovelace") -> "ada.lovelace"
* make_username("Alan", "Turing") -> "alan.turing"
* make_username("Ana Maria", "De Leon") -> "anamaria.deleon"

**Requirement:** Use basic string methods and string concatenation. Return the completed username.

## Practice Problem 5: BOOKEND SWAP PROBLEM

**Description:** 

Create a function named swap_bookends() that accepts a list containing at least two elements. Unpack the list into three variables:
* first - the first element.
* middle - a list containing everything between the first and last elements.
* last - the last element.

Using these variables, return a new list in which the first and last elements have exchanged positions.[cite: 1] The elements in `middle` must remain in their original order. Do not modify the input list.

**Function format:** swap_bookends(items)

**Examples:**[cite: 1]
* swap_bookends([1, 2, 3, 4, 5, 6]) -> [6, 2, 3, 4, 5, 1]
* swap_bookends(["red", "green", "blue"]) -> ["blue", "green", "red"]
* swap_bookends([8, 3]) -> [3, 8]

**Requirement:** Use extended sequence unpacking in the following form: first, *middle, last = items

 
