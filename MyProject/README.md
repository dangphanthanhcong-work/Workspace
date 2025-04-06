# Modern Full-Stack Template

> Built with passion for clean architecture and exceptional user experience

## Personal Mission

This project reflects my commitment to building robust, scalable applications with a focus on code quality and developer experience. As a full-stack developer who values clean architecture, I've crafted this template to embody best practices and modern development approaches.

## Key Principles

- **Code Quality** - Every component is written with maintainability in mind
- **Developer Experience** - Intuitive project structure and comprehensive documentation
- **Modern Practices** - Incorporating latest industry standards and patterns
- **Performance Focus** - Optimized for both development and production environments

## 💻 Tech Stack

### Backend Technologies

- **.NET Core Web API** - Modern, fast, cross-platform framework
- **PostgreSQL** - Enterprise-grade relational database
- **Entity Framework Core** - Powerful ORM for .NET
- **Clean Architecture** - SOLID principles & DDD
- **xUnit** - Comprehensive testing framework

### Frontend Technologies

- **Angular** - Enterprise-ready web platform
- **Angular Material** - Professional UI components
- **SCSS** - Maintainable styling system
- **Karma/Jasmine** - Robust testing suite

---

## 🏗️ Project Structure

<details>
<summary><strong>Click to expand full structure</strong></summary>
 expand full structure</summary>

```
📦 MyProject
├── 📁 Server/                            # Backend solution
│   ├── 📁 src/                          # Source code
│   │   ├── Server.API/                  # API Layer
│   │   │   ├── Controllers/            # API endpoints
│   │   │   ├── Middlewares/           # Custom middleware
│   │   │   ├── Extensions/            # Extension methods
│   │   │   └── appsettings.json       # Configuration
│   │   │
│   │   ├── Server.Application/         # Application Layer
│   │   │   ├── DTOs/                  # Data transfer objects
│   │   │   ├── Features/              # CQRS features
│   │   │   │   ├── Commands/          # Write operations
│   │   │   │   └── Queries/           # Read operations
│   │   │   ├── Mappings/             # Object mappings
│   │   │   ├── Behaviors/            # Pipeline behaviors
│   │   │   └── Validators/           # Input validation
│   │   │
│   │   ├── Server.Core/               # Domain Layer
│   │   │   ├── Entities/             # Domain models
│   │   │   ├── Interfaces/           # Abstractions
│   │   │   └── Services/             # Domain services
│   │   │
│   │   └── Server.Infrastructure/     # Infrastructure Layer
│   │       ├── Data/                 # Data access
│   │       ├── Services/             # External services
│   │       └── Persistence/          # Database context
│   │
│   └── 📁 tests/                      # Test projects
│       ├── Server.UnitTests/          # Unit tests
│       ├── Server.IntegrationTests/   # Integration tests
│       └── Server.FunctionalTests/    # End-to-end tests
│
└── 📁 Client/                          # Frontend application
    ├── 📁 src/                        # Source files
    │   ├── app/                       # Application code
    │   │   ├── core/                 # Core functionality
    │   │   │   ├── auth/            # Authentication
    │   │   │   ├── guards/          # Route guards
    │   │   │   ├── interceptors/    # HTTP interceptors
    │   │   │   ├── services/        # Core services
    │   │   │   └── models/          # Core models
    │   │   │
    │   │   ├── shared/              # Shared components
    │   │   │   ├── components/      # Reusable UI components
    │   │   │   ├── directives/      # Custom directives
    │   │   │   ├── pipes/           # Custom pipes
    │   │   │   └── utils/           # Utility functions
    │   │   │
    │   │   ├── features/            # Feature modules
    │   │   │   ├── dashboard/       # Dashboard feature
    │   │   │   ├── user-profile/    # User profile feature
    │   │   │   └── settings/        # Settings feature
    │   │   │
    │   │   └── layout/              # App layout components
    │   │       ├── header/          # Header component
    │   │       ├── footer/          # Footer component
    │   │       └── sidebar/         # Sidebar component
    │   │
    │   ├── assets/                  # Static assets
    │   │   ├── images/             # Image files
    │   │   ├── icons/              # Icon files
    │   │   └── fonts/              # Font files
    │   │
    │   ├── styles/                  # Global styles
    │   │   ├── themes/             # Theme files
    │   │   ├── variables/          # SCSS variables
    │   │   └── mixins/             # SCSS mixins
    │   │
    │   └── environments/            # Environment configs
    │
    ├── 📁 tests/                    # Test files
    │   ├── unit/                   # Unit tests
    │   └── e2e/                    # End-to-end tests
    │
    ├── angular.json                # Angular configuration
    ├── package.json               # Dependencies
    ├── tsconfig.json             # TypeScript config
    └── tailwind.config.js        # Tailwind CSS config
```

</details>

---

## ⚡ Quick Start

### Prerequisites

- .NET 8 SDK
- Node.js (LTS)
- PostgreSQL 14+
- Angular CLI

### Backend Setup

```bash
cd Server
dotnet restore
dotnet ef database update
cd src/Server.API
dotnet run
```

### Frontend Setup

```bash
cd Client
npm install
ng serve
```

---

## 🛠️ Development

### Testing

```bash
# Backend Tests
dotnet test

# Frontend Tests
ng test
```

### Documentation

- [Architecture Overview](./project-structure.md)
- [API Reference](http://localhost:5000/swagger)
- [Frontend Guide](./Client/README.md)

---

## 🔒 Security Features

- ✅ JWT Authentication
- ✅ Role-based Authorization
- ✅ HTTPS Enforcement
- ✅ Input Validation
- ✅ CORS Policies

---

## ⭐ Core Features

- Clean Architecture Implementation
- Domain-Driven Design Patterns
- CQRS Implementation
- Repository Pattern
- Dependency Injection
- API Documentation
- Comprehensive Testing
- Database Migrations

---

## 📋 Best Practices

- [.NET Coding Standards](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- [Angular Best Practices](https://angular.io/guide/styleguide)
- Unit Testing Guidelines
- Documentation Standards
- Git Commit Conventions

---

## Development Philosophy

My approach to this template emphasizes:

- Writing self-documenting, clean code
- Building scalable and maintainable systems
- Following SOLID principles consistently
- Ensuring comprehensive test coverage
- Creating intuitive developer experiences

## 👤 Author

**Đặng Phan Thành Công**

- Full-Stack Developer | Clean Architecture Enthusiast
- 📧 Email: <dangphanthanhcong-work@gmail.com>
- 💻 GitHub: [@dangphanthanhcong-work](https://github.com/dangphanthanhcong-work)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<div align="center">
<strong>Built with precision for professional development</strong>
</div>
