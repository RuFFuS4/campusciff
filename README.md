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

###	<div style="text-align: center;">CON CONFLICTO</div>
En esta ocasión realizaremos un _conflicto_ para poder ver lo que sucede cuando simultáneamente queremos modificar un mismo archivo desde dos ramas diferentes y fusionarlas.<br>
Para ello, en primer lugar modificaremos el archivo ___1.txt___ del ___master___ :
<pre><code>git checkout master
echo "Hola" >> 1.txt
git add .
git commit -m "hola en 1.txt"
</code></pre>
Y después el mismo archivo ___1.txt.___ de la rama ___v2.0___: 
<pre><code>git checkout v0.2
echo "Adios" &gt;&gt; 1.txt
git add .
git commit -m "adios en 1.txt"
</code></pre>

Como vemos en la primera rama hemos escrito _"Hola"_ y en la segunda _"Adiós"_ lo que al intentar fusionarlas provocará un conflicto. <br>
Para poder observarlo nos volveremos a ir a la rama ___master___ y haremos el ___MERGE___ :
<pre><code>git checkout master
git merge v0.2
vim 1.txt
git add .
git commit -m "arreglado merge en 1.txt"
</code></pre>

<h2><a id="user-content-listado-de-ramas" class="anchor" aria-hidden="true" href="#listado-de-ramas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Listado de ramas</h2>
<ol>
<li>Listar las ramas con merge y las ramas sin merge.</li>
</ol>
<pre><code>git branch --merged
git branch --no-merged
</code></pre>
<h2><a id="user-content-arreglar-conflicto" class="anchor" aria-hidden="true" href="#arreglar-conflicto"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Arreglar conflicto</h2>
<ol>
<li>Arreglar el conflicto anterior y hacer un commit.</li>
</ol>
<pre><code>vim 1.txt
git add .
git commit -m "arreglado merge en 1.txt"
</code></pre>
<h2><a id="user-content-borrar-rama" class="anchor" aria-hidden="true" href="#borrar-rama"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Borrar rama</h2>
<ol>
<li>Crear un tag <strong>v0.2</strong></li>
</ol>
<pre><code>git tag v0.2
</code></pre>
<ol>
<li>Borrar la rama <strong>v0.2</strong></li>
</ol>
<pre><code>git branch -d v0.2
</code></pre>
<h2><a id="user-content-listado-de-cambios" class="anchor" aria-hidden="true" href="#listado-de-cambios"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Listado de cambios</h2>
<ol>
<li>Listar los distintos commits con sus ramas y sus tags.</li>
</ol>
<pre><code>git config --global alias.list 'log --oneline --decorate --graph --all'
git list
</code></pre>
<h2><a id="user-content-cuenta-de-github" class="anchor" aria-hidden="true" href="#cuenta-de-github"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Cuenta de GitHub</h2>
<ol>
<li>
<p>Poner una foto en vuestro perfil de GitHub.</p>
</li>
<li>
<p>Poner el doble factor de autentificación en vuestra cuenta de GitHub.</p>
</li>
<li>
<p>Añadir (si no lo habéis hecho ya) la clave pública que se corresponde a tu ordenador.</p>
</li>
</ol>
<h2><a id="user-content-uso-social-de-github" class="anchor" aria-hidden="true" href="#uso-social-de-github"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Uso social de GitHub</h2>
<ol>
<li>
<p>Preguntar los nombres de usuario de GitHub de tus compañeros de clase, búscalos, y sigueles.</p>
</li>
<li>
<p>Seguir los repositorios <strong>masteruah</strong> del resto de tus compañeros.</p>
</li>
<li>
<p>Añadir una estrella a los repositorios <strong>masteruah</strong> del resto de tus compañeros.</p>
</li>
</ol>
<h2><a id="user-content-crear-una-tabla" class="anchor" aria-hidden="true" href="#crear-una-tabla"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Crear una tabla</h2>
<ol>
<li>Crear una tabla de este estilo en el fichero <strong>README.md</strong> con la información
de varios de tus compañeros de clase:</li>
</ol>
<table>
<thead>
<tr>
<th>NOMBRE</th>
<th>GITHUB</th>
</tr>
</thead>
<tbody>
<tr>
<td>Nombre del compañero 1</td>
<td><a href="http://github.com/asanzdiego">enlace a github 1</a></td>
</tr>
<tr>
<td>Nombre del compañero 2</td>
<td><a href="http://github.com/asanzdiego">enlace a github 1</a></td>
</tr>
<tr>
<td>Nombre del compañero 3</td>
<td><a href="http://github.com/asanzdiego">enlace a github 3</a></td>
</tr>
</tbody>
</table>
<h2><a id="user-content-colaboradores" class="anchor" aria-hidden="true" href="#colaboradores"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Colaboradores</h2>
<ol>
<li>Poner a <a href="http://github.com/asanzdiego">github.com/asanzdiego</a> como colaborador
del repositorio <strong>masteruah</strong></li>
</ol>
<h2><a id="user-content-crear-una-organización" class="anchor" aria-hidden="true" href="#crear-una-organización"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Crear una organización</h2>
<ol>
<li>Crear una organización llamada <strong>masteruah-tunombredeusuariodegithub</strong></li>
</ol>
<h2><a id="user-content-crear-equipos" class="anchor" aria-hidden="true" href="#crear-equipos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Crear equipos</h2>
<ol>
<li>
<p>Crear 2 equipos en la organización <strong>masteruah-tunombredeusuariodegithub</strong>,
uno llamado <strong>administradores</strong> con más permisos y otro <strong>colaboradores</strong> con menos permisos.</p>
</li>
<li>
<p>Meter a <a href="http://github.com/asanzdiego">github.com/asanzdiego</a> y a 2 de vuestros
compañeros de clase en el equipo <strong>administradores</strong>.</p>
</li>
<li>
<p>Meter a <a href="http://github.com/asanzdiego">github.com/asanzdiego</a> y a otros 2 de vuestros
compañeros de clase en el equipo <strong>colaboradores</strong>.</p>
</li>
</ol>
<h2><a id="user-content-crear-un-indexhtml" class="anchor" aria-hidden="true" href="#crear-un-indexhtml"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Crear un index.html</h2>
<ol>
<li>Crear un index.html que se pueda ver como página web en la organización.</li>
</ol>
<h2><a id="user-content-crear-pull-requests" class="anchor" aria-hidden="true" href="#crear-pull-requests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Crear Pull-requests</h2>
<ol>
<li>
<p>Hacer 2 forks de 2 repositorios <strong>masteruah-tunombredeusuariodegithub.github.io</strong>
de 2 organizaciones de las que no seais ni administradiores ni colaboradores.</p>
</li>
<li>
<p>Crearos una rama en cada fork.</p>
</li>
<li>
<p>En cada rama modificar el fichero <strong>index.html</strong> añadiendo vuestro nombre.</p>
</li>
<li>
<p>Con cada rama hacer un pull-request.</p>
</li>
</ol>
<h2><a id="user-content-gestionar-pull-requests" class="anchor" aria-hidden="true" href="#gestionar-pull-requests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Gestionar Pull-requests</h2>
<ol>
<li>Aceptar los pull-request que lleguen a los repositorios de tu organización.</li>
</ol>
</article>
