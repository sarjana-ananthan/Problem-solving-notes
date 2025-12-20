# Problem: Print Even Values (Java)
## Problem Statement 
Write a program to print even values from an array
## Input 
Array values:5,4,1,2,6 
## 👉 Numbers which are even (% 2 == 0)
Even values in array:
4
2
6

## Program Java(Print Even Values – Next Line)

public class Main {
    public static void main(String[] args) {

        int[] arr = {5, 4, 1, 2, 6};

        // Print even values, each in next line
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] % 2 == 0) {
                System.out.println(arr[i]);
            }
        }
    }
}

▶ Output

4
2
6

## Logic (Easy)
Traverse array using loop
Check even using % 2 == 0
println() prints each value in new line
