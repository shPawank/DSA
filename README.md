# DSA\
#include<stdio.h>
#include<conio.h>
#include<alloc.h>
typedef struct nodetype
{
int coeff,power;
struct nodetype *next;
} node;
addnode(ptr3,coef,powe);
void addpolynomial(node *ptr1, node *ptr2, node *ptr3)
{
float coef;
int powe;
while((ptr1!=NULL)&&(ptr2!=NULL))
{
if(ptr1->power<ptr2->power)
{
coef=ptr1->coeff;
powe=ptr1->power;
ptr1=ptr1->next;
}
else
   {
   coef=ptr1->coeff+ptr2->coeff;
   powe=ptr1->power;
   ptr1=ptr1->next;
   ptr2=ptr2->next;
   }
if(coef!=0)
 addnode(ptr3,coef,powe);
 }
 if(ptr1==NULL)
 {
 for(;ptr2!=NULL;ptr2=ptr2->next)
 addnode(ptr3,ptr2->coeff,ptr2->power);
 else if(ptr2==NULL)
 {
 for(;ptr1!=NULL;ptr1=ptr1->next)
 addnode(ptr3,ptr1->coeff,ptr->power)
 }
 }
 void main()
 {
 node *poly;
 *next=NULL;
 void addpolynomial(node *,node*,node**)
 getch();
 }


































