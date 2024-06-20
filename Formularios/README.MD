Etiqueta Form

input
textarea
select
option
optgroput
label-> crea un titulo para el elemento del form que va relacionado con el id o el name
button->ejecuta una accion en el formulario (Enviar data) Es importante especficar el type
<<<<<<<<<<<<>>>>>>>>>>>>
fielset: agrupa elementos similares
legend: agrega un titulo al fieldset si no tiene css siempre se va a ver
datalist-> usa option predefinidas listas desplegables es distinto a <select>
output -> contenedor que muestra la salida del form

los atributos de etiqueta <form></form> son opcionales
metodo por defecto es GET -> es incluida como parametro en la URL
POST-> mas recomendable por que no se ve en la URL

Dialog -> Mas reciente para mostrar un popup que muestra el mensaje de confirmacion

Baseline para saber si las propiedades son soportadas en los navehadores la documentacion

novalidate-> omite las validaciones

Es importante declarar el metodo de accion

Trabajando con distintos controles

imput
cajas de texto
botones de radio

Controles de tipo de entrada
text
button
checkbox
colorpiker
fecha
datetime
email
image
hidden
file-> Se le debe indicar que tipo de archivo se puede subir con el atributo accept
password --->Enmascara el contenido
mont
number
search->solo busqueda

<input type="text" >//Si no se especificia el tipo por default es texto
Solo es la etiqueta input

name -> Se usa para dar el nombre al control
value -> provee un valor inicial

<textarea> campo de texto multiliena
<select> tiene <option> que se pueden agrupar en <optgroup> por ejemplo mamiferos es una buena practica ponerles un label

botones de radio y cajas de chequeo
el label debe tener el for anidado con el input que puede ser name o id
