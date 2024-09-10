# Product-Category-App
C#, ASP.NET, Entity Framework, CSS, HTML, Bootstrap WebApp to manage Products
Product And Category Application

FRUIT SA

TECHSTACK
*Web application Created using Visual Studio 2022, MSSQL.
*ASP.NET
*ENTITY Framework 6
*MVC - Model-View-Controller
*CSS with Bootstrap

PURPOSE
The Web-Application is created, to manage Products as well as the Category in which the Product belongs too, it is a Web-Application in which a new user needs to register, from there it allows a user to login and Manage Products.



INSALLING AND CONFIGURING THE WEB_APPLICATION
1. We use a Repository called GitHub.
2. Download/Clone the Repo to your PC
	`git clone https://github.com
3. Unzip the file
4. Go to appsettings.json file, set up and configure you Database
5. Add Migration - Tools - Nuget Package Manager - Package Manager Console(PMC) - Default Project should be FruitSA.DataAccess -
	*Add-Migration MigrationName Migration name can be any name of your choice can be e.g. FirstMigration, SecondMigration etc.
	*Update-Database
6. Build Application 
7. Run Application 

WE NOW DONE WITH INSTALLING AND CONFIGURING THE WEB-APPLICATION!!!!!!!! 


HOW TO USE WEB-APPLICATION
1. Register NEW USER and I believe you will be able to play around the WEB-APPLICATION


IMPORTANT EXCEL FILE SHOULD HAVE BELOW COLUMNS IN THIS ORDER
*********ProductId, ProductCode, Name, Description, CategoryId, Price, ImageUrl, Username, CreatedDate, UpdatedAt_******

HOW TO UPLOAD PRODUCTS USING EXCEL
1. I attached a EXCEL DOCUMENT called Products, USE that one.
2. Content Managment - Product and upload the Excel file and Upload
3. Back to HOME PAGE, Products have been added
4. when download, AGAIN Content Managment, check downloadBUTTON



HOW TO UPLOAD OWN PRODUCTS USING EXCEL
1. First create Categories by navigating to Content Management - Category and click the Create New Category button
2. Then go to Content Management - Product and upload the Excel file
   

