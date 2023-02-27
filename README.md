# Marplate
*A Minimalist Slide/Presentation Template*

Marplate is the answer for any developer that has been tasked with making a presentation and have found themselves asking "Why use PowerPoint when I could be using tools I already know and love?"  Marplate is a markdown-based slide template, optimized for use with VS Code (or your editor of choice...looking at you VI) and powered by Marp.  It is minimalist – As templated, basic formatting and layout may be tweaked but the point is to let you focus on the content and not battle with tools. Marplate is built on the [Marp Presentation Ecosystem](https://marp.app/)  and the the [.NET Core Template Engine](https://github.com/dotnet/templating/).

## Requirements
- .Net 6 or better
- VS Code or editor of your choice

## Installing with the .Net Core Template Engine
To install the template for use with the template engine, clone the repository and execute the following commands:
```console
  cd marplate
  dotnet new -i templates/minimal/
```

## Creating a New Presentation
To create a new presentation execute:
```console
   dotnet new marp.minimal --name <presentation>
```

Open VS Code and enjoy a life free of PowerPoint :)
