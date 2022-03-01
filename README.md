# Get_next_line
### The aim of the mandatory part: 
To code a function that returns a line, read from a file descriptor.
### Run:
```
%> gcc -Wall -Wextra -Werror -D BUFFER_SIZE=42 <files>.c
```
>A buffer size of 42 is used as an example.
### The aim of the bonus part:
To code a function get_next_line that be able to manage multiple file descriptors. For
example, if the file descriptors 3, 4 and 5 are accessible for reading, then you can
call get_next_line once on 3, once on 4, once again on 3 then once on 5 etc.
without losing the reading thread on each of the descriptors.
