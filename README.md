# Repositorio1
### Repositori per fer proves
   

1. El primer que he fet ha estat obrir el compte a GitHub i he creat un repositori. (Aquí comença una **_ordered list_**)
2. I després... (ahora crearé una **_unordered sublist_** posant 2 espais i *)
  * He copiat codis de **ps**, **xml**, **html** i **rtf** per crear fitxers d'exemple.
  * Els he pujat a repositori. 
    * He creat una carpeta.(Això és una **unordered sublist** dins una altra. Ho faig deixant 2 espais més.
    Ha de ser aquest nombre d'espais perquè si no me canvia el símbol)
      * I ara estic fent proves, editant el README i intentant que em surti algo amb el *Markdown*. (A l'edició això me
      surt en vermell, m'imagin que perquè no es poden posar ja més subllistes...)
      * dos * y un _ abriendo y cerrando palabras para **negrita** (bold) y _cursiva_ (italic) respectivamente. 
      Se pueden combinar: **_mejor fuera los * y dentro la \__**
      * Para escribir la última frase he tenido que escribir la barra \ delante de _ para que lo interpretara como un caracter. 
      Es decir así: **\*\*\_mejor fuera los * y dentro la \_\_\*\***

EDITADO: CREO QUE SÓLO HAY QUE PONER UN ASTERISCO Y UN ESPACIO ANTES DEL TEXTO. SI QUEREMOS HACER UNA LISTA DENTRO DE OTRA LISTA (NESTED LIST) ENTONCES SÍ QUE LE PONEMOS UN ESPACIO ANTES DEL ASTERISCO.
EDITADO: LOS SIGNOS * Y _ SIRVEN INDISTINTAMENTE PARA NEGRITA O CURSIVA, SI PONEMOS DOS SALDRÁ NEGRITA Y SI PONEMOS UNO CURSIVA

><del>Ahora intento poner [aqui] (https://rawgit.com/) un enlace a rawgit (que por cierto no se exactamente **QUÉ ES!!**)
Vale, funciona pero no exactamente como yo quería, quiero que el enlace esté sobre la palabra aquí, bueno ya lo miraré.</del>
>
><del>Y ahora intento poner un enlace a rawgit, pero a la página que me crea al leer el documento html que tengo en GitHub
que se abre a través de rawgit (https://rawgit.com/MariaAdrover/Repositorio1/master/ejemploHTML.html)</del>
>
>Creo que ya sé como poner el enlace [AQUÍ](https://libro.cursohtml5desdecero.com/) de un tutorial que tiene muy buena pinta, muy claro y bien elaborado, y parece que de verdad es desde cero. Esto son **inline links**.
  * Pues sí que funciona, resulta que **NO PUEDES DEJAR ESPACIO ENTRE EL PARÉNTESIS Y EL CORCHETE!!!**, 20 veces prueba y error
  * Y veo que para poner lo de las **unordered sublists** tampoco puedes dejar espacios después del asterisco
>  
>Ahora pondré unos **reference links** para utilizar el mismo link en varias palabras. Pongo la palabra entre [ ] y al lado tambien entre [ ] el nombre de la referencia que le doy al enlace. A final del documento hay que poner entre [ ] el nombre de la referencia seguido de **:** (_colon_ en inglés) y el link. Pondré un fragmento de un supuesto artículo sobre lenguajes de programación y tutoriales. Los lenguajes estaran enlazados a una página con un ejemplo de código de todos y los tutoriales a una página de tutoriales.
>
>_"... y algunos de los lenguajes de programación que veremos son: [**html**][código] ([**tutorial de html**][tutorial]) (...) por supuesto es preferible [**CSS**][código] ([**tutorial de CSS**][tutorial]) (...) que también hace referencia a [**JavaScript**][código] ([**tutorial de JavaScript**][tutorial])."_ 

[código]: https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=779:diferencias-entre-javascript-y-java-html-css-php-frontera-entre-lenguajes-en-desarrollos-web-cu01105e&catid=78&Itemid=206
[tutorial]: https://www.aprenderaprogramar.es/index.php?option=com_content&view=article&id=57&Itemid=86


Dejo los enlaces enmedio del documento, a ver si funciona o efectivamente ha de estar al final. Bueno voy a añadir otro enlace a los tutoriales a ver si funciona...
[tutorial de Java][tutoriales]

No va, hay que poner el link tab después.
```
Estoy en la master branch. Acabo de modificar el documento y lo he guardado pero creando una new branch. No me lo ha guardado directamente sino que ha tcrado una **pull request**. HHa aparecido la solicitud en la página principal. H añadido un comentario, no sé si como administradora o como usuaria, y luego he intentado aprobar la pull request pero no me ha dejado xk dice que no puedo aprobar una pull request creada por mi... Obviamente, en esta copis no salen los cambios que habia hecho :confused: :laughing:
Ahora grabo esto como siempre, en el master branch con el botón **commit changes**
```
Al párrafo anterior le he puesto los signos del fenced code block y me los ha puesto en la ventanita. Como lo que hace esta ventanita es mantener la justificación tal cual se la pones, y yo lo he escrito todo seguido, sin ningun intro, pues me lo pone como una frase y por eso me mete una barra de desplazamiento (supongo).






**NO SE COMO SEPARAR LOS PARRAFOS CON MAS DE UNA LINEA. EN EL EDITOR, ANTES DE ESTA FRASE LE HE METIDO 6 ESPACIOS Y NO ME LO SEPARA NAA!!!**

Ahora voy a poner una imagen. Ígual que con los links hay dos sistemas:
El prpimer sistema es _inline image link_. Pones el signo **!** y entre corchetes [ ] el nombre de la imagen o el texto que quieras (esto no aparecerá en el texto, sólo la imagen), y a continuación, **sin espacios** y entre paréntesis ( ) la url de la imagen.

![server and hosting](http://www.shipshapeit.com/Libraries/Shipshape_Images/Server_And_App_Hosting_Diagram.sflb.ashx)

El segundo sistema es por referencia, _reference image_, igual que con los links.
[reference image][referencia]
dkdcwcwjokcmd le añado este texto y tampoco va, me añade una imagen otra vez. Ahora sí funciona. Hay que poner el texto que saldrá
en el documento resaltado en azul, que enlaza a la imagen igual que con los links, o sea entre corchetes. No hay que poner el signo de exclamacion. Después también entre corchetes, el tag de referencia. **LUEGO HAY QUE PONER MÁS TEXTO, PORQUE SI NO, NO VA BIEN**, y luego ya,
entre corchetes la etiqueta de la referencia, los dos puntos: y el enlace a la imagen.

[referencia]: http://www.shipshapeit.com/Libraries/Shipshape_Images/Server_And_App_Hosting_Diagram.sflb.ashx

pues no se xk no va...

**BLOCKQUOTES**

> Sirven para hacer resaltar un texto dandole un formato especial a un párrafo. Se consigue añadiendo el signo > al principio del
párrafo que queremos resaltar. Hasta aquí es un párrafo.

Esto ya es otro párrafo sin resaltar.

Se puede incluir en el blockquote todos los párrafos que se quiera; basta con poner el signo > al principio de cada párrafo y en todos los espacios intermedios. Voy a meter en un blockquote los párrafos que tratan cómo incluir un enlace en un texto.

**SOFTBREAK**

Si quiero poner frases cortas  
que salgan en líneas separadas  
pero formando un bloque  
he de escribir la frase  
y escribir dos espacios  
antes de darle al intro  
para escribir la misma frase.

Ahora escribiré lo mismo de antes pero sin poner dos espacios antes del intro:

Si quiero poner frases cortas
que salgan en líneas separadas
pero formando un bloque
he de escribir la frase
y escribir dos espacios
antes de darle al intro
para escribir la misma frase.
  

## GitHub Flavored Markdown : GFM

GitHub.com utiliza su propia version de Markdown syntax, GFM

  
**USERNAME** no sé qué es


**ISSUE REFERENCES** tampoco



**FENCED CODE BLOCKS**

Sirve para meter bloques de código en una ventana. Hay que escribir tres **\`** (accent greu) al principio y tres al final. 
Si se pone el nombre del código las palabras reservadas se resaltarán en otro color.

EJEMPLO EN JAVASCRIPT

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

EJEMPLO EN CSS

```css
body {
    background-color: lightblue;
}
h1 {
    color: white;
    text-align: center;
}
p {
    font-family: verdana;
    font-size: 20px;
} 
```

  

**TASKS LISTS**

Listas superchulas con un cuadradito marcado o sin marcar

- [x] Crea a ma amb notepad o equivalent un PS, RTF, XML i HTML (si pots amb un CSS que funcioni amb rawgit).
- [x] Fes una compte a github, edita README.md i puja tots els exemples de fitxers anteriors.
- [ ] Entrega la url del teu repositori de github.

Se consiguen poniendo un guión **-** un espacio y dos corchetes [x] o [ ] según si la tarea está o no hecha.

  

**TABLES**

Si escribo esto:  

LUNES \| MARTES \| MIÉRCOLES  
----- \| ------ \| ---------  
Bases de dades \| Entorns de desenvolupament \| FOL  
Sistemes informàtics \| Programació \| Llenguatge de marques

Saldrá esto:

LUNES | MARTES | MIÉRCOLES
----- | ------ | ---------
Bases de dades | Entorns de desenvolupament | FOL
Sistemes informàtics | Programació | Llenguatge de marques

  

**TACHAR TEXTO**

No sé si sólo sirve en GitHub o es un standar Markdown.   
Ejemplo: **\<del>lo que queremos tachar\</del>**  
Y quedará así:  
<del>lo que queremos tachar</del>

  

Y PARA ACABAR, LOS **EMOJIS**  
Hay que poner **:** luego el nombre del emoji \(los encontraremos [aquí](https://www.webpagefx.com/tools/emoji-cheat-sheet/)\) y otra vez **:**.

:rocket: :metal: :blush:


  
