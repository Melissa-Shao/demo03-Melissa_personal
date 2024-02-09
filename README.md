# demo03-Melissa_personal
title: week03_lecture_demo
author: Melissa

## *** STEP 2 ***
Step Over doesn't go into the function. Step Into goes into the function.

## *** STEP 4 ***
What is happening to the stack of function calls?   
Every time calls the function fibonacci(nth_term), it will make two more calls to itself fibonacci(nth_term - 1) and fibonacci(nth_term - 2). This recursive continues until nth_term is 0 or 1.   

Why is it taking so long to shrink and return to the main?   
Each function call creates two more function, making the calculation time grow quickly.   

Why is it growing and shrinking?   
Before the nth_term reaches 1 or 0, each function call creates two additional calls, causing growth. After nth_term reaches 1 or 0, it returns a value to the upper stack, leading to shrinking.   