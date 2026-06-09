# Pointers: Reverse a String Using Pointers in C

## 🎯 Aim

To write a C program that prints a string in reverse using a pointer.

## 🧠 Algorithm

1. **Input**: Read a string from the user.
2. **Reverse String**:
   - Use a pointer to traverse the string to find its length.
   - Then, move the pointer to the last character of the string.
   - Print characters in reverse by decrementing the pointer.
3. **Output**: Display the reversed string.

## Program
```
#include <stdio.h>
int main() {
    char str[100];
    char *ptr;
    printf("Enter a string: ");
    scanf("%s", str);
    ptr = str;
    while(*ptr != '\0') {
        ptr++;
    }
    ptr--;
    printf("Reversed string: ");
    while(ptr >= str) {
        printf("%c", *ptr);
        ptr--;
    }

    return 0;
}
```

## Output
<img width="917" height="238" alt="Screenshot 2026-06-09 140336" src="https://github.com/user-attachments/assets/f712ce35-6046-40ab-be9f-32673836ff2b" />


## Result
C program to prints a string in reverse using a pointer is written.
