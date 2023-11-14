# MARKDOWN DE APUNTES
## PRIMERA CLASE

Lo que se realizo fue personalizar Visual Studio Code (VSCode) con las siguientes caracteristicas :
1. Instalar JDK
![ JDK logo](https://benjagarrido.com/wp-content/uploads/2015/07/java_logo.png)
2. Crear cuenta de GitHub e integrar al VSCode
3. Jugar - Mecanografía: Enciende el juego y practica la mecanografía mientras usas el VSCode.
4. Extensiones para VSCode: Abre el VSCode y ve a la sección de Extensiones en el panel izquierdo.
Busca "Extension Pack for Java" e instala esta extensión. Esto incluirá varias extensiones útiles para el desarrollo en Java.
Instalar GitBash: Descarga e instala GitBash desde este enlace.

5. Consola-Terminal: Abre el VSCode e ve a "Terminal" en el menú superior.
Asegúrate de que el terminal predeterminado sea "Git Bash".
Personaliza la terminal siguiendo estos pasos:
Para instalar Windows Terminal Preview, sigue las instrucciones en este enlace.
Para personalizar el tema y la tipografía en Windows Terminal, crea un archivo de configuración (settings.json) en la siguiente ubicación: %USERPROFILE%\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
Para configurar el tema y la tipografía, sigue las instrucciones
## SEGUNDA CLASE
En esta clase se trabajo el IDE ( Entorno de desarrollo integrado).
Para eso tuvimos que instalarnos en elVScode los siguientes programas:

##  Extension pack for java:

![Extension pack for java logo](https://docs.cse.lehigh.edu/images/removing-vscode-java-ext/removing-vscode-java-ext03.png
)
## Draw.io Integration con sus extenciones:
![Draw.io Integration: logo](https://miro.medium.com/v2/resize:fit:1400/1*edoKlg4bETb_u3Hj3XESjg.png)

## Excalidraw:
![ Excalidraw Logo](https://bestofjs.org/api/og/projects/excalidraw?t=2023-11-06T21-20)

## Makefile Tools:
![Makefile Tools Logo](https://earthly.dev/blog/assets/images/vscode-make/9360.png)
## Markdown PDF y sus extensiones:
![ markdown Logo](https://prod-content-island.s3.eu-west-3.amazonaws.com/lemoncode%2Flemoncode-tv%2Flesson%2Fexport-pdf%2Finstall-markdown-pdf.png)
## Live Share:
![Live Share Logo](https://code.visualstudio.com/assets/learn/collaboration/live-share/live-share-extension.png)
## Excalidraw:
![Excalidraw Logo](https://excalidraw.nyc3.cdn.digitaloceanspaces.com/github/excalidraw_github_cover_2.png)
## SQlite Viewer y sus extensiones:
![SQLite Viewer Logo](https://bobbyhadz.com/images/blog/vscode-view-query-sqlite/install-sqlite-extension.webp)

# TERCERA CLASE:
Aprendimos sobre los shortcuts.
## Shortcuts del editor:
tabla
| Key | Action |
| --- | --- |
| ctrl + shift + n | New Window |
| ctrl + p | Quick Open |
| ctrl + o | Show All Commands |
| alt + up / down | Move lines up and down |
| alt + left / right | Indent lines or selected text in the specified direction |
| ctrl + k z | Undo last action |
| ctrl + shift + k z | Redo last undone action |
| ctrl + s | Save file |
| ctrl + f | Find in File |
| ctrl + h | Replace in File |
| ctrl + g | Go to line |
| ctrl + w | Close tab |
| ctrl + q | Quit Visual Studio Code |
| ctrl + ` | Switch between tabs |P
| ctrl + [ ] | Navigate through open tabs |
| ctrl + pageup / pagedown | Scroll up and down pages |
| ctrl + home / end | Scroll to top and bottom of viewport |
| ctrl + numpad . | Scroll to center current line |
| ctrl + numpad - | Decrease font size |
| ctrl + numpad + | Increase font size |
| ctrl + numpad * | Reset zoom level to default |
| ctrl + numpad / | Zoom in |
| ctrl + numpad \ | Zoom out |
| ctrl + , | Open settings |
| ctrl + ; | Open command palette |
| ctrl + t | Open new terminal |
| ctrl + b | Toggle sidebar visibility |
| ctrl + x | Close active tab |
| ctrl + d | Duplicate active tab |
| ctrl + e | Open explorer (if installed) |
| ctrl + r | Reload window if no changes detected |
| ctrl + shift + r | Force reload window |
| ctrl + a | Select all |
| ctrl + z | Undo |

## Marckdown
### Encabezamientos
- #H1

- ##H2

- ###H3

- ####H4

- #####H5
  
### Énfasis (cursiva y negrita)
- *texto en cursiva *
- **texto en negritas **
- *** texto en cursiva y negritas***
  
### Listas
#### Lista no ordenada:
- Elemento 1
- Elemento 2
- Elemento 3

#### Lista Ordenada:
1. Elemento 1
2. Elemento 2
3. Elemento 3

Las listas pueden ser ordenadas o no ordenadas. Para las listas no ordenadas, se utiliza un guion, un asterisco o un signo.

### Enlaces
`[Texto del enlace](URL)
`
### Imagen
`![Imagen descritiva](ruta/de/la/imagen "Titulo de la imagen")`

### Código inline
'`Inline code`'









## CUARTA CLASE

Lo que se vio en esta clase fue sobre el Git

### ¿Qué es git?
Git es un sistema de control de versiones, lo que significa que nos permite tener una traza del historial y los cambios realizados.
### GIT & LINUX

Comandos para uso del GIT

$ git --version
TU IDENTIDAD

$ git config --global user.name "tunombre"


$ git config --global user.email "nombredeusuariol@gmail.com"

*VERIFICANDO GIT*

$ git config --global user.name

$ git config --global user.email 


$ git init  *->*  haremos un seguimiento.

$ git status  

------------------- (On branch main)


$ git add < file >  *->* guardar uno por uno, segun su nombre.


$ git add .  *->* guardar todo.

---<><><><>---------------- (On branch main)

        new file:   c++/multi.cpp
        new file:   c++/resta.cpp
        new file:   c++/suma.cpp
        new file:   readme.md/readme.md

$  git commit -m "C1 PRJ-start"

                                  C1
---<><><><>------|----------- (On branch main)
   -                      4o095yg

     Ahora otro:

$ git add .gitignore
                                    
---<><><><>------|-------------<> (On branch main)
                              3trggi4          - .gitignore

 $ git commit -m "C2 add .gitignorre"

                                C1              C2
---<><><><>------|-----<>---|--- (On branch main)
   -                                              19084

guardado.   

---<><><.....>-----|--- (main) ------<  (req / fix)
                               |
                               |
                               | --<>< ..>-*(config)

### linux

$  clear   

$  ctrl + l      ( arroup up)    (tab : autocomplete)

$  cd/home/usuario/proyecto_git   (ingresar a los directorios)

$  ls -l            ( listados.)

$ pwd  ( en que directorio estamos)

$ cd .. ( carpeta anterior )

$ cat         (ver el cont. de un archivo, concatenar)

$ echo "hola" > file.txt (crear un archivo y escribir en el)

$ touch    (crear el archivo)

$ git rm " " (eliminar archivo de la rama)


*Inic. Control De Versiones - CLONANDO*

$ git clone https://github.com/xxyy/abc

$ git clone https://github.com/xxyy/abc miPropioNombre
  ## QUINTA CLASE
  $ git ra red.pdf        (Borrar archivo de la rama)
  --------<><><...>---|-----------<>  (On branch master)
                    35b936f          -.gitignore

$ git commit -m "C2  add .gitignore"
                    C1              C2
--------<><><...>---|------------<>-|---      (On branch master)
                 35b936f           43eab06


--------<><><...>---|---          |(main) -----<  (req / fix)
                    |
                    |
                    |----<><><...>--- *(Config)


--------<><><...>---|---             (main) -----<  (req / fix)
                    |
                    |              C1
                    |----<><><...>-| *(Config)
                                  93fa79b


--------<><><...>---|---                      (main) -----<  (req / fix)
                    |                           ^
                    |              C1           |
                    |----<><><...>-|--       ***|(Config)
                                  93fa79b


                     





### Codigo "Hola mundo"

```java public class Hi_Karo{
     public static void main (String[] args){
        System.out.println("Hi Karo");
    }
} 





