
# PROGRAMACIÓN BÁSICA
* HTML : 
NO es un lengaje de programacion.
    * archivo
    * contenido del documento
    * estructurar la información 
    * Información organizada

* CSS : 
Diseño del documento o información.

* JavaScript : 
Interactividad, interactuar con la infroamción.

#### Nota: JavaScript != Java

### Navegador

*  alert("mensaje");
* var: variable en JavaScript
*       var X = 10;
        alert(" El valor de X es " + X);

## HTML CSS JavaScript
Algunas etiquetas basicas son:

        <etiqueta> contenido </etiqueta>
        <> 
        <html>  </html>
        <head> aquí colocamos los estilos </head>
        <tittle> Titulo de mi Página </tittle>
        <body> cuerpo de mi documento </body>
        <strong> Negrita <strong>
        <p> etiqeuta de Parrafo </p>

Ejemplo de Estilo. 

        <style>
        body {
            background-color: blue; // fondo //
            color: White; // color de las letras //
            font-family: Helvetica; // tipo de letra //
        }
        </style>

Aplicando JavaScript : JavaScript debe ejecutarse justo despues que los elementos visuales estén en pantalla, por esa razón vamos a hacerlo antes de que el <Body> termine.

        <body>
            <p> Seguimos en el <strong> proceso </strong> </p>
            <p> segundo parrafo </p>
            <script>

                alert("mensaje con alert");
                document.write("mensaje con alerta");

                var X = 1;
                documet.write(" El valor de X es " + X);

            </script>


# PESO EN OTRO PLANETA

Gravedad Marte = 3.7
Gravedad Tierra = 9.8 m/seg 2
peso = 60 kg
marte (peso * 3.7) / 9.8

        variable = parseInt(variable); // convierte textos o numeros flotantes a numeros enteros//

        var usuario = prompt("cual es tu peso?") // almacena valores que el mismo usuario digita //


# FLUJO Y CONDICIONES

* En JavaScript 
        * un = es para asignar
        * el == es para comparar
        