# Day20-of-43-of-Teachersdaychallenge

Due to the coronavirus pandemic, city authorities obligated citizens to keep a social distance. The mayor of the city Semyon wants to light up Gluharniki park so that people could see each other even at night to keep the social distance.

The park is a rectangular table with n
 rows and m
 columns, where the cells of the table are squares, and the boundaries between the cells are streets. External borders are also streets. Every street has length 1
. For example, park with n=m=2
 has 12
 streets.

You were assigned to develop a plan for lighting the park. You can put lanterns in the middle of the streets. The lamp lights two squares near it (or only one square if it stands on the border of the park).

The park sizes are: n=4
, m=5
. The lighted squares are marked yellow. Please note that all streets have length 1
. Lanterns are placed in the middle of the streets. In the picture not all the squares are lit.
Semyon wants to spend the least possible amount of money on lighting but also wants people throughout the park to keep a social distance. So he asks you to find the minimum number of lanterns that are required to light all the squares.

Input
The first line contains a single integer t
 (1≤t≤104
) — the number of test cases in the input. Then t
 test cases follow.

Each test case is a line containing two integers n
, m
 (1≤n,m≤104
) — park sizes.

Output
Print t
 answers to the test cases. Each answer must be a single integer — the minimum number of lanterns that are required to light all the squares.

Example
Input
5
1 1
1 3
2 2
3 3
5 3
Output
1
2
2
5
8


A. Young Physicist
time limit per test2 seconds
memory limit per test256 megabytes
A guy named Vasya attends the final grade of a high school. One day Vasya decided to watch a match of his favorite hockey team. And, as the boy loves hockey very much, even more than physics, he forgot to do the homework. Specifically, he forgot to complete his physics tasks. Next day the teacher got very angry at Vasya and decided to teach him a lesson. He gave the lazy student a seemingly easy task: You are given an idle body in space and the forces that affect it. The body can be considered as a material point with coordinates (0; 0; 0). Vasya had only to answer whether it is in equilibrium. "Piece of cake" — thought Vasya, we need only to check if the sum of all vectors is equal to 0. So, Vasya began to solve the problem. But later it turned out that there can be lots and lots of these forces, and Vasya can not cope without your help. Help him. Write a program that determines whether a body is idle or is moving by the given vectors of forces.

Input
The first line contains a positive integer n (1 ≤ n ≤ 100), then follow n lines containing three integers each: the xi coordinate, the yi coordinate and the zi coordinate of the force vector, applied to the body ( - 100 ≤ xi, yi, zi ≤ 100).

Output
Print the word "YES" if the body is in equilibrium, or the word "NO" if it is not.

Examples
InputCopy
3
4 1 7
-2 4 -1
1 -5 -3
Output
NO
Input
3
3 -1 7
-5 2 -4
2 -1 -3
Output
YES
