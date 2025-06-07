
markdown open preview
<!-- HEADINGS -->

# Mi titulo
## Mi Titulo H2
### mi titulo h3
##### mi titulo h5

<!-- italic -->

this is an *italic* text

<!-- strong -->
this is an **strong** text

<!-- strikethrough -->
esto es un  ~~texto~~ tachado con tilde ondulada (alt+126)

<!-- UL -->
* Apple
   * Apple 2
* orange
    * Circle
* etc

1. Apple
    1. Apple 2
2. Orange

[faztweb.com](http://www.faztweb.com)

[faztweb.com](http://www.faztweb.com "Custom title")

> this is a quote
---
___

console.log("hello world")

```SQL
SELECT * 
   FROM movies 
   WHERE year 
   BETWEEN 2000 AND 2010;
```

```python
print("hello world")
```

```html
<h1>hello world</h1>
```
| tilde vertical = alt+124  "|"

| First Header  | Second Header | Tird Header   |         
| ------------- | ------------- | ------------- |
| Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  |

![ visual studio code logo](https://repository-images.githubusercontent.com/657248114/d3c7b91a-b285-4d1e-8429-5de1acc5f61e)

llamar imagen guardada
![ visual studio code logo](vscodelogo.png "vs code logo")

<!-- GITHUB MARKDOWN -->
* [X] Tarea 1
* [ ] Tarea 2
* [ ] Tarea 3
* [X] Tarea 4
* [X] Tarea 5

anotar terminal integrate para importar a Github

//inicias terminal

crear un repositororio git = git init

me muestra todos los archivos que voy a subir a git = git status

agregar archivos= git add .

verifica de nuevo =git status "(*deben salir en verde que significa que ya estan subidos*)"

para guardarlos como ..= git commit -m "markdown-test"

configurar usuario y correo en git= git config --global user.email "ingmaomedina@gmail.com"

git config --global user.name "Maomedina33"

una vez terminado puedes generar un commit =
git commit -m "markdown-test"

copias el enlace de codigo de git y lo ejecutas en el terminal para agregar un repositorio remoto, en este caso fue: git remote add origin https://github.com/Maomedina33/-Markddown-test1-.git

ahora vamos a subirlo = git push -u origin master


