# Homework 1
#include <stdio.h>



int main(){

 char letter;
 printf("Enter letter");
 scanf("%c",&letter);
 if(letter >= 'a' && letter <='z'){
  letter = letter - 'a' + 'A';
}

 printf("Uppercase:%c\n",letter);

return 0;

}
