# AngularAndDotnetTrialProject
This is an angular app with .Net API and I basically tried to learn basic concepts.


Angular CLI: 16.2.0
Node: 20.5.1 (Unsupported)
Package Manager: npm 6.14.18
OS: win32 x64

- I also downloaded Angular Language Service in VSCode.

- I used Angular routing and CSS.
- I created components, models and services folders inside the CRUD_Project\CRUD.UI\src\app folder.

-----

There are two main folders. 

- CRUD.UI consists of the angular application that is able to connect an SQL server and perform all CRUD operations via the .NET API. There are buttons on the .html folders that are able to connect and perform the CRUD operations and app can take inputs from the user such that desired values can be changed on the SQL database.
- CRUD_API consits of the .NET API that is able to perform Create, Read, Update and Delete operations.
- I used Microsoft SQL Server Management Studio for my SQL server and I migrated the project.

  -----

  - I installed Microsoft.EntityFrameworkCore, NuGet package Microsoft.EntityFrameworkCore.Design and Microsoft.EntityFrameworkCore.SqlServer to the project.
  - I added couple of buttons and text boxes in order to provide some UI to the client in to editusercomponent.html. I also bonded update, delete and create functions to the corresponding buttons.
  - I added 2 main buttons to app.component.html as edit and create buttons. I also added the http call for real time table refresh and sql database update by writing the corresponding CRUD operation functions to editUser component.
  - I migrated the project and acquired migrations folder. Then, created the SQL database.
  - I modified the userController to possess the DataContext thus, it is directly communicating with the SQL database.
