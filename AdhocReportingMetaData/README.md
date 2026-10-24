# Ad-hoc reporting (database metadata) — EasyQuery on ASP.NET MVC 5

**Ad-hoc reporting.** A basic ad-hoc reporting tool: users keep a list of reports, set up the columns and conditions of each one, and see the result as a table (with grouping and totals) or a chart.

Part of [EasyQuery samples for ASP.NET MVC 5 (.NET Framework)](../README.md).

## Tech stack

| | |
|---|---|
| Host | .NET Framework 4.6.1 |
| UI | ASP.NET MVC 5 |
| Language | C# |
| EasyQuery | 7.5.0 — `Korzh.EasyQuery.Db`, `Korzh.EasyQuery.Linq`, `Korzh.EasyQuery.DataExport`, `Korzh.EasyQuery.AspNet4`, `Korzh.EasyQuery.EntityFramework6`, `Korzh.EasyQuery.MsSqlGate` |
| EasyData | 1.6.0 — `EasyData.Exporters.ClosedXML`, `EasyData.Exporters.PdfSharp` |
| Database | SQL Server Express LocalDB |

## Prerequisites

* Windows with .NET Framework 4.6.1 (Developer Pack) and Visual Studio 2022 17.2 or later
* SQL Server Express LocalDB (installed with Visual Studio)

## Run it

### Visual Studio

1. Open `Samples.AspNet4x.MVC.sln` from the repository root.
2. Set `EqDemo.AspNet4x.AdhocReporting.Metadata` as the startup project.
3. Press F5.

## License key

EasyQuery needs a license key. Get a free 30-day trial key on
[korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-aspnet4-mvc&utm_content=AdhocReportingMetaData#get-started).

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

* [Ad-hoc reporting — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Razor.AdHocReporting)
* [Ad-hoc reporting (TypeScript) — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/RazorTypeScript.AdHocReporting)
* [Ad-hoc reporting — ASP.NET Core + Angular](https://github.com/easyquery/eq-samples-aspnetcore-angular/tree/main/AdHocReporting)
* [Ad-hoc reporting (Blazor WebAssembly) — ASP.NET Core + Blazor](https://github.com/easyquery/eq-samples-aspnetcore-blazor/tree/main/AdHocReporting.BlazorWasm)
* [Ad-hoc reporting — ASP.NET MVC 5 (.NET Framework)](https://github.com/easyquery/eq-samples-aspnet4-mvc/tree/main/AdhocReporting)
