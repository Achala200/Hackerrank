# Hackerrank
Python If-else correct solution
Task
Given an integer,N , perform the following conditional actions:

If N is odd, print Weird
If N is even and in the inclusive range of 2 to 5, print Not Weird
If  is even and in the inclusive range of  6 to 20 , print Weird
If N is even and greater than 20 print Not Weird
import sys



if __name__ == '__main__':
    N = int(input().strip())
if (N%2!=0):
    print ("Weird")
else:
    if (N >= 2) and (N <= 5):
       print ("Not Weird");
    elif (N >= 6) and (N <= 20):
        print ("Weird");
    elif (N > 20):
        print ("Not Weird");
