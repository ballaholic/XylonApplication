# XylonApplication

![Build](https://github.com/YOUR_USERNAME/XylonApplication/actions/workflows/dotnet.yml/badge.svg)
![.NET](https://img.shields.io/badge/.NET-9.0-blue.svg)
![License](https://img.shields.io/badge/license-Custom-red)

XylonApplication is a **clean ASP.NET Core 9.0 solution template** with modular architecture, pre-configured code quality tools, and CI/CD ready for GitHub Actions.

---

## 📂 Project Structure

XylonApplication/
├── .editorconfig
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
├── stylecop.json
├── .github/
│ └── workflows/dotnet.yml
└── src/
├── XylonApplication.sln
├── XylonApplication.Web/
├── XylonApplication.Data/
├── XylonApplication.Services/
├── XylonApplication.Common/
└── XylonApplication.Tests/

---

## ✅ Features
- ✅ **ASP.NET Core 9.0** Web Application
- ✅ Modular architecture: **Web**, **Services**, **Data**, **Common**, **Tests**
- ✅ **StyleCop & .editorconfig** for consistent coding style
- ✅ **GitHub Actions CI/CD** (Build & Test)
- ✅ `.gitattributes` & `.gitignore` preconfigured

---

## 🚀 Getting Started

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or Rider
- GitHub account for repository hosting

### Clone and Build
```bash
git clone https://github.com/ballaholic/XylonApplication.git
cd XylonApplication/src
dotnet build
```

### Run Web App

```bash
cd XylonApplication.Web
dotnet run
```

### Run Tests

```bash
dotnet test
```

## 📦 Continuous Integration
The project uses GitHub Actions to:

 - Restore dependencies
 - Build the solution
 - Run unit tests
 - You can find the workflow in .github/workflows/dotnet.yml.

## ✨ Contributing
This repository is read-only. No contributions or forks are allowed without permission.

## 📜 License
This project is licensed with the MIT license.