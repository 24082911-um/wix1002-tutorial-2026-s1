# Tutorial 01 — Answers 
## Tiang Xin Yuan 24082911


## Part I

### Question 1

#### **IPO Model**

| Input            | Process                               | Output  |
|------------------|---------------------------------------|---------|
| Number1, Number2 | Product = Multiply Number1 by Number2 | Product |


#### **Pseudocode**

```
START
    INPUT Number1
    INPUT Number2
    Product = Number1 * Number2
    PRINT Product
END
```


#### **Flowchart**

![flowchart 1.png](image/flowchart%201.png)


### Question 2
#### **IPO Model**

| Input | Process                                                     | Output                                                  |
|-------|-------------------------------------------------------------|---------------------------------------------------------|
| None  | - Generate a random number<br/>- Compare the number with 50 | - Message: Greater than 50, or less than or equal to 50 |


#### **Pseudocode**

```
START
    Generate a random number 
    IF the random number > 50 THEN
        PRINT "Greater than 50"
    ELSE
        PRINT "Less than or equal to 50"
    ENDIF
END
```


#### **Flowchart**

![flowchart 2.png](image/flowchart%202.png)



### Question 3

#### **IPO Model**

| Input | Process              | Output      |
|-------|----------------------|-------------|
| Mark  | Compare mark with 40 | Pass / Fail |


#### **Pseudocode**

```
START
    INPUT mark
    IF mark >= 40 THEN
        PRINT "Pass"
    ELSE
        PRINT "Fail"
    END IF
END
```


#### **Flowchart**

![flowchart 3.png](image/flowchart%203.png)![img.png](image/flowchart%203.png)

### Question 4

#### **IPO Model**

| Input                           | Process                 | Output                             |
|---------------------------------|-------------------------|------------------------------------|
| Player 1 dice<br/>Player 2 dice | Compare both dice value | Player 1 Wins/ Player 2 Wins / Tie |


#### **Pseudocode**

```
START
    Player1 = Generate random number (1-6)
    Player2 = Generate random number (1-6)
    
    PRINT Player1 
    PRINT Player2
    
    IF Player1 > Player2 THEN
        PRINT "Player 1 wins"
    
    ELSE IF Player2 > Player1 THEN
        PRINT "Player 2 wins"
    
    Else
        PRINT "Tie"
    
    END IF
    
END
```
#### **Flowchart**

![flowchart 4.png](image/flowchart%204.png)

### Question 5
#### **IPO Model**

| Input            | Process                          | Output    |
|------------------|----------------------------------|-----------|
| length<br/>Width | Perimeter = 2 * (Length + Width) | Perimeter |


#### **Pseudocode**

```
START
    INPUT Length
    INPUT Width
    
    Perimeter = 2 * (Length + Width)
    
    PRINT Perimeter
END
```

#### Flowchart

![flowchart 5.png](image/flowchart%205.png)
### Question 6
#### **IPO Model**

| Input | Process                                                                                                      | Output             |
|-------|--------------------------------------------------------------------------------------------------------------|--------------------|
| none  | - Assign the first number as the minimum<br/>- Compare each new random number with the minimum and update it | The minimum number |


#### **Pseudocode**

```
START
    Generate a random number
    Minimum = random number
    
    Counter = 1
    
    WHILE Counter < 10
        Generate a new random number
        
        IF Randomnumber < Minimum THEN
            Minimum = RandomNumber
        ENDIF
        
        Counter = Counter + 1
    ENDWHILE
    
    PRINT Minimum
END
```

#### Flowchart
![img.png](image/flowchart%206.png)
### Question 7
#### **IPO Model**

| Input | Process                                                                                                               | Output                                              |
|-------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| None  | - Check each number: if number modulus 2 equal 0 it is even,otherwise it is odd.<br/>- count the numbers even and odd | - Number of odd numbber<br/>- Number of even number |


#### **Pseudocode**

