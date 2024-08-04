```bash
dotnet new console -o EFGetStarted
cd EFGetStarted
```

```bash
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
```

```bash
dotnet tool install --global dotnet-ef
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet ef migrations add InitialCreate
dotnet ef database update
```

```bash
dotnet run
```
