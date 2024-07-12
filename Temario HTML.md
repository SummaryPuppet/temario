1. Introducción a HTML ✔️
	1. ¿Qué es HTML?  ✔️
	2. Estructura básica de html
		1. Etiquetas ✔️
			- Etiqueta de apertura
			- Etiqueta de cierre
		2. Atributos ✔️
			- Atributos booleanos 
2. Etiquetas y Estructura básica ✔️
	1. Etiquetas esenciales 
		- `<!DOCTYPE html>` No es una etiqueta es una declaración al navegador que versión de HTML o XML estas usando ✔️
		- `<html>` Representa el elemento raíz del de un documento HTML todos los demás elementos descienden de este ✔️
		- `<head>` Provee información general (metadatos) acerca del documento, incluyendo su título y enlaces a scripts y hojas de estilos ✔️
		- `<title>` Define el título del documento que se muestra en un navegador la barra de título o la pestaña de una página. ✔️
		- `<body>` Representa el contenido de un documento HTML. Solo puede haber uno en el texto ✔️
	2. Metadatos `<meta>` Sirve para aportar información en el documento ✔️
	3. Encabezados: `<h1>` a `<h6>`
	4. Parrafos: `<p>`
3. Texto y formato ✔️
	1. Etiquetas de texto ✔️
		- `<strong>` Enfatiza las partes más especiales de un texto (El navegador lo vueve negrita) 
		- `<em>` Enfatiza las partes más especiales de un texto (El navegador lo vuelve italica)
		- `<small>` Hace el texto una talla más pequeña
		- `<mark>` Resalta el texto como con un resaltador
		- `<del>` Marca las partes de un texto que fueron suprimidas o sustituidas (Las tacha) 
		- `<ins>` Marca las partes de un texto que fueron añadidas (El navegador las subraya)
	2. Listas ✔️
		- `<ul>` Indica que es una lista desordenada
		- `<ol>` Indica que es una lista ordenada
		- `<li>` Es un item de la lista
	3. Citas y referencias ✔️
		- `<blockquote>` Son para citas en bloque 
		- `<q>` Son para citas breves 
		- `<cite>` Marca una referencia a una fuente o el autor de un texto citado
		- `<abbr>` Es para meter abreviaturas con el atributo tittle para ponerlo completo
4. Enlaces e Imágenes ✔️
	1. Enlaces: `<a>`  
		- `href`
		- `target`
	2. imágenes : 
		1. `<img>`
			- `src`
			- `alt`
		2. `<figure>`
5. Tablas ✔️
	1. Estructura de tablas 
		-  `<thead>`
		- `<table>`
		- `<tr>`
		- `<tbody>`
		- `<td>`
	3. Atributos de las tablas
		- `colspan` para que un elemento abarque más de una columna  
		- `rowspan` para que un elemento abarque más de una fila
	4. `<caption>` Es el encargado de darle un título descriptivo a las tablas
6. Formularios
	1. Elementos básicos
		- `<form>` Representa una sección de un documento que contiene controles interactivos que permiten a un usuario enviar información a un servidor web.
		- `<input>` Se usa para crear controles interactivos para formularios basados en la web con el fin de recibir datos del usuario
		- `<textarea>` Representa un control para la edición multilínea de texto sin formato
		- `<button>` Representa un elemento cliqueable de tipo botón que puede ser utilizado en formularios o en cualquier parte de la página que necesite un botón estándar y simple de aplicar.
	2. Etiquetas y agrupación
		- `<label>` Representa una etiqueta para un elemento en una interfaz de usuario. Este puede estar asociado con un input ya sea mediante la utilizacion del atributo for, o ubicando el input dentro del elemento label.
		- `<fieldset>` Permite organizar los campos de un formulario
		- `<legend>` Le da un titulo al fieldset
	3. Tipos de input
		- `text`
		- `password`
		- `email`
		- `number`
		- `radio`
		- `checkbox`
		- `file`
		- `submit`
	4. Selectores
		- `<select>`
		- `<option>`
		- `<optgroup>`
7. Elementos semánticos
	1. Estructura del documento
		- `<header>` Representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, así como también un logo, un formulario de búsqueda, un nombre de autor y otros componentes.
		- `<nav>` Representa una sección de una página cuyo propósito es proporcionar enlaces de navegación, ya sea dentro del documento actual o a otros documentos.
		- `<main>` Representa el contenido principal del `<body>` de un documento o aplicación. No debe haber más de un elemento `<main>` en el documento y no debe ser descendiente de cualquiera de esta lista.
		- `<footer>` Representa un pie de página. Un pie de página típicamente contiene información acerca de el autor de la sección, datos de derechos de autor o enlaces a documentos relacionados.
		- `<section>` Representa una sección genérica independiente de un documento, que no tiene un elemento semántico más específico para representarla. Las secciones siempre deben tener un título, con muy pocas excepciones.
		- `<article>` Representa una composición auto-contenida en un documento, una página, una aplicación o en un sitio, que se quiere que sea distribuíble y/o reutilizable de manera independiente, por ejemplo, en la redifusión. Algunos ejemplos podrían ser un mensaje en un foro, un artículo de una revista o un periódico, una entrada de blog, el comentario de un usuario, un widget o gadget interactivo, o cualquier otro elemento de contenido independiente.
		- `<aside>` Representa una sección de una página que consiste en contenido que está indirectamente relacionado con el contenido principal del documento. Estas secciones son a menudo representadas como barras laterales o como inserciones y contienen una explicación al margen como una definición de glosario, elementos relacionados indirectamente, como publicidad, la biografía del autor, o en aplicaciones web, la información de perfil o enlaces a blogs relacionados.
	2. Otros elementos
		- `<figure>` Representa contenido independiente, a menudo con un título. Si bien se relaciona con el flujo principal, su posición es independiente de éste. Por lo general, se trata de una imagen, una ilustración, un diagrama, un fragmento de código, o un esquema al que se hace referencia en el texto principal, pero que se puede mover a otra página o a un apéndice sin que afecte al flujo principal.
		- `<figcaption>` Representa un subtítulo o leyenda asociado al contenido del elemento padre `<figure>`
		- `<time>` Representa un periodo específico en el tiempo. Puede incluir el atributo `datetime` para convertir las fechas en un formato interno legible por un ordenador, permitiendo mejores resultados en los motores de búsqueda o características personalizadas como recordatorios.
		- `<address>` aporta información de contacto para su `<article>` más cercano o ancestro `<body>` en el último caso lo aplica a todo el documento.
8. Multimedia
	1. Audio `<audio>`
		- `src`
		- `controls`
	2. Video `<video>`
		- `src`
		- `controls`
		- `poster`
9. Iframes
	1. `<iframes>`
		- `src`
		- `width`
		- `height`
		- `frameborder`
10. Accesibilidad
	1. Atributos ARIA
11.  Proyectos