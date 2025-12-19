# Problem: Print odd values each in same line (Java)
## Problem Statement 
Write a java program to print odd values each in same line from an array 
## Input 
Array values:5,4,1,2,6 

## Input Understanding 

👉 Numbers which are odd (% 2 != 0)
Odd values in array:
5, 1
👉 use print() use, not println() 

## Program Java (Print Odd Values in Same Line)

public class Main {
    public static void main(String[] args) {

        int[] arr = {5, 4, 1, 2, 6};

        // Print odd values in the same line
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] % 2 != 0) {
                System.out.print(arr[i] + " ");
            }
        }
    }
}

▶ Output

5 1

## Logic (Simple)

Loop through array

Check arr[i] % 2 != 0

Use System.out.print for same line
