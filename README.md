# Blazor DataGrid - Calculated Columns with Dialog Editing

A sample Blazor application demonstrating how to automatically update calculated columns in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component when editing values through a dialog interface.

## Overview

This repository demonstrates how to implement reactive calculated columns in a Blazor DataGrid component. When users edit price and quantity values through a dialog, the total amount is automatically recalculated and updated without requiring manual computation or page refresh.

## Features

- **Real-time Calculations**: Automatic total computation based on price and quantity inputs
- **Dialog-Based Editing**: Edit form with inline number inputs for a polished user experience
- **Reactive Components**: Uses Blazor event bindings to trigger instant updates
- **Validation**: Built-in validation rules for required fields
- **Formatting**: Currency formatting (C2) for financial data display

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`InsideDialogEditing.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-calculated-columns-inside-dialog-editing
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/in-line-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=fluent2