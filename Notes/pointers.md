## Pointers

- A pointer stores the address of another variable.
- `*` is used when declaring a pointer variable. Example: `int *p;`
- `&` gives the address of a variable. Example: `p = &a;` (if a is already an int variable)

```c
int a;
int *p;
p = &a;              // &a is the address of a
a = 5;
printf("%p", p);     // address stored in p
printf("%d", *p);    // *p is the value at the address p points to: 5
printf("%p", &a);    // address of a
*p = 12;             // the value of a is changed to 12
```

## Pointer arithmetic

- p + 1 moves to the next int, not the next byte.
- Example: if p = 202, then p + 1 = 206, because an int takes 4 bytes.