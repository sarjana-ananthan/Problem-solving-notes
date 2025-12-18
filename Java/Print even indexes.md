# Problem: Print even indexes (java)

## Problem Statement 
Write a java program to print even indexes from an array 

## Input 
Array values: 5,4,1,2,6 

## Index understanding

Index : 0  1  2  3  4
Value : 5  4  1  2  6

👉 Even indexes = 0, 2, 4

## Program Java (Print Even Indexes)

public class Main {
    public static void main(String[] args) {

        int[] arr = {5, 4, 1, 2, 6};

        // Print elements at even indexes
        for (int i = 0; i < arr.length; i += 2) {
            System.out.println(arr[i]);
        }
    }
}

Output

5
1
6

## Logic (Simple)

Start loop from index 0

Increment by 2

Only even indexes accessed
