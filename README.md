# .NET 8 Clean Web API Template

This repository provides a .NET 8 Web API template. 
Folder Structure;

```bash
src
├── Application
│   ├── Interfaces
│   ├── Services
│   ├── Exceptions
│   └── Behaviors
│
├── Domain
│   ├── Entities
│   ├── ValueObjects
│   ├── Enums
│   └── Events
│
├── Infrastructure
│   ├── Persistence
│   ├── Identity
│   ├── Services
│   └── Configurations
│
├── Presentation (or WebAPI)
│   ├── Controllers
│   ├── Filters
│   ├── Models
│   └── Middleware
│
└── Tests
    ├── UnitTests
    ├── IntegrationTests
    └── FunctionalTests
```

## Installation Instructions

1. Download the repository files to your local machine.
2. Copy the `.zip` file to the Visual Studio templates folder:
C:\Users<username>\Documents\Visual Studio 2022\Templates\ProjectTemplates

## Using the Template

1. Open Visual Studio and click on **Create a New Project**.
2. You should see the new template listed among your available project templates.

## Troubleshooting

If the template does not appear in the list, try clearing the cache by deleting all files in the following directory:
C:\Users<username>\AppData\Local\Microsoft\VisualStudio\17.0_e98a41c8\ComponentModelCache
