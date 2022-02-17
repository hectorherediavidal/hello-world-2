# hello-world-2
Tarea 3 entregable

# Primero os muestro el archivo file1 sin modificar.

   ![5](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/15.PNG)

# Primero debemos movernos al repositorio de Git en el que queremos trabajar.
    cd "nombre del repositorio"
    Ejemplo: cd hello-world-2/
   ![16](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/16.PNG)
   
# Ahora debemos actualizar nuestra "branch".
    git pull
   ![17](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/17.PNG)

# Nos movemos a la "branch" donde queremos trabajar.
    git checkout "nombre de la branch"
    Ejemplo: git checkout branchprueba
   ![18](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/18.PNG) 
    
# Ahora vamos a editar el archivo file1 con el siguiente comando.
    nano file1.md
    
   ![20](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/20.PNG) 
    
# Una vez dentro del archivo, ponemos lo que queramos.
    
    
   ![19](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/19.PNG) 
    
    
 # Una vez actualizado, debemos añadir el archivo file1.md:
    git add "nombre del archivo"
    Ejemplo: git add file1.md
   ![21](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/21.PNG) 
    
 # Ahora vamos a confirmar lo que hemos añadido y a dejar un comentario:
    git commit -m "lo que queramos"
   ![22](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/22.PNG) 
    
 # Para acabar, debemos exportar a Github el trabajo hecho desde la consola de Git
    git push 
    
   ![23](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/23.PNG)

