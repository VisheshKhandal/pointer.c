// #include<stdio.h>

// int main() {
//      int i = 34;
//     int *j = &i;  // TODO: j wiil now store in the address of i 

//     printf("the value of i is %d\n", i);
//     printf("the address of i is %p\n", j); 

//     return 0;
// }  



// pascle triangele 
// #include<stdio.h>

// int main() {
//     int row, i, j ;
//     printf("enter the number of rows : ");
//         scanf("%d", &row);
//     printf("\n here it is left half pyramid");
//     for (int i = 1; i <= row; i++) {
//         printf("\n");
//         for (int k = 0;k < row-i; k++) {
//             printf(" ");
//         }   

//         for (int j = 0; j < i; j++) {
//             printf("1");
//         }
        
//     }                                                                                   
//     return 0;
// }
// #include <stdio.h>

// int main() {
//     int rows; // Change this value for a different number of rows
//     printf("Enter the number of rows : ");
//     scanf("%d", &rows);
//     for (int i = 1; i <= rows; i++) {
//         // Print leading spaces
//         for (int space = 1; space <= rows - i; space++) {
//             printf(" ");
//         }

//         // Print numbers in increasing order
//         for (int j = 1; j <= i; j++) {
//             printf("%d", j);
//         }

//         printf("\n");
//     }

//     return 0;
// }




// #include<stdio.h>

// int main() {
//     int n;
//     printf("enter the number of row : ");
//     scanf("%d",&n);
//     int row = 1;
//     while (row <= n) {
//         int col = 1;
    
//         while(col <= row) {
//             printf("%d", col);
//             col++;
//         }
//         printf("\n");
//         row++;
//      }
//      return 0;
// }

 
