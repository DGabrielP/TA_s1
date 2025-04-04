# Tarea Autónoma Semana 1: Comandos de Linux

## Descripción

Este repositorio contiene la **Tarea Autónoma de la Semana 1** de la asignatura de Aplicaciones Tecnologicas. El objetivo de esta tarea es realizar una serie de prácticas utilizando comandos en Linux para la creación, manipulación y gestión de archivos y carpetas.

## Objetivos de la Práctica

Los objetivos principales de esta práctica son:

- Crear una estructura de carpetas y archivos.
- Manipular archivos en Linux utilizando la terminal.
- Realizar operaciones de redirección, concatenación y eliminación de archivos.
- Generar un informe en formato markdown con los pasos realizados y los resultados obtenidos.

## Estructura de Carpetas

1. Se creó la siguiente estructura de carpetas en el directorio de trabajo:

proyecto_comandos/ ├── documentos/ ├── imagenes/ └── scripts/


## Pasos Realizados

### 1. Creación de carpetas y archivos

- Se creó la carpeta `proyecto_comandos` y dentro de ella, las subcarpetas `documentos`, `imagenes` y `scripts`.

### 2. Manipulación de Archivos

- Dentro de la carpeta `documentos`, se creó el archivo `notas.txt` con el siguiente contenido:

3 lineas iniciales y una cuarta luinea que no se sobreescriba

- Se copió el archivo `notas.txt` a la carpeta `scripts` y se cambió su nombre a `backup_notas.txt`.
- Luego, se movió el archivo `backup_notas.txt` a la carpeta `imagenes`.

### 3. Redirección y Concatenación

- Se creó el archivo `resumen.txt` en la carpeta `documentos`.
- Se redirigió el contenido de `notas.txt` a `resumen.txt`.
- Se añadió una nueva línea de texto al final de `resumen.txt` sin sobrescribir el contenido existente.

### 4. Eliminación de Archivos y Carpetas

- Se eliminó el archivo `backup_notas.txt` de la carpeta `imagenes`.
- Se eliminó la carpeta `imagenes` (solo después de asegurarse de que estaba vacía).

### 5. Comando `history`

- El contenido del comando `history` se volcó a un archivo llamado `tarea-s1-diego_gabriel.txt`.

## Instalación y Ejecución de Github

Aprendí a ejecuta Github desde la consola de Linux siguiendo los siguientes pasos:

1. **Inicialización del repositorio**: Se creó el repositorio local utilizando el comando `git init`.
2. **Creación de archivo README.md**: Se generó este archivo para proporcionar información sobre el proyecto.
3. **Añadido de archivos al repositorio**: Se añadieron los archivos de la tarea al repositorio con `git add .`.
4. **Primer commit**: Se realizó el primer commit utilizando `git commit -m "Primer commit: informe y archivo de tarea"`.
5. **Configuración de repositorio remoto**: Se configuró el repositorio remoto en GitHub con el comando `git remote add origin`.
6. **Push de cambios a GitHub**: Se subieron los archivos al repositorio remoto utilizando `git push -u origin main`.

