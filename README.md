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

