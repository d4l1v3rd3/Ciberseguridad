# Shell TOTALMENTE INTERACTIVA

Con python 
```
which python
```
```
python3 -c 'import pty; pty.spawn("/bin/bash")'
```
Para poder usar ‘clear’ podemos añadir:
```	
export TERM=screen-256color
```
Para conseguir que nuestra shell no se cierre con CTRL-C y podamos hacer cosas como usar la teclas flecha, debemos:
```
[Ctrl Z]
echo $TERM
stty raw -echo
fg
[INTRO]
export TERM=screen
```
Al escribir el comando ‘stty raw -echo’ nuestra terminal se vera rara, solo tenemos que escribir ‘fg’ y darle a INTRO para volver a la shell

https://ironhackers.es/tutoriales/como-conseguir-tty-totalmente-interactiva/
