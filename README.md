# Blazor DataGrid — Filter by Multiple Keywords using Filter Menu

A sample Blazor application demonstrating how to perform filtering on a [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) column with multiple values programmatically using the [Blazor MultiSelect Dropdown](https://www.syncfusion.com/blazor-components/blazor-multiselect-dropdown) component in a custom filter menu.

## Overview

This repository demonstrates how to implement advanced filtering in a Blazor DataGrid using the Syncfusion components. Instead of using the default filter operator UI, this sample replaces the filter template for the "Customer Name" column with a `Blazor MultiSelect Dropdown` component, enabling users to select multiple values at once and filter the grid programmatically.

The filtering is performed using the Blazor DataGrid's `FilterByColumnAsync` method with the `or` logical operator, allowing flexible data queries across multiple keywords.

## Features

- **Multi-select filtering**: Filter DataGrid columns using a multi-select dropdown with checkboxes
- **Custom filter templates**: Replace default filter UI with custom Syncfusion components
- **Programmatic filtering**: Use `FilterByColumnAsync` to apply complex filter logic
- **User-friendly UI**: Intuitive checkbox-based selection for multiple filter values
- **Select All functionality**: Built-in "Select All" option in the multi-select component
- **Sample data**: Pre-populated grid with realistic order data

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-filter-by-multiple-keywords-using-filter-menu.git
cd blazor-datagrid-filter-by-multiple-keywords-using-filter-menu
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

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/filter-menu

**Online example**: https://blazor.syncfusion.com/demos/datagrid/filter-menu?theme=fluent2
