#HackerRank Algorithms
##Just some fun exercises provided by HankerRank completed in JavaScript.

### Two Characters - Easy
String 't' always consists of two distinct alternating characters. For example, if string 's' two distinct characters are x and y, then 't' could be 'xyxyx' or 'yxyxy' but not 'xxyy' or 'xyyx'.

You can convert some string 's' to string 't' by deleting characters from 's'. When you delete a character from 's', you must delete all occurrences of it in 's'. For example, if 's' = 'abaacdabd' and you delete the character a, then the string becomes 'bcdbd'.

Given 's', convert it to the longest possible string 't'. Then print the length of string 't' on a new line; if no string 't' can be formed from 's', print 0 instead.

Input Format
The first line contains a single integer denoting the length of .
The second line contains string .

Output Format
Print a single integer denoting the maximum length of 't' for the given 's'; if it is not possible to form string 't', print 0 instead.

Constraints
*1 <= 's' <= 1000
*'s' only contains lowercase English alphabetic letters (i.e., a to z).*


### Mini-Max Sum - Easy
Given five positive integers, find the minimum and maximum values that can be calculated by summing exactly four of the five integers. Then print the respective minimum and maximum values as a single line of two space-separated long integers.

Input Format
A single line of five space-separated integers.

Constraints
*Each integer is in the inclusive range [1, 10^9].*

Output Format
Print two space-separated long integers denoting the respective minimum and maximum values that can be calculated by summing exactly four of the five integers. (The output can be greater than 32 bit integer.)

Sample Input
1 2 3 4 5

Sample Output
10 14

### Designer PDF Viewer
When you select a contiguous block of text in a PDF viewer, the selection is highlighted with a blue rectangle. In a new kind of PDF viewer, the selection of each word is independent of the other words; this means that each rectangular selection area forms independently around each highlighted word. For example: PDF-highighting.png

In this type of PDF viewer, the width of the rectangular selection area is equal to the number of letters in the word times the width of a letter, and the height is the maximum height of any letter in the word.

Consider a word consisting of lowercase English alphabetic letters, where each letter is 1mm wide. Given the height of each letter in millimeters (mm), find the total area that will be highlighted by blue rectangle in when the given word is selected in our new PDF viewer.

Input Format
The first line contains 26 space-separated integers describing the respective heights of each consecutive lowercase English letter.
The second line contains a single word, consisting of lowercase English alphabetic letters.

Constraints
*1 <= h subscript ?, where ? is an English lowercase letter.
*Word contains no more than 10 letters.*


### Apple and Orange
Sam's house has an apple tree and an orange tree that yield an abundance of fruit. In the diagram below, the red region denotes his house, where  is the start point and s is the end point t. The apple tree is to the left of his house, and the orange tree is to its right. You can assume the trees are located on a single point, where the apple tree is at point a and the orange tree is at point b.

Apple and orange(2).png

When a fruit falls from its tree, it lands d units of distance from its tree of origin along the x-axis. A negative value of d means the fruit fell d units to the tree's left, and a positive value of d means it falls d units to the tree's right.

Given the value of d for m apples and n oranges, can you determine how many apples and oranges will fall on Sam's house (i.e., in the inclusive range s, t)? Print the number of apples that fall on Sam's house as your first line of output, then print the number of oranges that fall on Sam's house as your second line of output.

Input Format
The first line contains two space-separated integers denoting the respective values of s and t.
The second line contains two space-separated integers denoting the respective values of a and b.
The third line contains two space-separated integers denoting the respective values of m and n.
The fourth line contains m space-separated integers denoting the respective distances that each apple falls from point a.
The fifth line contains n space-separated integers denoting the respective distances that each orange falls from point b.

Constraints
*1 <= s, t, a, b, m, n <= 10^5
*-10^5 <= 5 <= 10^5
*a < s < t < b*

### Kangaroo
There are two kangaroos on an x-axis ready to jump in the positive direction (i.e, toward positive infinity). The first kangaroo starts at location x(1) and moves at a rate of v(1) meters per jump. The second kangaroo starts at location x(2) and moves at a rate of v(2) meters per jump. Given the starting locations and movement rates for each kangaroo, can you determine if they'll ever land at the same location at the same time?

Input Format
A single line of four space-separated integers denoting the respective values of x(1), v(1), x(2), and v(2).

Constraints
*0 <= x(1) < x(2) <= 10000
*1 <= v(1) <= 10000
*1 <= v(2) <= 10000*

