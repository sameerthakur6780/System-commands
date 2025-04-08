# Week-4 Practice MCQ_MSQ

## Problem 1

The file "Pincode\_info.csv" has information about the postal circle, division, pin codes and state details. The output of the command "head -5 Pincode\_info.csv" is given below.

```
Circle Name,Region Name,Division Name,Office Name,Pincode,OfficeType,Delivery,District,StateName
Andhra Pradesh Circle,Kurnool Region,Anantapur Division,A Narayanapuram B.O,515004,BO,Delivery,ANANTHAPUR,Andhra Pradesh
Andhra Pradesh Circle,Kurnool Region,Anantapur Division,Akuledu B.O,515731,BO,Delivery,ANANTHAPUR,Andhra Pradesh
Andhra Pradesh Circle,Kurnool Region,Anantapur Division,Alamuru B.O,515002,BO,Delivery,ANANTHAPUR,Andhra Pradesh
Andhra Pradesh Circle,Kurnool Region,Anantapur Division,Allapuram B.O,515766,BO,Delivery,ANANTHAPUR,Andhra Pradesh
```



Which of the following commands can be used to extract only the pin codes and write to a file "pincodes.csv"? [MSQ]

A. `egrep -o '[0-9]{6}' Pincode_info.csv > pincodes.csv`
B. `egrep -o '[[:digit:]]{6}' Pincode_info.csv >> pincodes.csv`
C. `touch pincodes.csv && egrep '[[:digit:]]{6}' Pincode_info.csv >> pincodes.csv`
D. `egrep -q '[0-9]{6}' Pincode_info.csv > pincodes.csv`

### Answer

A - egrep -o '[0-9]{6}' Pincode_info.csv > pincodes.csv

B - egrep -o '[[:digit:]]{6}' Pincode_info.csv >> pincodes.csv

---

## Problem 2

Match the following options used with grep to their corresponding use.

| Options | Uses                                               |
| ------- | -------------------------------------------------- |
| 1. e    | A. Invert the sense of matching                    |
| 2. v    | B. Used for multiple patterns                      |
| 3. i    | C. Print only the matched parts of a matching line |
| 4. o    | D. Ignores case sensitivity                        |

A. 1-B, 2-D, 3-A, 4-C
B. 1-D, 2-C, 3-A, 4-B
C. 1-C, 2-B, 3-D, 4-A
D. 1-B, 2-A, 3-D, 4-C

### Answer

D. 1-B, 2-A, 3-D, 4-C

---

## Problem 3

What is the command in vi editor to copy the character under the cursor and paste it next to itself?

Note: `<C-c>`, `<C-p>` and `<ESC>` represent "Ctrl+c", "Ctrl+v" and Escape key respectively.

A. `<C-c><C-v>`
B. `<ESC>vyp`
C. `<ESC>vcp`
D. `<ESC>:vyp`

### Answer

B. `<ESC>vyp`

---

## Problem 4

What character needs to be pressed when you wish to enter from navigation (normal) mode to insert mode from the beginning of a line in the vi editor?

### Answer

I

---

## Problem 5

```bash
iarray=(1 2 3 4 5)
unset iarray[2]
echo ${iarray[@]:1}
```
What will be the output of the above command sequence? 

a. 1 3 4 5
b. 1 2 3 4 5
c. 2 4 5
d. 2 3 4 5

### Answer
c. 2 4 5

---

## Problem 6

What one-word command in navigation mode can be used to delete consecutive 8 lines in vi editor?

### Answer

8dd

---

