# Navegar en el sistema de archivos

En Linux, todo está organizado en un **árbol de directorios**.

## **`cd` (change directory)** → moverse entre carpetas.

```python
cd /home/kali       # ir a la carpeta /home/kali
cd ..               # subir un nivel (a la carpeta padre)
cd                  # volver al directorio personal (/home/usuario)
cd -                # volver al directorio anterior
```

# Crear directorios y archivos

## **`mkdir` (make directory)** → crear carpetas.

```python
mkdir pruebas       # crea una carpeta llamada "pruebas"
mkdir -p a/b/c      # crea varias carpetas anidadas
```

## `nano` (editor de texto simple en consola)

```python
nano archivo.txt
```

Luego:

- Escribes tu texto.
- Guardar: `CTRL + O`
- Salir: `CTRL + X`

# Ver contenido de archivos

## **`cat` (concatenate)** → mostrar archivos en pantalla.

```python
cat archivo.txt       # muestra el contenido completo
cat /etc/passwd       # ver usuarios del sistema
```

> [!WARNING] less
> Si el archivo es muy largo, mejor usar `less`:
> less archivo_grande.txt
> (para avanzar, usa la barra espaciadora; para salir, `q`).


# Ver dónde estás y qué hay

## **`pwd` (print working directory)** → ver la ruta actual.

```python
pwd
```

## **`ls` (list)** → listar archivos y carpetas.

```python
ls          # lista básica
ls -l       # lista detallada (permisos, dueño, tamaño)
ls -a       # muestra archivos ocultos
ls -lh      # lista en “modo humano” (tamaños en KB, MB, GB)
```

