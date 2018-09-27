# Control 4: Descifrador

## Autores
- Nicolás Cortés.
- Rodrigo Echeverría.
- Daniel Espinoza.

## Descripción
El programa descifra un texto y genera un archivo con las claves. Cada clave tiene entre 6 y 10 caracteres.

## Requerimientos
Es necesario tener instalado openssl (sudo apt-get install libssl-dev).
Para compilar es necesario disponer del programa make (sudo apt-get install make) y ejecutar:

make

## Ejecución (sin corchetes [])
Imprimir integrantes:
./dist/programa -v

Descifrar:
./dist/programa -f [ruta]

ruta: Ruta donde se creará el archivo claves.txt
