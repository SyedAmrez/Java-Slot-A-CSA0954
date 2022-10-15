1. Create Customer class with deposit() and withdraw() as synchronized methods. Declare
AccountNo, AccName and Balance as Instance Variables inside the class. From the main
class, Input the amount for withdraw() operation and if requested amount is not available in
existing Balance amount, withdraw() method should be temporarily suspended using wait()
method until deposit() method receives the input for amount, to be added in the existing
Balance amount and then withdraw() would be completed in a successful manner. Develop
the above scenario using Synchronization and Inter-Thread Communication.
Note : existing Bank balance amount 10000
Sample Input : 12000, 3000
Sample Output : Withdraw operation success, balance amount 1000

2. Given an integer n, return a string array answer (1-indexed) where:
answer[i] == "FizzBuzz" if i is divisible by 3 and 5.
answer[i] == "Fizz" if i is divisible by 3.
answer[i] == "Buzz" if i is divisible by 5.
answer[i] == i (as a string) if none of the above conditions are true.
Example 1:
Input: n = 3
Output: ["1","2","Fizz"]

3. Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.
Symbol Value
I 1
V 5
X 10
L 50
C 100
D 500
M 1000
For example, 2 is written as II in Roman numeral, just two ones added together. 12 is written
as XII, which is simply X + II. The number 27 is written as XXVII, which is XX + V + II.
Roman numerals are usually written largest to smallest from left to right. However, the
numeral for four is not IIII. Instead, the number four is written as IV. Because the one is
before the five we subtract it making four. The same principle applies to the number nine,
which is written as IX. There are six instances where subtraction is used:
 I can be placed before V (5) and X (10) to make 4 and 9.
 X can be placed before L (50) and C (100) to make 40 and 90.
 C can be placed before D (500) and M (1000) to make 400 and 900.
 Given a roman numeral, convert it to an integer.
Example:
Input: s = "III"
Output: 3

4. Given two strings ransomNote and magazine, return true if ransomNote can be constructed
by using the letters from magazine and false otherwise. Each letter in magazine can only be
used once in ransomNote.
Example 1:
Input: ransomNote = "a", magazine = "b"
Output: false

5. You are given an m x n binary matrix mat of 1's (representing soldiers) and 0's (representing
civilians). The soldiers are positioned in front of the civilians. That is, all the 1's will appear
to the left of all the 0's in each row.
A row i is weaker than a row j if one of the following is true:
The number of soldiers in row i is less than the number of soldiers in row j.
Both rows have the same number of soldiers and i< j. Return the indices of the k weakest
rows in the matrix ordered from weakest to strongest.
Example 1:
Input: mat =
[[1,1,0,0,0],
[1,1,1,1,0],
[1,0,0,0,0],
[1,1,0,0,0],
[1,1,1,1,1]],
k = 3
Output: [2,0,3]

6. Given an integer num, return the number of steps to reduce it to zero. In one step, if the
current number is even, you have to divide it by 2, otherwise, you have to subtract 1 from it.
Example 1:
Input: num = 14
Output: 6
Explanation:
Step 1) 14 is even; divide by 2 and obtain 7.
Step 2) 7 is odd; subtract 1 and obtain 6.
Step 3) 6 is even; divide by 2 and obtain 3.
Step 4) 3 is odd; subtract 1 and obtain 2.
Step 5) 2 is even; divide by 2 and obtain 1.
Step 6) 1 is odd; subtract 1 and obtain 0.
