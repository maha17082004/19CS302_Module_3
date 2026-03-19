# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1. Start the program.
2. Read number of rows and columns.
3. Input elements into the 2D array.
4. Traverse the array and check each element (if element % 2 ≠ 0).
5. Print odd elements and stop the program.

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: MAHALAKSHMI A
RegisterNumber:212222060139
#include <stdio.h>

int main() {
    int rows, cols;

    // Input size of array
    printf("Enter number of rows and columns: ");
    scanf("%d %d", &rows, &cols);

    int arr[rows][cols];

    // Input elements
    printf("Enter elements of the array:\n");
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            scanf("%d", &arr[i][j]);
        }
    }

    // Print odd elements
    printf("Odd elements in the array are:\n");
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            if(arr[i][j] % 2 != 0) {
                printf("%d ", arr[i][j]);
            }
        }
    }

    return 0;
}
*/
```

## Output:
```
Enter number of rows and columns: 2 3
Enter elements of the array:
1 2 3
4 5 6
Odd elements in the array are:
1 3 5
```

## Result:
Thus the program was executed and the output was verified successfully.
