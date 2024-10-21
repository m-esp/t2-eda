Requisitos
Para compilar y ejecutar el código:

Un compilador compatible con C++11 o superior.
CMake (opcional, pero recomendado para la construcción).

Primero clonar el repositorio: 
```bash
git clone https://github.com/m-esp/t2-eda
cd imagepro
mkdir build
cd build
cmake ..
cmake --build .
./Debug/imagepro.exe
```
(Ojo que esto es para windows, yo usé Visual Studio 

Ejemplos de uso
```bash
Cargar imagen: 

>> im1 = read ../images/image_1.bmp
Leyendo imagen: ../images/image_1.bmp
Imagen cargada como im1

Mostrar imagen:
>> show im1

Detectar regiones:
>> getregions im1
La imagen im1 tiene 18 regiones.
Región 1 -> size 373
Región 2 -> size 342
...

Mostrar región específica:
>> showregion im1 1
```
