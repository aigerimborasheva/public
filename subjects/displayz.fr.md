## displayz

### Instructions

Écrire un programme qui prend une `string`, et qui affiche le premier caractère `z` qu'il trouve dedans, suivi par un retour à la ligne (`'\n'`). Si il n'y a pas de caractère `z` dans la `string`, le programme affiche juste un `z` suivi d'un retour à la ligne (`'\n'`). Si le nombre de paramètres n'est pas 1, le programme affiche un `z` suivi d'un retour à la ligne (`'\n'`).

### Utilisation

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test "xyz"
z
student@ubuntu:~/[[ROOT]]/test$ ./test "bcvbvZ"
z
student@ubuntu:~/[[ROOT]]/test$ ./test "nbv"
z
student@ubuntu:~/[[ROOT]]/test$ ./test
```
