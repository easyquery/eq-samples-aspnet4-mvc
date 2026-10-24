# Advanced search — EasyQuery on ASP.NET MVC 5

**Advanced search.** A full-page query builder: users pick the columns, combine any conditions they need, run the query and work with the result — sorting, paging and export.

Part of [EasyQuery samples for ASP.NET MVC 5 (.NET Framework)](../README.md).

## Tech stack

| | |
|---|---|
| Host | .NET Framework 4.8 |
| UI | ASP.NET MVC 5 |
| Language | C# |
| EasyQuery | 7.5.0 — `Korzh.EasyQuery.Db`, `Korzh.EasyQuery.AspNet4`, `Korzh.EasyQuery.DataExport`, `Korzh.EasyQuery.EntityFramework6`, `Korzh.EasyQuery.MsSqlGate` |
| EasyData | 1.6.0 — `EasyData.Exporters.ClosedXML`, `EasyData.Exporters.PdfSharp` |
| Database | SQL Server Express LocalDB |

## Prerequisites

* Windows with .NET Framework 4.8 (Developer Pack) and Visual Studio 2022 17.2 or later
* SQL Server Express LocalDB (installed with Visual Studio)

## Run it

### Visual Studio

1. Open `Samples.AspNet4x.MVC.sln` from the repository root.
2. Set `EqDemo.AspNet4x.AdvancedSearch` as the startup project.
3. Press F5.

## License key

EasyQuery needs a license key. Get a free 30-day trial key on
[korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-aspnet4-mvc&utm_content=AdvancedSearch#get-started).

Put it into `Web.config`:

```xml
<appSettings>
  <add key="EasyQuery:LicenseKey" value="your trial key goes here" />
</appSettings>
```

## Sample database

The demo database is created and filled automatically on the first start (about a minute or
two). It uses SQL Server Express LocalDB; the connection string is in the app's configuration file.

## Related samples

* [Advanced search — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Razor.AdvancedSearch)
* [Advanced search — ASP.NET Core + Angular](https://github.com/easyquery/eq-samples-aspnetcore-angular/tree/main/AdvancedSearch)
* [Advanced search (Blazor Server) — ASP.NET Core + Blazor](https://github.com/easyquery/eq-samples-aspnetcore-blazor/tree/main/AdvancedSearch.BlazorServer)
* [Advanced search — ASP.NET Core + React](https://github.com/easyquery/eq-samples-aspnetcore-react/tree/main/AdvancedSearch)
* [Advanced search (Vue 3) — ASP.NET Core + Vue](https://github.com/easyquery/eq-samples-aspnetcore-vue/tree/main/Vue3)
* [Advanced search (Vue 2) — ASP.NET Core + Vue](https://github.com/easyquery/eq-samples-aspnetcore-vue/tree/main/Vue2)
* [Advanced search — ASP.NET Core + Stencil](https://github.com/easyquery/eq-samples-aspnetcore-stencil/tree/main/AdvancedSearch)
* [Advanced search (separate front-end and service apps) — ASP.NET MVC 5 (.NET Framework)](https://github.com/easyquery/eq-samples-aspnet4-mvc/tree/main/AdvancedSearch-Multilayered)
* [Advanced search (C#) — ASP.NET Web Forms (.NET Framework)](https://github.com/easyquery/eq-samples-aspnet4-webforms/tree/main/AdvancedSearch)
* [Advanced search (Visual Basic) — ASP.NET Web Forms (.NET Framework)](https://github.com/easyquery/eq-samples-aspnet4-webforms/tree/main/VB.AdvancedSearch)
