Download Link: https://assignmentchef.com/product/solved-cse111-lab-3
<br>
<strong>Problem 1: Write a java program that will ask user to input a string (containing exactly one word). Then your job is to sort alphabetically all the letters in it. For simplicity, you can consider all letters will be either capital or small.</strong>

<strong>Example: </strong>Suppose, user inputs “BANGLADESH”. Then you will sort all the letters in it alphabetically.

So output will be “AABDEGHLNS”.

<strong>Input:</strong>

BANGLA

<strong>Output:</strong>

AABGLN

<strong>Input:</strong>

BOOK

<strong>Output:</strong>

BKOO

<strong>Problem 2: Given a line as keyboard input in small letters, print the next alphabet in sequence for each alphabet found in the input.</strong>

<strong>Input: </strong>abcd <strong>Output: </strong>bcde

<strong>Input: </strong>the cow <strong>Output: </strong>uif dpx

<strong>Problem 3: Given a line as keyboard input in small letters, do the opposite of <u>Problem</u> <u>2 </u>Input: </strong>bcde <strong>Output: </strong>abcd

<strong>Input: </strong>uif dpx <strong>Output: </strong>the cow

<strong>Medium:</strong>

<strong>Problem 1: Write a java program that will ask user to input a string (containing exactly one word). Then your job is to print subsequent substring of given string.</strong>

<strong>Input:</strong>

BANGLA

<strong>Output:</strong>

B

BA

BAN

BANG

BANGL

BANGLA

<strong>Input:</strong>

DREAM

<strong>Output:</strong> D

DR

DRE

DREA

DREAM

<strong>Problem 2: Write a program that will ask the user to input a word where each of it’s alphabets is unique and has not been entered before by the user. If the user does input a word which consists of duplicate alphabets, the program should reject the user’s input and ask for another word.</strong>

<strong>Input:</strong>

Radeon

<strong>Output:</strong>

You entered Radeon.

<strong>Input: </strong>Hello

<strong>Output:</strong>

‘l’ has been counted 2 times in the word “hello”.. Please enter another word.

<strong>Problem 3: </strong>Write a program which takes <strong>TWO string inputs</strong> <strong>(containing exactly one word in each string)</strong> from the user. <strong>Concatenate those two strings</strong> with a single space in between them. <strong>Generate a number</strong> which is the <strong>sum of all the letters in that concatenated string</strong> (you have to avoid the value of that space), Where A = 65, Z = 90, a = 97 and z = 122. <strong>Your task is to print that concatenated string and the number generated from that string. </strong>(You are not allowed to use “+” operator to concatenate.)

<strong>Sample Input:</strong> Hello

World

<strong>Sample Output:</strong>

Hello World

1020

<strong>Sample Input:</strong>

Java

CHOWDHURY

<strong>Sample Output:</strong>

Java CHOWDHURY

1087

<strong>Problem 4 (Remove duplicates)</strong>

Given a string, create a new string with all the <u>consecutive</u> duplicates removed. For example,

ABBCCCCCBBAB becomes ABCBAB.

<strong>Sample Input:</strong>

AAABBBBCDDBBECE

<strong>Sample Output:</strong> ABCDBECE

<strong>Hard:</strong>

<strong>Problem 1: 3-Divisibility</strong>

Write a program that prints whether a given number is divisible by 3. The number can be huge (may contain up-to 1000 digits).

(<strong>Hint</strong>: A number is divisible by 3 if the<strong> sum of its digits</strong> is divisible by 3.)

<strong>Input:</strong>

141414141414141414 <strong>Output:</strong>

141414141414141414 is divisible by 3.

<strong>Input:</strong>

2368049403457746389253849640734644954763 <strong>Output:</strong>

2368049403457746389253849640734644954763 is divisible by 3.

<strong>Input:</strong>

557629788989463427894562342368049403457746389253849640734644954763 <strong>Output:</strong>

557629788989463427894562342368049403457746389253849640734644954763 is divisible by 3.

<strong>Input:</strong>

453429584564664689844654558446458764996446944666478998466554879658945646278945623423680 49

40345774638 <strong>Output:</strong>

453429584564664689844654558446458764996446944666478998466554879658945646278945623423680 49 40345774638 is not divisible by 3.

<strong>Problem 2:</strong> Write a program which takes <strong>TWO string inputs (containing exactly one word in each string)</strong> from the user. First input will be the <strong>name of a programming team</strong> and Second input will be the <strong>name of a Coach</strong> of that team. Both the name of the team and the name of the coach are <strong>converted into a number</strong> in the following manner: the final number is just the product of all the letters in the name, where <strong>“A” is 1</strong> and <strong>“Z” is 26</strong>. For instance: the team name “EAGLE” would be 5*1*7*12*5 = 2100 and the coach name “JAMES” would be 10*1*13*5*19 = 12350.

If <strong>the team’s number mod 14 is less than the coach’s number mod 14</strong>, then your program should print “<strong>I Am Happy With My Coach</strong>”. Otherwise, your program should print “<strong>I Am Sad With My Coach</strong>”. (Remember that “a mod b” is the remainder left over after dividing a by b; 34 mod 10 is 4.)

The name of the team and the coach will be a <strong>string of capital letters</strong> with <strong>no spaces or punctuation, 1 to 6 characters long</strong>.

<strong>Sample Input:</strong>

EAGLE

JAMES

<strong>Sample Output:</strong>

I Am Happy With My Coach

<strong>Sample Input:</strong>

PRIME JOHN

<strong>Sample Output:</strong>

I Am Sad With My Coach

<strong>Problem 3: (Word Reverse)</strong>

Suppose you have a String and a CAPITAL letter in that indicates ending of a word. For example, if you have <strong>wElovEbangladesH</strong> where E, E and H indicates end of the words wE, lovE and bangladesH respectively. You need to reverse each word (as you know where it ends). Don’t reverse the String as a whole. To illustrate, if we give <strong>wElovEbangladesH </strong>as input output should be <strong>EwEvolHsedalgnab. </strong> See wE became Ew, lovE became Evol and so on. (Input will contain only alphabetic characters)

<strong>Sample Input: </strong>merrYeatSpieS

<strong>Sample Output: </strong>YrremStaeSeip

<strong>Sample Input: </strong>programminGiSfuN

<strong>Sample Output:</strong>

GnimmargorpSiNuf

<strong>Problem 4: (Mystery words)</strong>

Write a program that takes a number and a String and then each letter in the String is replaced by a letter number of positions down the alphabet. For example, with number=3, A would be replaced by D, B would become E, and so on. (finally Z becomes C). Input will contain upper-case letters only.

<strong>Sample Input: </strong>

1

HELLOWORLD

<strong>Sample Output: </strong>IFMMPXPSME

<strong>Sample Input:</strong>

3

HELLOWORLD

<strong>Sample Output:</strong>

KHOORZRUOG

<strong>Sample Input:</strong>

4

HAPPYPEOPLE

<strong>Sample Output:</strong>

LETTCTISTPI