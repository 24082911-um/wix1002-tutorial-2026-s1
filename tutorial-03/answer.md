# Tutorial 03 — Answers
TIANG XIN YUAN 24082911

### Question 1
Write statements for each of the following

#### a. Determine whether 3x8=27.
```
boolean isEqual = 3 * 8 == 27;
System.out.println("3 x 8 == 27: " + isEqual); 
```
#### b. Determine whether an input integer is an odd number or even number.


```
if (num % 2 == 0) {
    System.out.println (“even”);
    }
else {
    System.out.println (“odd”);
    }
```

#### c. Determine whether a character is a capital letter.

```
if (ch >= 'A' && ch <= 'Z') {
    System.out.println("capital letter");
    }
else {
    System.out.println("not capital letter");
    }
```
#### d. Display two strings in alphabetical order ignoring their case.

``` 
if (s1.compareToIgnoreCase(s2) <= 0) {
    System.out.println(s1);
    System.out.println(s2);
} else {
    System.out.println(s2);
    System.out.println(s1);
}

```
#### e. A switch statement that display Sunday, Monday, ..., Saturday if the input is 0,1, …, 6.
``` 
switch (day){
    
    case 0:
        System.out.print("Sunday");
        break;
    
    case 1:
        System.out.print("Monday");
        break;
        
    case 2:
        System.out.print("Tuesday");
        break;
    
    case 3:
        System.out.print("Wednesday");
        break;  
        
    case 4:
        System.out.print("Thursday");
        break;
        
    case 5:
        System.out.print("Friday");
        break;
    
    case 6:
        System.out.print("Saturday");
        break;    
    
    default:
        System.out.print("Not applicable");
    }    

```


### Question 2
Correct the error for the following statements.
   
#### a.
```
error: 
if (num1 = num2)
   System.out.println("Number 1 is equal to number 2.");
   
corrected:
if (num1 == num2){
    System.out.println("Number 1 is equal to number 2. ");
    }
```

#### b.
```
error: 
if (x > y > z)
   System.out.println("x is the largest number");
   
corrected:
if (x > y && x > z){
    System.out.println("x is the largest number");
    }

```
   
#### c.
``` 
error:
String s1, s2;
   if (s1==s2)
   System.out.println("They are equal strings.");
   else (s1!=s2)
   System.out.println("They are not equal strings.");
   
corrected:
String s1, s2;
    if (s1.equals(s2)){
        System.out.println("They are equal strings.");
        }
    else{
        System.out.println("They are not equal strings.");
        }
```
   
#### d. 
``` 
error:
if x>0 or y>0;
    System.out.println("Either x or y is positive");

corrected:
if (x>0 || y>0){
    System.out.println("Either x or y is positive");
    }
```
   
### Question 3

#### 3. Write the output for the following statements when x=9 and y=10
a.

```
if (x < 10)
    if (y > 10)
        System.out.println("*****");
    else
        System.out.println("#####");
System.out.println("$$$$$");

output: 
#####
$$$$$
```

b.
``` 
if (x < 10) {
    if (y < 10)
        System.out.println("*****");
else{
    System.out.println("#####");
    System.out.println("$$$$$");
    }
}

output: 
#####
$$$$$
```

c.
``` 
if (x < 10) {
    if (y < 10)
        System.out.println("*****");
    System.out.println("#####");
}    
else{
    System.out.println("$$$$$");
}
    
output:
#####
```

d.
``` 

if (x > 10) {
    if (y > 10) {
        System.out.println("*****");
        System.out.println("#####"); }
    else
        System.out.println("$$$$$");
}

output: 
```
#### Question 4
Write the java statements that used the if statement to find the biggest number among three given integers.
``` 
int num1, num2, num3;

if (num1 > num2 && num1 > num3){
    System.out.println(num1 + " is the biggest number.");
    }    
else if (num2 > num1 && num2 > num3){
    System.out.println(num2 + " is the biggest number.");
    }
else if (num3 > num1 && num3 > num2){
    System.out.println(num3 + " is the biggest number.");    
    }
```



#### Question 5
Write the java statements that determine whether the Leap year. 
A Leap year is divisible by 4 but not by 100. 
However, a Leap year is also divisible by 400.
``` 
if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
    System.out.println(year + " is a leap year.");
}
else {
    System.out.println(year + " is not a leap year.");
}


```
