<p align="center">
  <img src="https://raw.githubusercontent.com/StruttonTechnologies/Assets/main/Logos/StruttonTechnologies_FullLogo.png" width="250"/>
</p>

# Strutton Technologies

Strutton Technologies develops practical software architecture, reusable engineering libraries, application templates, and engineering documentation for building maintainable, scalable .NET applications.

---

# 🎯 Mission

The goal of Strutton Technologies is to make enterprise software architecture practical and repeatable by providing clear architectural guidance, reusable engineering libraries, application templates, and reference implementations built around consistent engineering principles.

---

# 📚 Engineering Documentation

## 📘 Application Architecture

The **Application Architecture** book is the foundation of this organization. It defines the architectural philosophy, terminology, design principles, and engineering practices used throughout every repository.

If you're exploring this organization for the first time, **Application Architecture** is the recommended starting point.

**Repository**

https://github.com/StruttonTechnologies/Documentation.Application.Architecture

Future volumes will expand on these concepts by covering application development, implementation patterns, infrastructure, security, engineering standards, and additional technical disciplines.

---

# 🏛️ Supported Architectures

The engineering platform supports multiple architectural styles while maintaining a consistent set of engineering principles.

- Clean Monolith
- Service-Based Architecture
- Microservices

---

# 🗂️ Repository Organization

Repositories are organized according to their purpose.

## Engineering Libraries

Reusable engineering libraries are grouped into repositories based on architectural responsibility. Each repository contains one or more related projects that evolve together and publish one or more NuGet packages.

| Repository | Purpose |
|------------|---------|
| **Core.Foundation** | Foundational contracts, domain abstractions, DTOs, messages, interfaces, rules, and shared assets. |
| **Core.ToolKit** | Cross-cutting engineering utilities that can be referenced from any architectural layer. |
| **Core.Testing** | Shared testing infrastructure, fixtures, builders, helpers, and reusable testing components. |
| **Core.Identity** | Identity management, authentication, authorization, and supporting identity infrastructure. |
| **Core.PresentationLayer** | Shared presentation technologies including APIs, Blazor applications, controllers, presentation abstractions, and related components. |
| **Core.Implementations** | Concrete implementations including persistence, repositories, services, integrations, and infrastructure components. |

Each engineering library repository contains its own documentation describing its internal organization, published packages, and intended usage.

## Applications

Applications are maintained as a single repository.

An application repository contains everything required to build, test, and deploy that application while consuming the reusable engineering libraries published by this organization.

Examples include:

- **RidgeRiders**
- Future customer applications
- Reference implementations

This separation keeps reusable platform components independent from the applications that consume them while allowing each application to evolve as a cohesive product.

---

# 🧱 Engineering Principles

Every repository is built around the same architectural philosophy.

Core principles include:

- Separation of Concerns
- Clear Architectural Boundaries
- Controlled Dependency Direction
- Explicit Contracts
- Reusable Engineering Components
- Architectural Enforcement over Convention

---

# ⚙️ Technology Focus

Current development is centered around the Microsoft .NET ecosystem.

## Languages

- C#

## Frameworks

- .NET
- ASP.NET Core
- Blazor

## Data Access

- Entity Framework Core

## Architectural Practices

- Layered Architecture
- Service-Based Architecture
- Dependency Injection
- Testable Application Design

---

# 🚧 Status

Strutton Technologies is under active development.

Additional engineering libraries, application templates, architectural guidance, reference implementations, and documentation will continue to be published as they mature. Each repository contains detailed documentation describing its specific purpose, architecture, and usage.
