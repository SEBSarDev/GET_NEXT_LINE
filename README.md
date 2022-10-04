# GET_NEXT_LINE
School 42 project which consists in reading a file descriptor line by line. Code in C language.

To run the project, please compile with :
```
$ gcc get_next_line.c get_next_line_utils.c main.c -D BUFFER_SIZE=32
$ ./a.out test.txt
``` 
You can change the size of BUFFER_SIZE.
You can pass your own file in argument.
If none file is provide, the program should read on STDIN.
