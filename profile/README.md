<p align="center">
  <img src="https://raw.githubusercontent.com/StruttonTechnologies/Assets/main/Logos/StruttonTechnologies_FullLogo.png" width="250"/>
</p>

# Strutton Technologies

Strutton Technologies develops practical software architecture, reusable engineering libraries, and application templates for building maintainable, scalable software systems.

---

## 🎯 Mission

The goal of Strutton Technologies is to make high-quality software architecture practical and repeatable by providing documentation, reusable engineering libraries, application templates, and reference implementations built around consistent architectural principles.

---

## 📚 Engineering Documentation

### 📘 [Application Architecture](https://github.com/StruttonTechnologies/Documentation.Application.Architecture)

*Application Architecture* is the first published volume in the Strutton Technologies Architecture Book series. It defines the architectural model, design philosophy, and engineering principles that guide software development throughout the organization.

Future volumes will expand on these concepts, covering application development, implementation patterns, infrastructure, security, engineering standards, and other technical disciplines.

If you're exploring this organization for the first time, **Application Architecture** is the recommended starting point.

---

## 🏛️ Supported Architectures

This organization develops guidance, tooling, and reusable components that support several architectural styles.

### Clean Monolith

A single deployable application with a well-defined internal structure and clear boundaries between presentation, application, domain, and infrastructure layers.

### Service-Based Architecture

A modular architecture where business capabilities are implemented as independent modules within a shared host application, providing clear separation while remaining a single deployable system.

### Microservices

Independently deployable services with well-defined boundaries, enabling systems to scale through service separation when operational complexity is justified.

---

## 📦 Engineering Libraries

The repositories in this organization provide reusable building blocks that support the architectural styles described above.

They include:

- reusable .NET libraries
- application templates
- architecture standards
- engineering guidance
- development conventions
- supporting documentation

Examples include:

- Core.ToolKits
- Core.Identity

---

## 🎯 Engineering Goals

The engineering platform is designed to help developers build software that is:

- maintainable
- modular
- scalable
- testable
- understandable throughout the lifetime of the application

---

## 🧱 Engineering Approach

Software developed using these repositories is designed to be:

- structured and predictable
- explicit in behavior and intent
- consistent across projects
- organized around clear architectural boundaries and responsibilities

Core architectural principles include:

- separation of concerns
- controlled dependency direction
- explicit contracts
- architectural enforcement over convention

---

## ⚙️ Technology Focus

Current work is centered around the Microsoft .NET ecosystem.

### Languages

- C#

### Frameworks

- .NET
- ASP.NET Core
- Blazor

### Data Access

- Entity Framework Core

### Architectural Practices

- Layered Architecture
- Service-Based Architecture
- Dependency Injection
- Testable Application Design

---

## 📦 Projects

The following engineering libraries are currently available.

### Available

#### **Core.ToolKits**
*Core Capability Toolkit*

Reusable engineering utilities including guard logic, validation, service composition, and testing support.

➡️ https://github.com/StruttonTechnologies/Core.ToolKits

---

#### **Core.Identity**
*Core Capability Identity Management*

Identity and authentication components designed to integrate with the core architectural model.

➡️ https://github.com/StruttonTechnologies/Core.Identity

---

### Planned

#### **Core**
*Core Capability Package*

Foundational components and shared capabilities that support higher-level modules and services.

---

#### **Templates.CleanMonolith**
*Clean Monolith Application Template*

A structured starting point for building layered applications with well-defined architectural boundaries.

---

#### **Templates.ServiceBased**
*Service-Based Application Template*

A modular application template for implementing scalable business capabilities within a single deployable application.

---

#### **Templates.Modules**
*Service-Based Module Template*

A reusable module structure for implementing isolated business functionality within service-based applications.

---

#### **Templates.MicroService**
*Microservice Application Template*

A template for building independently deployable services aligned with the Strutton Technologies architectural model.

---

## 🚧 Status

This organization is under active development. Additional documentation, engineering libraries, application templates, architectural guidance, and reference implementations will be published as they become available.
