# phone-number-tracker 

# Instagram account
👉[![Instagram  ](https://img.shields.io/badge/INSTAGRAM-FOLLOW-red?style=for-the-badge&logo=instagram)](https://www.instagram.com/shubhamg0sai)👈

# YouTube video
[![video](https://img.shields.io/badge/YOUTUBE-VIDEO-red?style=for-the-badge&logo=instagram)](https://youtu.be/xeZz0oDPB7M)
# screenshot
![ ](https://raw.githubusercontent.com/shubhamg0sai/phone-number-tracker/Delete/screenshot/Screenshot_20220207_201629.jpg)
# Installation
apt update -y

 apt upgrade -y

 apt install git -y

 apt install python -y

 apt install python2 -y

 pip2 install requests

 pip2 install mechanize

git clone https://github.com/shubhamg0sai/phone-number-tracker

cd phone-number-tracker
 
# ussage 
python run.py


#include<stdio.h>
#include<math.h>
int main()
{
    float abserror, relerror, percerror, trueval, approxval;
    printf("enter true value\n");
    scanf("%f",&trueval);
    printf("enter approx value\n");
    scanf("%f",&approxval);
    abserror=fabs(trueval-approxval);
    relerror=abserror/trueval;
    percerror=relerror*100;
    printf("absolute error = %f\n",abserror);
    printf("relative error = %f\n",relerror);
    printf("percentage error = %f\n",percerror);

    return 0;
}


#include <stdio.h>
int main() {

  int i, n;

  // initialize first and second terms
  int t1 = 0, t2 = 1;

  // initialize the next term (3rd term)
  int nextTerm = t1 + t2;

  // get no. of terms from user
  printf("Enter the number of terms: ");
  scanf("%d", &n);

  // print the first two terms t1 and t2
  printf("Fibonacci Series: %d, %d, ", t1, t2);

  // print 3rd to nth terms
  for (i = 3; i <= n; ++i) {
    printf("%d, ", nextTerm);
    t1 = t2;
    t2 = nextTerm;
    nextTerm = t1 + t2;
  }

  return 0;
}


#include <math.h>
#include <stdio.h>
int main() {
    double a, b, c, discriminant, root1, root2, realPart, imagPart;
    printf("Enter coefficients a, b and c: ");
    scanf("%lf %lf %lf", &a, &b, &c);

    discriminant = b * b - 4 * a * c;

    // condition for real and different roots
    if (discriminant > 0) {
        root1 = (-b + sqrt(discriminant)) / (2 * a);
        root2 = (-b - sqrt(discriminant)) / (2 * a);
        printf("root1 = %.2lf and root2 = %.2lf", root1, root2);
    }

    // condition for real and equal roots
    else if (discriminant == 0) {
        root1 = root2 = -b / (2 * a);
        printf("root1 = root2 = %.2lf;", root1);
    }

    // if roots are not real
    else {
        realPart = -b / (2 * a);
        imagPart = sqrt(-discriminant) / (2 * a);
        printf("root1 = %.2lf+%.2lfi and root2 = %.2f-%.2fi", realPart, imagPart, realPart, imagPart);
    }

    return 0;
} 



#include <stdio.h>
int main() {
int power(int n1, int n2);
int base, a, result;

printf("Enter base number: ");
scanf("%d", &base);
printf("Enter power number(positive integer): ");
scanf("%d", &a);
result = power(base, a);
printf("%d^%d = %d", base, a, result);
return 0;
}

int power(int base, int a) {
    if (a != 0)
        return (base * power(base, a - 1));
    else
        return 1;
}




#include<stdio.h>
long int m(int n);
int main() {
    int n;
    printf("Enter a positive integer:\n");
    scanf("%d",&n);
    printf("Factorial of %d = %ld", n, m(n));
    return 0;
}

long int m(int n) {
    if (n>=1)
        return n*m(n-1);
    else
        return 1;
}





