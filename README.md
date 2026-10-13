# Getting Started with the Syncfusion Blazor Media Query Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Media Query](https://www.syncfusion.com/blazor-components/blazor-mediaquery) mbly application to create responsive and adaptive user interfaces. The implementation detects viewport size changes and updates UI content based on media query breakpoints. This approach helps developers deliver optimized experiences across desktop, tablet, and mobile devices while keeping the application logic inside Blazor components.

The sample focuses on responsive design patterns using Syncfusion Blazor components and provides a practical reference for implementing adaptive layouts in modern Blazor applications.

## Key Features

- Uses the Syncfusion Media Query component to evaluate screen-width changes.
- Demonstrates responsive UI rendering based on configured media query breakpoints.
- Dynamically adapts application content according to detected viewport size.
- Registers Syncfusion Blazor services through `builder.Services.AddSyncfusionBlazor()`.
- Runs as a Blazor WebAssembly application.
- Includes a dedicated Razor page (`Pages/Index.razor`) that demonstrates responsive layout behavior using the Media Query component.
- Shows how adaptive layouts can be implemented without manually writing JavaScript viewport detection logic.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone this repository.
2. Open the repository folder in Visual Studio 2022.
3. Restore NuGet packages.
4. Set the Blazor WebAssembly project as the startup project if required.
5. Build the project.
6. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Clone this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

5. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/Index.razor` — Primary sample page demonstrating the Syncfusion Media Query component and responsive layout behavior.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the https://blazor.syncfusion.com/documentation/media-query/getting-started.

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.