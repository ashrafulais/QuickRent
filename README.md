Sample .NET project - Structured

### Commands
- `dotnet new sln -o QuickRent`
- `dotnet new webapi -o Backend/QuickRent.API`
- Add all the csproj to the solution `dotnet sln add $(ls -r **/*.csproj)`
- Add specific proj to the solution `dotnet sln add Backend/QuickRent.API/QuickRent.API.csproj`

- Build the solution: `dotnet build`
- Run the project: `dotnet run --project Backend/QuickRent.API`
- Run & Hot reload: `dotnet watch run --project Backend/QuickRent.API`
- Stop the proj: `CTRL + C`

- `dotnet new classlib -o Backend/something.Models`