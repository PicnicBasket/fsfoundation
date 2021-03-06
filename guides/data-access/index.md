---
layout: default
title: Guide - Data Access | The F# Software Foundation
headline: Guide - Data Access with F#
redirect_from: "/data-access/index.html"
---

F# supports all common data import and access techniques. In addition, the type provider feature of 
F# brings simplicity and flexibility to accessing data, including databases, web-scale data and structured 
text formats like JSON, and XML.  

If the data access libraries you need are not listed here, you can search for them on [nuget](http://nuget.org).  [Try F#](http://tryfsharp.org/learn) also contains specific tutorials related to data access. 


<div class="jumbotron visible-lg calloutBox" id="how-to-add-testimonial"> 
    <p>This guide includes resources related to data access with F#. To contribute to this guide, log on to GitHub, <a href="https://github.com/fsharp/fsfoundation/edit/gh-pages/guides/data-access/index.md">edit this page</a> and send a pull request.</p>
    <hr />
    <p>Note that the resources listed below are provided only for educational purposes related to the F# programming language. The F# Software Foundation does not endorse or recommend any commercial products, processes, or services. Therefore, mention of commercial products, processes, or services should not be construed as an endorsement or recommendation.</p>
</div>              

## Resources for Data Access

* auto-gen TOC:
{:toc}


### CSV, HTML, JSON and XML data

Many [NuGET](http://nuget.org) packages exist for document access. Some specific frameworks dedicated to simplifying document data access include:

#### FSharp.Data

[FSharp.Data](http://fsharp.github.io/FSharp.Data/) - The F# Data library (FSharp.Data.dll) implements functionality to access data in your F# applications and scripts. 
   
It implements F# type providers for working with structured file formats (CSV, HTML, JSON and XML) and for accessing the WorldBank and Freebase services. It also includes helpers for parsing CSV, HTML and JSON files and for sending HTTP requests.

#### Json.NET

[Json.NET](http://json.codeplex.com/) provides full support for serialization of F# types to and from JSON

#### Direct access to CSV and other log file formats
 
Direct access to CSV and other log file formats is simple. For example, see [Log File Analysis with F#](http://jyliao.blogspot.co.uk/2011/03/log-analysis-with-f.html)


### SQL Data Access

A wide range of high-quality libraries exist for SQL data access from F#. Many can be found on [NuGET](http://nuget.org).
Some resources are listed below:

#### FSharp.Data.SqlClient

[FSharp.Data.SqlClient](http://fsprojects.github.io/FSharp.Data.SqlClient/) - Use SQL to specify your queries, explore Stored Procedures, User Defined Types and Functions with IntelliSense right in your F# code.

#### FSharp.Data.SQLProvider

[FSharp.Data.SQLProvider](http://fsprojects.github.io/SQLProvider/) - A general SQL database type provider, supporting LINQ queries, schema exploration, individuals and much more besides.

#### SqlDataConnection Type Provider
The [SqlDataConnection Type Provider](http://msdn.microsoft.com/en-us/library/hh361033.aspx) - For accessing SQL using F# 3.0 LINQ queries

#### SqlEntityConnection Type Provider

[The SqlEntityConnection Type Provider](http://msdn.microsoft.com/en-us/library/hh361035.aspx) - For accessing SQL using F# 3.0 LINQ queries and Entity Framework

#### ADO.NET

[ADO.NET](http://msdn.microsoft.com/en-us/library/aa286484.aspx) - A set of classes that expose data access services to the .NET programmer

### Web Data Stores

F# allows for the direct integration of scalable data stores into F# programming. Some specific examples are:

#### Freebase 

[Freebase](http://freeebase.com) - A type provider for Freebase is available in the [FSharp.Data](http://fsharp.github.io/FSharp.Data/) library

#### World Bank

[World Bank](http://worldbank.org) - A type provider for the World bank data sets is available in the [FSharp.Data](http://fsharp.github.io/FSharp.Data/) library

### Exploratory Data Frame and Time Series Programming

* See the [Data Science](/guides/data-science) guide for more information on data science with F#.



