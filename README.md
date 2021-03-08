# Parcial1Code
Codigo usado para el primer parcial de Programacion III hecho por Alan E. Ramirez. 

Link del Video: https://youtu.be/mL3JZORBPR4

Links de descarga:
SQLYog: https://sqlyog.en.softonic.com/download
Ampps: https://ampps.com/downloads
Northwind: https://drive.google.com/file/d/1nwUUk2j9zxcBZJtAhaV2tHQRqQQb5ZDC/view?usp=sharing



Comandos en powershell para obtener los paquetes necesarios para realizar la conexion EntityFramework:

dotnet add package Microsoft.EntityFrameworkCore.Relational -v 3.1.12

dotnet add package Microsoft.EntityFrameworkCore.SqlServer -v 3.1.12

dotnet add package Microsoft.EntityFrameworkCore.Tools -v 3.1.12

dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design -v 3.1.5

dotnet add package Pomelo.EntityFrameworkCore.MySql -v 3.2.4

Comando para realizar la conexion EntityFramework a northwind:

dotnet ef dbcontext scaffold "server=localhost;uid=root;pwd=mysql;database=northwind" Pomelo.EntityFrameworkCore.MySql --output-dir Models --force
