# Client

This project was generated with .NET 5 and Angular version 12.

## Development server

Run `cd .\client\` and then `ng serve` for a client server. Navigate to `http://localhost:4200/`.

The app will automatically reload if you change any of the source files. 
#
Run `cd .\API\` and then `dotnet watch run` for dev .NET server. 

Navigate to `https://localhost:5001/swagger/index.html` to see auto-generated documentation.

## Build

To build project hosted on .NET server 

Run `cd .\client\` and then `ng build`, files will be built and save in `.\API\wwwroot`. 

Navigate to `https://localhost:5001/` to see FE part of project or `https://localhost:5001/swagger/index.html` to see auto-generated documentation.

## Database

To run Postgres database locally, use Docker (if you have locally running postgres change port e.g 5433:5432).

`docker run --name dev -e POSTGRES_USER=appuser -e POSTGRES_PASSWORD=Passw0rd -p 5432:5432 -d postgres:latest`

To change connection with database go to `.\API\appsettings.Development.json`

