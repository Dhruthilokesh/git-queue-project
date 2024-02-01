
void delete(){
    int y;
    if(front==-1 || front>rear){
        printf("queue underflow\n");
    }
    else{
        y=queue[front];
        if(front==rear){
            front=rear==-1;
        }
        else{
            front=front+1;
        }
    printf("element deleted is:%d\n",y);
    }
}
