# Huffman-Coding-Algorithm
Huffman coding is a lossless data compression algorithm. The idea is to assign variable-length codes to input characters, lengths of the assigned codes are based on the frequencies of corresponding characters. The most frequent character gets the smallest code and the least frequent character gets the largest code.


Example: 

Original string :
abacdcbad 

Size of Original string : 9 bytes which is also equal to 72 bits.

Huffman Codes are :

a-> 11 ,
b-> 10 ,
d-> 00 ,
c-> 01 .

Encoded string is :
111011010001101100

Size of Encoded string : 18 bits. So we are able to compress our string from 72 bits to 18 bits.

Decoded string is : 
abacdcbad

Size of Decoded string : 72 bits. 

Time complexity: O(nlogn) where n is the number of unique characters.


