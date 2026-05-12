# just-palindrome
 #include &lt;stdio.h> int main() { int n, temp, rev = 0, digit; printf("Enter a number: "); scanf("%d", &amp;n); temp = n; while (n > 0) { digit = n % 10; rev = rev * 10 + digit; n = n / 10; } if (rev == temp) { printf("It is a palindrome\n"); } else { printf("It is not a palindrome\n"); } return 0;  }
