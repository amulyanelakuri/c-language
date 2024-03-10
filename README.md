# c-language
#Data types are int, char, float, etc. all these pointers point to different data types
#include <stdio.h>
#include <string.h>

int main() {
    char source[] = "Hello, World!";
    char destination[20];

    strcpy(destination, source);

    printf("Source: %s\n", source);
    printf("Destination: %s\n", destination);

    return 0;
}
# char
#include <stdio.h>
#include <string.h>

int main() {
    char str[] = "Hello, World!";
    size_t length = strlen(str);

    printf("Length of the string: %zu\n", length);

    return 0;
}

