# ft_printf

## about

This project consists in duplicate the behavior of the C function printf(). It is not necessary to implement the buffer management of the original function. It must handle the following parameters:

char type variables.
string type variables.
int type variables.
unsigned int type variables.
hexadecimal int type variables (uppercase and lowercase).
pointer type variables.
You will find more details in the [subject of the project]("https://github.com/Droied4/printf/blob/master/es.subject.pdf").

## Instructions

### 1. Compiling the archives

To compile the proiect, go to its path and run:

For __mandatory__ functions:
```
$ make
```
### 2. Cleaning all binary (.o) and executable files (.a)

To delete all files generated with make, go to the path and run:
```
$ make fclean
```

### 3. Using it in your code

To use this project in your code, simply include this header:
```
#include "ft_printf.h"
```
