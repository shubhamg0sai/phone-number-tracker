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



