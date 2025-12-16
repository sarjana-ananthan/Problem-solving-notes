# Problem: Print in Reverse order (Java)
## Problem Statement 
Write a java program to print in reverse oder from an array
## Input 
Array values: 5,4,1,2,6
## Program Java Code (Reverse Order)

public class Main {
    public static void main(String[] args) {

        int[] arr = {5, 4, 1, 2, 6};

        // Print array in reverse order
        for (int i = arr.length - 1; i >= 0; i--) {
            System.out.println(arr[i]);
        }
    }
}
Output
6
2
1
4
5
## Logic (Simple)

arr.length - 1 → last index

Loop decrement (i--)

Print till index 0
