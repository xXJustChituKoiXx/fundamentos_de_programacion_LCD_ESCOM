# **FUNDAMENTOS DE PROGRAMACIÓN**
### **Escuela Superior de Cómputo (ESCOM) - IPN**

Repositorio oficial que recopila las prácticas de laboratorio, bibliotecas propias y ejercicios de modularización en lenguaje C desarrollados durante el semestre.

---

## **Descripción General**

Este proyecto contiene el código fuente enfocado en el aprendizaje de programación estructurada, compilación separada (archivos de cabecera `.h` y código fuente `.c`), manejo de memoria básica y creación de programas modulares.

---

## **Estructura del Repositorio**

El contenido se encuentra organizado por módulos y prácticas de la siguiente manera:

### **1. Código Suma**
Ejercicios introductorios de modularización y enlace de archivos.
* `suma.c` — Implementación de las funciones matemáticas.
* `suma.h` — Archivo de cabecera con los prototipos de las funciones.
* `usa_suma.c` — Programa principal que invoca la biblioteca.

### **2. Práctica 11 (`P11`)**
Batería de ejercicios básicos de entrada, salida y estructuras de control en C.
* `hello01.c` hasta `hello18.c` — Serie progresiva de programas introductorios y pruebas de sintaxis.

### **3. Práctica 12 (`P12`)**
Implementación utilizando archivos objeto precompilados y manejo de errores.
* `error.h` — Definición de códigos y manejo de errores.
* `rubik2.h` — Interfaz y prototipos del módulo Rubik.
* `rubik2.o` — Código objeto precompilado.
* `usa_rubik2.c` — Programa cliente que enlaza e implementa las funciones del módulo.
* `P12.pdf` — Documentación y reporte de la práctica.

### **4. Práctica 13 (`P13`)**
Manejo de paso de parámetros por referencia y documentación formal.
* **Carpeta `DOC`**
  * `P13-NOGUEZ_OJEDA_RICARDO-1AV1.pdf` — Reporte técnico de la práctica.
* **Carpeta `SRC`**
  * `swap.c` — Implementación de la función de intercambio mediante apuntadores.
  * `swap.h` — Archivo de cabecera correspondiente.
  * `usa_swap.c` — Programa principal de prueba.

### **5. Práctica 21 (`P21`)**
Desarrollo modular aplicado al cálculo o trazado de figuras.
* `figuras.c` — Lógica e implementación de funciones para figuras.
* `figuras.h` — Prototipos y definiciones de estructuras.
* `usa_fig.c` — Programa principal de ejecución.

---

## **Requisitos de Compilación**

* Compilador de C estándar (`GCC` / `MinGW` en Windows o entornos Unix/Linux).
* Terminal o línea de comandos para el enlazado de múltiples archivos fuente y objeto.

---

## **Instrucciones de Uso**

Para compilar y ejecutar proyectos divididos en múltiples archivos (ejemplo con `Código suma` o `P13`):

```bash
gcc usa_suma.c suma.c -o programa
./programa
```

Para compilar enlazando un archivo objeto precompilado (como en `P12`):

```bash
gcc usa_rubik2.c rubik2.o -o rubik
./rubik
```"# fundamentos_de_programacion_LCD_ESCOM" 
