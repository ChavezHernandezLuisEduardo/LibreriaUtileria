# LibreriaUtileria.js
Actividad 2  de la materia de Programacion Web donde Realizamos una actividad de crear nuestra propia libreria en js para posteriormente utilizarla
Instituto Tecnologico de Oaxaca
Chavez Hernandez Luis Eduardo
Actividad 2 Utileria.js
Profesora Martinez Nieto Adelina

Utileria.js es una libreria de Javascript que incluye las validaciones y herramientas iniciales basicas y escenciales para la realizacion de formularios web en html.
Especificamente en la validacion de campos y valores que comunmente pueden necesitar de verificaciones para poder hacer uso correctamente de los datos que sean introducidos en los input, como por ejemplo validacion de edad, texto, numeros, longitud.

El problema que resuelve, es poder definir una libreria con las funciones establecidas listas y flexibles ante todo tipo de necesidad relacionada con la validacion de estos datos para formularios como lo son logins, o registros sign up, asi facilitando y agilizando la forma en la que se desarrolla el codigo para estas tareas.


Instialacion >>>>>>
Para la instalacion de esta libreria solo es necesario descargar el archivo utileria.js
>>posteriormente introducir en la carpeta destinada a scripts, y ser enlazado en los archivos html con ayuda de la etiqueta
>> <script src="js/utileria.js"></script>


USO
1. `validarCorreo(correo)`
Revisa que el correo tenga el formato `algo@dominio.extensdominio`.

```javascript
validarCorreo("hola@mail.com");   // true
validarCorreo("hola@gmail");       // false
```

2. `soloLetras(texto)`
Revisa que el texto tenga solo letras y espacios (acepta acentos y ñ).

```javascript
soloLetras("Jose");   // true
soloLetras("Maria12345");     // false
```

 3. `validarLongitud(numero, maxLongitud)`
Revisa que un número no pase de cierta cantidad de dígitos.

```javascript
validarLongitud("76521", 5);   // true
validarLongitud("765432199", 9); // false
```

4. `calcularEdad(fechaNacimiento)`
Calcula la edad exacta a partir de una fecha de nacimiento.

```javascript
calcularEdad("2000-08-10");   // ejemplo: 26
```

 5. `esMayorDeEdad(fechaNacimiento)`
Regresa `true` si la persona ya tiene 18 años o más.

```javascript
esMayorDeEdad("2000-05-10");   // true
esMayorDeEdad("2015-05-10");   // false
```

6. `validarPassword(password)`
Revisa que la contraseña tenga mayúscula, minúscula, número, carácter especial y mínimo 8 caracteres.

```javascript
validarPassword("Hola123!");    // true
validarPassword("hola123");     // false
```

 7. `limpiarEspacios(texto)` 
Quita los espacios de más al inicio, al final, y entre palabras.

```javascript
limpiarEspacios("   Luis    Jose   ");   // "Maria Jose"
```
 8. `generarPasswordFuerte(longitud)` 
Genera una contraseña segura al azar, con mayúscula, minúscula, número y carácter especial estableciendo la longitud.

```javascript
generarPasswordFuerte(12);   // ejemplo: "aB3!fT9kLp#Q"
```
<img width="314" height="531" alt="image" src="https://github.com/user-attachments/assets/21f26250-0241-45a4-831f-71832b1f5ece" />

PRUEBAS DE IMPLEMENTACION
IMPLEMENTACION EN Inputs de datos
<img width="1345" height="679" alt="image" src="https://github.com/user-attachments/assets/a6f45235-647c-4fef-bf65-089de34ce618" />
Implementacion en un registro login
<img width="1353" height="687" alt="image" src="https://github.com/user-attachments/assets/54de4333-7fb0-4b83-80b2-8d7de65aff54" />



https://github.com/user-attachments/assets/7fd1e8a2-5a49-471b-8bb2-1623f28cde3e



