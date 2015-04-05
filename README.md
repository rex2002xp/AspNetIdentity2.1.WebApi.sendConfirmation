# Tutorial para el manejo de usuarios y contrase�as en una soluci�n WebApi con Identity 2.1

#### Autor:
> Victor Cornejo , rex2002xp (at) gmail (dot) com

#### Licencia:
> Creative Commons

####Aclaraci�n
* He tomado como referencia los excelentes art�culos publicados por Taiseer Joudeh sobre el tema, la �nica intenci�n es facilitar el acceso de esta informaci�n en el idioma Espa�ol. En ning�n momento deseo acreditarme o plagiar el excelente trabajo que Taiseer realiza en su blog. Te invito a revisar su blog en [bitoftech.net] no te arrepentir�s.

####Objetivo
Para esta soluci�n he tomado como base el c�digo fuente que se genero en el repositorio [AspNetIdentity2.1.WebApi] , de esta forma podemos reutilizarlo y ampliar las funcionalidades.

En esta ocasi�n cubriremos las siguientes funcionalidades:
* El env�o de un correo electr�nico para confirmar la creacion de la cuenta.
* Configurar el usuario (Username, Email) y aplicar pol�ticas de seguridad a la contrase�a.
* Activaremos la funcionalidad para cambio la contrase�a y si el usuario desea eliminar su cuenta, tambi�n le proporcionaremos esa opci�n.


[AspNetIdentity2.1.WebApi]:https://github.com/rex2002xp/AspNetIdentity2.1.WebApi
[bitoftech.net]:http://bitoftech.net/