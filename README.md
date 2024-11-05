# Talento Tech Caribe

## Actividad 1 Sesion 13
Paginba web personal, se podría tomar como principio de portafolio.
### Directrices de la actividad
1. Pagina web simple es decir, estatica:
    - Un encabezado con tu nombre.
    - Una sección para una breve infografía.
    - Una lista de habilidades tecnicas, pila tecnológica.
    - Un pie de página con tus datos de contacto 
2. usar hojas de estilo:
    - Utilizar colores y fuentes personalizadas 
    - Crear un layout sencillo utilizando Flexbox
    - Estiliza los enlaces y botones
3. interactividad con javascript:
    - Un boton que muestre un mensjae de bienvenida cuando se haga clic.
    - Validación de un formulario de contacto.

#### Codigo fuente de validación:

```js
//validacion de formulario
const form = document.getElementById('contactForm');

form.addEventListener('submit', funtion(event)){
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;

    if(name === " || email === "){
        alert('Porfavor, complete todos los campos');
        event.preventDefault();

    }else{
        alert('¡Formulario complketado correctamente! Pronto me comunicaré con usted.')

    }
}
```

