# Discord-Redirect-CloudFlare-or-Website

Ejemplo usando website: [Click Here](https://github.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/blob/master/index.html)

Explanation in orthers langs:


| Idioma | Link | Autor |
| --- | --- | --- |
| EN | [Click Aquí](https://github.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/blob/master/README.md) | [@Happyuky7](https://github.com/Happyuky7) |
| ES | [Click Aquí](https://github.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_ES.md) | [@Happyuky7](https://github.com/Happyuky7) |
| DE | [Click Aquí](https://github.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_DE.md) | [@InfoBlock](https://github.com/InfoBlock) |
| JP | [Click Aquí](https://github.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_JP.md) | [@Happyuky7](https://github.com/Happyuky7) |

---

A mi me funciona gracias tutorial completo por si alguien lo ha entendido.

**Esto es para CloudFlare**

Crear Add Record "A"

Este tipo "A" debe contener en Nombre: "Nombre que desea para el subdominio", y en dirección IPv4 deben colocar "8.8.8.8", estado Proxy activado.


<img src="https://raw.githubusercontent.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/master/5YtzR.png" alt="discord"/>


Luego van a "Rules"

Aquí añaden una Crear una nueva regla, y colocan los siguientes datos en URL: "yoursubdomanin.yourdomain.com", luengo en Luego la configuración es: Seleccionar "Forwarding URL", luego en Seleccionar código de estado: Seleccione "301 - Permanent Redirect"

en Introducir URL de destino (obligatorio) pones la url de la invitación de Discord: "https://discord.gg/tuCodigodeInvitacion".

<img src="https://raw.githubusercontent.com/Happyuky7/Discord-Redirect-CloudFlare-or-Website/master/oBufr.png" alt="discord"/>

Así funciona, en caso de que no te cargue porque ya has probado muchos métodos con "discord.yourdomain.com", prueba con otro subdominio mientras se reactiva el otro o prueba desde otro dispositivo, ejemplo de otro dominio dub "discord1.yourdomain.com".

**Eso es adiós :D**
