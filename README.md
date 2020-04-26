# billetera-offline.com
Generador de cartera Bitcoin del lado del cliente de JavaScript

Ahora las direcciones Bitcoin y su clave privada correspondiente pueden ser convenientemente
generado sin cargo en un navegador web.

El proyecto billetera-offline.com proporciona un documento HTML todo en uno con
JavaScript/Css/Images. El JavaScript es legible no minimizado y no contiene
XMLHttpRequest (sin AJAX). El beneficio de esta técnica es que puede cargar el
JavaScript localmente y confiar en que el JavaScript no cambió después de ser
Cargado.

Por favor envíe donaciones para este proyecto a la dirección bitcoin: 
12ksUF4SwiHzzvwWaPJ6oiegd6atSL4ux4


NOTAS DEL USUARIO FINAL:

1) Para direcciones en masa usar Google Chrome, es el más rápido.

2) Requiere IE9+, Firefox, Chrome o suficiente soporte JavaScript.

3) Mobile Safari solo funciona con iPhone4 o dispositivos más recientes.
Los dispositivos más antiguos se agotarán mientras se ejecuta JavaScript.

4) NO utilice Opera Mini que representa el lado del servidor de salida JavaScript, por lo tanto
podrían grabar la clave privada que generó.

5) BIP38 muy probablemente no funcionará en dispositivos móviles debido a limitaciones de hardware.

Aviso de derechos de autor y licencias:
---------------------------------------
El proyecto billetera-offline.com, el software y los recursos integrados son propiedad de billetera-offline.com

El nombre y el logotipo de billetera-offline.com no forman parte de la licencia de código abierto.

Algunas partes del documento HTML todo en uno contienen códigos JavaScript que
son los derechos de autor de otros. Los derechos de autor individuales están incluidos
a lo largo del documento junto con sus licencias. JavaScript incluido
las bibliotecas se separan con etiquetas de script HTML.

Resumen de funciones JavaScript con una licencia redistribuible:

Funcion Javascript	|	Licencia
-------------------	|	--------------
Array.prototype.map	|	Public Domain
window.Crypto | BSD License
window.SecureRandom	| BSD License
window.EllipticCurve	|	BSD License
window.BigInteger |	BSD License
window.QRCode | MIT License
window.Bitcoin | MIT License

El software billetera-offline.com está disponible bajo la licencia MIT (MIT)
Copyright (c) 2011-2020 billetera-offline.com

Por la presente se concede permiso, de forma gratuita, a cualquier persona que obtenga
una copia de este software y los archivos de documentación asociados (el
"Software" "), para tratar el Software sin restricciones, incluyendo
sin limitación los derechos de uso, copia, modificación, fusión, publicación,
distribuir, sublicenciar y/o vender copias del Software, y para
personas a las que se proporciona el Software para hacerlo,
las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso serán
todas las copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTIA DE NINGUN TIPO,
EXPRESA O IMPLICITA, INCLUYENDO PERO NO LIMITADA A LAS GARANTIAS DE
COMERCIABILIDAD, IDONEIDAD PARA UN FIN PARTICULAR Y
NO INFRACCIóN. EN NINGÚN CASO LOS AUTORES O TITULARES DE DERECHOS DE AUTOR SE HARA
RESPONSABLE DE CUALQUIER RECLAMO, DAÑOS U OTRA RESPONSABILIDAD, YA SEA EN UNA ACCION
CONTRATO O DE OTRA MANERA, QUE SURJA DE, FUERA DE O EN RELACIONES
CON EL SOFTWARE O EL USO U OTROS TRATAMIENTOS EN EL SOFTWARE.

