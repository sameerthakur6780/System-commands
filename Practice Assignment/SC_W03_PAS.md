# Practice Programming Questions.
# Week 3 

---

## Problem 1

Which of the following ways is the correct method to declare a shell variable that is intended to be referenced in a shell script?[MSQ]

(1) ``` declare myvar=”abc” ```

(2) ``` declare -x myvar=”abc” ```

(3) ``` export myvar=”abc” ```

(4) ``` myvar=”abc” ```

### Answer

(2) ``` declare -x myvar=”abc” ```

(3) ``` export myvar=”abc” ```

<div style="page-break-after: always; break-after: page;"></div>

---

## Problem 2

Which of the following ways is the correct method to store the output of the list  command in a shell variable?[MSQ]

(1) ``` myout=ls ```

(2) ``` myout=”ls” ```

(3) ``` myout=`ls` ```

(4) ``` myout=$(ls) ```

### Answer

(3) ``` myout=`ls` ```

(4) ``` myout=$(ls) ```



## Problem 3

What is the expected behaviour of the folowing command?[MCQ]

```bash
ls || date && file *
```

(1) Prints output of `ls`, `date`

(2) Prints output of `ls`, `file`

(3) Prints output of `date`, `file`

(4) Prints output of `ls`

### Answer

(2) 



## Problem 4

Which of the following command can be used to find if a package is installed or not?[MCQ]

(1) ``` dpkg -S ```

(2) ``` apt-get install ```

(3) ``` apt-file ```

(4) ``` apt-get update ```

### Answer

(1) ``` dpkg -S ```



## Problem 5

Each option consists of a pair of operators. Choose the option in which the pair of operators does not perform a similar function. [MCQ]

(1) `||`, `&&`

(2) `|`, `;`

(3) `>`, `>>`

(4) `>>`, `2>`

### Answer

(2) `|`, `;`

<div style="page-break-after: always; break-after: page;"></div>
