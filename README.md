# Devhack-1

## Teoria

¿ Para que tipo de proyectos recomienda usar Angular(2+) ?

¿ Cuando se debe usar Componentes ? Defina un Componente en un .ts 

¿ Cuando se debe usar Directivas ? Defina una Directiva en un .ts

¿ Cuál es la diferencia entre un Componente y una Directiva ?

¿ Para que se utilizan los Servicios en Angular ? Defina un Servicio en un .ts

¿ Para que se utilizan los Pipes en Angular ? Defina un Pipe en un .ts

¿ Que es una Promesa ? Defina la estructura general de una promesa imprimendo en `console.log()` si hay respuesta existosa y en `console.error()` si no hay respuesta.

¿ Que es un Observable ? Defina un metodo que se llame `getInfo()` e imprima en consola el llamado a `https://fakeApi/fakeEndpoint` usando una Observable. 

¿Como funciona el sistema de enrutamiento en Angular ? Defina un enrutamiento `/dashboard` que llame al componente `dashboardComponent`, a `/users` que llame al componente `usersComponent` y por defecto en caso de que la ruta sea desconocida redirija a `/`

¿Qué es un Módulo y cual es la recomendación para su uso?

¿ En qué proyectos recomiendas utilizar Promesas y en cual Observables ?

¿ Conoces sobre el ciclo de vida de los Hooks?, ¿ Cuáles son los principales que recuerdes y el orden ?

¿ Conoce de Event Emitters?, ¿para qué los usó?

¿ Como funciona el Change Detection en Angular ?

¿ Que es Redux ?

¿ Has usado Redux con Angular, que librerias ?

¿ Que es JIT y AOT en Angular y cuando lo aplicas ?

## Practico

Debemos crear una aplicacion Web responsiva la cual nos permita conectarnos a la API de Rick & Morty `https://rickandmortyapi.com/`

### Requisitos

- Crear y obtener un Api key en `https://rickandmortyapi.com/`
- Utilizar Angular CLI.
- Utilizar tu libreria UI preferida (Bootstrap o Material) integrado correctamente en un proyecto de Angular.

### Tareas.

- Nuestro Website debe tener Home (/home), Lista de personajes (/characters), y detalle de personaje (/detail), en caso que no encuentre alguna URL debera enviar al /home.

- En el Home se va a mostrar 3 Imagenes aleatorias de los personajes y un boton de (Ver todos) - Mockup 1.

- En la lista de personajes se va a mostrar la lista en forma de Grid de todos los personajes, aca puedes usar un Infinite Scroll o un sistema de paginacion. - Mockup 2

- En el detalle deberas mostrar la imagen y la info del personaje elegido, en caso de no tener info puedes usar un [Loren Ipsum](https://lipsum.com/) - Mockup 3

### Adicionales

- A medida que vayas avanzando en la solucion realizar los commits en un repo privado en bitbucket.

- Cuando hayas terminado el ejercicio realizar un build para produccion y enviarlo a `firebase` con un `$ firebase deploy` o algun sistema parecido.

### Bonus Point (Opcionales).

- Agregar pruebas unitarias.
- Agregar un indicador de carga para los requests.
- Agregar lazy loading.
