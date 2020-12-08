# OneDark.Avalonia

A simple OneDark theme for Avalonia generated with Avalonia Theme Editor

### Getting Started

The easiest way to get started is to install the library as a NuGet package:

```powershell
Install-Package OneDark.Avalonia
# Or 'dotnet add package OneDark.Avalonia'
```

Then, reference the preffered theme from your `App.xaml` file:

```xml
<Application xmlns="https://github.com/avaloniaui"
             xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
             x:Class="YourNamespace.App">
  <Application.Styles>
    <!-- Keep default theme has this thme only ovveride some styles -->
    <StyleInclude Source="avares://Avalonia.Themes.Default/DefaultTheme.xaml"/>
    <!-- OneDark.Avalonia theme
    <StyleInclude Source="avares://OneDark.Avalonia/OneDark.xaml"/>
  </Application.Styles>
</Application>
```

### Technologies and Tools Used

- <a href="https://github.com/avaloniaui">AvaloniaUI</a> cross-platform XAML-based GUI framework
- <a href="https://github.com/wieslawsoltes/ThemeEditor">Avalonia Theme Editor</a> an Avalonia UI Framework theme editor.
