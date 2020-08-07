#include<stdio.h>
int main(){
    double Kilometers;
    double Miles;
    int i;
    
    
  printf("Do you want to convert from (1)Kilometers to miles or (2)Miles to kilometers, please enter the repective number:\n");
  scanf("%d",&i);
   
   if (i==1){
    puts("Kindly enter the distance in Kilometers:");
    scanf("%lf",&Kilometers);
    
   Miles=  (0.621371*Kilometers);
   
    
    printf("%lfKm is equal to: %.6lf miles",Kilometers,Miles);
   }
   
   else if (i==2){
       puts("Kindly enter the distance in Miles:");
    scanf("%lf",&Miles);
    
   Kilometers= (Miles*1.60934);
   
    
    printf("%lfMiles is equal to: %.6lf Km",Miles,Kilometers);
   }
   else{
       printf("Incorrect Input");
   }
    
    
    return 0;
}
