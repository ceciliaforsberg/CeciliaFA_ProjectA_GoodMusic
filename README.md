# GoodMusic

ASP.NET Core MVC web application demonstrating a loosely coupled service layer 
that can switch between two data sources without changing the application layer: 
a local SQL Server database (via Entity Framework Core) and an external Web API.

## Tech stack
C#, ASP.NET Core MVC, Entity Framework Core, SQL Server, REST API

## What it does
- CRUD operations for music groups, albums, and artists
- Service layer implementation using dependency injection to switch data sources
- Demonstrates separation of concerns between application and data access layers

---
This project was built on a template provided by Seido AB as part of the 
.NET developer program at Teknikhögskolan.
