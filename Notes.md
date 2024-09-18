# Notes for [Kevin Dockx's Authentication and Authorization in ASP.NET Core 8 Blazor](https://www.pluralsight.com/courses/dot-net-core-blazor-authentication-authorization) course

## 1. Introduction

Sources: https://github.com/KevinDockx/AuthNZinBlazor/tree/latest-and-greatest

- Nem b�zhatunk a kliens �ltal kalkul�lt dolgokban (a k�d m�dos�that� hackerek �lta). - egy serveren kell autentik�lnunk

Types of Authentication:
- No auth
- Individual accounts (Blazor Identity UI)
- Identity provider integration

## Individual User Accounts

- In app user management solution, no external dependencies needed.

### Approaches to Identity Access Management (IAM)

- Handling by yourself (registration with email)
- Delgating it to a third party (e.g. Microsoft, google, facebook login)
	- Better and easier for users and developers

- Blazor Identity UI: Set of pre built UI components for handling IAM tasks.
- ASP:NET Core Identity: Server framework for manageing IAM tasks.

