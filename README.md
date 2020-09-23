<div align="center">

## a pointer example


</div>

### Description

Demonstrates a simple example of a pointer in C.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Dr\. Apache](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dr-apache.md)
**Level**          |Beginner
**User Rating**    |4.4 (31 globes from 7 users)
**Compatibility**  |C
**Category**       |[Data Structures](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/data-structures__3-8.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dr-apache-a-pointer-example__3-4697/archive/master.zip)

### API Declarations

<stdio.h>


### Source Code

```
#include <stdio.h>
int i = 1;
/* declare a pointer to i */
int *p;
int main()
{
p = &i; /* Tell p to point to i */
printf("\nIf you access the integer directly...... i = %d", i);
printf("\nIf you access via the pointer or indirectly...... i = %d", *p);
printf("\nThe address of the integer is %d", &i);
printf("\nAddress the pointer points to is %d\n", p);
return 0;
}
```

