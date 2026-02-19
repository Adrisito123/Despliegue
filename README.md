1. Administración del Servidor

Software: XAMPP con FileZilla Server.

Protocolo: SFTP (puerto 22 de SSH) para garantizar el cifrado en el movimiento de activos.

Usuarios: Se han creado los usuarios dev_junior (permisos limitados) y dev_senior (permisos totales) para evitar el uso de la cuenta de administrador.

2. Infraestructura de Red

DNS Local: Se ha utilizado el archivo de hosts para simular un entorno virtualizado.

Dominios: El proyecto responde a frontend.test, backend.test y db.test.


Ruta del archivo: C:\Windows\System32\drivers\etc\hosts.

3. Control de Versiones

Herramienta: Git.

Metodología: Despliegue basado en commits, no en archivos sueltos.


Ramas: Se utilizó la rama fix-styles para cambios de CSS y se fusionó con la rama principal.

4. Requisitos del Sistema

Servidor Web: Apache (XAMPP).
