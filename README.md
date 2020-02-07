# Hacker-Rank-
Problems solved on Hacker-rank 
# Question 1:- Hello World
## Objective: 
This is a simple challenge to help you practice printing to stdout. You may also want to complete Solve Me First in C++ before attempting this challenge.
We're starting out by printing the most famous computing phrase of all time! In the editor below, use either printf or cout to print the string **Hello World**  to stdout.
## Input format:
You do not need to read any input in this challenge.
## Output Format: 
Print **Hello World** to stdout.
```
#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    printf("Hello, World!");
    return 0;
}
```
# Question 2:- Input and Output
## Objective: 
In this challenge, we're practicing reading input from stdin and printing output to stdout.
In C++, you can read a single whitespace-separated token of input using cin, and print output to stdout using cout. For example, let's say we declare the following variables: 
string s;
int n;
and we want to use cin to read the input "High 5" from stdin. We can do this with the following code:
cin >> s >> n;
The above code reads the first word ("High") from stdin and saves it as string **s** , then reads the second word ("**5**") from stdin and saves it as integer . If we want to print these values to stdout, we write the following code:
cout << s << " " << n << endl;
The above code prints the contents of string , which is the word "High". Then it prints a single space (), followed by the contents of integer . Because we also want to ensure that nothing else is printed on this line, we end our line of output with a newline via endl. This results in the following output:
