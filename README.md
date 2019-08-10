# hackathon
#include<stdio.h>
int main(){
   int x,p,sum;
   scanf("%d %d",&x,&p);
   sum=x;
   while(x!=0){
   m=(p*x)/100;
   x=x-m;
   sum=sum+x;
   
   }
   printf("%d",sum);
   
}
