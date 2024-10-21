# Avalonia Hello World App

Simple hello world app initially created with Visual Studio 2022 for Mac using the Avalonia templates available here:

https://github.com/Noemata/AvaloniaTemplatesMac

The original barebones Avalonia app template is too minimal.  Provided additions give you what you need for quick and dirty work.

## Credits

Starting point: https://github.com/AvaloniaUI/avalonia-dotnet-templates

## Screenshots
![Screenshot](https://github.com/Noemata/AvaloniaHelloWorld/blob/master/Screenshot.png)

## Notes

This is also an example of a minimal MVVM pattern where the code behind is used as the model.

Look at the releases section for a current build of the templates nuget package.

## To uninstall templates:

dotnet new uninstall Avalonia.Templates

## To install templates from nuget package:

dotnet new install Avalonia.Templates.11.1.4.nupkg

## To create this hello world app:

dotnet new avalonia.app -o AvaloniaHelloWorld
