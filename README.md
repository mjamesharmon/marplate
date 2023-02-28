# Marplate
*A Minimalist Slide/Presentation Template*/

Marplate is for developers (or anyone else) who dislike using tools like PowerPoint for presentations and just want to stick with the tools they already know and love.  It's a markdown-based slide template optimized for use with VS Code (or the editor of your choice… hullo VI). Built on the [Marp Presentation Ecosystem](https://marp.app/) and the [.NET Core Template Engine](https://github.com/dotnet/templating/), Marplate is a minimalist solution that simplifies formatting and layout, so you can focus on creating beautiful presentations.

## Requirements
- .Net 6 or better
- VS Code or editor of your choice
- Marp extension for VS Code

## Installing with the .Net Core Template Engine
To install the template for use with the template engine, clone the repository and execute the following commands:
```console
  cd marplate/src
  dotnet pack -c Release
  dotnet new install bin/Debug/Marplate.1.0.0.nupkg
```

## Creating a New Presentation
To create a new presentation execute:
```console
   dotnet new marplate --name <presentation>
```

Open VS Code and enjoy a life free of PowerPoint :)

## Configuring Theme from the Command Line
THe primary, secondary and tertiary colors can be configured from the command line:

```console
Template options:
  -p, --primaryColor <primaryColor>      Type: string
                                         Default: #1B9CDF
  -s, --secondaryColor <secondaryColor>  Type: string
                                         Default: #CCCCCC
  -te, --tertiaryColor <tertiaryColor>   Type: string
                                         Default: #FFBD3E
```
