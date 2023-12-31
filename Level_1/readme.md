[Scroll Down](#end)

# PYTHON : 10 DAYS LEVEL-UP CHALLANGE [DAY-1]

## 1. Welcome To The Challange
Our first exercise starts with very basic concept in which ask user for input his/her name and welcome that user with his/her name.

For this exercise to be more than basic, we can do something extra, like we greet user according to the time like night, day or noon.

### Require Topics :
- [Python Time Module](https://docs.python.org/3/library/time.html) 
- [Python Type Casting](https://docs.python.org/3/library/functions.html#int)
- [input() Method](https://docs.python.org/3/library/functions.html#input)
- [print() Method](https://docs.python.org/3/library/functions.html#print)
- [Python If-Else](https://docs.python.org/3/tutorial/controlflow.html#if-statements)

so here we go...


**Steps :**

  - [Extract Current time of the day](#--extract-current-time-of-the-day)
  - [User Input](#--user-input)
  - [Set Greeting Quote](#--set-greeting-quote)
  - [Output](#output)
         

### - Extract Current time of the day
For extracting exact time [Time](https://docs.python.org/3/library/time.html) module is used. [Modules](https://www.w3schools.com/python/python_modules.asp) are basically block of codes which are written by someone else and we are use it in our code via importing them, like :

```python
import time
realTime = int(time.strftime('%H'))
```

* Here we import the [Time](https://docs.python.org/3/library/time.html) module and with the help of method `time.strftime('%H')`, we get current hour and store it in variable after conevert it into a intiger via Type-casting [int( )](https://docs.python.org/3/library/functions.html#int). 

### - User Input
In Python user input taken by [input( )](https://docs.python.org/3/library/functions.html#input)

```python
user = input("Enter Your Name: ")
```

### - Set Greeting Quote
Now, greet text individually set accorfing to realTime. For that we use python [if..elif..else](https://docs.python.org/3/tutorial/controlflow.html#if-statements) statement.

```python
if(realTime<12):
    print("Good Morning", user, end=". ")

elif(realTime<16):
    print("Good Afternoon", user, end=". ")

else:
    print("Good Night", user, end=". ")
```


> Note: In python `Indentation` used for indicating block or any function of loop instead of any { }

* Python [print( )](https://docs.python.org/3/library/functions.html#print) used to display and `[end=" "]` is parameter in the print function is used to add any string. At the end of the output of the print statement in python
  
* > By default, the print function ends with a newline `'\n'`.

<br>

At the end welcome statement will placed
```python
print("Welcome To The 10 Days Python Level-Up Challange.")
```

## Output
To run This file in VS Code simpl click on `run code` button : 
![image](/img/level1_output/run_1.png) 

or : 
![image](/img/level1_output/run_2.png) 

OUTPUT : 
![image](/img/level1_output/output.png) 

---

Code : 
[Exercise 1](exe1.py) 

---
<br>

###### END


> See You In Level 2 👀....

