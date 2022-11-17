# Point-of-sale-system
#include<stdio.h>
#include<stdio.h>
int main()
{
int item,qty,cashgiven;
float change,prodprice,tax,totalprice,purchaseprice;
printf("enter quantities=");
scanf("%d",qty);
printf("enter items=");
scanf("%d",items);
printf("enter price of items=");
scanf("%f",prodprice);
purchaseprice=qty*prodprice;
tax=purchaseprice*0.16;
totalprice=purchaseprice-tax;
printf("purchase price is %2f\n",purchaseprice);
printf(tax is %2f\n",tax);
totalprice("totalprice is %2f\n",totalprice);
printf("enter cash=");
scanf("%d",cashgiven);
change=cashgiven-totalprice;
printf("change to be given=%2f\n",change);
return 0;
}
