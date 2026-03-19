# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start the program.
2. Read the size of the array and its elements.
3. Traverse the array using a loop.
4. If element % 2 == 0, print 'E'; otherwise, print the element.
5. Stop the program.
   

## Program:
```
/*
Program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
Developed by: MAHALAKSHMI A
RegisterNumber:  212222060139

#include <stdio.h>

#include <stdio.h>

int main() {
    int arr[100], n, i;

    printf("Enter the number of elements: ");
    scanf("%d", &n);

    printf("Enter the elements:\n");
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    printf("Modified array:\n");
    for(i = 0; i < n; i++) {
        if(arr[i] % 2 == 0)
            printf("E ");
        else
            printf("%d ", arr[i]);
    }

    printf("\n");
    return 0;
}
*/
```

## Output:
<img width="450" height="261" alt="image" src="https://github.com/user-attachments/assets/e77bdc8b-94c1-4227-ae9b-1502291f8274" />

## Result:
Thus the program was executed and the output was verified successfully.
