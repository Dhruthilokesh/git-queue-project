
void insert(int ele){
    if(rear==ss-1){
        printf("queue overflow\n");
    }
    else{
        if(front=rear==-1){
            front=0;
            rear=0;
        }
        else{
            rear=rear+1;
        }
        queue[rear]=ele;
        printf("element inserted is:%d\n",queue[rear]);
    }
}
void peek()
{
if(isEmpty())
printf("Peek operation cannot be performed\n");
else
{
printf("Peek element is %d\n",queue[front]);
}
}