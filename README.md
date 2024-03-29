# Cracking The Coding Interview
Solutions of Cracking the Coding Interview algorithms using Python
### Arrays & Strings
##### 1.1 IS Unique :
Implement an algorithm to determine if a string has all unique characters. What if you cannot use additional data structures?


##### 1.2 Check Permutation :
Given two strings, write a method to decide if one is a permutation of the other.

##### 1.3 URLify :
Write a method to replace all spaces in a string with '%20'. You may assume that the string has sufficient character at the end to hold additional characters and that you have given true length of the string.
```
e.g.
Input:  'Mr. John Smith      '
Output: 'Mr%20John%20Smith'
```

##### 1.4 Palindrome Permutation :
Given a string, write a function to check if its a permutation of a Palindrome. The palindrome doesn't need to be limited to just dictionary words. You can ignore casing and non-letter characters.
```
e.g.
Input:   Tact Coa
Output:  True (permutations: 'taco cat', 'atco cts' etc.)
```


##### 1.5 One Away :
There are 3 types of edits that can be performed on strings: insert a character, remove a character or replace a character. Given two strings, write a function to check if they are one edit(or zero edit) away.
```
e.g.
pale, ple     -> True
pales, pale   -> True
pale, bale    -> True
pale, bake    -> False
```


##### 1.6 String Compression :
Implement a method to perform basic string Compression using the counts of repeated characters. ```For example, the string aabcccccaaa would become a2b1c5a3.``` If the compressed string would not become smaller than the original string, your method should return the original string. You can assume that the string has only uppercase and lowercase characters.


##### 1.7 Rotate Matrix :
Given an image represented by N x N matrix, where each pixel in the image is represented by an integer, write a method to rotate the image by 90 degrees, Can you do this in place?


##### 1.8 Zero Matrix :
Write an algorithm such that if an element in an M x N matrix is 0, its entire row and column are set to 0.


##### 1.9 String Rotation :
Assume you have a method isSubstring which checks if one word is a substring of another. Given two strings s1 and s2, write code to check if s2 is a rotation of s1 using only one call to isSubstring
```(e.g. waterbottle is a rotation of erbottlewat)```
