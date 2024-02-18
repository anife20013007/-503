#include<stdio.h>
#include<stdbool.h>
bool is_Prime(int number){
  if(number <= 1){
      return false;
  }
    for(int i=2; i<=number/2; i++){
        if(number%i==0){
            return false;
        }
    }
    return true;
}
int main(){
int number;
printf("Add number:");
scanf("%d", &number);

if(is_Prime(number)){
    printf("prime");
}else{
    printf("not prime");
}
}
