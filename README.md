# Pruebas de un formulario GET
Pruebas destinadas a probar que la codificación "application/x-www-form-urlencoded" usa el signo "+" para los espacios en blanco en vez de un %20 como en las URLs.

# Pregunta
Al enviar un formulario mediante el método GET a la URL https://miweb.es/ con un campo de nombre "mensaje" y valor "hola a todos", la URL generada por el navegador será:

1. `https://miweb.es/?mensaje=hola a todos`
1. `https://miweb.es/?mensaje=hola+a+todos`
1. `https://miweb.es/?mensaje=hola_a_todos`
1. `https://miweb.es/?mensaje=hola%20a%20todos`