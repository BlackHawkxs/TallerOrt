# Este es el inicio del repositorio "Taller ORT"
---


![ORTlogo](./ORTlogo.jpg)

GIT es un Systema de Control de versiones distribuido (DCVS). Cada desarrollador tiene una copia completa
del repositorio, por lo que en caso de perdida del repositorio central, cualquier repositorio cliente se puede usar
como respaldo. También esto permite que la mayoría de las operaciones se puedan realizar fuera de línea. Solo
se requiere conexión al repositorio principal para recuperar los últimos cambios y subir los cambios propios.

Los comandos basicos que se pueden utilizar son:

1. git add . - Permite agregar los cambios al directorio de trabajo
2. git status - muestra el estado del repositorio
3. git commit - Agrega los cambios al repositorio local
4. git push -   Agrega los cambios al repositorio remoto
5. git pull - trae los cambios al repositorio local
6. git log - muestra registros del repositorio

El siguiente es un ejemplo para inicializar un repositorio a nivel local:

        $mkdir proyecto
        $cd proyecto
        $git init

Devolviendo el siguiente output:

"Initialized empty Git repository in /home/[UserDirectory]/[ProyectName]/.git/"