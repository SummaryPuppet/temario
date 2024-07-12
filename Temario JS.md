1. Introducción a JS
	1. ¿Qué es JavaScript?
	2. Cómo incluir JavaScript en HTML (etiqueta `<script>`).
	3. En donde se usa JS?
		- Web (Apps webs, paginas staticas)
			- [Reactjs](https://react.dev/)
			- [Angular](https://angular.dev/)
			- [Vue](https://vuejs.org/)
			- [Astro](https://astro.build/)
		- Sonido
			- [Tonejs](https://tonejs.github.io/)
			- [Howler js](https://howlerjs.com/)
		- Videojuegos
			- [Phaser](https://phaser.io/)
			- [Babylonjs](https://www.babylonjs.com/)
		- Presentacion tipo powerpoint
			- [slides](https://slides.com/)
			- [revealjs](https://revealjs.com/)
		- Reenderizado 3D 
			- con WEBGL
			- con threejs [threejs](https://threejs.org/)
		- Inteligencia Artificial
			- [Tensorflowjs](https://www.tensorflow.org/js)
		- Webscrapping
		- Servidor
			- [Nodejs](https://nodejs.org/en)
			- [Express](https://expressjs.com/)
			- [Koa](https://koajs.com/)
			- [Nestjs](https://nestjs.com/)
		- Movil
			- [Ionic](https://ionicframework.com/)
			- [React Native](https://reactnative.dev/)
		- Desktop
			- [Electronjs](https://www.electronjs.org/)
			- [Tauri](https://tauri.app/)
			- [NodeGUI](https://docs.nodegui.org/)
		- Arduino 
			- [Johnny-Five](https://johnny-five.io/)
		- CLI
			- [Commander](https://www.npmjs.com/package/commander)
			- [Inquirer](https://www.npmjs.com/package/inquirer)
1. Fundamentos de JavaScript
	1. Sintaxis basica
	2. Variables 
		- `var`
		- `let`
		- `const`
	3. Tipos de datos 
		- números
		- cadenas
		- booleanos
		- `null`
		- `undefined`
		- `NaN`
2. Operadores
	1. Operadores aritméticos 
	2. Operadores de asignación
	3. Operacion de comparación
	4. Operadores lógicos
3. Estructuras de Control
	1. Condicionales 
		- `if`
		- `else`
		- `else if`
		- `switch`
	2. Bucles
		- `for`
		- `while`
		- `do while`
4. Funciones
	1. Funciones conocidas
		```js
		alert()
		prompt()
		parseInt()
		```
	2. Declaracion de funciones 
	3. Funciones flecha
	4. Parametros y valores de retorno
6. Eventos y DOM
	1. Selección de elementos
		- `document.getElementById`
		- `document.querySelector`
	2. Manipulación del DOM (cambiar contenido, estilos)
		1. Cambiando contenido
			- `textContent`
			- `innerText`
			- `innerHTML`
		2. `style`
	3. Manejando eventos 
		- `onclick`
		- `addEventListener`
7. Arrays
	1. Creacion y manipulacion de arrays
	2. Métodos de arrays
		- `push`
		- `pop`
		- `shift`
		- `unshift`
		- `forEach`
		- `map`
8. Objetos
	1. Creacion y manipulacion de objetos
9. Programacion orientada a objetos (POO)
	1.  Conceptos basicos de POO
		1. Clase (Receta, Fabrica)
		2. Objeto
		3. Atributos
		4. Metodos
		5. Constructor
		6. Instanciacion
	2. Herencia
	3. Encapsulamiento
10. Consola
	- `console.log()` muestra un mensaje en la consola
	- `console.clear()` limpia la consola
	- `console.error()` muestra un mensaje de error
	- `console.info()` muestra un mensaje info
	- `console.table()` el primer parametro es obligatorio tiene que ser un array o un objeto
	- `console.warn()` muestra un mensaje de advertencia en la consola
	- funciones de tiempo
		- `console.time()` inicia un temporizador
		- `console.timeEnd()` termina un temporizador
	- funciones de agrupacion
		- `console.group()` Crea un nuevo grupo en linea en el registro de la consola web
		- `console.groupEnd()` Remueve un grupo en linea en el registro de la consola web
		- `console.groupCollapsed()` Crea un grupo en linea, pero contraido el usuario debe ser el que lo abra.
11. Asincronia
	1. Callbacks
		1. Funciones de orden superior.
	2. Promises 
		1. Creacion y uso de promesas
		2. Métodos
			1. `then`
			2. `catch`
			3. `finally`
	3. Async/Await
		1. Funciones asincronas
		2. Manejo de errores con `try`/`catch`.
12. Manipulación del DOM Avanzado
	1. Creación y eliminación de elementos
		- `createElement`
		- `appendChild`
		- `removeChild`
	2. Clonación de nodos
		1. `cloneNode`
13. Trabajando con APIs
	1. Fetch API 
		- Realizar solicitudes GET y POST.
		- Manejo de respuestas
	2. JSON
		1. Parseo y serialización
			1. `JSON.parse`
			2. `JSON.stringify`
14. Proyectos
	1. To-Do List 
	2. Calculadora
	3. Rick and Morty API [documentación](https://rickandmortyapi.com/documentation)