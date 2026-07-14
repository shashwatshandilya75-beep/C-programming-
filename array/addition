#include <stdio.h>

int main() {
    int A[3][3], B[3][3], sum[3][3];

    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            
            if (i == j) {
                A[i][j] = i + 1;
            } else if (i + j == 2) {
                if (i == 0) A[i][j] = 6;
                if (i == 2) A[i][j] = 4;
            } else {
                A[i][j] = 0;
            }

            if (i == 1) {
                B[i][j] = j + 4;
            } else {
                B[i][j] = 0;
            }
        }
    } 
    printf("ARRAY OF A :\n");
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            printf("%d ",A[i][j]);
        }
        printf("\n");
    }
    printf("ARRAY OF B :\n");
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            printf("%d ",B[i][j]);
        }
        printf("\n");
    }
    

    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            sum[i][j] = A[i][j] + B[i][j];
        }
    }

    printf("Result of Addition:\n");
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            printf("%d\t", sum[i][j]);
        }
        printf("\n");
    }

    return 0;
}
