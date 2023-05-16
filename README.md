# Run the .NET 6.0 Boilerplate API Locally

Configure SMTP settings for email within the AppSettings section in the /appsettings.json file. For quick testing you can create a temporary inbox at https://ethereal.email/ and copy the SMTP configuration options.

Start the API by running dotnet run from the command line in the project root folder (where the WebApi.csproj file is located), you should see the message Now listening on: http://localhost:4000, and you can view the Swagger API documentation at http://localhost:4000/swagger.
