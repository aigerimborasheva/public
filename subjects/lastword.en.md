## lastword

### Instructions

Write a program that takes a `string` and displays its last word, followed by a newline (`'\n'`).

-   A word is a section of `string` delimited by spaces or by the start/end of the `string`.

-   The output will be followed by a newline (`'\n'`).

-   If the number of parameters is different from 1, or if there are no word, the program displays a newline (`'\n'`).

### Usage

```console
student@ubuntu:~/[[ROOT]]/lastword$ go build
student@ubuntu:~/[[ROOT]]/lastword$ ./lastword "FOR PONY" | cat -e
PONY$
student@ubuntu:~/[[ROOT]]/lastword$ ./lastword "this        ...       is sparta, then again, maybe    not" | cat -e
not$
student@ubuntu:~/[[ROOT]]/lastword$ ./lastword "  " | cat -e
$
student@ubuntu:~/[[ROOT]]/lastword$ ./lastword "a" "b" | cat -e
$
student@ubuntu:~/[[ROOT]]/lastword$ ./lastword "  lorem,ipsum  " | cat -e
lorem,ipsum$
student@ubuntu:~/[[ROOT]]/lastword$
```
