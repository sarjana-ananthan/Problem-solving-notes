# Problem: Print odd indexes (java)

## Problem Statement: 
write a java program to print odd indexes from an array 
## Input 
Array values:5,4,1,2,6 
## Index understanding

Index : 0  1  2  3  4
Value : 5  4  1  2  6

👉 Odd indexes = 1, 3

So values printed:

4
2

## Program Java (Print Odd Indexes)

public class Main {
    public static void main(String[] args) {

        int[] arr = {5, 4, 1, 2, 6};

        // Print elements at odd indexes
        for (int i = 1; i < arr.length; i += 2) {
            System.out.println(arr[i]);
        }
    }
}

Output

4
2 

## Logic (Easy)

Start loop from index 1

Increment by 2 (i += 2)

Only odd indexes accessed
