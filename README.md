# Tutorial para el manejo de usuarios y contraseñas en una solución WebApi con Identity 2.1

#### Autor:
> Victor Cornejo , rex2002xp (at) gmail (dot) com

#### Licencia:
> Creative Commons

####Aclaración
* He tomado como referencia los excelentes artículos publicados por Taiseer Joudeh sobre el tema, la única intención es facilitar el acceso de esta información en el idioma Español. En ningún momento deseo acreditarme o plagiar el excelente trabajo que Taiseer realiza en su blog. Te invito a revisar su blog en [bitoftech.net] no te arrepentirás.

####Objetivo
Para esta solución he tomado como base el código fuente que se genero en el repositorio [AspNetIdentity2.1.WebApi] , de esta forma podemos reutilizarlo y ampliar las funcionalidades.

En esta ocasión cubriremos las siguientes funcionalidades:
* El envío de un correo electrónico para confirmar la creacion de la cuenta.
* Configurar el usuario (Username, Email) y aplicar políticas de seguridad a la contraseña.
* Activaremos la funcionalidad para cambio la contraseña y si el usuario desea eliminar su cuenta, también le proporcionaremos esa opción.


[AspNetIdentity2.1.WebApi]:https://github.com/rex2002xp/AspNetIdentity2.1.WebApi
[bitoftech.net]:http://bitoftech.net/