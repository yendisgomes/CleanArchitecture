# CleanArchitecture

# Technologies
ASP.NET Core 3.1 WebApi
REST Standards
.NET Core 3.1 / Standard 2.1 Libraries
# Features
- [x] Onion Architecture
- [x] CQRS with MediatR Library
- [x] Entity Framework Core - Code First
- [x] Repository Pattern - Generic
- [x] MediatR Pipeline Logging & Validation
- [x] Serilog
- [x] Swagger UI
- [x] Response Wrappers
- [x] Healthchecks
- [x] Pagination
- [ ] In-Memory Caching
- [ ] Redis Caching
- [x] In-Memory Database
- [x] Microsoft Identity with JWT Authentication
- [x] Role based Authorization
- [x] Identity Seeding
- [x] Database Seeding
- [x] Custom Exception Handling Middlewares
- [x] API Versioning
- [x] Fluent Validation
- [x] Automapper
- [x] SMTP / Mailkit / Sendgrid Email Service
- [x] Complete User Management Module (Register / Generate Token / Forgot Password / Confirmation Mail)
- [x] User Auditing


``update-database -Context IdentityContext``

``update-database -Context ApplicationDbContext``

Finally, build and run the Application.

Default Roles & Credentials
As soon you build and run your application, default users and roles get added to the database.

Default Roles are as follows.

- SuperAdmin
- Admin
- Moderator
- Basic
Here are the credentials for the default users.

- Email - superadmin@gmail.com / Password - 123Pa$$word!
- Email - basic@gmail.com / Password - 123Pa$$word!
You can use these default credentials to generate valid JWTokens at the ../api/account/authenticate endpoint.
