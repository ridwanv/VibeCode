# VibeCode

VibeCode is a multi-tenant Blazor Server application based on Clean Architecture. The checked-in application provides contacts, documents, products, picklists, tenant and identity administration, audit trails, and system logs.

## Build and run

Install the .NET SDK required by the solution, then run `dotnet build CleanArchitecture.Blazor.slnx` and `dotnet test CleanArchitecture.Blazor.slnx`. Start the UI from `src/Server.UI`.

Database migrators support SQL Server, PostgreSQL, and SQLite. Configure database and identity settings locally or through environment variables; never commit secrets.
