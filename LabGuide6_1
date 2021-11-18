#include <stdio.h>
#include<stdlib.h>
#include <time.h>

int main (void)
{
	srand(time(0));
	int number=rand()%100;
	int userGuess;
	
	printf("Make a choice: ");
	scanf("%d",&userGuess);
	
	while(userGuess!=number){
		if(userGuess<number){
			printf("Wrong! Up Please! New guess: ");
			scanf("%d",&userGuess);
		}
			if(userGuess>number){
				printf("Wrong! Down Please! New guess: ");
				scanf("%d",&userGuess);
				}
	}
	if(userGuess==number)
		printf("Yes this is the correct guess! Thank you!");
	
}
