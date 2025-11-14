Q134: Define an enum with SUCCESS, FAILURE, and TIMEOUT, and print messages accordingly.

/*
Sample Test Cases:
Input 1:
FAILURE
Output 1:
Operation failed

*/

#include <stdio.h>
#include <string.h>

int main() {
    enum Status {SUCCESS, FAILURE, TIMEOUT};
    enum Status s;
    char input[10];

    printf("Enter status (SUCCESS, FAILURE, TIMEOUT): ");
    scanf("%s", input);

    if (strcmp(input, "SUCCESS") == 0)
        s = SUCCESS;
    else if (strcmp(input, "FAILURE") == 0)
        s = FAILURE;
    else if (strcmp(input, "TIMEOUT") == 0)
        s = TIMEOUT;
    else {
        printf("Invalid input");
        return 1;
    }

    switch(s) {
        case SUCCESS: printf("Operation successful"); break;
        case FAILURE: printf("Operation failed"); break;
        case TIMEOUT: printf("Operation timed out"); break;
    }

    return 0;
}
