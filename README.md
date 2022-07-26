## Practice

This practice comprises 4 exercises

### Problem Statements

#### Practice 1 - Find the Largest Number​

Find the Largest Number From 3 Unequal Numbers​
- nested if  ​
- ternary operator  ​

Value1 | Value2 | Value3
|-|-|-| 
30 |  50 |  45

For the given values,
```
Output: Largest Number is 50
```

The solution for this exercise should be provided in `p1-submission.js` file.

The file is located inside the folder `p1-find-the-largest-number`.

#### Practice 2 - Day Count​

Number of days in the 1st, 3rd, 5th, 7th, 8th, and 12th  month equals 31 days.​

Number of days in the 4th, 6th, 9th, and 11th  month equals 30 days.​

Number of days in month 2 is 29 when it is a leap year, otherwise the number of days is 28.​

Write a program that checks the month and year value and prints the number of days in that month. 

For example, if month = 2 and year = 2008,

```
Output: No. of days 29
```

The solution for this exercise should be provided in `p2-submission.js` file.

The file is located inside the folder `p2-day-count`.

#### Practice 3 - Fibonacci Series for First 10 numbers

Print first 10 numbers of a Fibonacci Series.

```
Output: 0 1 1 2 3 5 8 13 21 34 
```

**Note:** Fibonacci numbers form a sequence of numbers where every number is the sum of the preceding two numbers. The first 2 values are 0 and 1 and their sum is 1 which is the next number in the sequence
0,1,1,2,3,5...​

Provide the solution for this exercise in `p3-submission.js` file. 

The file is located inside the folder `p3-fibonacci-first-10`.

#### Practice 4 - Weighted Average​

The placement team of an engineering college needs to select eligible candidates for campus placement. To do so, they require individual weighted average scores of the students.​

​Write a program to calculate the weighted average for individual students. ​

### Task -1
- The percentage value assigned for each of the different types of assessments conducted is listed below. 

Serial No|Assessment Type|Percentage
|-|-|-|
1|Assignments|10
2|Projects|35
3|Quiz|10
4|Mid-Term-Evaluation|15
5|Final Exams|30

- Write a program that calculates the weighted average score and displays the weighted average score of the student.

### Task - 2
- Create the method `calculateWeightedAverage()`. Initialize the variables from the below table and pass these variables as parameters to the method and write the logic inside the function body to calculate the Weighted Average.
- Call the above method globally
- Below is the list of weightages

Variable|Values
|-|-|
assignmentWeight|10
projectWeight|35
quizWeight|10
midTermWight|15
finalExamWeight|30

- Below are the scores of the students secured for the maximum score of 100

Variable|Values
|-|-|
assignmentScore|97
projectScore|82
quizScore|60
midTernScore|60
midTermScore|75
finalExamScore|80

### Task - 3

Calculate the individual weights of all the scores and store it in variables. For example, calculate the weighted score for assignments using the given formula.​

​`assignmentPercentSCore = (assignmentWeight/100) * assignmentScore`

Similarly calculate the weighted score for all the weights.

### Task - 4

- Calculate the overall weighted percentage and store it in a variable as shown below.​

`overallPercentage = assignmentPercentageSCore + projectPercentageSCore + quizPercentageSCore + midTerPercentageScore + finalExamPercentageScore`
- Display all the details in the below format
```
Weights      % Value of SCore
Assignments  9.7
Projects     28.699999
Quizzes      6.0
Mid Term     11.25
Final Exam   24.0

The weighted average score is 79.649994%

```

- The solution for this exercise should be provided in `p4-submission.js` file.
- The file is located inside the folder `p4-weighted-average`.