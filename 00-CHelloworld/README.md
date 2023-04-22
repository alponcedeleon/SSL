![UTN BA  LOGO](https://www.frba.utn.edu.ar/wp-content/uploads/2017/10/utnbamediano.jpg)
# Sintaxis y Semántica de los Lenguajes 
**Legajo:**  211.860-9<br>
**Apellido:** Ponce de León <br>
**Nombre:** Alejo Gabriel <br>
**Usuario:** [alponcedeleon](https://github.com/alponcedeleon/SSL) <br>
## Trabajo N° 0 - "Hello,World!" en C 
**Enunciado** 

1. Indique en el readme.md el compilador seleccionado.
2. Pruebe el compilador con un programa hello.c que envie a stdout la 
lmea Hello, World! o similar.
3. Ejecute el programa y verifique que la salida es la esperada. 
4. Ejecute el programa con la salida redireccionada a un archivo 
output.txt; verifique su contenido.

**Resolución**
1. El compilador utilizado es [MinGW](https://www.msys2.org/)
2. El código del programa hello.c se detalla a continuación y fue probado, compilandolo con `gcc -o hello.exe hello.c` 

```
//HOLA MUNDO
#include <stdio.h>

int main(){
printf("Hola Mundo!\n");
return 0;
}
```
3. Para ejecutar el programa se utiliza `./hello` y la salida esperada fue **Hola Mundo!**
4. Para este paso se utiliza `./hello > output.txt` lo cual me genera un archivo txt de nombre **output** donde dentro de ese archivo se encuentra nuestro **Hola Mundo!**
