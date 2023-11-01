Debemos entender la estructura con la que esta compuesta los formularios

Si usamos bootstrap, recordad que los formularios se hacen con grillas (o grid de 12)
es por ello que tenemos que tener en cuenta usar un div padre con la clase ROW 
y los div hijos que tendran la clase col-# 
tenemos que crear un input que contenga los soguiente elementes dentro de su tag
1. type o tipo de datos para el input
2. class"form-control"
3. Id "con el nombre que lo quieras identificar"
4. placeholder "para la frase que quieras que aparezca en el recuadro"
5. escribir "required"

ahora para que este input tenga funcionalidad hay que llamarlo con un Label
los elementos dentro dellabel son los siguientes: 

1. for "el Id colocado en el input que queremos llamar
2.  class="form-label" 
3. agregamos el nombre que tendra nuestra casilla

Para los checkbox usamos la siguiente estructura, creamos un div.form-check y: 
1. usar input y agregar el type "checkbox"
2. class "form-check-input"
3. Id = nombre de identificacion
Usar un label:
1. for = "checkbox"
2. class="form-check-label"
3. escribir el nombre que tendra el checkbox

Para poder tener una mayor funcionalidad se agrega un boton de submit: 
1. estasblece un col-# para el boton
2. crear un tag Button type="submit" class="btn btn-primary"
3. Pon nombre del boton

Si queremos crear mensajes de validacion para los campos de nuestro formulario
1. justo debajo del input y el label crea un div.valid-feedback, dentro escribe el mensaje
    que debe aparecer en caso de valido 
2. crea otro div.invalid-feedback debajo del anterior y escribe el mensaje que debe aparecer 
    en caso de ser invalido 
3.  busca en Bootstrap: validation y copia el Javascript fuera del div padre y dentro del body

