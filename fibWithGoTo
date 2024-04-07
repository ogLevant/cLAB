#include <stdio.h>

int rangeCheck(int n){
    int maxTerm = 46;
    
    if (n > maxTerm) {
        printf("Error! Out of Range!");
        goto labelA;
    }
    printf("Range Check GOOD!\n");
    return 0;
    
    labelA:
    return 1;
}

int fibo(int n) {
    int i, sum;
    int term = n;
    
    int fibo[2] = {0,1};
    
    printf("%d\n",fibo[0]);
    printf("%d\n",fibo[1]);
    
    for (i = 2; i < n; i++) {
        sum = fibo[0] + fibo[1];
        printf("%d\n", sum);
        fibo[0] = fibo[1];
        fibo[1] = sum;
    }
    
}

int main() {                 //main method
    printf("Enter number of terms to calculate: ");
    int term;
    scanf("%d",&term);
    int test = rangeCheck(term);
    
    if (test) {
        printf("\nFunction Exiting\n");
        goto endmain;
    }
    
    fibo(term);
    goto endall;
        
    endmain:
        printf("That entry did not work properly.\n");
        
    endall:
        printf("Program did as expected.\n");
}
