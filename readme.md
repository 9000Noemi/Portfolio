<h1 align="center"> PRÁCTICA HTML Y CSS </h1>

### Creación de un portfolio con HTML y CSS

***

#### Clonar el repositorio:

Para clonar el repositorio y poder visualizar la práctica usamos el siguiente comando en la terminal  *Visual Studio Code*:
```
git clone https://github.com/9000Noemi/Portfolio
```

Una vez clonado, instalamos la extensión *Live Server* y, haciendo click derecho en el *archivo index.html* abrimos el portfolio.

***
#### Organización:

- En los archivos *index.html* y *obras.html* tenemos la estructura del portfolio.

- En la carpeta styles tenemos:

    1) El archivo normalize.css
    2) El archivo utils donde irán las variables y estilos de elementos comunes que usaremos en el proyecto.
    3) Una hoja de estilos CSS por cada sección de la web.

***
#### Estructura:

- **Header** con una barra de navegación con enlaces a cada elemento del portfolio. Todos los links tienen el estado hover suavizado con una transición. En la versión movil tenemos un menú hamburguesa.

- Una **sección** (llamada *aboutme*) con una descripción del personaje y sus habilidades como barras de progreso animadas con animaciones css.

- Un **banner** con imagen de fondo que es distinta para movil  y para pantallas más grandes, poniendo en práctica las *media querys*.

- Un **formulario** de contacto con los siguientes inputs y sus validaciones:
````
Nombre (campo requerido)
Apellidos (campo requerido)
Teléfono (campo requerido)
Unos radio inputs para responder a "¿Cómo me conociste?" (campo requerido)
Tag de GitHub (usar regexp ^@[^\s]+ para validación @username)
Mensaje con más información del usuario(textarea con máx 180 caracteres,campo requerido)
Checkbox de acceso a la newsletter
Botones de guardado y de reset
````

- Un **footer** con links a las redes sociales del personaje. Tener en cuenta que son links a recursos externos.

- Una nueva página con un **video** que se reproduzca al entrar en la web y aparezca con una animación fadeIn.

- Una nueva página con un **grid** con los proyectos.


#### Detalles de implementación

- El diseño debe ser responsivo y mobile first.

- Solo debe usarse html y css, no se puede usar JavaScript.

