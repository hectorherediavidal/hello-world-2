# hello-world-2
Tarea 3 entregable

# Primero necesitamos tener un repositorio creado.

# Una vez que lo tengamos, en la consola de git debemos usar el siguiente comando:
    git clone "nuestra url del repositiorio de git"
   ![1](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/1.PNG)
   
# Una vez que hayamos exportado nuestro repositorio desde Github, tenemos que ir al repositorio desde la consola de Git:
    cd repo
   ![2](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/2.PNG)

# Ahora debemos crear una nueva "branch" en nuestro repositorio:
    git branch "nombre que queramos" 
    Ejemplo: git branch branchprueba
   ![3](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/3.PNG) 
    
# Cambiamos a la "branch que acabamos de crear":
    git checkout "nombre que hemos elegido
    Ejemplo: git checkout branchprueba
   ![4](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/4.PNG) 
    
# Ahora crea un archivo cualquiera y escribe cualquier cosa:
    touch file1.md
    
    Y para editarlo: nano file1.md
    
    
 # A continuación debemos añadir el archivo modificado del paso anterior:
    git add "nombre del archivo"
    Ejemplo: git add file1.md
   ![5](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/5.PNG) 
    
 # Ahora vamos a confirmar lo que hemos añadido y a dejar un comentario:
    git commit -m "lo que queramos"
   ![6](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/6.PNG) 
    
 # Para acabar, debemos exportar a Github el trabajo hecho desde la consola de Git
    git push --set-upstream origin "nombre de nuestra branch"
    Ejemplo: git push --set-upstream origin branchprueba
   ![7](https://github.com/hectorherediavidal/hello-world-2/blob/branchprueba/img/7.PNG)
