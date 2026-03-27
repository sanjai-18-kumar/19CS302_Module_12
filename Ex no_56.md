# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## AIM:
To write a C function to display stack elements using Linked List.
## Algorithm
1. Start.
2. Define a variables.
3. Write a program to display stack elements using linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End
   

## Program:
```c
Struct Node
{
int data;
struct Node *next;
}*head;
void display()
{
struct Node *temp= head; 
while(temp!=NULL)
{
printf("%d\n",temp->data); 
temp=temp->next;
}
}

```

## Output:

![image](https://github.com/user-attachments/assets/25129bed-eead-4b41-bda5-17c004f6fccc)


## Result:
Thus the program was executed and the output was verified successfully.
