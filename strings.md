# Strings

- Write a method that to remove the nth index character from a nonempty string.

- Write a method that to remove the characters which have odd index values of a given string. 

- Write a method that takes input from the user and displays that input back in upper and lower cases. 

- Write a method that reverses a string if it's length is a multiple of 4

- Write method to convert a given string to all uppercase if it contains at least 2 uppercase characters in the first 4 characters.

- Write a method that to remove a newline.

- Write a method to display formatted text (width=50) as output

- Write a method that formats a number with a percentage

-  Write a method that reverses a string.

-  Write a method that strips a set of characters from a string. 

- Write a method that transforms to lowercase first n characters in a string

- Write a method to capitalize first and last letters of each word of a given string.

- Write a method to compute sum of digits of a given string(if any).

## Clean the text
You will get a text from where you will need to clean the text because it contains a lot of strange
characters that don’t belong there ( ^ <, > &+ @%$)
```
Input:
Hi^>there<<I’m+ telling%%you, you &need% to$ do& your $homeworks. @Hate ^me^ %now% and %thank% me &later.
Output:
Hi there I’m telling you, you need to do your homeworks. Hate me now and thank me later.
```

## Ing, ly
Write a method to add 'ing' at the end of a given string (length should be at least 3). If the given string already ends with 'ing' then add 'ly' instead. If the string length of the given string is less than 3, leave it unchanged.
```
Input : 'abc'
Output : 'abcing' 
Input : 'string'
Output: 'stringly'
```
## Obfucate Email
You have some text that contains your email address. And you want to hide that. You decide to censor
your email: to replace all characters in it with asterisks ('*') except the domain.
Assume your email address will always be in format [username]@[domain]. You need to replace the
username with asterisks of equal number of letters and keep the domain unchanged.
You will get as input the email address you need to obfuscate

```
Input: awesome@dotnet.com
Output: *******@dotnet.com
```


## Re-string
Write a method to get a string made of the first 2 and the last 2 chars from a given a string. If the string length is less than 2, return instead of the empty string. 
```
Sample String : “w3resource”
Expected Result :”'w3ce”
Sample String :”w3”
Expected Result : “w3w3”
Sample String : “w”
Expected Result : Empty String 
```
## Replace Char
Write a method to get a string from a given string where all occurrences of its first char have been changed to '$', except the first char itself.
```
Sample String : 'restart'
Expected Result : 'resta$t'
```

- Write a method to get a single string from two given strings, separated by a space and swap the first two characters of each string.
```
Input: 'abc', 'xyz' 
Output: 'xyc abz'
```
- Write a method to find the first appearance of the substring 'not' and 'poor' from a given string, if 'not' follows the 'poor', replace the whole 'not'...'poor' substring with 'good'. Return the resulting string.

```
Input: 'The lyrics is not that poor!'
Output : 'The lyrics is poor!'
Input  : 'The lyrics is good!'
Output : 'The lyrics is poor!'

```
## Longest word
 Write a method that takes a list of words and returns the length of the longest one. 

## Last Part
Write a method to get the last part of a string before a specified character.
```
Input :  https://www.siit.com/net-exercises
         -
Output:  https://www.siit.com/net
```

 - Write a method to check whether a string starts with specified characters
 ```
 input: awesome string
        a
 output : Yes, starts with a
 ```

-  Write a method to count occurrences of a substring in a string
 ```
 input: alabala portocala
        ala
 output : 3
 ```
 
- Write a method to swap comma and dot in a string. 
```
Input: "32.054,23"
Output: "32,054.23"
```
- Write a method to remove spaces from a given string.

## Palindrome
 Check if a string is palindrome (same value read from left to right and right to left)
 Ex: alabala -> True
