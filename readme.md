# Avalonia Prism Templates for `dotnet new`

For more information about `dotnet new` templates see [here](https://blogs.msdn.microsoft.com/dotnet/2017/04/02/how-to-create-your-own-templates-for-dotnet-new/).

## Installing the templates

Run from a command line:

```powershell
dotnet new install Avalonia.Prism.Templates
```

[//]: # (The templates should now be available in `dotnet new list`:)

[//]: # ()
[//]: # (```)

[//]: # (Template Name                        Short Name                 Language  Tags)

[//]: # (-----------------------------------  -------------------------  --------  -----------------------------------------)

[//]: # (Avalonia .NET Core App               avalonia.app               [C#],F#   Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (Avalonia .NET Core MVVM App          avalonia.mvvm              [C#],F#   Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (Avalonia Cross Platform Application  avalonia.xplat             [C#],F#   Desktop/Xaml/Avalonia/Web/Mobile)

[//]: # (Avalonia Resource Dictionary         avalonia.resource                    Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (Avalonia Styles                      avalonia.styles                      Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (Avalonia TemplatedControl            avalonia.templatedcontrol  [C#]      Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (Avalonia UserControl                 avalonia.usercontrol       [C#],F#   Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (Avalonia Window                      avalonia.window            [C#],F#   Desktop/Xaml/Avalonia/Windows/Linux/macOS)

[//]: # (```)

[//]: # (**Note:**)

[//]: # ()
[//]: # (By default dotnet CLI would create a **C#** template,if you want to create **F#** template you will need to add ```-lang F#``` to the end of the command.)

# Creating a new Application

To create a new barebones application called `MyApp` in its own subdirectory, run:

```
dotnet new avalonia.prism.dialog -o MyApp
```

Available parameters:

``-A, --AvaloniaVersion``

*Description*: The target version of Avalonia NuGet packages.

*Options*: **0.10.18**, **11.0.0-preview4**

*By default*: 0.10.18
