# control flow satement
in which you defind the order in which code or block of the statment are executed 

Types of the control flow satement/
1. Conditional statement/

 1.if,elif,else we called condition satements\
 2.for,while we called loop statements(iterative statment)\
 3.break,continue and pass we called jump statement\
 4.try,except,finally 

## **if and else statment**
if statment is used to execute a block of code if a condition is true
*else statment is used to execute a block of code if a condition is false*
### Example 1

 > age=17\
if age>=18:\
    print("eligible")\
else:\
    print("not eligible")

### Example 2

>*adnan_pocket_money = 11000\
if adnan_pocket_money > 1000:\
    print("i can buy a car")\
elif adnan_pocket_money > 500:\
    print("i can buy a bike")\
elif adnan_pocket_money > 100:\
    print("i can buy a laptop")\
else:\
    print("i can't buy anything")*

### Example 3 

>*marks = 85\
if marks >= 90:\
print("A grade")\
elif marks >= 80:\
print("B grade")\
elif marks >= 70:\
print("C grade")
else:\
print("F grade")*

### Example 4

>asad =adnan_pocket_money

if adnan_pocket_money>50:

    print("adnan can borrow the money from asad")

else:

    print("adnan can't borrow the money from asad")


### Example 5

>***month_expense =100000\
adnan_pocket_money=10000\
if adnan_pocket_money==month_expense:\
    print("need more money")\
elif month_expense<adnan_pocket_money:\
    print("brow money from asad")\
elif month_expense>adnan_pocket_money:\
    print("adnan can't borrow the money from asad")\
else:]
    print("enough money")***

### Example 6

1. a=15
2. b=25
3. if a==b:
4.    print("a is equal to b")
5. if a!=b:
6.    print("a is not equal to b")

 ### Example 7

```
{
 siblings=["asad","haris","zakriya"]
if "asad" and "maryam"in siblings:
    print("no they are siblings")
elif "zakriya" or "asad":
    print("yes they are siblings")
else:
    print("add maryam in sibling list"
}
```
```
### Example 8
{
    is_sunny= True
is_happy= False
if is_sunny==is_happy:
    print("you can outside for walk")
elif is_sunny!=is_happy:
    print("stay home and do meditation")
else:
    print("you can not outside for walk")
    }
```
#### Example 10

```{
for i in range(1, 6):  # Outer loop for numbers 1 to 5
    for j in range(1, 6):  # Inner loop for numbers 1 to 5
        result = i * j  # Calculate the multiplication result
        if result % 2 == 0:  # Check if the result is even
            print(f"{i} * {j} = {result} is even")
        else:  # If the result is not even, it's odd
            print(f"{i} * {j} = {result} is odd")
    print()  # Print a blank line after each row of the 
```
### Example 11 

```
{
age=17
license=True
if age>18:
    if license==True:
        print("you can drive")
    else:
        print("you can not drive")
else:
    print("you can not drive")
}
```

