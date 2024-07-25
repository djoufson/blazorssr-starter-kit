# Blazor SSR Starter Kit

Find the repository at this link [nuget.org/packages/BlazorSSR.Starter.Kit](https://www.nuget.org/packages/BlazorSSR.Starter.Kit/)

This repository serves as a starter kit for Blazor SSR projects using .NET 8. It provides a basic setup and structure to kickstart your Blazor SSR development journey.

## Features

- Boilerplate code for Blazor SSR projects.
- Basic project structure and setup.
- TailwindCSS support.
- Simplified configurations for quick development.

## Getting Started

To get started with this starter kit, follow these steps:

### 1. Install the template using `dotnet new`

```sh
dotnet new install BlazorSSR.Starter.Kit
```

You should see the template in the list of templates from `dotnet new list` after this installs successfully. Look for "BlazorSSR Starter Kit" with Short Name of `"blazorssr"`.

### 2. Create your project based on the template with the cli

Navigate to the parent directory in which you'd like the solution's folder to be created.

Run this command to create the solution structure in a subfolder name Your.ProjectName:

```sh
dotnet new blazorssr -o Your.ProjectName
```

The Your.ProjectName directory and solution file will be created, and inside that will be all of your new solution contents, properly namespaced and ready to run.
