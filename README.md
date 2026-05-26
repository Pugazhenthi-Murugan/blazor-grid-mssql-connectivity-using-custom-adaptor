# Blazor DataGrid — MSSQL connectivity using CustomAdaptor

A concise sample that demonstrates connecting the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) to a Microsoft SQL Server using the Grid's CustomAdaptor to perform data binding and CRUD operations.

## Overview

This repository contains a minimal Blazor Server sample (`BlazorApp6`) showing how to wire a Syncfusion DataGrid to a SQL Server database using a custom adaptor. It demonstrates mapping Grid actions (read, insert, update, remove) to server-side database operations against the provided `NORTHWND.MDF` sample database.

## Contents

- **Sample**: A small Blazor Server app (`BlazorApp6`) that shows how to wire a DataGrid to a SQL Server database using a custom adaptor.
- **Database**: `NORTHWND.MDF` (App_Data)

## Features

- Server-side CRUD (Create, Read, Update, Delete) via a CustomAdaptor implementation
- Example mapping between Grid actions and database operations
- Minimal configuration — intended as a learning sample

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting started
### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-dataform-localization.git
cd blazor-dataform-localization
```

### Run with Visual Studio

1. Open `BlazorApp6.sln` in Visual Studio.
2. In **Server Explorer**, right-click **Data Connections** and choose **Attach DB File...**. Select `BlazorApp6/App_Data/NORTHWND.MDF` to attach the sample database.
3. Open `BlazorApp6/Data/OrderData.cs` and update the connection string to match your environment.
4. Build the solution and run the `BlazorApp6` project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- Demo: https://blazor.syncfusion.com/demos/datagrid/overview?theme=fluent2
- Documentation: https://blazor.syncfusion.com/documentation/datagrid/getting-started-with-web-app
- [Working with SQL Server in ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/working-with-sql)


