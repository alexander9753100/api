API de Productos

Esta API permite gestionar productos con operaciones CRUD mediante .NET 8.0 y Entity Framework Core. Requiere una base de datos SQL Server y usa Swagger para la documentación. Para ejecutarla, configura la cadena de conexión en appsettings.json, aplica migraciones (dotnet ef migrations add InitialCreate y dotnet ef database update), y ejecuta dotnet run. Los endpoints permiten obtener, crear, actualizar y eliminar productos. 
