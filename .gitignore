#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main()
{
    int num, guess,no_of_guesses=1;
    srand(time(0));
    num=rand()%100+1;
    //Generate random numbers between
    //1 to 100
    printf("Hello Pretties!");
   // printf("The guessing number is %d",num);
    
    //keep running the loop
    //until the number is guessed
    do{
    printf("Enter a Guessing Number Between[1-100] :\n");
    scanf("%d",&guess); 
    if(guess>num) 
        printf("Lower number please\n"); 
    else if(guess<num)
        printf("Higher number please");
    else
        printf("You guessed it in %d attempts\n",no_of_guesses);
    no_of_guesses++;
    }while(guess!=num);
    
    return 0;
}
