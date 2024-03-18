# Installation Guide

This guide provides instructions for installing the necessary DLL files for using Microsoft Report Viewer WinForms and Microsoft Visual Basic Power Packs in your Visual Basic project.

## Prerequisites

Before proceeding with the installation, ensure you have the following:

- Visual Studio installed on your system.
- Access to the installation files for Microsoft Report Viewer WinForms and Microsoft Visual Basic Power Packs.

## Installation Steps

### 1. Microsoft Report Viewer WinForms

1. Navigate to the folder where you have the installation files for Microsoft Report Viewer WinForms.
2. Run the installer file (`ReportViewer.msi` or similar).
3. Follow the on-screen prompts to complete the installation.
4. After installation, locate the `Microsoft.ReportViewer.WinForms.dll` file. This file is typically located in one of the following directories:
   - Global Assembly Cache (GAC) (`C:\Windows\Microsoft.NET\assembly`)
   - Installation directory of Report Viewer (e.g., `C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\ReportViewer`)
5. Remember or note down the path to the `Microsoft.ReportViewer.WinForms.dll` file for reference when adding the reference to your Visual Studio project.

### 2. Microsoft Visual Basic Power Packs

1. Navigate to the folder where you have the installation files for Microsoft Visual Basic Power Packs.
2. Run the installer file (`PowerPacksSetup.exe` or similar).
3. Follow the on-screen prompts to complete the installation.
4. After installation, locate the `Microsoft.VisualBasic.PowerPacks.dll` file. This file is typically located in one of the following directories:
   - Global Assembly Cache (GAC) (`C:\Windows\Microsoft.NET\assembly`)
   - Installation directory of Visual Basic Power Packs (e.g., `C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Visual Basic Power Packs`)
5. Remember or note down the path to the `Microsoft.VisualBasic.PowerPacks.dll` file for reference when adding the reference to your Visual Studio project.

## Adding References to Your Project

Once you have located the DLL files for both Microsoft Report Viewer WinForms and Microsoft Visual Basic Power Packs, you can add references to your Visual Studio project by following these steps:

1. Open your Visual Basic project in Visual Studio.
2. Right-click on your project in the Solution Explorer and select "Add" > "Reference...".
3. In the Reference Manager window, click on the "Browse" button.
4. Navigate to the directory where you located the `Microsoft.ReportViewer.WinForms.dll` and `Microsoft.VisualBasic.PowerPacks.dll` files.
5. Select the DLL files and click "OK" to add them as references to your project.

## Additional Notes

- Ensure that the versions of the DLL files you have installed match the requirements of your project and Visual Studio environment.
- After adding the references, rebuild your project to ensure that the DLLs are correctly linked and accessible during compilation.
