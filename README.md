# <div style="text-align: center;">EJERCICIO BÁSICO FINAL GIT</div>
##	<div style="text-align: center;">1. CUENTA GITHUB</div>
En primer lugar debemos dirigirnos a [Github](https://github.com/) para **registrarnos** y posteriormente **iniciar sesión**.

![](GIFs/1.gif)
---
##	<div style="text-align: center;">2. CREAR REPOSITORIO</div>
El siguiente paso será crear nuestro repositorio **CAMPUSCIFF**.

![](GIFs/2.gif)
---
##	<div style="text-align: center;">3. CLONAR REPOSITORIO</div>
Tenemos el repositorio alojado en [Github](https://github.com/) pero tenemos que **clonarlo** en una carpeta local que en mi caso será <code>_G:\Mi unidad\DEI\EjercicioFinalGit_</code>

![](GIFs/3.gif)
---
##	<div style="text-align: center;">4. CREAR README y COMMIT</div>
Aunque nosotros creamos el archivo _README.md_ a la hora de crear el repositorio, haremos un nuevo archivo ___README2.md___ para ver como se crearía dicho archivo mediante comandos. <br>
Además haremos nuestro primer ___COMMIT___.

![](GIFs/4.gif)
---
##	<div style="text-align: center;">5. PUSH</div>
Ya hemos realizado nuestro primer _COMMIT_ no obstante, los archivos todavía permanecen en nuestro equipo y para enviarlos a nuestro repositorio online debemos realizar un **PUSH**.

![](GIFs/5.gif)
---
##	<div style="text-align: center;">6. IGNORAR ARCHIVOS</div>
Suele ser habitual el no querer añadir cierto tipos de archivos "basura". <br>
Para ello debemos crear un archivo ___.gitignore___ en el cual añadiremos aquellos archivos concretos o extensiones en general que queremos que **Git** ignore cuando hacemos un **add**.

Para realizar una prueba en primer lugar crearemos el fichero _privado.txt_ y la carpeta _privada_:

![](GIFs/6.gif)

Una vez comprobamos que se han creado con éxito, crearemos el fichero ___.gitignore___ en el que añadiremos los archivos:

![](GIFs/7.gif)

Para comprobar que ha funcionado haremos un **add**:

![](GIFs/8.gif)
---
##	<div style="text-align: center;">7. TAGs</div>
El siguiente paso será crear la primera versión de nuestro repositorio a partir de un ___TAG___.<br>
Antes de eso crearemos el archivo _1.txt_:

![](GIFs/9.gif)

Crearemos el **TAG** sobre el último _COMMIT_ realizado:

![](GIFs/10.gif)

Haremos un nuevo _COMMIT_ para "marcar" cuando hemos creado la versión:

![](GIFs/11.gif)

Para comprobar que se ha creado correctamente podemos hacer:

![](GIFs/12.gif)

Para finalizar subiremos el **TAG** al repositorio online y haremos un último _COMMIT_ indicando que hemos terminado.

![](GIFs/13.gif)

![](GIFs/14.gif)

---
##	<div style="text-align: center;">8. CUENTA GITHUB</div>
* **FOTO DE PERFIL**
  
  <div style="text-align: center;"> <img src="Img/Perfil.png"></div>

* **DOBLE FACTOR DE AUTENTIFICACIÓN**
  
  <div style="text-align: center;"> <img src="Img/FactorAutentificacion.png"></div>
  <div style="text-align: center;"> <img src="Img/FactorAutentificacion2.png"></div>

  Tras esto recibiremos unos códigos de recuperación que debemos guardar. Y posteriormente enlazar la cuenta con un número de teléfono para la utentificación por ___SMS___ o por ___APP___. Esto último será mi caso.<br>
  La ___APP___ que yo utilizo es: [OctoPrint](https://play.google.com/store/apps/details?id=com.gh4a)
    <div style="text-align: center;"> <img src="Img/FactorAutentificacion3.png" width=48%><img src="Img/FactorAutentificacion4.png" width=48%></div>
	<br>
    Una vez terminado nos debe aparecer:
    <div style="text-align: center;"> <img src="Img/FactorAutentificacion5.png"></div>
	<br>

* **SEGUIR COMPAÑEROS**
	<br>
	<h3 style="text-align: center;">Fran</h2>
	<div style="text-align: center;"> <img src="Img/FollowFran.png"></div>
  	<h3 style="text-align: center;">Miriam</h2>
  	<div style="text-align: center;"> <img src="Img/FollowMiriam.png"></div>
  	<h3 style="text-align: center;">David</h2>
  	<div style="text-align: center;"> <img src="Img/FollowDavid.png"></div>
  	<h3 style="text-align: center;">Miguel</h2>
  	<div style="text-align: center;"> <img src="Img/FollowMiguel.png"></div>
	<br><br>
* **SEGUIR REPOSITORIOS Y AÑADIR ESTRELLAS**
	
	Voy a seguir el repositorio de uno de mis compañeros y le añadiré una estrella. Para realizarlo con el resto sería de igual manera.
	<div style="text-align: center;"> <img src="Img/Star.png"></div>

---
##	<div style="text-align: center;">9. TABLA</div>
| Nombre | Enlace |
| -- |-- |
| Miguel | https://github.com/miguelj93/campusciff.git |
| Miriam | https://github.com/MIRIAM-GIT/campusciff.git |
| David | https://github.com/davidfuentes2755/campusciff.git |

---
##	<div style="text-align: center;">10. COLABORADORES</div>
Desde la pestaña _Settings_ y en la opción _Collaborators_ podemos hacer colaborador a otro usuario:
<div style="text-align: center;"> <img src="Img/Colaborador.png"></div>

---
<br>

# <div style="text-align: center;">EJERCICIO AVANZADO FINAL GIT</div>
##	<div style="text-align: center;">1. RAMA</div>
Crearemos una rama

<code>git branch v2.0</code>

Posicionaremos la carpeta de trabajo en esa rama

<code>git checkout v2.0</code>

<div style="text-align: center;"> <img src="Img/Rama1.png"></div><br>

Vamos a añadir un fichero llamado ___1.txt___ y haremos un _COMMIT_ indicándolo.

<pre><code>touch 2.txt
git add .
git commit -m "añadido 2.txt"</code></pre>

<div style="text-align: center;"> <img src="Img/Rama2.png"></div><br>

Por último enviaremos la **rama** creada al repositorio online:

<code>git push origin v2.0</code>

<div style="text-align: center;"> <img src="Img/Rama3.png"></div><br>
---

##	<div style="text-align: center;">2. MERGE</div>
Ahora vamos a hacer un ___MERGE___ o fusión de la rama _master_ con la nueva rama que hemos creado. Para ello debemos posicionarnos en primer lugar en la rama ___master___:

<code>git checkout master</code>

Para posteriormente hacer un merge de la rama **v2.0** en el ___master___.
<br>

<code>git merge v2.0 -m "merge v2.0 sin conflictos"</code>

<div style="text-align: center;"> <img src="Img/Merge.png"></div><br>

###	<div style="text-align: center;">CON CONFLICTO</div>
En esta ocasión realizaremos un _conflicto_ para poder ver lo que sucede cuando simultáneamente queremos modificar un mismo archivo desde dos ramas diferentes y fusionarlas.<br>
Para ello, en primer lugar modificaremos el archivo ___1.txt___ del ___master___ :
<pre><code>echo "Hola" >> 1.txt
git add .
git commit -m "hola en 1.txt"
</code></pre>
Y después el mismo archivo ___1.txt.___ de la rama ___v2.0___: 
<pre><code>git checkout v2.0
echo "Adios" >> 1.txt
git add .
git commit -m "Adios en 1.txt"
</code></pre>

<div style="text-align: center;"> <img src="Img/MergeConflicto.png"></div><br>

Como vemos en la primera rama hemos escrito _"Hola"_ y en la segunda _"Adiós"_ lo que al intentar fusionarlas provocará un conflicto. <br>
Para poder observarlo nos volveremos a ir a la rama ___master___ y haremos el ___MERGE___ :
<pre><code>git checkout master
git merge v2.0
vim 1.txt</code></pre>

<div style="text-align: center;"> <img src="Img/MergeConflicto2.png"></div><br>

Como podemos ver ___Git___ nos permite ver cual es el cambio que causa el conflicto:

<div style="text-align: center;"> <img src="Img/MergeConflicto3.png"></div><br>

###	<div style="text-align: center;">LISTADO RAMAS</div>
Antes de arreglar el conflicto causado procederemos a mostrar las ramas que han sufrido un ___MERGE___ y las que no para así observar como el conflicto evita que las ramas sean fusionadas hasta ser resuelto.

<div style="text-align: center;"> <img src="Img/ListadoRamas.png"></div><br>

###	<div style="text-align: center;">SOLUCION CONFLICTO</div>
Para solucionar el conflicto elegiremos cual de las dos partes del mismo nos interesa conservar y haremos un ___COMMIT___ :
<pre><code>git add .
git commit -m "arreglado merge en 1.txt"
</code></pre>

<div style="text-align: center;"> <img src="Img/ArreglandoConflicto.png"></div><br>
---

##	<div style="text-align: center;">3. BORRAR</div>
Por último vamos a borrar la rama _v2.0_ para lo cual antes crearemos un ___TAG___ :

<code>git tag v2.0</code>

Ahora la borramos:

<code>git tag v2.0</code>

<div style="text-align: center;"> <img src="Img/BorrarRama.png"></div><br>

##	<div style="text-align: center;">4. LISTAR CAMBIOS</div>
Por último mostraremos los distintos ___COMMITS___ y ___TAGS___ realizados:

<pre><code>git config --global alias.list 'log --oneline --decorate --graph --all'
git list</code></pre>

<div style="text-align: center;"> <img src="Img/Listar.png"></div><br>

---
