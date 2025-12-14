# Problem: Print Array Values (java)
## Problem Statement
Write the Java program to print the values from an array
## Input
array values = 5,4,1,2,6
## Program ( java code)
public class Main {  
    public static void main(String[] args) {  

        int[] arr = {5, 4, 1, 2, 6};  // given input  

        System.out.println("Array values:");

        for(int i = 0; i < arr.length; i++) {   // loop to print values
            System.out.println(arr[i]);
        }
    }  
}
Output
