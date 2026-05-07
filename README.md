# GUID Manager Extension

A simple Visual Studio extension built using C# and VSIX that helps developers quickly generate and automatically copy GUIDs directly inside Visual Studio.

## Features

* Generate unique GUIDs instantly
* Automatically copies generated GUID to clipboard
* Simple and clean tool window UI
* Integrated inside Visual Studio
* Reduces repetitive copy-paste workflow during development and testing

## Purpose

This extension was developed to simplify the workflow of generating GUIDs frequently during development and testing activities. Instead of switching between external tools or websites, developers can generate GUIDs directly inside Visual Studio.

## Technologies Used

* C#
* WPF (XAML)
* VSIX Extension Framework
* Visual Studio SDK

## Current Functionality

1. Open the extension tool window inside Visual Studio
2. Click the "Generate GUID" button
3. A new GUID is generated automatically
4. The GUID is copied to clipboard automatically for immediate use

## Project Structure

* `GUID.xaml` → User Interface
* `GUID.xaml.cs` → GUID generation logic
* `ToolWindow1.cs` → Tool window setup
* `GUID_EXTENTIONPackage.cs` → Extension package initialization

## Future Improvements

* Support for multiple GUID formats
* Improved UI design
* Extension icon and branding
* VSIX packaging for distribution
* Better clipboard handling and notifications

## Screenshots

*Add screenshots of the extension UI here.*

## Author

Developed as part of Visual Studio Extension learning and project implementation.
