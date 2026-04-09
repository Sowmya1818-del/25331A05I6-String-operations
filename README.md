#include <stdio.h>
#include <string.h>
int main() {
char str1[100], str2[100];
char copyStr[100];
printf("Enter first string: ");
scanf("%s", str1);
printf("Enter second string: ");
scanf("%s", str2);
 printf("\nLength of first string: %lu", strlen(str1));
 printf("\nLength of second string: %lu", strlen(str2));
strcpy(copyStr, str1);
 printf("\nCopied string: %s", copyStr);
strcat(str1, str2);
 printf("\nConcatenated string: %s", str1);
if(strcmp(copyStr, str2) == 0)
  printf("\nStrings are equal");
else
   printf("\nStrings are not equal");
   printf("\n25331A05I6");
return 0;
}
