Download Link: https://assignmentchef.com/product/solved-csc281-discrete-math-for-computer-science-rsa-cryptography
<br>
<strong>Public key cryptosystems</strong> known as the <strong>RSA system. </strong>RSA cryptosystem is based on the dramatic difference between the ease of finding large primes and the difficulty of factoring the product of two large prime numbers (the integer factorization problem).

In this project, you have to write an implementation for the RSA cryptosystem in a console mode of Java. Your code should implement the following components:

<h2>• extended-Euclid(int p, int q)</h2>

Finds the greatest common divisor of two integers p and q using the extended Euclid’s algorithm as below:

<ul>

 <li><u>long <strong><em>find_inverse</em></strong>(long a, long m)</u>:!</li>

</ul>

Finds the modular multiplicative inverse of a modulo m based on the following algorithm:










<ul>

 <li><u>int <strong><em>random_prime</em></strong>()</u>:</li>

</ul>

Generates a random prime number.




<ul>

 <li><u>boolean <strong><em>isPrime</em></strong>(int p)</u>:!</li>

</ul>

Check if a number is prime or not.




<ul>

 <li><u>long[] <strong><em>generate_keys</em></strong>()</u>:</li>

</ul>

Generate Keys method.




<ul>

 <li><u>long <strong><em>modular_exponentiation</em></strong>(long b, long n, long m)</u>:!</li>

</ul>

Find (b^n mod m) when we are dealing with big numbers, Same as algorithm 5 in 4.2 in the book

<ul>

 <li></li>

 <li><u>long <strong><em>string_to_int</em></strong>(String text)</u>:!</li>

</ul>

Takes a string and converts each character to int , ex: Input:KBL, Output: 100111.




<ul>

 <li><u>String <strong><em>int_to_String</em></strong>(long inttext)</u>:!</li>

</ul>

Convert from int_to_String , ex: Input: 100111, Output: KBL




<ul>

 <li><u>long[] <strong><em>encrypt</em></strong>(String plaintext, long e, long n)</u>:</li>

</ul>

Encryption method.




<ul>

 <li>String <strong>decrypt</strong>(long[] ciphertext, long d, long n) <em><u>Notes:</u> </em></li>

 <li>Your code will include Class <strong>main</strong> for testing and Class <strong> RSA </strong>class is the important class that contains the previous methods.

  <ul>

   <li>Since we will be dealing with big numbers, use long instead of int.</li>

   <li>Again, since the numbers are big, use modular_exponentiation instead of</li>

  </ul></li>

</ul>

Math.pow.

<ul>

 <li>Do not use Class BigInteger.</li>

 <li>You must implement all previous methods.</li>

 <li>You may add as many auxiliary methods as needed.</li>

 <li>You should <strong>print</strong> the results <strong><u>of each step</u></strong> on RSA.</li>

 <li>You should write <strong>exactly</strong> the same name of each method.</li>

</ul>
















<em> </em>