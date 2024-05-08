<!--
 Copyright 2024 prans
 
 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at
 
     https://www.apache.org/licenses/LICENSE-2.0
 
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->
Purpose:
This Python script offers functions to compute Fibonacci numbers and factorials efficiently, accompanied by mechanisms to measure their execution times.

External Library:

time:
The standard Python module time facilitates time-related operations.
Specifically, the time.time() function is utilized to capture the system time for measuring execution durations accurately.
Functions:

Fibonacci Calculation (fibonacci(n)):

This function computes the nth Fibonacci number using recursion.
Fibonacci numbers follow the sequence where each number is the sum of the two preceding ones.
Base cases are set for 0 and 1, returning the value itself.
For other values of n, the function recursively calls itself with adjusted indices to obtain the Fibonacci number.

Factorial Calculation (factorial(n)):

This function determines the factorial of a non-negative integer n.
Factorial is the product of all positive integers up to the given number.
Base case is established for n equals 0, returning 1.
For n greater than 0, the function recursively calls itself with decremented values to compute the factorial.


Main Function (main()):
Purpose:
main() functions as the starting point of the program, orchestrating computations and displaying results.


Timing Computations:
Fibonacci Calculation Timing:
Commences by recording the start time (start_time_fib).
Invokes the fibonacci() function with a chosen input value.
Captures the end time (end_time_fib) post function execution.
Calculates the duration by subtracting start time from end time and prints the Fibonacci result alongside execution time.


Factorial Calculation Timing:
Similar to Fibonacci, begins by noting the start time (start_time_fact).
Calls the factorial() function with a specified input value.
Records the end time (end_time_fact) after computation.
Determines the duration and displays the factorial result along with execution time.


Usage:
Adjust input values for Fibonacci and factorial calculations as needed within the main() function.
Run the script to observe the results, including the calculated Fibonacci numbers and factorials, along with their respective execution times.


Conclusion:
This Python script encapsulates efficient algorithms for calculating Fibonacci numbers and factorials, demonstrating their implementation through recursive functions. Additionally, the integration of time measurement provides insights into the computational efficiency of these operations
 