```
START
    OddCount = 0
    EvenCount = 0
    Count = 0
    
    WHILE count is < 10
        Generate RandomNumber between 10-100
    IF RandomNumber MOD 2 == 0 THEN
        EvenCount = EvenCount + 1
    ELSE 
        OddCount = OddCount + 1
    ENDIF
    
    Count = Count + 1
    ENDWHILE
    
    PRINT OddCount
    PRINT EvenCount
END
```
#### Flowchart

![img.png](image/flowchart%207.png)





---
## Part II

### Question 8

#### **IPO Model**

| Input      | Process                                                                  | Output                          |
|------------|--------------------------------------------------------------------------|---------------------------------|
| A sentence | - Read each character of the sentence<br/>- Count the characters U and M | - Number of U<br/>- Number of M |


#### **Pseudocode**

```
START
    INPUT sentence
    
    alphabetU = 0
    alphabetM = 0
    index = 0
    WHILE index is < length of sentence
        READ the char at index
        IF the char is U or char is u THEN
                alphabetU = alphabetU + 1
        ELSE IF the char is M or char is m THEN
                alphabetM = alphabetM + 1
        ENDIF
        index = index + 1
    ENDWHILE
    
    PRNIT alphabetU
    PRINT alphabetM    
END
```


#### **Flowchart**
![flowchart 8.png](image/flowchart%208.png)

### Question 9

#### **IPO Model**

| Input                     | Process                          | Output               |
|---------------------------|----------------------------------|----------------------|
| Web page content, keyword | Search for the keyword and count | Frequency of keyword |


#### **Pseudocode**

```
START
    
    INPUT WebPage
    INPUT Keyword
    
    Frequency = 0
    Index = 0
    
    WHILE Index < total number of words
        Read the word according to index
        
        IF the word == keyword
            Frequency = Frequency + 1
        END IF
        
        Index = Index + 1
    ENDWHILE
    
    PRINT Frequency
    
END
```


#### **Flowchart**

![flowchart 9.png](image/flowchart%209.png)![img.png](image/flowchart%209.png)

### Question 10

#### **IPO Model**

| Input | Process                                                                            | Output                    |
|-------|------------------------------------------------------------------------------------|---------------------------|
| None  | Gender of 100 randomly generated <br/>- Check each student's gender, count females | Number of female students |


#### **Pseudocode**

```
START
    FemaleCount = 0
    Counter = 1
    
    WHILE Counter <= 100
        Randomly generate RANDOM (F,M)
        
        IF Gender = F
            FemaleCount = FemaleCount + 1
        ENDIF
        
        Counter = Counter + 1
    ENDWHILE
    
    PRINT FemaleCount
END
```


#### **Flowchart**
![img.png](image/flowchart%2010.png)
### Question 11

#### **IPO Model**

| Input | Process                                                                       | Output                        |
|-------|-------------------------------------------------------------------------------|-------------------------------|
| None  | Generate 5 random number and compare and swap them if they are in wrong order | 5 numbers in decending number |


#### **Pseudocode**

```
START
    Counter = 0

    WHILE Counter < 5
        Generate a random number (1-100)
        Store the number in a list

        Counter = Counter + 1
    ENDWHILE

    FOR Index = 0 TO 3
        FOR Next = Index + 1 TO 4
            IF Index < Next THEN
                Temporary = Index
                Index = Next
                Next = Temporary
            ENDIF
        ENDFOR
    ENDFOR

    PRINT List
END

```


#### **Flowchart**
![img.png](image/flowchart%2011.png)
### Question 12

#### **IPO Model**

| Input        | Process                                                         | Output                       |
|--------------|-----------------------------------------------------------------|------------------------------|
| user's guess | Generate random number<br/>Compare the guess with random number | Too High / Too Low / Success |


#### **Pseudocode**

```
START
    
    Generate randomNumber (1-100)
    
    INPUT guessNum
    
    WHILE guessNum != randomNumber
    
        IF guessNum < randomNumber
            PRINT "Too Low"
        ELSE IF guessNum > randomNumber
            PRINT "Too High"
        ELSE IF
        
        INPUT guessNum
       
    ENDWHILE
    
    PRINT "Correct!"
END
```


#### **Flowchart**

![flowchart 12.png](image/flowchart%2012.png)


