# Tutorial 02 — Answers 
TIANG XIN YUAN 24082911
## Part I

### Question 1

#### a.

```
System.out.print("Faculty ");
System.out.print("of ");
System.out.print("Computer ");
System.out.print("Science ");
System.out.print("and ");
System.out.print("Information ");
System.out.print("Technology ");

```

#### b. 
```
System.out.print(Faculty \nof \nComputer \nScience \nand \nTechnology)
```
### Question 2

```
System.out.print("\"SDN\" -Software-defined networking");
```

### Question 3
    a. System.Println("Java Programming");
        -> System.println("Java Programming");

    b. System.in.println("Introduction to Java!")
        -> System.println("Introduction to Java!");

    c. System.out.println("\t is the horizontal tab character");
        -> System.out.println("\\t is the horizontal tab character");

    d. system.out.println("Java is case sensitive!" );
        ->System.out.println("Java is case sensitive!");    

### Question 4
a. string
b. double
c. boolean
d. long
e. char
f. string


### Question 5
a. 
``` 
double AMOUNT = 32.5；
AMOUNT += 10;
System.out.println("The amount is "+ AMOUNT)
```

b. 
```
String chapter = "Summary";
System.out.println(chapter);

```

c. 
``` 
int num = 0;
num++;
int num1 = num;
```

d. 
``` 
int num = 3000;
System.out.printf("%4.2f\n", + (double) num);
```

e. 
``` 
String contact;
Scanner keyboard = new Scanner(System.in);
contact = keyboard.nextLine();

```
### Question 6
``` 

import java.util.Scanner;

public class Main {
    public static void main (String[] args){

        double diameter = 0;
        double circumference = 0;

        Scanner input = new Scanner(System.in);

            System.out.print("Enter diameter: ");
            diameter = input.nextDouble();

            circumference = Math.PI * diameter;

        System.out.printf("The circumference of the circle is: %.3f\n" , circumference);

       input.close();
        }

    }


```
### Question 7
``` 
import java.util.Scanner;

public class Main {
    public static void main (String[] args){

        double inch = 0;
        double meters = 0;

        Scanner input = new Scanner(System.in);

            System.out.print("Enter value in inch: ");
            inch = input.nextDouble();

            meters = inch * 0.0254;

        System.out.printf("%.2f inches = %.2f meters", inch, meters);

       input.close();
        }

    }
```
