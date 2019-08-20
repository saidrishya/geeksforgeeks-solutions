/*
Design a data-structure SpecialStack (using the STL of stack) that supports all the stack operations like push(), pop(), isEmpty(), 
isFull() and an additional operation getMin() which should return minimum element from the SpecialStack. Your task is to complete all the 
functions, using stack data-Structure.

Input Format:
The first line of input contains an integer T denoting the no of test cases. Then T test cases follow. Each test case contains two lines.
The first line of input contains an integer n denoting the number of integers in a sequence. In the second line are n space separated
integers of the stack.

Output Format:
For each testcase, in a new line, print the minimum integer from the stack. 

Your Task:
Since this is a function problem, you don't need to take inputs. Just complete the provided functions.

Constraints:
1 <= T <= 100
1 <= N <= 100

Example:
Input:
1
5
18 19 29 15 16
Output:
15
*/


void push(int a)
{
   s.push(a);
}
bool isFull(int n)
{
 if(s.size()==n) return true;
 else return false;
}
bool isEmpty()
{
    return s.empty();
}
int pop()
{
    if(!s.empty()){
   int x=s.top();
   s.pop();
   return x;
    }
else return -1;
}
int getMin()
{
   int min=s.top();
   s.pop();
   while(!s.empty()){
       if(min>s.top()){
           min=s.top();
       }
       s.pop();
   }
 return min;
}
