# Time-Table



//time table if pressed 1 monday routine 2 for tues...upto fri
#include <stdio.h>

int main() {
 char i;
 printf("Welcome To Check Your Routine !!\n");
 printf("[a-monday,b-tuesday,c-wednesday,d-thrusday,e-friday]\n");
 printf("\nEnter the alphabet for the day you wanna know bout :\n");
 scanf("%c",&i);

 switch(i)
 {
     case'a':
            printf("9:10-10:10 AM  10:10-12:10 EG lab 12:10-1:10 Min Track \n");
            printf("1:50-2:50 Oopc  2:50-3:50 fbgc 3:50-4:50 Eome "); 
     break;
      case'b':
           printf("9:10-10:10 Lfe  10:10-11:10 Oopc 11:10-12:10 Bee \n");
    printf("12:10-1:10 Am   1:50-2:50 Ec  2:50-4:50 Eome lab "); 
     break;
     case'c':
           printf("9:10-10:10 Am  10:10-11:10 Eome  11:10-12:10 Ec \n");
printf("12:10-1:10 Min Track 1:50-2:50 Bee 2:50-3:50 Bee 3:50-4:50 Fbgc  "); 
     break;
     case'd':
    printf("9:10-10:10 Bee  10:10-11:10 Ec lab  11:10-12:10 Ec lab \n");
  printf("12:10-1:10 Am 1:50-2:50 Pwpe 2:50-3:50 Bee Lab 3:50-4:50 BeeLab");
  break;
    case'e':
      printf("9:10-10:10 Oopc  10:10-11:10 Oopc  11:10-12:10 Ec  \n");
    printf("12:10-1:10 MinorT 1:50-2:50 Oopc 2:50-3:50 dels 3:50-4:50 Eg Lab ");
     }
    return 0;
} 
