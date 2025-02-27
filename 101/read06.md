# 1. ¿Qué hacen los siguientes comandos?

1. **`pwd`**:  
   Te dice en qué carpeta estás ahora.

2. **`ls`**:  
   Muestra todos los archivos y carpetas que hay en la carpeta actual.

3. **`cd`**:  
   Te permite ir a otra carpeta. Por ejemplo, `cd nombre_carpeta` te lleva a "nombre_carpeta".

4. **`mkdir`**:  
   Crea una nueva carpeta. Por ejemplo, `mkdir nueva_carpeta` crea una carpeta llamada "nueva_carpeta".

5. **`touch`**:  
   Hace un nuevo archivo vacío o actualiza uno que ya existe. Por ejemplo, `touch archivo.txt` crea un archivo llamado "archivo.txt".
Si necesitas algo más, ¡dímelo!


# ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).

1. **Te mueves a "projects".**
   - **Comando**: `cd projects`
   - **Descripción**: Cambias el directorio actual a la carpeta llamada "projects". Si la carpeta no existe, se mostrará un error.

2. **Creas "new-project".**
   - **Comando**: `mkdir new-project`
   - **Descripción**: Creas una nueva carpeta llamada "new-project" dentro de "projects". Si "new-project" ya existe, se mostrará un error.

3. **Creas "newfile.md" dentro de "new-project".**
   - **Comando**: `touch new-project/newfile.md`
   - **Descripción**: Creas un nuevo archivo vacío llamado "newfile.md" dentro de la carpeta "new-project". Si "new-project" no existiera, el comando fallaría.

4. **Regresas a "projects".**
   - **Comando**: `cd ..`
   - **Descripción**: Regresas al directorio anterior, que es la carpeta "projects". El doble punto (`..`) indica "un nivel arriba" en la jerarquía de carpetas.

5. **Listas el contenido de "new-project" y ves "newfile.md".**
   - **Comando**: `ls projects/new-project`
   - **Descripción**: Listas los archivos y carpetas dentro de "new-project". Deberías ver el archivo "newfile.md" que creaste previamente.


- Te mueves a "projects".
- Creas "new-project".
- Creas "newfile.md" dentro de "new-project".
- Regresas a "projects".
- Listas el contenido de "new-project" y ves "newfile.md".



# 3. ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

Para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS, usarías el siguiente comando:



ls -a
Explicación de los Parámetros:
ls:
Este es el comando principal que se utiliza para listar los archivos y directorios en el directorio actual.

-a:
Este es un parámetro (o opción) que significa "all" (todos). Incluye en la lista los archivos ocultos, que son aquellos cuyos nombres comienzan con un punto (.). Sin esta opción, ls solo mostrará los archivos y directorios visibles.



