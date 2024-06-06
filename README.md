# API de Nombres de Personas

Este proyecto es una API para gestionar nombres de personas, construida con ASP.NET Core y documentada utilizando OpenAPI (Swagger).

## Descripción

La API permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre una lista de nombres de personas. Está diseñada para ser sencilla y fácil de usar, proporcionando una interfaz intuitiva y bien documentada gracias a Swagger.

## Características

- **Crear Nombre**: Añadir un nuevo nombre a la lista.
- **Leer Nombres**: Obtener la lista de nombres disponibles.
- **Actualizar Nombre**: Modificar un nombre existente.
- **Eliminar Nombre**: Quitar un nombre de la lista.

## Requisitos

- [.NET 8 SDK]
- [Visual Studio 2022] o [Visual Studio Code]
- [SQL Server]
## Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/pauldev24/Api-Personas-Asp.Net.git
   cd Api-Personas-Asp.Net

2. Restaura los paquetes Nuget necesarios

   ```sh
   dotnet restore

3. Configure su base de datos
   ```sh
   Esto de ser necesario en el archivo WebApiPerson/appsettings.json

5. Inicie la aplicación

   ```sh
   dotnet run
