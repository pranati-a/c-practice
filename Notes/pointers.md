##pointers 

-stores value of another variable
-* is used while declaring and pointer variable 
eg: int *p;
-& is used when assigning an address value.
eg: p=&a (if a is already an int variable)

'''
int a;
int *p;
p=&a;     // &a is address of a
a=5;
printf("%d",p);
printf("%d",*p);     //*p - value at address pointed by p
printf("%d",&a);    // address of a is displayed.
*p= 12;    // the value at a is changed
'''

#pointer arithmetic

- p+1 will increment 
eg: p=202, p+1 will be 206 since p is int and int has 4 bytes memory, p+1 shall print to next int address
