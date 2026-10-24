# Data filtering — EasyQuery on ASP.NET MVC 5

**Data filtering.** Filtering and paging added to an existing data page for one entity, without the EasyQuery middleware: a few elements on the page and a few lines in the controller or page model. Includes a simple full-text search.

Part of [EasyQuery samples for ASP.NET MVC 5 (.NET Framework)](../README.md).

## Tech stack

| | |
|---|---|
| Host | .NET Framework 4.6.1 |
| UI | ASP.NET MVC 5 |
| Language | C# |
| EasyQuery | 7.5.0 — `Korzh.EasyQuery.Db`, `Korzh.EasyQuery.Linq`, `Korzh.EasyQuery.AspNet4`, `Korzh.EasyQuery.EntityFramework6` |
| Database | SQL Server Express LocalDB |

## Prerequisites

* Windows with .NET Framework 4.6.1 (Developer Pack) and Visual Studio 2022 17.2 or later
* SQL Server Express LocalDB (installed with Visual Studio)

## Run it

### Visual Studio

1. Open `Samples.AspNet4x.MVC.sln` from the repository root.
2. Set `EqDemo.AspNet4x.DataFiltering` as the startup project.
3. Press F5.

## License key

EasyQuery needs a license key. Get a free 30-day trial key on
[korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-aspnet4-mvc&utm_content=DataFiltering#get-started).

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

* [Data filtering — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Razor.DataFiltering)
* [Data filtering — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Mvc.DataFiltering)
* [Data filtering with authentication — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Mvc.DataFiltering.Auth)
