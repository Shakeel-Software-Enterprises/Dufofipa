# Dufofipa

## Duplicate Folders and Files Probe Agent

Dufofipa is a Windows desktop application designed to help users identify and manage duplicate files, duplicate folders, and empty folders.

It provides tools for scanning selected locations, identifying files and folders that may be duplicates, comparing files, reviewing scan results, and performing selected file and folder management operations.

---

## Features

- Scan for empty folders.
- Scan for duplicate files.
- Scan for duplicate folders containing files.
- Compare files to determine whether their contents are identical.
- Review scan results before taking action.
- Mark selected files and folders for further operations.
- Remove selected files and folders.
- Move or merge files and folders where supported.
- Perform file-management operations with a focus on user review before changes are made.
- Maintain operation information required for supported do/redo operations.
- Provide an integrated Help system.

Dufofipa is intended to assist users in finding unnecessary duplicates and organizing their file collections.

**Always review scan results carefully before deleting, moving, or otherwise modifying files or folders.**

---

## Download

The latest version of Dufofipa is available from the official GitHub Releases page:

**[Download Dufofipa Releases](https://github.com/Shakeel-Software-Enterprises/Dufofipa/releases)**

Two installation options are provided.

### Standard Version

The Standard version is a framework-dependent installation.

It is recommended for computers that already have the required Microsoft .NET 10 Windows Desktop Runtime installed.

**Advantages:**

- Smaller application download.
- Uses the .NET runtime already installed on the computer.
- Suitable for systems that already have the required .NET 10 runtime.

**Requirements:**

- Microsoft .NET 10 Windows Desktop Runtime.
- Microsoft Edge WebView2 Runtime for the integrated Help system.

If the required .NET 10 Windows Desktop Runtime is not detected, the Standard installer will guide you to the official Microsoft .NET download page.

If Microsoft Edge WebView2 Runtime is not available, the installer will guide you to the official Microsoft WebView2 download page.

### Standalone Version

The Standalone version is a self-contained installation.

It includes the required .NET runtime components and is intended for users who prefer not to install the .NET runtime separately.

**Advantages:**

- Does not require a separate installation of the .NET 10 runtime.
- Suitable for computers where the required .NET runtime is not already installed.
- Provides a more convenient installation experience on systems without the required .NET runtime.

The Microsoft Edge WebView2 Runtime is still required for the integrated Help system.

---

## System Requirements

### Operating System

Dufofipa is designed for 64-bit Windows systems compatible with the application's .NET 10 Windows Desktop Runtime requirements.

A 64-bit Windows environment is required for the current release.

### Standard Version

The Standard version requires:

- Microsoft .NET 10 Windows Desktop Runtime.
- Microsoft Edge WebView2 Runtime for the integrated Help system.

### Standalone Version

The Standalone version includes the required .NET runtime components.

Microsoft Edge WebView2 Runtime is still required for the integrated Help system.

---

## Microsoft Edge WebView2 Runtime

Dufofipa uses Microsoft Edge WebView2 for its integrated Help system.

If WebView2 Runtime is not available on your computer, the installer will guide you to the official Microsoft WebView2 download page.

For security and reliability, always obtain WebView2 Runtime from the official Microsoft website.

Microsoft WebView2 download page:

**https://developer.microsoft.com/en-us/microsoft-edge/webview2/**

---

## Installation

### Standard Version

1. Download the Standard installer from the official GitHub Releases page.
2. Run the installer.
3. Follow the installation instructions.
4. If the required .NET 10 Windows Desktop Runtime is not detected, follow the instructions provided by the installer.
5. If WebView2 Runtime is required, follow the instructions provided by the installer.
6. Complete the installation.
7. Launch Dufofipa from the Windows Start Menu or from the Desktop shortcut if one was created during installation.

### Standalone Version

1. Download the Standalone installer from the official GitHub Releases page.
2. Run the installer.
3. Follow the installation instructions.
4. If WebView2 Runtime is required, follow the instructions provided by the installer.
5. Complete the installation.
6. Launch Dufofipa from the Windows Start Menu or from the Desktop shortcut if one was created during installation.

---

## Desktop Shortcut

During installation, you can choose whether to create a Desktop shortcut.

If the Desktop shortcut option is selected, Dufofipa can be launched directly from the Windows Desktop.

If the option is not selected, Dufofipa remains available through the Windows Start Menu.

---

## Getting Started

After launching Dufofipa:

1. Select the appropriate operation from the available options.
2. Add the folders or locations you want to examine.
3. Start the selected scan.
4. Wait for the scan to complete.
5. Review the results carefully.
6. Select the files or folders on which you want to perform an operation.
7. Perform the desired operation.

Because file-management operations may affect data on your computer, always review the results carefully before confirming an operation.

It is strongly recommended that important personal data be backed up before performing operations that delete, move, or otherwise modify files.

---

## Data and Privacy

Dufofipa is designed as a Windows desktop application that operates on files and folders selected by the user.

The application does not require users to create an online account to perform its primary file and folder scanning functions.

The primary scanning and file-management operations are performed locally on the user's computer.

Dufofipa does not require users to upload their files to an online service in order to perform its primary functions.

Users should review the application's behavior and permissions before using it on sensitive or important data.

---

## Application Data

Dufofipa may create application data required for its operation, including temporary data used to support application operations.

The application stores its temporary operational data in the appropriate user-accessible application data location rather than requiring routine write access to the application's installation directory.

---

## Safety and Data Protection

Dufofipa is a file-management utility. Some operations may result in files or folders being moved, deleted, or otherwise modified.

Before performing an operation:

- Review the scan results carefully.
- Confirm that the selected files and folders are the intended ones.
- Keep backups of important data.
- Do not delete files solely because they appear to have the same name.
- Verify duplicate-file results before deleting anything.
- Be particularly careful when working with system folders or application directories.

The user is responsible for reviewing and confirming operations performed using Dufofipa.

---

## Release Information

### Current Release

**Version:** 1.1.0

**Release Type:** First Public Release

Dufofipa 1.1.0 is the first public release of the application.

This release provides two installation options:

- Standard Installer
- Standalone Installer

For detailed release-specific information, see the release notes associated with the corresponding GitHub Release.

---

## Download the Latest Release

To download the latest version of Dufofipa, visit the official GitHub Releases page:

**[Download Dufofipa](https://github.com/Shakeel-Software-Enterprises/Dufofipa/releases)**

Available installation packages may include:

- **Standard Installer** — Framework-dependent installation requiring the Microsoft .NET 10 Windows Desktop Runtime.
- **Standalone Installer** — Self-contained installation that includes the required .NET runtime components.

Always download installers from the official Dufofipa GitHub repository or another official distribution channel maintained by Shakeel Software Enterprises.

---

## Documentation

Additional documentation and Help resources are provided with the application where applicable.

For application-specific guidance, refer to the integrated Help system included with Dufofipa.

---

## End User License Agreement

Dufofipa is distributed subject to the End User License Agreement (EULA).

Please read the EULA before installing or using the software.

The EULA is provided with the official release package and is also presented during installation.

By installing or using Dufofipa, you agree to the applicable terms and conditions of the EULA.

---

## Support and Bug Reports

If you encounter a problem with Dufofipa, please provide as much information as possible when reporting the issue.

Useful information includes:

- Dufofipa version.
- Windows version.
- Whether you are using the Standard or Standalone version.
- A description of the problem.
- Steps required to reproduce the problem.
- Relevant error messages.
- Screenshots, where appropriate.
- Any relevant information about the files or folders involved.

Please do not include personal or sensitive information in a public issue report.

Bug reports and feature requests can be submitted through the **[Issues](https://github.com/Shakeel-Software-Enterprises/Dufofipa/issues)** section of the Dufofipa GitHub repository.

---

## Project

**Dufofipa**  
**Duplicate Folders and Files Probe Agent**

Developed and maintained by:

**Shakeel Software Enterprises**

Official GitHub repository:

**https://github.com/Shakeel-Software-Enterprises/Dufofipa**

---

## Source Code

The Dufofipa source code is maintained privately by Shakeel Software Enterprises and is not publicly distributed through this repository.

This public repository is intended for distributing the software, release information, documentation, and associated public release materials.

---

## License

Dufofipa is distributed under the terms specified in the accompanying End User License Agreement.

The software, installers, documentation, and associated materials remain the property of Shakeel Software Enterprises unless otherwise stated.

---

## Disclaimer

Dufofipa is provided subject to the terms of the applicable End User License Agreement.

Although care is taken in the development and testing of the application, users should maintain appropriate backups of important data before performing file-management operations.

Shakeel Software Enterprises is not responsible for data loss resulting from the use or misuse of the software, to the extent permitted by applicable law and subject to the terms of the applicable End User License Agreement.

---

**© 2026 Shakeel Software Enterprises. All rights reserved.**