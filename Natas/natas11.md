# Natas Nivel 11

*URL:* http://natas11.natas.labs.overthewire.org

*Usuario:* natas11

*Solución:* se encontró la contraseña partiendo de la cookie llamada “data” que contenía una cadena codificada usando una función de cifrado XOR. Entonces se decodifico la cookie  de base64 a bytes, luego se aplicó la operación XOR  entre la cookie decodificada y el dato original en formato json: "showpassword"=>"no", "bgcolor"=>"#ffffff". Con la clave obtenida se genero una nueva cookie modificando el json de “no” a “si”, por ultimo remplazar la cookie anterior por la modificada.

*Contraseña:* yZdkjAYZRd3R7tq7T5kXMjMJlOIkzDeB
