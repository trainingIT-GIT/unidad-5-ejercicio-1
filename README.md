# unidad-5-ejercicio-1
Ejercicio uno de la unidad 5

1. Clona en tu máquina, con el comando git clone, el repositorio que hay aquí:
https://github.com/trainingIT-GIT/unidad-5-ejercicio-1.

- ésa no es la URL del repositorio, sino la de la interfaz web para gestionar el repositorio.
- es recomendable copiar la URL asegurándote antes de que estás logueado con tu cuenta.
- el comando `git clone` te creará una subcarpeta, recuerda entrar en ella para empezar a trabajar.
2. Lanza el comando `git checkout develop` para poder ver las dos ramas que te has bajado (si no, sólo verás _main_).
3. Mira el _log_. Comprobarás que hay dos ramas: _main_ y _develop_, que han divergido y avanzado en paralelo, dando como resultado una bifurcación.
4. Vuelca el trabajo de la rama _develop_ en la rama _main_. Para ello asegúrate de que estás en la rama _main_ y lanza el comando `git merge develop`.
5. Resuelve los conflictos por el método que prefieras.
6. Cierra el _merge_ y comprueba con el _log_ que se ha creado un nuevo _commit_ con la fusión de ambas ramas.
7. Mira el contenido de los archivos que tenían conflictos y asegúrate de que tienen todo el código que se desarrolló en ambas ramas.