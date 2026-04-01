# 🚀 MyDotNetApp

A sample ASP.NET Core application packaged in this repository for Azure deployment and local development.

## 🧩 Project Overview

- Folder: `/home/simarjit/GitHub/ASP.NET-Azure/MyDotNetApp`
- Project file: `MyDotNetApp.csproj`
- Framework: ASP.NET Core MVC
- Primary files:
  - `Program.cs`
  - `Controllers/HomeController.cs`
  - `Views/Home/Index.cshtml`
  - `Views/Home/Privacy.cshtml`
  - `wwwroot` static assets

## ⚙️ Features

- MVC architecture
- Razor views
- Default Home and Privacy pages
- Error view support
- Static asset serving from `wwwroot`

## 🛠️ Getting Started

### Prerequisites

- .NET SDK 8.0+ (or the version specified by `MyDotNetApp.csproj`)
- Visual Studio / VS Code, or terminal usage

### Run locally

```bash
cd /home/simarjit/GitHub/ASP.NET-Azure/MyDotNetApp
dotnet restore
dotnet build
dotnet run
```

Then open `https://localhost:5001` or `http://localhost:5000`.

### Docker (if you want)

```bash
docker build -t mydotnetapp .
docker run -d -p 8080:80 mydotnetapp
```

Then visit `http://localhost:8080`.

## 🧪 Tests

No dedicated test project is present in this sample. Add an xUnit/NUnit/MSTest project under `/tests` for unit and integration tests.

## 📄 Configurations

- `appsettings.json` (base settings)
- `appsettings.Development.json` (development override)
- `Properties/launchSettings.json` (launch profiles)

## 🧹 Clean & Build

```bash
dotnet clean
dotnet build
```

## 📦 Deployment

Deploy to Azure App Service or any container platform.

## 🙌 Contributing

1. Fork repository
2. Create a feature branch
3. Add code, commit, and push
4. Create a pull request

## 📞 Support

For help, raise an issue in the repository and include OS, .NET SDK version, and steps to reproduce.

---

Made by Simarjit Singh in ASP.NET Core.