# Operators-Bitwise-Operators
In C++, bitwise operators perform operations on integer data at the individual bit-level.


# **AIM**

Operators-in-C-

## **THEORY**

An operator is a symbol that operates on a value to perform specific mathematical or logical computations. They form the foundation of any programming language. In C++, we have built-in operators to provide the required functionality.

An operator operates the operands. For example, 

int c = a + b;
Here, ‘+’ is the addition operator. ‘a’ and ‘b’ are the operands that are being ‘added’


## **ALGORITHM**

- **Enter Your PRN**

1.It declares two integer variables prn and digit to store the PRN and individual digits, respectively.

2.It prompts the user to enter their PRN.

3.It enters a while loop that continues as long as prn is greater than 0.

4.Inside the loop:

5.It calculates the last digit of prn using the modulo operator (%) and assigns it to the digit variable.

6.It prints the digit on a new line.

7.It divides prn by 10 to remove the last digit.

8.The loop continues until all digits of the PRN have been extracted and printed.

- **Enter marks of each subjects and find the grade based on average**

1.It declares integer variables sub1, sub2, sub3, sub4, sub5 to store the marks of five subjects, and variables sum and average to store the sum of marks and the average, respectively.

2.It prompts the user to enter marks for each subject.

3.It calculates the sum of the marks from all five subjects.

4.It calculates the average by dividing the sum by 5.

5.It uses a series of if and else if statements to determine the grade based on the average:

6.If the average is greater than or equal to 90, it assigns the grade "O."

7.If the average is between 85 and 89, it assigns the grade "A+."

8.If the average is between 75 and 84, it assigns the grade "A."

9.If the average is between 65 and 74, it assigns the grade "B+."

10.If the average is between 55 and 64, it assigns the grade "B."

11.If the average is between 40 and 54, it assigns the grade "C."

12.If none of the above conditions are met, it assigns the grade "Student has failed."

13.It prints the grade based on the average.



## **OUTPUT**
![Screenshot 2023-10-08 at 11 32 12 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/a8d6e4b8-936b-4563-9d81-8f7be23b2732)


![Screenshot 2023-10-08 at 11 32 19 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/617fbbdf-7dcc-4374-957e-ae1364607117)



**EXP 4**
**AIM**

Bitwise operator

## **THEORY**

In C++, bitwise operators perform operations on integer data at the individual bit-level. These operations include testing, setting, or shifting the actual bits. For example,

a & b;
a | b;

Here is a list of 6 bitwise operators included in C++.

Operator	Description
&	Bitwise AND Operator
|	Bitwise OR Operator
^	Bitwise XOR Operator
~	Bitwise Complement Operator
<<	Bitwise Shift Left Operator
>>	Bitwise Shift Right Operator

**C++ Right Shift Operator**

The right shift operator shifts all bits towards the right by a certain number of specified bits. It is denoted by >>.

When we shift any number to the right, the least significant bits are discarded, while the most significant bits are replaced by zeroes.

One bit Right Shift Operator

![Screenshot 2023-10-08 at 11 34 33 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/106cf9ff-ab39-4ef2-b79d-d5743b79a64f)


As we can see from the image above, we have a 4-bit number. When we perform a one-bit right shift operation on it, each individual bit is shifted to the right by 1 bit.

As a result, the right-most bit is discarded, while the left-most bit remains vacant. This vacancy is replaced by a 0.

**C++ Left Shift Operator**

The left shift operator shifts all bits towards the left by a certain number of specified bits. It is denoted by <<.
![Screenshot 2023-10-08 at 11 34 43 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/dbc1df47-bc98-4e7a-8725-705a278629af)


As we can see from the image above, we have a 4-bit number. When we perform a 1 bit left shift operation on it, each individual bit is shifted to the left by 1 bit.

As a result, the left-most bit is discarded, while the right-most bit remains vacant. This vacancy is replaced by a 0.

## ALGORITHM**

- **Set and Resst the given bit**

- *Set Bit Algorithm*:

1.Start

2.Declare an integer variable (e.g., num) where you want to set a bit.

3.Declare an integer value (e.g., bitPosition) indicating the bit position you want to set (0-based index).

4.Use the bitwise OR operator | to set the bit:

5.Set num = num | (1 << bitPosition).

6.The specified bit is now set in the variable num.

7.End

- *Reset (Clear) Bit Algorithm*:

1.Start

2.Declare an integer variable (e.g., num) where you want to reset (clear) a bit.

3.Declare an integer value (e.g., bitPosition) indicating the bit position you want to reset (0-based index).

4.Use the bitwise AND operator & with the bitwise NOT operator ~ to reset the bit:

Set num = num & ~(1 << bitPosition).

5.The specified bit is now reset (cleared) in the variable num.

6.End

- **Left Shift Algorithm**:

1.Start

2.Declare an integer variable (e.g., num) that you want to left-shift.

3.Declare an integer value (e.g., shiftAmount) indicating the number of positions to left-shift num.

4.Use the left-shift operator << to perform the left shift:

Set num = num << shiftAmount.

5.The variable num will now contain the result of left-shifting by shiftAmount positions.

6.End

- **Right Shift Algorithm**:

1.Start

2.Declare an integer variable (e.g., num) that you want to right-shift.

3.Declare an integer value (e.g., shiftAmount) indicating the number of positions to right-shift num.

4.Use the right-shift operator >> to perform the right shift:

Set num = num >> shiftAmount.

5.The variable num will now contain the result of right-shifting by shiftAmount positions.

6.End

- **Bit to be set or reset** 

*Set Bit Based on User Input Algorithm*:

1.Start

2.Declare an integer variable (e.g., num) where you want to set a bit.

3.Prompt the user to enter the bit position they want to set (0-based index) and store it in an integer variable (e.g., bitPosition).

4.Use the bitwise OR operator | to set the bit:

Set num = num | (1 << bitPosition).

5.The specified bit is now set in the variable num.

6.End

*Reset (Clear) Bit Based on User Input Algorithm*:

1.Start

2.Declare an integer variable (e.g., num) where you want to reset (clear) a bit.

3.Prompt the user to enter the bit position they want to reset (0-based index) and store it in an integer variable (e.g., bitPosition).

4.Use the bitwise AND operator & with the bitwise NOT operator ~ to reset the bit:

Set num = num & ~(1 << bitPosition).

5.The specified bit is now reset (cleared) in the variable num.

6.End

## **OUTPUT**

- **Set and Reset the given bit**


![Screenshot 2023-10-08 at 11 34 53 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/c1e2da9f-5433-4032-8833-0f1918b0953b)


- **Left Shift AND Right Shift**



 ![Screenshot 2023-10-08 at 11 34 59 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/8cc2a5c3-fc87-428c-b07b-a2f5ff9dc572)


- **Bit to be set or reset**

![Screenshot 2023-10-08 at 11 35 05 AM](https://github.com/sanskkriti/Operators-Bitwise-Operators/assets/140137289/b9db43f0-4f1f-44a3-8c23-3af6f3bfdbd2)

