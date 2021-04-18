#include<stdio.h>
#include<stdlib.h>

struct node
{
	int data;
	struct node*next;
}*first;

void create(){
	int a[100];
	int i,n;
	struct node *t,*last;
	printf("enter limit for link list=");
	scanf("%d",&n);
	printf("enter element ");	
	for(i=0;i<n;i++)
	{
		scanf("%d",&a[i]);
	
	}
	
	first=(struct node*)malloc(sizeof(struct node));
	first->data=a[0];
	first->next=NULL;
	first=last;
	for(i=1;i<n;i++)
	{
		t=(struct node*)malloc(sizeof(struct node));
		t->data=a[i];
		t->next=NULL;
		t=last;
	}

}
 void display()
 {
 	struct node*p=first;
 	while(p!=NULL)
 	{
 		print(" %d",p->data);
 			p=p->next;
	 }
 }
int main()
{
	printf("------linke list -----\n");
	printf("1. create \t 2. insert \t 3. delete\n");
	int in;
		printf("enter choice=");
		scanf("%d",&in);
		switch(in)
		{
			case 1:
				create();
				break;
			case 2:
				dispaly();	
				break;
			default:
				printf("wrong input");	
		}
		return 0;
}
