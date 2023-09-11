# Informacion Franquicia-Brilla ⚡

## Descargas...
### Descarga KeyPass 🔐
Programa para administrar las contraseñas de:

+ VPN
+ Base de Datos
+ Repositorio

Link de Descarga ->  [KeyPass](https://keepass.info/download.html)

---

### Descarga VPN Client Azure 🔌
Vpn para conectar a la Base de Datos.
 
Link de Descarga -> [VPN](https://apps.microsoft.com/store/detail/cliente-vpn-de-azure/9NP355QT2SQB?hl=es-es&gl=es)

---

### Descarga IDE Intellij IDEA 👨🏻‍💻

Ide para progamar.

Link de Descarga -> [Intellij](https://www.jetbrains.com/idea/download/?section=mac)

---

### Descarga Gestor de Base de Datos 🗄️
Gestor para trabajar con la base de datos.

Link de Descarga -> [Sql Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms)

Link de Descarga (Opcional) -> [DBeaver](https://dbeaver.io/download/)

---

### Descarga GitBash 🗿
Consola para trabajar con Git.

Link de Descarga -> [Git](https://git-scm.com/downloads)

---

### Descarga SourceTree 📁
Programa para administrar el repositorio.

Link de Descarga -> [SourceTree](https://www.sourcetreeapp.com)

---

## Configuracion...

### Configuracion del KeyPass

1. Descargar el archivo -> [DataBaseConexion](https://drive.google.com/file/d/1EwspWX4sz7IIwYBspVnpH2K34is-weyJ/view)
2. Importar el archivo descargado en KeyPass.
3. Ingresar la contraseña (Preguntar por slack)


### Configuracion de la VPN
1. Descargar el archivo -> [Untitled](https://drive.google.com/file/d/18fazv5sZ-TuYNOOOAd1T8vPaYoF0_H-D/view)
2. Importar el archivo descargado en la VPN.
3. Ingresar el correo y la contraseña que aparece en el KeyPass para la VPN.
4. En caso de que no se conecte tener en cuenta la zona horaria del sistema.
   
### Configuracion de la base de datos (Sql Server Management Studio)

1. Crear conexion
   - Host-> ***sql-eastus2-001.privatelink.database.windows.net***
   - UserName -> ***Esta en el KeyPass.***
   - Password -> ***Esta en el KeyPass.***
 
2. En el apartado de options.
   - En Network Protocol marcarlo como TCP/IP.
   - Marcar la opcion Trust server certificate.
       
4. Probar la conexion.

### Configuracion de la base de datos (DBeaver)
1. Crear conexion
   - Host-> ***sql-eastus2-001.privatelink.database.windows.net***
   - DataBaseName -> ***sql-portalbrilla-dev-promigas***
   - UserName -> ***Esta en el KeyPass.***
   - Password -> ***Esta en el KeyPass.***
     
4. Descargar el **Driver de SQL Server** si no lo tiene (Esto lo hara automaticamente DBeaver).
5. Probar la conexion.

### Configuracion del Repositorio
1. Crear una carpeta en documentos con el nombre brilla.
2. Dentro de la carpeta brilla crear una nueva carpeta con el nombre backend.

---
 
1. Ingresar a [EnlaceCSCa](https://dev.azure.com/EnlaceCSC/)
2. Ingresar correo y contraseña que aprece en el ***KeyPass***
3. Elegir el proyecto ***franquiciaBrilla***
4. Ingresar al apartado de Repos.
5. buscar la rama ***back-web-portal***
6. Dar click en clonar y copiar url.
7. Dar click en generate git credencial.

---

1. Abrir ***SourceTree***
2. Ir al apartado para clonar repositorios remotos.
3. Pegar la url copiada anteriormente.
4. En caso de pedir credenciales poner las del ***keyPass***.
   - Si esta opcion no funciona dar en la opcion generate git credencial
     y copiar las credenciales.
6. Dar en el boton clonar, verificar haciendo un pull. 
