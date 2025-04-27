# Advanced-C-Lab-Manual 
EXP NO:6A C PROGRAM TO DISPLAY STACK ELEMENTS USING 
LINKED LIST. 
Aim: 
To write a C program to display stack elements using linked list. 
Algorithm: 
1.
 2.
 3.
 4.
 5.
 6.
 7.
 Define a structure Node with two members: data to store the integer value and 
next to point to the next node in the linked list. 
Declare a global variable head representing the starting node of the linked list. 
Define a function display to print the elements of the linked list. 
Declare a pointer p and initialize it with the head of the linked list. 
Use a while loop to traverse the linked list: 
Print the data of the current node. 
Move to the next node using the next pointer.

Program: 
struct Node 
{ 
int data; 
struct Node *next; 
}*head; 
void display() 
{ 
struct Node *p; 
p=head; 
while(p!=NULL
 ) 
{ 
} 
} 
printf("%d\n",p->data); 
p=p->next; 
Output:

![image](https://github.com/user-attachments/assets/eb08f69f-4bda-4a29-98e4-b4efc5dda277)

Result: 
Thus, the program to display stack elements using linked list is verified successfully


EXP.NO:6B C PROGRAM TO POP AN ELEMENT FROM THE GIVEN 
STACK USING  
LINKED LIST. 
Aim: 
To write a C program to pop an element from the given stack using liked list. 
Algorithm: 
1.
 2.
 3.
 4.
 Check for Empty Stack 
If head is equal to NULL, Print "Stack is empty." 
Else Proceed to the next step. 
Set head to point to the next node in the stack.

Program: 
struct Node 
{ 
int data; 
struct Node *next; 
}*head; 
void pop() 
{ 
} 
if(head==NULL) 
{ 
printf("stack is empty"); 
} 
else 
{ 
head=head->next; 
} 
Output:


![image](https://github.com/user-attachments/assets/91e483b7-aa1a-4ea1-889c-e6caf54f0e16)

Result: 
Thus, the program to pop an element from the given stack using liked list is verified 
successfully.

EXP NO:6C  C PROGRAM TO DISPLAY QUEUE ELEMENTS USING 
LINKED LIST. 
Aim: 
To write a C program to display queue elements using linked list. 
Algorithm: 
 Check if Queue is Empty 
Display Queue Elements 
Print the data of the current node pointed to by front 
Update front to point to the next node. 
End the display function.

Program: 
struct Node 
{ 
char data; 
struct Node *next; 
}*front=NULL,*rear=NUL
 L; void display() 
{ 
} 
if(front==NULL) 
{ 
printf("queue is empty"); 
} 
else 
{ 
printf("queue elements:\n"); 
while(front!=NULL) 
{ 
printf("%c\n",front->data); 
front=front->next; 
} 
} 
Output:

![image](https://github.com/user-attachments/assets/81aeeab3-fd25-49b8-8e87-f845bd574853)

Result: 
Thus, the program to display queue elements using linked list is verified successfully.

EXP NO:6D C PROGRAM TO INSERT ELEMENTS IN QUEUE USING 
LINKED LIST 
Aim: 
To write a C program to insert elements in queue using linked list 
Algorithm: 
1.
 2.
 3.
 4.
 5.
 6.
 Allocate Memory for New Node 
Set Data and Next Pointer 
Check if Queue is Empty 
Set both front and rear to point to the new node p. 
Set the next pointer of the current rear to point to the new node p. 
End of Enqueue Operation

Program: 
struct Node 
{ 
int data; 
struct Node *next; 
}*front=NULL,*rear=NUL
 L; void enqueue(int data) 
{ 
struct Node *p=(struct Node*)malloc(sizeof(struct Node)); 
p->data=data; 
p->next=NULL; 
if(front==NULL) 
{ 
front=rear=p; 
} 
else 
{ 
rear->next=p; 
rear=p; 
} 
} 
Output:

![image](https://github.com/user-attachments/assets/4430846a-7e80-4805-8694-2e7f16b28c1c)

Result: 
Thus, the program to insert elements in queue using linked list is verified successfully.
EXP NO:6E C FUNCTION TO FIND THE PEEK OF QUEUE USING LINKED 
LIST. 
Aim: 
The aim of this function is to retrieve the "peek" (the front element) of a queue 
implemented using a linked list 
Algorithm: 
1. Check if the queue is empty: 
o If the queue is empty (i.e., the front pointer is NULL), return an error or a 
message indicating that the queue is empty. 
2. Access the front element: 
o If the queue is not empty, return the data stored in the front node of the linked 
list (i.e., the element at the head of the queue).

Program: 
struct Node 
{ 
char data; 
struct Node *next; 
}*front=NULL,*rear=NULL; 
void peek() 
{ 
printf("%c",front->data); 
} 
Output:

![image](https://github.com/user-attachments/assets/7b48651d-e4a3-471d-91bf-ddc17e3ee927)


Result: 
Thus, the program to retrieve the "peek" (the front element) of a queue implemented 
using a linked list is verified successfully.

























