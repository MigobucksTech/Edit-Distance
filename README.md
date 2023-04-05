# Edit Distance
Welcome to the sokoskills coding test!

This repository contains a coding test for candidates applying for a programming position. Please read the instructions carefully and complete the tasks as specified.

Instructions
Fork this repository to your own GitHub account.
Clone the repository to your local machine.
Complete the coding tasks in the given files.
Test your code thoroughly to ensure it works as expected.
Commit your changes and push them to your forked repository.
Create a pull request to the original repository with your changes.

# Files

 Given two strings word1 and word2, return the minimum number of operations required to convert word1 to word2.

You have the following three operations permitted on a word:

Insert a character
Delete a character
Replace a character

Example 1:

Input: word1 = "horse", word2 = "ros"
Output: 3
Explanation: 
horse -> rorse (replace 'h' with 'r')
rorse -> rose (remove 'r')
rose -> ros (remove 'e')
Example 2:

Input: word1 = "intention", word2 = "execution"
Output: 5
Explanation: 
intention -> inention (remove 't')
inention -> enention (replace 'i' with 'e')
enention -> exention (replace 'n' with 'x')
exention -> exection (replace 'n' with 'c')
exection -> execution (insert 'u')
 

Constraints:

0 <= word1.length, word2.length <= 500
word1 and word2 consist of lowercase English letters.

Submission
Please ensure that you have completed all the tasks and that your code passes all the tests before submitting your solution. When you are ready, create a pull request to the original repository with your changes. We will review your code and get back to you as soon as possible.

Thank you for your time and effort. Good luck!
