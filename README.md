# .NET — Hello World Templates

A set of ready-to-run "Hello World" templates for .NET. Each template is a standalone starting point: **fork the one you want, run it with `gws`, and start building**.

## Available Templates

| Template | Language | Framework |
|----------|----------|-----------|
| [dotnet-aspnet](./dotnet-aspnet) | C# | [ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/) |
| [dotnet-blazor](./dotnet-blazor) | C# | [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor) |
| [dotnet-fsharp](./dotnet-fsharp) | F# | [ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/) |
| [dotnet-minimal-api](./dotnet-minimal-api) | C# | [Minimal API](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis) |

## Getting Started

### 1. Create a GetWebstack account

Sign up for a free account at [app.getwebstack.com](https://app.getwebstack.com). You'll need it to initialise and manage your projects with the `gws` CLI.

### 2. Pick a template and fork it

Browse the templates above, choose the framework you want to work with, and fork that repository into your own GitHub account.

### 3. Install the GetWebstack CLI

```bash
curl -sSL https://getwebstack.com/install.sh | bash
```

### 4. Log in to GetWebstack

```bash
gws login
```

This authenticates the CLI with your GetWebstack account.

### 5. Initialise the project

Inside the forked project directory, run:

```bash
gws init
```

This discovers the application and generates the necessary configuration files to run it locally.

### 6. Start the application

```bash
gws up
```

This builds the application and starts it in a local Kubernetes cluster. Each template returns a simple `Hello World` response to confirm everything is working.

### 7. Start developing

The templates are intentionally minimal — just enough to get a working server running. Add routes, middleware, database connections, and anything else your project needs.

## Other Template Collections

| Collection | Description |
|------------|-------------|
| [go-projects](https://github.com/GetWebstack-public/go-projects) | Hello World templates for Go backends |
| [js-ts-backend](https://github.com/GetWebstack-public/js-ts-backend) | Hello World templates for JavaScript and TypeScript backends |
| [js-ts-frontend](https://github.com/GetWebstack-public/js-ts-frontend) | Hello World templates for JavaScript and TypeScript frontends |
| [python-projects](https://github.com/GetWebstack-public/python-projects) | Hello World templates for Python backends |
