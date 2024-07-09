# GameStore
C# dotnet 8 API
Codealong after https://www.youtube.com/watch?v=AhAxLiGC7Pc and https://www.youtube.com/watch?v=RBVIclt4sOo

# Create EF migration
dotnet ef migrations add InitialCreate --output-dir .\Data\Migrations
dotnet ef migrations add SeedGenres --output-dir .\Data\Migrations\

# Create DB
dotnet ef database update
