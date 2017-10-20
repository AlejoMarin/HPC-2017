Parcial 2 HPC utilizando CUDA para la aplicación del filtro de Sobel

Filtro Sobel

Para compilar:

    1. Crear una carpeta con el nombre build
    2. Dirigirse a esa carpeta
    3. Escribir en el terminal:

cmake -DCUDA_USE_STATIC_CUDA_RUNTIME=OFF ..
make

Esto generará el ejecutable Image.out

Para ejecutar:

sbatch  constantMemory.sh

Local

En la carpeta build escribir lo siguiente:

./Image.out Balon
