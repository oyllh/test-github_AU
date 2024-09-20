#include <stdio.h>

int main() {
    char crush_name[20]; // assume crush's name is less than 20 characters
    char proposal_message[100]; // assume proposal message is less than 100 characters

    printf("Enter your crush's name: ");
    scanf("%s", crush_name);

    printf("Enter your proposal message: ");
    scanf("%s", proposal_message);

    printf("\n\n");

    // The big question
    printf("Dear %s,\n", crush_name);
    printf("%s\n", proposal_message);
    printf("Will you be my Valentine?\n");

    // Wait for response (just kidding, this is a program, not real life!)
    printf("Response: (just imagine a 'yes' or 'no' here)\n");

    return 0;
}
