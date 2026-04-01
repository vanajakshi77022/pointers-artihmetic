# pointers-artihmetic
#include <stdio.h>
int main() {
    int arr[] = {10, 20, 30, 40, 50};
    int *ptr = arr;  
    int i;
    printf("Array elements using pointer arithmetic:\n");
    for(i = 0; i < 5; i++) {
        printf("Element %d: %d\n", i, *(ptr + i)); 
    }
    printf("\nAddresses of array elements:\n");
    for(i = 0; i < 5; i++) {
        printf("Address of arr[%d]: %p\n", i, (ptr + i)); 
    }
    return 0;
}
