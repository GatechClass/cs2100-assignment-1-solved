# cs2100-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS2100 Assignment 1 Solved](https://mantutor.com/product/cs2100-computer-organization-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112870&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2100  Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
&nbsp;

Instructions

5. Complete your answers on the provided CS2100Assg1AnsBk.docx file. Save it as AxxxxxxY.pdf before submitting.

7. You should do these assignments on your own. Do not discuss the assignment questions with others.

8. Please use the Canvas Discussion Forums for clarifications.

In Tutorial 2 Question 5 we looked at calculating the parity for a 32-bit word.

In this question we will write a program that computes parity across a block of bytes to create a parity byte. To understand what we mean by this, let’s consider a block of four bytes: 0x1A, 0x30, 0x4B and 0x1C. We stack them up like this (for neatness the “0b” prefix for binary numbers is omitted):

0x1A: 0001 1010

0x20: 0010 0000

0x4B: 0100 1011

0x1C: 0001 1100

Let’s assume that we are using the ODD parity scheme. In the odd parity scheme, if there are even number of 1’s in the data bits, the parity bit generated is 1; if there are odd number of 1’s in the data bits, the parity bit generated is 0. In other words, the number of 1’s in the data bits and parity bit must be odd.

We now compute an odd parity byte where each bit at position k in the parity byte is a parity bit generated for the corresponding position-k bits of each byte in the block. Let’s illustrate using the block of 4 bytes above, starting from left (MSB) to right (LSB):

The leftmost column has 0 bits that are ‘1’. Hence, the parity for that column is ‘1’:

0 0 0 1 1 0 1 0

0 0 1 0 0 0 0 0

0 1 0 0 1 0 1 1

0 0 0 1 1 1 0 0

1

There is 1 bit in the next column that is ‘1’. Since there is an odd number of ‘1’ bits, the partiy for this column is 0.

0 0 0 1 1 0 1 0

0 0 1 0 0 0 0 0

0 1 0 0 1 0 1 1

0 0 0 1 1 1 0 0

1 0

Continuing in this manner, the parity bits for the 8 columns are computed as follows:

0 0 0 1 1 0 1 0

0 0 1 0 0 0 0 0

0 1 0 0 1 0 1 1

0 0 0 1 1 1 0 0

1 0 0 1 0 0 1 0

Thus, the parity byte is 0b1001 0010 or 0x92.

a. Calculate the odd parity byte for the block below (you are advised to do this manually so that you can check the output of your program later. Write your answer in hexadecimal. (1 mark)

0x3C 0x4A 0x34 0x98 0x5B 0x4E 0x7F 0x4B

You are given five files:

i. test.c – Test harness for your code.

ii. test.txt – Test file containing strings of bytes and their parities. iii. q1.c – A program just to ask for a string of bytes and print out the parity. iv. parity.h – Contains prototypes for the functions in parity.c.

v. parity.c – You need to implement your odd parity byte calculation codes here.

What we want to do is to take hexadecimal values as a string in this form: “3A 2B 10 4A” and compute the odd parity byte for this string of bytes. We will leave this parity as an 8-bit unsigned integer between 0 and 255.

To do this you need to implement the following functions in parity.c (do not change any other file!):

Function Description

uint8_t findParity(uint8_t *array, uint8_t len) Calculates the odd parity byte for an array of bytes “array” of length “len”.

uint8_t hex2dec(char *byte) Converts the 2-hexadecimal-digit in “byte” to a decimal. E.g. if byte contains “2F”, this function should return 47 (216+15).

Complete this function in a single line to gain credit.

uint8_t calculateParity(char *str) Calculates the odd parity byte for a string of 2hexadecimal-digit values in “str” and returns it in decimal. For example, if str contains “1A 20 4B 1C” your function should return 146.

Note: Do not include the 0x in the hex bytes! Also do not omit the leading zero, e.g. “4 A B” should be represented as “04 0A 0B”.

void string2bytes(char *str, uint8_t *bytes, uint8_t *len) Converts a string of hexadecimal values in parameter “str” into bytes in the array “bytes”. The parameter len returns the number of bytes converted.

For example, if str=”03 0B 1C”, then bytes will contain the values 3, 11 and 28 (hex 1C = 116 + 121 = 28), and “len” will contain the value 3 since 3 bytes were converted.

Note: The difference between calculateParity and findParity is that while findParity takes in an array of unsigned 8-bit integers, calculateParity takes in a string. The two functions are related but not the same.

To play around with your parity code, ensure that parity.h, parity.c and q1.c are in the same directory, then compile and run using:

gcc parity.c q1.c -o q1

./q1

This program will read in a string of bytes and print out the parity in decimal and hexadecimal.

To test your implementation, ensure that parity.h, parity.c, test.c and test.txt are in the same directory, then compile and run using:

gcc parity.c test.c -o test

./test

i. 1527+3417 =𝑋7. 𝑋 in base 7 is ______________. ii. 3125+𝑌5 =4415. 𝑌 in base 5 is ______________.

iii. 411𝑍−232𝑍 =168𝑍. The mystery base 𝑍 is ______.

i. What is the smallest positive number that can be represented? Note that 0 is not a positive number.

ii. What is the largest positive number that can be represented? iii. What is the most negative number that can be represented? iv. What is the absolute error in representing the number 17.143? Calculate up to a maximum of 8 fraction bits; do not calculate to 9 fraction bits to decide rounding.

Though some variation from the MIPS code is unavoidable, your C code should follow the MIPS code as closely as possible.

a. Variable to register assignments: $s1 mapped to integer variable ctr, $s2 mapped to integer variable x. (1 mark)

addi $t0, $zero, 5 andi $s2, $s2, 0

a: slt $t1, $t0, $s2 bne $t1, $zero, b srl $s1, $s1, 1 addi $s2, $s2, 1 j a b: …

b. Variable to register assignments: $s1 mapped to integer variable ctr, $s2 mapped to integer variable x. (1 mark)

addi $t0, $zero, 5 addi $s2, $t0, 10

a: srl $s1, $s1, 1 addi $s2, $s2, -1 slt $t1, $s2, $t0 beq $t1, $zero, a b: …

sll $t0, $s4, 2 add $s5, $s2, $t0 sll $t0, $s1, 2 add $t1, $s3, $t0 add $t0, $s2, $t0

a: slt $t2, $t0, $s5 beq $t2, $zero, c lw $t2, 0($t0) lw $t3, 0($t1) slt $t4, $t2, $t3 bne $t4, $zero, b sw $t2, 0($t1) sw $t3, 0($t0) b: addi $t0, $t0, 4 addi $t1, $t1, 4

j a c: …

We are given the following code in MIPS assembly. Register $s0 contains the base address for an array A of 32-bit integers. The LSB of every byte is 1 and hence every ulw results in loading an odd integer. Answer the questions that follow:

add $t0, $s0, $zero addi $t1, $s0, 16 addi $s1, $zero, 0 a: slt $t2, $t0, $t1 beq $t2, $zero, c ulw $t2, 0($t0) andi $t3, $t2, 1 beq $t3, $zero, b addi $s1, $s1, 1 b: addi $t0, $t0, 2 j a c: … # THIS LINE

=== END OF PAPER ===
