#include <stdio.h>
#include<stdlib.h>
#define qs 30
int queue[qs], front = -1, rear = -1;
void main(){
    int ele, choice;
    printf("1. enqueue \n 2. dequeue \n 3. peek \n 4. display \n ");
    while(1){
        printf("enter the choice");
        scanf("%d", &choice);
        switch(choice){
            case 1:
            printf("Enter the element to be inserted");
            scanf("%d", &ele);
            enqueue(ele);
            break;
            case 2:
            dequeue();
            break;
            case 3:
            peek();
            break;
            case 4:
            display();
            break;
            case 5:
            exit(1);
            break;

        }
    }
}
