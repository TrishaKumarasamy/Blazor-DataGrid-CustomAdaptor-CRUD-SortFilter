# Blazor DataGrid with CustomAdaptor

A complete example demonstrating how to build a data-driven Blazor application using [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) with a custom data adaptor for CRUD operations and advanced data operations like sorting, filtering, and paging.

## Overview

This sample project showcases best practices for building scalable data management solutions in Blazor. It demonstrates:

- **Server-side Data Binding** - Efficiently load and manage data on the server
- **CRUD Operations** - Seamlessly perform Create, Read, Update, and Delete operations
- **Advanced Filtering** - Filter data with multiple conditions
- **Sorting** - Sort data by multiple columns in ascending or descending order
- **Paging** - Handle large datasets with efficient pagination

The application uses `CustomAdaptor` pattern, which extends the `DataAdaptor` class to implement custom Read, Insert, Update, and Remove methods, giving you full control over how data is fetched and manipulated.

## Features

- **Sorting and Filtering**:  Define custom logic for fetching data with sorting and filtering
- **Insert Operation**: Handle INSERT operations when users add new records
- **Update Operation**: Handle UPDATE operations when users modify existing records
- **Delete Operation**: Handle DELETE operations when users remove records

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/Blazor-DataGrid-CustomAdaptor-CRUD-SortFilter.git
cd Blazor-DataGrid-CustomAdaptor-CRUD-SortFilter
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/connecting-to-adaptors/custom-adaptor

**Online examples**: https://blazor.syncfusion.com/demos/datagrid/custom-binding?theme=bootstrap5


