Q1 Ramesh’s basic salary is input through the keyboard. His dearness allowance is 40% of basic salary, and house rent allowance is 20% of basic salary. Write a program to calculate his gross salary.

#include <stdio.h>

int main()
{
    float basic_sallary, d_allowance, house_rent,gross_sallary;
  
  printf("enter ramesh's basic sallary");
  scanf("%f" ,&basic_sallary);
    
    d_allowance=0.4*basic_sallary;
    house_rent=0.2*basic_sallary;
    gross_sallary=d_allowance+house_rent+basic_sallary;
    
    
    
    printf("da%.2f " ,d_allowance);
    
    printf("house rent%f.2f" ,house_rent);
    
    printf("gross salary%.2f " ,gross_sallary);
    

    return 0;
}
