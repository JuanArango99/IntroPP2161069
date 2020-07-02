OMP_JULIA_SET.C
Código propuesto para emplear omp y paralelizar el programa que tiene como fin generar conjuntos de julia, son conjuntos de fractales que se obtienen al estudiar el comportamiento de los números complejos.

COMPILACIÓN DEL PROGRAMA:
Para compilar este programa escrito en c se debe hacer el uso de gcc para obtener el archivo ejecutable con nombre 'omp_julia_set' por medio de la siguiente instrucción:

gcc -fopenmp omp_julia_set.c -o omp_julia_set.


EJECUCIÓN DEL PROGRAMA EN LOCAL:
Para ejecutar el programa en local basta con ejecutar directamente el archivo compilado en el paso anterior con la instrucción: ./omp_julia_set


EJECUCIÓN DEL PROGRAMA EN GUANE-1:
Para trabajar desde el servidor de SC3 se debe correr desde SLURM con la ayuda de un archivo sbatch el cual ya hace referencia al programa ya compilado 'omp_julia_set', siendo así se debe ejecutar llamando a la instrucción: sbatch julia_set.sbatch


RESULTADOS DE LA EJECUCIÓN:
El programa debe dar como salida una imágen 'julia_set.tga' con la representación fractal del número imaginario descrito en el programa.


Como salida textual se tiene la descripción del empleamiento de programación paralela sobre el conjunto de julia del numero imaginario, junto con la cantidad de hilos y tiempo de ejecución.


Además de la correcta ejecución del programa, el archivo imágen generado y el momento en tiempo real de la ejecución.