Output Format
Print YES if they can land on the same location at the same time; otherwise, print NO.
Note: The two kangaroos must land at the same location after making the same number of jumps.

### Between Two Sets
Consider two sets of positive integers, A and B. We say that a positive integer,x , is between sets A and B if the following conditions are satisfied:

All elements in A are factors of x.
x is a factor of all elements in B.
Given A and B, find and print the number of integers (i.e., possible 's) that are between the two sets.

Input Format
The first line contains two space-separated integers describing the respective values of  n(the number of elements in set A) and  m (the number of elements in set )B.
The second line contains n distinct space-separated integers describing A.
The third line contains m distinct space-separated integers describing B.

Constraints
*1 <= n, m <= 10,
*1 <= a <= 100,
*1 <= b <= 100*
Sample Input
2 3
2 4
16 32 96
Sample Output
3
Explanation
The integers that are between A = {2, 4} and B = {16, 32, 96} are 4, 8, and 16.

### Divisible Sum Pairs
You are given an array of n integers,a(0)... a(n - 1) , and a positive integer, k. Find and print the number of (i, j) pairs where i < j and a(i) + a(j) is evenly divisible by k.

Input Format
The first line contains 2 space-separated integers, n and k, respectively.
The second line contains n space-separated integers describing the respective values of a(0)... a(n - 1).

Constraints
*2 <= n <= 100
*1 <= k <= 100
*1 <= a(i) <= 100*

Output Format
Print the number of (i, j) pairs where i < j and a(i) + a(j) is evenly divisible by k.

Sample Input
6 3
1 3 2 6 1 2
Sample Output
5

### Richie Richie
A palindrome is a word, phrase, number, or other sequence of characters which reads the same backward as it does forward. For example, madam is a palindrome. Make the n-digit number palindromic by changing no more than k digits. You can only change 1 digit at a time, and cannot add digits to (or remove digits from) the number.

Given k and an n-digit number, determine the largest possible number that can make by changing <= k digits.

Note: Treat the integers as numeric strings. Leading zeros are permitted and can't be ignored (So 0011 is not a palindrome, 0110 is a valid palindrome). A digit can be modified more than once.

Constraints
*0 < n <= 10^5
*0 < k <= 10^5
*Each character i in the number is an integer where 0 <= i <= 9.*
Output Format
Print a single line with the largest number that can be made by changing no more than k digits; if this is not possible, print -1.

Sample Input 0
n = 4
k = 1
number = "3943"
Sample Output
"3993"

Sample Input 1
n = 6
k = 3
number = "092282"
Sample Output
"992299"

Sample Input 2
n = 4
k = 1
number = "0011"
"0011"
Sample Output
-1

Explanation
Sample 0
There are two ways to make 3943 a palindrome by changing exactly k=1 digits:
1. 3443
2. 3993

3993 > 3443, so we print.

### Super Reduced String
Steve has a string, s, consisting of n lowercase English alphabetic letters. In one operation, he can delete any pair of adjacent letters with same value. For example, string "aabcc" would become either "aab" or "bcc" after 1 operation.
Steve wants to reduce s as much as possible. To do this, he will repeat the above operation as many times as it can be performed. Help Steve out by finding and printing s's non-reducible form!
Note: If the final string is empty, print Empty String s.

Input Format
A single string, s.

Constraints
*1 <= n <= 100*
Output Format
If the final string is empty, print Empty String; otherwise, print the final non-reducible string.

Sample Input 0
"aaabccddd"
Sample Output 0
"abd"
Sample Case 0
Steve can perform the following sequence of operations to get the final string:

"aaabccddd" → "abccddd"
"abccddd" → "abddd"
"abddd" → "abd"
Thus, we print "abd".

Sample Input 1
"baab"
Sample Output 1
Empty String

Explanation 1

Steve can perform the following sequence of operations to get the final string:

"baab" → "bb"
"bb" → Empty String
Thus, we print Empty String.

Sample Input 2
"aa"
Sample Output 2
"Empty String"
Explanation 2
Steve can perform the following sequence of operations to get the final string:
"aa" → "Empty String"
Thus, we print Empty String.

### Pangrams
Pangrams are sentences constructed by using every letter of the alphabet at least once. Given a sentence , determine if it is a pangram or not.

Input Format
Input consists of a string s.

Constraints
Length of s can be at most 10^3 (1 <= s <= 10^3) and it may contain spaces, lower case and upper case letters. Lower-case and upper-case instances of a letter are considered the same.

Output Format
Output a line containing pangram if s is a pangram, otherwise output not pangram.

Sample Input
Input 1
"We promptly judged antique ivory buckles for the next prize"    

Input 2
"We promptly judged antique ivory buckles for the prize    
Sample Output"

Output 1
"pangram"
Output 2
"not pangram"

### Caesar Cipher
Julius Caesar protected his confidential information by encrypting it in a cipher. Caesar's cipher rotated every letter in a string by a fixed number, K, making it unreadable by his enemies. Given a string, S, and a number, K, encrypt S and print the resulting string.
Note: The cipher only encrypts letters; symbols, such as -, remain unencrypted.

Input Format
The first line contains an integer, N, which is the length of the unencrypted string.
The second line contains the unencrypted string, S.
The third line contains the integer encryption key, K, which is the number of letters to rotate.

Constraints
*1 <= N <= 100*
*0 <= K <= 100*
S is a valid ASCII string and doesn't contain any spaces.

Output Format
For each test case, print the encoded string.

Sample Input
n = 11
s = "middle-Outz"
k = 2
Sample Output
"okffng-Qwvb"
Explanation
Each unencrypted letter is replaced with the letter occurring K spaces after it when listed alphabetically. Think of the alphabet as being both case-sensitive and circular; if K rotates past the end of the alphabet, it loops back to the beginning (i.e.: the letter after z is a, and the letter after Z is A).

### Mars Exploration
Letters in some of the SOS messages are altered by cosmic radiation during transmission. Given the signal received by Earth as a string, S, determine how many letters of Sami's SOS have been changed by radiation.

Input Format
There is one line of input: a single string, S.
Note: As the original message is just SOS repeated  times, S's length will be a multiple of 3.

Constraints
*1 <= S <= 99*
*S % 3 = 0*
*S will contain only uppercase English letters.*

Output Format
Print the number of letters in Sami's message that were altered by cosmic radiation.

Sample Input 0
"SOSSPSSQSSOR"
Sample Output 0
3
Sample Input 1
"SOSSOT"
Sample Output 1
1

### Funny String
Suppose you have a String, S, of length N that is indexed from 0 to N - 1. You also have some String, R, that is the reverse of String S. S is funny if the condition Math.abs(s[i] - s[i - 1]) = Math.abs(r[i] - r[i - 1]) is true for every character i from N to 1.
Note: For some String S, S[i] denotes the ASCII value of the  ith 0-indexed character in S. The absolute value of an integer, s, is written as |x|.

Input Format
The first line contains an integer, T (the number of test cases).
Each line i of the T subsequent lines contain a string, S.

Constraints
*1 <= T <= 10*
*0 <= i <= T - 1*
*2 <= length of S <=10000*
Output Format
For each String S(j) (where 0 <= j <= T - 1), print whether it is "Funny" or "Not Funny" on a new line.

Sample Input
2
"acxz"
"bcxz"
Sample Output
"Funny"
"Not Funny"

### Gemstones
John has discovered various rocks. Each rock is composed of various elements, and each element is represented by a lower-case Latin letter from 'a' to 'z'. An element can be present multiple times in a rock. An element is called a gem-element if it occurs at least once in each of the rocks.
Given the list of N rocks with their compositions, display the number of gem-elements that exist in those rocks.

Input Format
The first line consists of an integer, N, the number of rocks.
Each of the next N lines contains a rock's composition. Each composition consists of lower-case letters of English alphabet.

Constraints
*1 <= N <= 100*
*Each composition consists of only lower-case Latin letters ('a'-'z').*
*1 <= length of each composition <= 100.*

Output Format
Print the number of gem-elements that are common in these rocks. If there are none, print 0.
Sample Input

3
"abcdde"
"baccd"
"eeabg"
Sample Output
2
Explanation
Only "a" and "b" are the two kinds of gem-elements, since these are the only characters that occur in every rock's composition.

### Alternating Characters
Shashank likes strings in which consecutive characters are different. For example, he likes ABABA, while he doesn't like ABAA. Given a string containing characters A and B only, he wants to change it into a string he likes. To do this, he is allowed to delete the characters in the string.
Your task is to find the minimum number of required deletions.

Input Format
The first line contains an integer T, i.e. the number of test cases.
The next T lines contain a string each.

Output Format
For each test case, print the minimum number of deletions required.

Constraints
*1 <= T <= 10*
*1 <= length of string <= 10^5*

Sample Input
5
AAAA
BBBBB
ABABABAB
BABABA
AAABBB
Sample Output
3
4
0
0
4
Explanation
AAAA => A, 3 deletions
BBBBB => B, 4 deletions
ABABABAB => ABABABAB, 0 deletions
BABABA => BABABA, 0 deletions
AAABBB => AB, 4 deletions because to convert it to AB we need to delete 2 A's and 2 B's

### Beautiful Binary String
Alice has a binary string, B, of length n. She thinks a binary string is beautiful if and only if it doesn't contain the substring "010". In one step, Alice can change a 0 to a 1 (or vice-versa). Count and print the minimum number of steps needed to make Alice see the string as beautiful.

Input Format
The first line contains an integer, n (the length of binary string B).
The second line contains a single binary string, B, of length n.

Constraints
*1 <= n <= 100*

Output Format
Print the minimum number of steps needed to make the string beautiful.

Sample Input 0
7
"0101010"
Sample Output 0
2
Sample Input 1
5
"01100"
Sample Output 1
0
Sample Input 2
10
"0100101010"
Sample Output 2
3
Explanation
Sample Case 0:
In this sample, B = "0101010"
Sample Case 1:
In this sample, B = "01100"
The substring "010" does not occur in B, so the string is already beautiful and we print 0.

### The Love-Letter Mystery
James found a love letter his friend Harry has written for his girlfriend. James is a prankster, so he decides to meddle with the letter. He changes all the words in the letter into palindromes.
To do this, he follows two rules:
1. He can reduce the value of a letter, e.g. he can change d to c, but he cannot change c to d.
2. In order to form a palindrome, if he has to repeatedly reduce the value of a letter, he can do it until the letter becomes a. Once a letter has been changed to a, it can no longer be changed.
Each reduction in the value of any letter is counted as a single operation. Find the minimum number of operations required to convert a given string into a palindrome.

Input Format
The first line contains an integer , i.e., the number of test cases.
The next T lines will contain a string each. The strings do not contain any spaces.

Constraints
*1 <= T <=10*
*1 <= length of string <= 10^4*
All characters are lower case English letters.

Output Format
A single line containing the number of minimum operations corresponding to each test case.

Sample Input
4
"abc"
"abcba"
"abcd"
"cba"

Sample Output
2
0
4
2
Explanation
1. For the first test case, abc -> abb -> aba.
2. For the second test case, abcba is already a palindromic string.
3. For the third test case, abcd -> abcc -> abcb -> abca = abca -> abba.
4. For the fourth test case, cba -> bba -> aba.

### Palindrome index
Given a string, S, of lowercase letters, determine the index of the character whose removal will make S a palindrome. If S is already a palindrome or no such character exists, then print -1. There will always be a valid solution, and any correct answer is acceptable. For example, if S= "bcbc", we can either remove 'b' at index 0 or 'c' at index 3.

Input Format
The first line contains an integer,T , denoting the number of test cases.
Each line i of the T subsequent lines (where 0 <= i <= T) describes a test case in the form of a single string, S(i).

Constraints
*1 <= T <= 20*
*1 <= |S| <= 10^5 + 5*
*All characters are lowercase English letters.*
Output Format
Print an integer denoting the zero-indexed position of the character that makes S not a palindrome; if S is already a palindrome or no such character exists, print -1.

Sample Input
3
"aaab"
"baa"
"aaa"

Sample Output
3
0
-1

### Anagram
Sid is obsessed with reading short stories. Being a CS student, he is doing some interesting frequency analysis with the books. He chooses strings S1 and S2 in such a way that len(S1) - len(S2) <= 1. Your task is to help him find the minimum number of characters of the first string he needs to change to enable him to make it an anagram of the second string. Note: A word x is an anagram of another word y if we can produce y by rearranging the letters of x.

Input Format
The first line will contain an integer, T, representing the number of test cases. Each test case will contain a string having length len(S1) + len(S2), which will be concatenation of both the strings described above in the problem.The given string will contain only characters from a to z.

Constraints
*1 <= T <= 100*
*1 <= len(S1) + len(S2) <= 10^4*

Output Format
An integer corresponding to each test case is printed in a different line, i.e. the number of changes required for each test case. Print -1 if it is not possible.

Sample Input
6
aaabbb
ab
abc
mnop
xyyx
xaxbbbxx
Sample Output
3
1
-1
2
0
1

### Making Anagrams
Alice is taking a cryptography class and finding anagrams to be very useful. We consider two strings to be anagrams of each other if the first string's letters can be rearranged to form the second string. In other words, both strings must contain the same exact letters in the same exact frequency For example, bacdc and dcbac are anagrams, but bacdc and dcbad are not. Alice decides on an encryption scheme involving two large strings where encryption is dependent on the minimum number of character deletions required to make the two strings anagrams. Can you help her find this number? Given two strings, a and b, that may or may not be of the same length, determine the minimum number of character deletions required to make a and b anagrams. Any characters can be deleted from either of the strings.

Input Format
The first line contains a single string, a.
The second line contains a single string, b.

Constraints
*1 <= |a|, |b| <= 10^4*
*It is guaranteed that a and b consist of lowercase English letters.*

Output Format
Print a single integer denoting the number of characters which must be deleted to make the two strings anagrams of each other.

Sample Input
cde
abc

Sample Output
4

### Game of Thrones
Dothraki are planning an attack to usurp King Robert's throne. King Robert learns of this conspiracy from Raven and plans to lock the single door through which the enemy can enter his kingdom. But, to lock the door he needs a key that is an anagram of a certain palindrome string. The king has a string composed of lowercase English letters. Help him figure out whether any anagram of the string can be a palindrome or not.

Input Format
A single line which contains the input string.

Constraints
*1 <= length of string <= 10^5*
*Each character of the string is a lowercase English letter.*

Output Format
A single line which contains YES or NO in uppercase.

Sample Input : 01
aaabbbb
Sample Output : 01
YES
Explanation
A palindrome permutation of the given string is bbaaabb.

Sample Input : 02
cdefghmnopqrstuvw
Sample Output : 02
NO
Explanation
You can verify that the given string has no palindrome permutation.

Sample Input : 03
cdcdcdcdeeeef
Sample Output : 03
YES
Explanation
A palindrome permutation of the given string is ddcceefeeccdd.

### Two Strings
Given two strings, a and b, determine if they share a common substring.

Input Format
The first line contains a single integer, p, denoting the number of (a,b) pairs you must check.
Each pair is defined over two lines:
1. The first line contains string a.
2. The second line contains string b.

Constraints
*a and b consist of lowercase English letters only.*
*1 <= p <= 10*
*1 <= |a|,|b| <= 10^5*
Output Format
For each (a,b) pair of strings, print YES on a new line if the two strings share a common substring; if no such common substring exists, print NO on a new line.

Sample Input
2
hello
world
hi
world

Sample Output
YES
NO

### Insertion Sort - Part 1
Sorting
One common task for computers is to sort data. For example, people might want to see all their files on a computer sorted by size. Since sorting is a simple problem with many different possible solutions, it is often used to introduce the study of algorithms.

Insertion Sort
These challenges will cover Insertion Sort, a simple and intuitive sorting algorithm. We will first start with an already sorted list.

Insert element into sorted list
Given a sorted list with an unsorted number e in the rightmost cell, can you write some simple code to insert e into the array so that it remains sorted?

Print the array every time a value is shifted in the array until the array is fully sorted. The goal of this challenge is to follow the correct order of insertion sort.

Guideline: You can copy the value of e to a variable and consider its cell "empty". Since this leaves an extra cell empty on the right, you can shift everything over until V can be inserted. This will create a duplicate of each value, but when you reach the right spot, you can replace it with e.

Input Format
There will be two lines of input:
 - size; the size of the array
 - arr; the unsorted array of integers
Output Format
On each line, output the entire array every time an item is shifted in it.

### Insertion Sort - Part 2
In Insertion Sort Part 1, you sorted one element into an array. Using the same approach repeatedly, can you sort an entire unsorted array? Guideline: You already can place an element into a sorted array. How can you use that code to build up a sorted array, one element at a time? Note that in the first step, when you consider an array with just the first element - that is already "sorted" since there's nothing to its left that is smaller. In this challenge, don't print every time you move an element. Instead, print the array after each iteration of the insertion-sort, i.e., whenever the next element is placed at its correct position. Since the array composed of just the first element is already "sorted", begin printing from the second element and on.

Input Format
There will be two lines of input:
s - the size of the array
arr- a list of numbers that makes up the array

Output Format
On each line, output the entire array at every iteration.

Constraints
*1 <= s <= 1000*
*-10000 <= x <= 10000, x E arr*

Sample Input
6
"1 4 3 5 6 2"
Sample Output
"1 4 3 5 6 2"
"1 3 4 5 6 2"
"1 3 4 5 6 2"
"1 3 4 5 6 2"
"1 2 3 4 5 6"
