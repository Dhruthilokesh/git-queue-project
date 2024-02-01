
void display(){
    if(front==-1){
        printf("queue underflow\n");
    }
    else{
        for(int i=front;i<=rear;i++){
            printf("%d",queue[i]);
        }
    }
    printf("\n");
}
