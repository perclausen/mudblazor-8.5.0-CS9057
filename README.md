MudBlazor 8.5.0 Code Analyzer issue.


Executing

```
dotnet build .\src\mudblazor-8.5.0-CS9057.csproj
```

Will produce below error:

```
CSC : warning CS9057: The analyzer assembly 'C:\Users\pcl\.nuget\packages\mudblazor\8.5.0\analyzers\dotnet\cs\MudBlazor.Analyzers.dll' references version '4.13.0.0' of the compiler, which is newer than the currently ru
nning version '4.11.0.0'. [C:\Users\pcl\source\repos\perclausen\mudblazor-8.5.0-CS9057\src\mudblazor-8.5.0-CS9057.csproj]
    1 Warning(s)
    0 Error(s)
```    


