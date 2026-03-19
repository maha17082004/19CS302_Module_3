# EX 14 C program to delete first element in an array.
## DATE:
## AIM:
To write a C program to delete first element in an array.

## Algorithm
1. Start the program.
2. Read the size of the array and its elements.
3. Shift all elements one position to the left (arr[i] = arr[i+1]).
4. Reduce the size of the array by 1.
5. Print the updated array and stop the program.
  

## Program:
```
/*
Program to delete first element in an array.
Developed by: MAHALAKSHMI A
RegisterNumber:  212222060139


#include <stdio.h>

int main() {
    int arr[100], n, i;

    printf("Enter the number of elements: ");
    scanf("%d", &n);

    printf("Enter the elements:\n");
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    // Deleting first element by shifting
    for(i = 0; i < n - 1; i++) {
        arr[i] = arr[i + 1];
    }

    n--; // Reduce size after deletion

    printf("Array after deleting the first element:\n");
    for(i = 0; i < n; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");

    return 0;
}
*/
```

## Output:

<img width="476" height="258" alt="image" src="https://github.com/user-attachments/assets/44fc5c31-03f7-4901-ae72-7baab04185b0" />

## Result:
Thus the program was executed and the output was verified successfully.
