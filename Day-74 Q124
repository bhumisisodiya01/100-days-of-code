Q124: Take two filenames from the user – a source file and a destination file. Copy all the content from the source file to the destination file using fgetc() and fputc().

/*
Sample Test Cases:
Input 1:
Source File: source.txt (Content: Learning C File Handling)
Output 1:
File copied successfully to destination.txt

*/

#include <stdio.h>

int main() {
    char sourceFile[50], destFile[50];
    FILE *src, *dest;
    char ch;

    printf("Enter source file name: ");
    scanf("%s", sourceFile);

    printf("Enter destination file name: ");
    scanf("%s", destFile);

    src = fopen(sourceFile, "r");
    if (src == NULL) {
        printf("Error opening source file");
        return 1;
    }

    dest = fopen(destFile, "w");
    if (dest == NULL) {
        printf("Error creating destination file");
        fclose(src);
        return 1;
    }

    while ((ch = fgetc(src)) != EOF) {
        fputc(ch, dest);
    }

    fclose(src);
    fclose(dest);

    printf("File copied successfully to %s", destFile);
    return 0;
}
