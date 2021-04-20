1)Abrir directorio de archivos 
2)Abrir terminal e ingresar los siguientes comandos:

*Modo de compilación:
    mpicc -o laboratorio2.exe laboratorio2.c

*Modo de ejecución:
     mpirun -np p ./laboratorio2.exe data.txt
     - Donde "p" es el numero de procesos con el que se realizara la ejecución del programa.
     -data.txt es el fichero con los datos.
