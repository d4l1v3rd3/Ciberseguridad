# Hacking-Petesting
Información, código, herramientas, comandos, guías sobre el hacking &amp; pentesting.

Este repositorio ha sido creado, para la investigación y aprendizaje para toda la comunidad del hacking & Pentesting.

Cualquier persona tiene el derecho de aprender y debatir sobre estos temas.

# [NoSQL](https://github.com/D4l1-web/Hacking-Petesting/blob/main/README.md#nosql-1)
# [TTY INTERACTIVA](https://github.com/D4l1-web/Hacking-Petesting/blob/main/README.md#tty-totalmente-interactiva)
# [PANDORA](https://github.com/D4l1-web/Hacking-Petesting/blob/main/README.md#pandora-vulnerabilidad)

## NoSQL

Repositorio sobre bypass de autentificación en NoSQL

https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/NoSQL%20Injection#authentication-bypass

# TTY TOTALMENTE INTERACTIVA

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

# PANDORA VULNERABILIDAD

Pandora FMS 742: Critical Code Vulnerabilities Explained

https://www.sonarsource.com/blog/pandora-fms-742-critical-code-vulnerabilities-explained/

# LinPEAS - Linux Privilege Escalation Awesome Script

https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS
