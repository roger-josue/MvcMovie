# First API with ASP.NET CORE Controllers
Step by step turorial from the .NET documentation. Aims to learn the fundamentals of building a .NET CORE MVC project with razor and EF Core.

## Objectives
- MVC structure
- EF Core
- Razor templates

## Used commands
    dotnet tool uninstall --global dotnet-aspnet-codegenerator\ndotnet tool install --global dotnet-aspnet-codegenerator\ndotnet tool uninstall --global dotnet-ef\ndotnet tool install --global dotnet-ef\ndotnet add package Microsoft.EntityFrameworkCore.Design\ndotnet add package Microsoft.EntityFrameworkCore.SQLite\ndotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design\ndotnet add package Microsoft.EntityFrameworkCore.SqlServer\ndotnet add package Microsoft.EntityFrameworkCore.Tools
    dotnet aspnet-codegenerator controller -name MoviesController -m Movie -dc MvcMovie.Data.MvcMovieContext --relativeFolderPath Controllers --useDefaultLayout --referenceScriptLibraries --databaseProvider sqlite
    dotnet ef migrations add InitialCreate
    dotnet ef database update
    dotnet watch


    