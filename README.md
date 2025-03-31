MudBlazor 8.5.0 Code Analyzer issue.

https://github.com/MudBlazor/MudBlazor/issues/11114

[![.NET](https://github.com/perclausen/mudblazor-8.5.0-CS9057/actions/workflows/dotnet.yml/badge.svg)](https://github.com/perclausen/mudblazor-8.5.0-CS9057/actions/workflows/dotnet.yml)

Executing

```
dotnet build .\src\mudblazor-8.5.0-CS9057.csproj
```

Will produce below error:

```
CSC : error CS9057: The analyzer assembly 'C:\Users\pcl\.nuget\packages\mudblazor\8.5.0\analyzers\dotnet\cs\MudBlazor.Analyzers.dll' references version '4.13.0.0' of the compiler, which is newer than the currently runn
ing version '4.11.0.0'. [C:\Users\pcl\source\repos\perclausen\mudblazor-8.5.0-CS9057\src\mudblazor-8.5.0-CS9057.csproj]
    0 Warning(s)
    1 Error(s)
```    


