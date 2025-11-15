Q137: Create an enum for user roles (ADMIN, USER, GUEST) and display messages based on role.

/*
Sample Test Cases:
Input 1:
GUEST
Output 1:
Welcome Guest!

*/

#include <stdio.h>
#include <string.h>

int main() {
    enum Role {ADMIN, USER, GUEST};
    enum Role r;
    char input[10];

    printf("Enter role (ADMIN, USER, GUEST): ");
    scanf("%s", input);

    if (strcmp(input, "ADMIN") == 0)
        r = ADMIN;
    else if (strcmp(input, "USER") == 0)
        r = USER;
    else if (strcmp(input, "GUEST") == 0)
        r = GUEST;
    else {
        printf("Invalid role");
        return 1;
    }

    switch(r) {
        case ADMIN: printf("Welcome Admin!"); break;
        case USER: printf("Welcome User!"); break;
        case GUEST: printf("Welcome Guest!"); break;
    }

    return 0;
}
