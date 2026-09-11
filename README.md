# Blazor DataGrid – Custom Command Editing

## Overview

This sample demonstrates how to perform editing operations in the Syncfusion Blazor DataGrid (`SfGrid`) using custom command buttons. The Grid is configured with built-in CRUD support through `GridEditSettings`, while row-level editing actions are exposed through a dedicated command column. Users can edit, delete, save, and cancel changes directly from the Grid by clicking command buttons without relying on double-click editing.

## Key Features

- Uses the Syncfusion Blazor `SfGrid` component with a strongly typed data source.
- Binds data using the `DataSource` property (`Orders` collection).
- Configures editing using `GridEditSettings`:
  - `AllowAdding="true"`
  - `AllowEditing="true"`
  - `AllowDeleting="true"`
  - `AllowEditOnDblClick="false"`
- Uses a custom command column implemented with `GridCommandColumns`.
- Provides row-level CRUD actions through:
  - `CommandButtonType.Edit`
  - `CommandButtonType.Delete`
  - `CommandButtonType.Save`
  - `CommandButtonType.Cancel`

## Prerequisites

- Visual Studio 2022 or later
- .NET SDK compatible with the project's target framework

## How to Run the Project

1. Clone or download this repository to your local machine.
2. Open `CustomCommandEditing.sln` in Visual Studio 2022.
3. Restore NuGet packages if they are not restored automatically.
4. Build the solution.
5. Run the project using **F5** or **Ctrl+F5**.
6. Navigate to the page containing the DataGrid sample.
7. Use the command buttons in the **Manage Records** column:
   - Click **Edit** to modify a row.
   - Click **Delete** to remove a row.
   - Click **Save** to commit changes.
   - Click **Cancel** to discard changes.

## Project Structure

- `Pages/Index.razor` — contains the `SfGrid` implementation, column definitions, command button configuration, sample data generation, and the `Order` model.

## Support and Feedback
- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Full documentation on Blazor DataGrid globalization and localization: https://blazor.syncfusion.com/documentation/datagrid/global-local

## License
This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/teamlicense) before using Syncfusion components in your own applications.