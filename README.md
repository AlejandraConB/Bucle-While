## 📌 Descripción
- El objetivo de este programa es demostrar el uso de un bucle while en C, así como las operaciones básicas de salida por consola mediante printf.
- Sin embargo, el bucle while nunca se ejecuta debido a la condición n > 10.
- Dado que la variable n se inicializa con el valor 10, la condición es falsa desde el inicio, por lo tanto, el cuerpo del bucle se omite completamente.
- Finalmente, el programa imprime un mensaje indicando que se ha salido del bucle, lo cual ocurre inmediatamente al iniciarse.

## 🚀 Estructura del Código
#### 1.#include <stdio.h>
  - Incluye la biblioteca estándar de entrada/salida (stdio.h), necesaria para usar funciones como printf.
  - Sin esta directiva, el compilador no reconocería printf.

#### 2.int n = 10;
  - Declara una variable global entera llamada n y la inicializa con el valor 10.
  - Esta variable es accesible desde cualquier función del archivo.

#### 3.int main()
  - Función principal del programa.
  - Es el punto de entrada cuando el programa se ejecuta.
  - Devuelve un entero (int) que indica si el programa terminó correctamente (0) o con errores (cualquier otro valor).

#### 4.while (n > 10)
  - Evalúa si n es mayor que 10.
  - Como n vale exactamente 10, la condición es falsa.
  - El bucle no se ejecuta.

#### 5.printf("n es igual a %d\n", n);
  - Esta línea no se ejecuta porque está dentro del bucle while.
  - Si n fuera mayor que 10, esta instrucción imprimiría su valor usando el especificador %d.

#### 6.n = n - 1;
  - Esta línea también no se ejecuta.
  - Si el bucle se ejecutara, decrementaría n en una unidad cada vez.

#### 7.return 0;
  - Indica que el programa finalizó correctamente.
  - Este valor es devuelto al sistema operativo.

## 🖥️ Tecnologías Utilizadas:

- Lenguaje programación C
- Visual Studio Code

## 📦 Requisitos:

- Compilador gcc o cc.

## ⚙️ Compilación

- Compilación en sistemas GNU/Linux es el siguiente comando: **gcc bucle-while.c -o bucle-while**.
- En entornos Windows con Microsoft Visual C++, se utiliza el compilador cl.exe. Para compilar un programa, se debe abrir una ventana de símbolo del sistema para desarrolladores y ejecutar un comando como: **cl bucle-while.c**. Esto genera un archivo ejecutable llamado **bucle-while.exe**.

</br>

💙 <strong>Alejandra Contreras</strong></br></br>
<a href="https://www.linkedin.com/in/alejandraconb-dev/" target="_blank">
<img align="left" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<img align="center" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Relieved%20Face.png" target="_blank" height="40"></a>
