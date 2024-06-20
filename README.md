# Integradora-Practica02

<p align="justify">En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de Versiones, Documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la asignatura de Integradora I. </p>

## Comandos Básicos para la Documentación, utilizando el estándar de Markdown (md)
<p align="justify">Markdown es el estándar utilizado por Git y GitHub, para maquetar la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.</p>

### 1. Encabezados o Títulos (HEADERS) 
<p align="justify">Para poder realizar una buena documentación del proyecto debemos, distribuir correctamente los contenido, para poder delimitar o hacer énfasis (enfatizar) , es decir resaltar las secciones importantes, podemos utilizar los siguiente: </p>

**EJEMPLOS:**

# Encabezado de Nivel 1 - Similar a H1 en HTML 
## Encabezado de Nivel 2 - Similar a H2 en HTML 
### Encabezado de Nivel 3 - Similar a H3 en HTML 
#### Encabezado de Nivel 4 - Similar a H4 en HTML 
##### Encabezado de Nivel 5 - Similar a H5 en HTML 
###### Encabezado de Nivel 6 - Similar a H6 en HTML 
####### Encabezado de Nivel 7 - Solo 6 son los niveles permitidos, a partir de este el maquetado será ignorado.

### 2. Separadores (SEPARATORS)
<p align="justify">Si desea marcar una separación más visual de contenidos pordemos utilizarlos indicando tres caracteres de "-" continuos, en el maquetado.</p>

**EJEMPLO:** 

Texto sección
---
Después del separador. 



### 3. Párrafos (PARAGRPAHS)
<p align="justify">Son utilizados para por presentar grandes secciones de texto que describen detalladamente las secciones de la documentación del proyecto.</p>

**EJEMPLO:**

Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1.

Este texto pertenece al párrafo 2  Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2

Lo que en una página utilizariamos usando la etiqueta \<P>.

También podemos aplicar estilos básicos de alineación: 

Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto

<p align="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación   
</p>

<p align="center">
Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación Este  párrafo esta centrado usando la propiedad de alineación Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación 
</p>

<p align="justify">
Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación
</p>
 
### 4. Texto Enfatizado  (BOLD, ITALIC, BOLD/ITALIC)
 <p align="justify">Si el texto que deseamos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.</p>

##### Texto en Negrita (BOLD) 
Para poder poner el texto en negrita, este deberá ser encerrado entre dobles **

**EJEMPLO:**

Texto  Texto Texto Texto Texto Texto **Texto Importante**  Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto

##### Texto en Cursiva (ITALIC)
<p align="justify">Algunas veces es necesario resaltar algunas secciones o textos en cursiva para que el lector detecte el texto importante, dentro del maquetado con el estándar Markdown lo podemos realizar ubicando el texto entre  * (asteríscos).</p>

**EJEMPLO:**

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Negrita y Cursiva (BOLD & ITALIC)


De igual manera podemos unir ammbos estilos  **Negrita** y *Cursiva* para resaltar los textos que consideremos importantes dentro de la documentación de nuestros proyectos de software, utilizando un triple * (asterísco).

**EJEMPLO:**

Texto Texto Texto Texto Texto ***Texto en Negrita y Cursiva*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto


##### Subrayado (UNDERLINE)

Algunas veces necesitaremos subraya texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML  usando el tag \<ins> y cerrando con  \</ins>.

**EJEMPLO:**

Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto Subrayado</ins> Texto.

### 5.Cuadros Para Código o Reseñas(BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración  y/o innicializacion o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que(>)

**EJEMPLO:**
Para instalar carpetas y archivos en desde una terminal de istema operativo Windows debemos ingresar el comando
>c:/dir
Después oprimimos la tecla "Enter".

También podemos ingresar textos multilínea 
**EJEMPLO:**
>Aquí se ingresan un conjunto de instrucciones 
>para explicar al usuario, como instalar el software que hemos diseñado 
Y si deseamos incluir viñetas para enlistar pasos podemos usar el carácter 
dentro del texto o documentar. 


**EJEMPLO:**
>--Descargar MySQL server del sitio Oficial
>--Instalar el sistema gESTOR DE BASE  DE DATOS DEFENDIENDO EL PUERTO y contraseña para el usuario ***root***
Descargamos el archivo la base de datos usando el archivo 'MySQL'

### 6. Listas Ordenadas y Listas Desordenadas.

Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro. Podemos 
hacerlo utilizando los números con un punto decimal si las deseamos ordenadas  o un guion medio - si solo queremos una viñeta.

**EJEMPLO:**
Para crear tu primer repositorio en GitHub deberas:

1.Contar con cuenta de GitHub 

1.Dar click en el botón: "nuevo repositorio"

