# Mario.c
To print steps as in Super Mario world

#include<stdio.h>
#include<cs50.h>
int main(void){
    int num;

    do{
        num = get_int("What is the number of rows:");
    }
    while(num<1||num>8);//To prompt until user enters a no between 1 & 8 (including 8)


 for (int i=0;i<num;i++){   
    for (int k=num;k>i;k--){ //for printing the space before the "#"
        printf(" ");
    }
           printf("#");   // for printing the "#"

        for (int j=0;j<i;j++){  //for looping the printing of "#"


            printf("#");
        }

            printf("\n");  //To print a new line after every row
        }


}
