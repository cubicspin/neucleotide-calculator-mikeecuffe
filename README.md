# Year 10 - Introduction to Games Programming and Data Science- Assessment 1
## Assessment Objectives: 
  * To show both understanding and practical use of the following Python concepts and functions: 
  * Floats and strings
  * Variables
  * Use of the “input” function to collect information from a user 
  * Use of f-strings 
  * Use of the simple “if” , "elif", and “else” statement to control the logic flow of a program 
  * Use of loop statements, either "for" or "while".

## Part 1:
Write a program to implement a Nucleotide Calculator for DNA sequences. The calculator has to: 
  1. count the number nucleotide in the sequence of adenosine (A), cytidine (C), guanine (G), and thymidine (T) in the sequence, and 
  1. print out the percentages of the nucleotides in the sequence. 

## Part 2: 
Extend the program you wrote in Part 1 so that the calculator also:
  1. counts the number of each pair of nucleotides, AA, AT, AG, AC, TA, TT, TG, TC, GA, GT, GG, GC, CA, CT, CG, and CC in the sequence, and 
  1. prints out the  percentages of each pair of nucleotides in the sequence. 

## Assumptions:
  * The DNA sequence will be entered in as a sequence of the following characters: A, C, G, T. 
### Examples:
  1. CGTAACAAGGTTTCCGTAGGTGAACCTGCGGAAGGATCATTGA
  1. TGAGACCGTGGAATAAACGATCGAGTGAATCCGGAGGACCGG
  1. TGTACTCAGCTCACCGGGGGCATTGCTCCCGTGGTGACCCTGA
  1. TTTGTTGTTGGGCCGCCTCGGGAGCGTCCATGGCGGGTTTGAA 
  1. CCTCTAGCCCGGCGCAGTTTGGGCGCCAAGCCATATGAAAGCA
  1. TCACCGGCGAATGGCATTGTCTTCCCCAAACCCGGAGCGGCGG
  1. CGTGCTGTCGCGTGCCCAATGAATTTTGATGACTCTCGCAAACG

Consider Example 1 above, then the following are the percentages your program should calculate :
A  (27.91%)   T (23.26%)  G  (30.23%)  C  (18.60%)
AA (9.524%)  AT (4.762%)  AG (7.143%)  AC (4.762%) 
TA (4.762%)  TT (7.143%)  TG (7.143%)  TC (4.762%) 
GA (9.524%)  GT (9.524%)  GG (9.524%)  GC (2.381%) 
CA (4.762%)  CT (2.381%)  CG (7.143%)  CC (4.762%) 

## Considerations
  * Make variable names appropriate and easy to understand
  * Clear message for the user.
  * Clear and well formatted output.
  * Use comments in your code to help other people read and understand what the code is doing 

## Extra Features
Marks will be awarded for extra features. Some examples may include: 
  * Using functionality not yet taught. 
  * Trapping errors which the user may make, such as not entering  a symbol which represents a valid nucleotide. 
  * Constructing a table that shows the number of times each nucleotide follows each type of nucleotide. 

## Organisation
Each calendar day, or part thereof, late will incur a 10% penalty. 
Extensions will be considered for special circumstances but only with advanced notice (not usually the day before it is due!)  Talk to your teacher early.

## Administration
When submitting Python code, your full name is to be on the first line of the python source file. 

Your documents are to submitted in Canvas. 

The file name structure of the submitted file is to be: 
**Surname-Firstname-NucleotideCalculator.py**
