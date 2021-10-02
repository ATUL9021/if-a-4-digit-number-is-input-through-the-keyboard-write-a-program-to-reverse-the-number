# if-a-4-digit-number-is-input-through-the-keyboard-write-a-program-to-reverse-the-number
#include &lt;stdio.h> int main() {    int digit;   printf("Enter a number\n");   scanf("%d", &amp;digit);    int mod = 0, div;    div = digit;    printf("Reversed number is ");    while (div != 0)   {     mod = div % 10;      div = div / 10;      printf("%d",mod);   } }
