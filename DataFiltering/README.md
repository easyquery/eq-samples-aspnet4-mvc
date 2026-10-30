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

You don't need one to start. On the first run the sample shows a **No license** dialog: enter your
email, then the code we send to it, and you get a free 30-day trial key on the spot. This sample has no EasyQuery API to save the key through, so take it from your account page on
korzh.com, as the dialog says, and put it into `Web.config` yourself.

Already have a key? Put it into `Web.config` and the dialog won't appear:

```xml
<appSettings>
  <add key="EasyQuery:LicenseKey" value="your key goes here" />
</appSettings>
```

Ready to buy? See the [licensing options on korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-aspnet4-mvc&utm_content=DataFiltering#licensing).

## Sample database

The demo database is created and filled automatically on the first start (about a minute or
two). It uses SQL Server Express LocalDB; the connection string is in the app's configuration file.

## Related samples

* [Data filtering — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Razor.DataFiltering)
* [Data filtering — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Mvc.DataFiltering)
* [Data filtering with authentication — ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc/tree/main/Mvc.DataFiltering.Auth)
