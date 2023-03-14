#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main() {
    char filename[] = "phone_numbers.txt";
    char number[20];
    char line[100];
    FILE *fp;

    printf("Enter a phone number: ");
    scanf("%s", number);

    fp = fopen(filename, "r");

    if (fp == NULL) {
        printf("Error opening file.\n");
        exit(1);
    }

    while (fgets(line, 100, fp) != NULL) {
        if (strstr(line, number) != NULL) {
            printf("Location: %s", line);
            break;
        }
    }

    if (feof(fp)) {
        printf("Phone number not found.\n");
    }

    fclose(fp);

    return 0;
}
