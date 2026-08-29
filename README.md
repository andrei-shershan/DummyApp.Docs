# DummyApp.Docs
**DummyApp** is just another dummy application which does something without any purpose rather that show my abilities to call myself a **software engineer**.

## Architecture and stack
### Architecture Diagram

<img width="667" height="517" alt="image" src="https://github.com/user-attachments/assets/b43664db-b845-456e-9393-48d80a37af70" />


### Stack

**Frontend**: React, TypeScript

**Backend**: C#, .NET 10, ASP.NET Core, Azure Functions

**Databases**: MySQL, Azure Cosmos DB

**Identity / Authentication**: ASP.NET Identity, OpenIddict

**DevOps / CI / CD**: GitHub Actions, Azure Pipelines

**Testing**: xUnit, Moq

**Messaging**: Azure Service Bus

**Cloud**: Azure

**Cloud Infrastructure**: Terraform 

**Containers**: Docker, Traefik

**Source control**: Git, Github

**Tools**: VS Code, Rancher Desktop

**AI**: GitHub Copilot

## Projects

### [DummyApp.FE ](https://github.com/andrei-shershan/DummyApp.FE) 

Frontend SPA for DummyApp, implementing client-side UI, routing, forms, and data display from backend services.

**React, TypeScript, Material UI**

### [DummyApp.ApiGateway](https://github.com/andrei-shershan/DummyApp.ApiGateway)

Central API gateway for microservices, handling HTTP requests, routing, authentication, payment processing, and internal service integration.

**ASP.NET Core 10, Web API, Stripe.net, Azure Service Bus**

### [DummyApp.BFF](https://github.com/andrei-shershan/DummyApp.BFF)

Backend-for-frontend service that proxies frontend requests and integrates with Identity and internal services.

**ASP.NET Core 10, YARP Reverse Proxy**

### [DummyApp.Identity](https://github.com/andrei-shershan/DummyApp.Identity)

User and authentication service implementing identity management, OpenIddict authorization, user storage, and role-based access control.

**ASP.NET Core 10, OpenIddict, ASP.NET Core Identity, Entity Framework Core, MySQL, Azure.Identity**

### [DummyApp.StorageService](https://github.com/andrei-shershan/DummyApp.StorageService)

Storage service managing persistence and storage-related workflows, publishing events to Service Bus and coordinating order/file operations.

**ASP.NET Core 10, Web API, Azure Service Bus, MySQ, xUnit, Moq**

### [DummyApp.Docker](https://github.com/andrei-shershan/DummyApp.Docker)

 Local development environment configuration with Docker Compose, setting up Traefik, certificates, MySQL, and all DummyApp services.

 **Docker, Docker Compose, Traefik, mkcert**

### [DummyApp.Infra](https://github.com/andrei-shershan/DummyApp.Infra)

Azure infrastructure deployment using Terraform, including App Services, storage accounts, Cosmos DB, resource groups, and managed identities.

**Terraform, Azure Resource Manager, Azure App Service, Azure Storage, Azure Cosmos DB, Azure Key Vault, Managed Identity.**

### [DummyApp.PaymentService](https://github.com/andrei-shershan/DummyApp.PaymentService)

Azure Function payment service processing Stripe transactions and webhooks, integrating with Service Bus for order event handling.

**Azure Functions, Stripe.net, Azure Service Bus**

### [DummyApp.BlobService](https://github.com/andrei-shershan/DummyApp.BlobService)

Azure Function service for blob storage operations, handling file upload/download via HTTP triggers.

**Azure Functions, Azure Storage Blobs**

### [DummyApp.EmailService](https://github.com/andrei-shershan/DummyApp.EmailService)

Azure Function email service sending messages through Azure Communication Services.

**Azure Functions, Azure Communication Email**

### [DummyApp.FileService](https://github.com/andrei-shershan/DummyApp.FileService)

Azure Function service for file management in the app, providing HTTP-based document and attachment handling.

**Azure Functions**

### [DummyApp.Analytics](https://github.com/andrei-shershan/DummyApp.Analytics)

Azure Function analytics service collecting events and serving analytics queries, backed by Cosmos DB.

**Azure Functions, Azure Cosmos DB**
