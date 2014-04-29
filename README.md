projecteuler
============

A set of solution for the first three problems on http://www.projecteuler.net

How to run
==========

````
node solutions.js
````

Problem Selection
=================
I just picked the first three problems on the site since I didn't have a lot of free time this week to work on the solutions. I spent about four hours thinking about the problems and implementing the solutions. The bulk of the time was spent familiarizing myself with the math.

General Methodology
===================

I limited myself to researching only the mathimaitcal formulas that would help me solve each problem. I purposly stayed away from links on popular sites (stackoverflow, etc..) that might have code hints. It felt good to solve the problems using algorithms that I had devised on my own.

 Problem two only took me about 30m to figure out. Problem three took me a little over 90m to solve. I took a few different approaches until I settled on the final algorithm. 

Problem 1
=========

Problem one took me about 90 minutes due to me getting snagged on the fact that I was double counting the common multiples. when I summed the multiples individually. It took me a while ot understand what was going on. I spent some time googling for 
````
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

Resources:
1) http://www.algebra.com/algebra/homework/Sequences-and-series.faq.question.427328.html

Sn = (n/2) * (a1 + an)
Sn = the sum of the n terms in the sequence.
a1 = the first term in the sequence.an = the nth term in the sequence.


Answer: 233168
Compute time: 1ms
````

````
Problem 2
Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, the first 10 terms will be:

1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.


Answer: 4613732
Compute time: 0ms

````

````
Problem 3
The prime factors of 13195 are 5, 7, 13 and 29.

What is the largest prime factor of the number 600851475143 ?


Answer: 6857
Compute time: 1ms
````
