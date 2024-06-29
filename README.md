# GameStore
C# dotnet 8 API

# Create EF migration
dotnet ef migrations add InitialCreate --output-dir .\Data\Migrations
dotnet ef migrations add SeedGenres --output-dir .\Data\Migrations\

# Create DB
dotnet ef database update