2.Asignarle un nombre a tu repositorio , por ejemplo: "practica03-3b"

8.Asignarle un nivel de privacidad entre:
    
-**publico:** si quieres que este disponible entre todos los usuarios.
   
-**privado:** si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto
   
5.Definir si incluye un archivo de descripción llamado : *README.MD*

50.  Definir si habrá exclusiones de archivo a través del archivo : *.gitignore*
 
3. Guardar los cambios

### 7. Ligas (Hipervinculos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el.Y se maquetan utilizando los corchetes \[\], inmediatamente después  pondremos la liga de referencia entre paréntesis()

***EJEMPLO:***
MI buscador favorito es [Google].(https://www.Google.com)

pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizar los símbolos \<\>

**EJEMPLO:**
Documentación creada por: **Antonio Ocpaco Dolores** 
<230642@utxicotepec.edu.mx> 
http://www.utxicotepec.edu.mx

#### 8. Tablas (Tables)

Si la documentacon lo requiere podemos presetar información en formato de tablas con filas y columnas, para maquetarlas podemos utilizar el carácter \(PIPEPIPE) para delifitar las columnas y \-para delimitar las filas.

**EJEMPLO:** 
| Encabezado 1 | encabezado 2 | Encabezado 3 | Encabezado 4|
|-----------------------------------------------------------|
|Fila 1 celda 1| Fila 1 celda 2| Fila 1 celda 3 | Fila 1 celda 4|
|Fila 2 celda 1| Fila 2 celda 2| Fila 2 celda 3 | Fila 2 celda 4|
|Fila 3 celda 1| Fila 3 celda 2| Fila 3 celda 3 | Fila 3 celda 4|

En caso de necesitar la función de celdas en columnas utlizaremos la propiedad "colpson" del tag \<td> y en el caso de necesitar la fusión de filas utlizaremos la propiedad

**EJEMPLO:**
| Encabezado 1 | Encabezado  2 |  Encabezado  3 | Encabezado  4 |
|--------------|---------------|----------------|---------------|
|Fila 1 celda 1| Fila 1 celda 2| Fila 1 celda 3 | Fila 1 celda 4|
|Fila 2 celda 1<td> colspon=2  | Fila 2 celda 2| Fila 2 celda 3 | Fila 2 celda 4|
|Fila 3 celda 1| Fila 3 celda 2| Fila 3 celda 3 | Fila 3 celda 4|
|              | Fila 4 celda 2| Fila 4 celda 3 | Fila 4 celda 4|
|              | Fila 5 celda 2| Fila 5 celda 3 | Fila 5 celda 4|
|Fila 5 celda 1| Fila 6 celda 2| Fila 6 celda 3 | Fila 6 celda 4|

Dado que el ejemplo pasado usando markdown no se puede realizar la fusión de filas debemos utilizar el estándar de HTML, usando los tags: \<th> para los encabezados, \<tr> para las filas y \<td> para las celdas, y en ellos poder utilizar la propiedad de "colspan" y "rowspan".
 
**EJEMPLO:**

<table>
<tr>
<th>Encabezado1</th>
<th>Encabezado2</th>
<th>Encabezado3</th>
</tr>

<tr>
<td>Fila 1 encabezado celda 1 </td>
<td>Fila 1 encabezado celda 2 </td>
<td>Fila 1 encabezado celda 3 </td>
<td>Fila 1 encabezado celda 4 </td>
</tr>

<tr>
<tr> Fila 2 celda 1</td>
<td colspan=3 align="center"> Fila 2 celda 2</td>
</tr>

<tr>
<td rowspan=3>Fila 3 celda 1</td>
<td> Fila 3 celda 2</td>
<td> Fila 3 celda 3</td>
<td> Fila 3 celda 4</td> 
</tr>

<tr>
<td>Fila 4 celda 2</td>
<td>Fila 4 celda 3</td>
<td>Fila 4 celda 4</td>
</tr>

<tr>
<td>Fila 5 celda 2</td>
<td>Fila 5 celda 3</td>
<td>Fila 5 celda 4</td>
</tr>

<tr>
<td>Fila 6 celda 1</td>
<td>Fila 6 celda 2</td>
<td>Fila 6 celda 3</td>
<td>Fila 6 celda 4</td>
</tr>

</table>


#### 9. Imágenes
comming(Bajo el apartado 8 se incorpora nueva información con el nombre de "Imagenes".)

Si la documentación requiere de implementar imágenes, esquemas, modelos, fotografías, o cualquier representación grafica utilizaremos la estructura de la liga maquetando el nombre de la imagen entre corchetes con un signo de admiración de cierre y la liga de referencia a la imagen usando paréntesis.

**EJEMPLO:**







