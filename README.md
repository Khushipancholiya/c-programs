# c-programs- To find a palindrome number
#include<stdio.h>
int main(){
int n,rev=0,rem,temp;
print("enter number:");
scanf("%d",&n);
temp=n;
while(n !=0){
rem=n%10;
rev=rev*10+rem;
n=n/10;
}
if(temp==rev)
printf("palandrome");
else
printf("not palindrome:);
return 0;
}

