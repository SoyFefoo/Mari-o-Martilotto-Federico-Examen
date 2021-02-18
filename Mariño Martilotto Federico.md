# Federico Mariño Martilotto

## Examen Entornos de desarrollo - Modelo A


#### 1. Crea un repositorio y lo inicialiuzamos con el comando:
(Examen paso 1)

    git init

<br />

#### 2. Despues de crear el directorio y los ficheros con su contenido, para pasar los directorios a preparado será con el comando:
(Examen paso 5)

    git add --all
<br />

#### 3. Nos podemos asegurar del estado de los firectorios y ficheros mediante el comando:

    git status

#### Seguido de esto procedemos a realizar la confirmacion mediante un commit con el comando:
(Examen paso 6)

    git commit -m "Index" /*El nombre que asignamos al commit es Index*/
    
<br />

#### 4. Modifica el texto del ultimo commit poniendo “ Index y unidades 1 y 2 “ mediante el comando:
(Examen paso 7)

    git commit --amend

<br />

#### 5. Podemos volver a hacer un status para comprobar que se borra el contenido y seguido volvemos a pasarlo con el comando:

    git add --all

<br />

#### 6. Miramos el estado del proyecto con el comando:

    git status

<br />

#### 6. Nuestro segundo commit con el comando:

    git commit -m "Eliminado texto de unidad 2"

<br />

#### 7. Visializamos el log del proyecto con el comando:

    git log

<br />

#### 8. Volvemos atras con el comando:

    git checkout "Index y unidades 1 y 2"

<br />

#### 9. Por ultimo volvemos al estado final con el comando:

    git checkout master

<br />

#### 10. Por ultimo subimos el proyecto a nuestro repositorio con el comando:

     git remote add origin https://github.com/SoyFefoo/Mari-o-Martilotto-Federico-Examen.git
     
#### Seguido de esto en mi caso me daba error en el push por lo tanto con el comando branch lo soluciono:

    git branch -M main
    
#### Y por ultimo realizamos el push del proyecto al repositorio

    git push -u origin main

<br />
<br />


