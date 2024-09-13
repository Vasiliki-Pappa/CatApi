# CatApi

CATPROJECT API

#### DESCRIPTION ####
The CATPROJECT API downloads 25 images from the website and applies filtering.


#### DATABASE ####
1.The database is configured in the appsettings.json file and named data3.
2.To create the database, I used the command:...AppCat/CatProject>dotnet ef migrations add init.
3.To update the database, I used the command:...AppCat/CatProject>dotnet ef database update.

#### EXECUTION ####
I executed the project using the command:...AppCat/CatProject>dotnet run
or ...AppCat/CatProject>dotnet watch run.

Running the project with the command dotnet watch run will show the Swagger UI.

/api/cat/fetch --> Downloads images and saves them to the database.
/api/cat/{id} ---> Filters by the ID of the CAT entity.
/api/cat/Tag ---> Filters by the tag.
/api/cat/byTag ---> Retrieves cats with a specific tag with paging support.


------- NOTE ------------
The rest are auxiliary for better understanding.
