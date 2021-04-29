# switch-case-food1
#include<stdio.h>
main()
{
  printf("pick an item:\n1.pizza\n2.burger\n3.pasta\n4.french fries\n5.sandwich");
  int choice=0;
  scanf("%d",&choice);
  switch(choice)
  {
    case 1:
    printf("food item-pizza"\n"price-rs 239");
    break;
    case 2:
    printf("food item-burger"\n"price-rs 129");
    break;
    case 3:
    printf("food item-pasta"\n"price-rs 179");
    break;
    case 4:
    printf("food item-french fries"\n"price-rs 99");
    break;
    case 5:
    printf("food item-sandwich"\n"price-rs 149");
    break;
    default: printf("invalid choice")
   }
 }
