# Chapter 1
# 2023-08-08

modern .NET: 7, 6,5
.NET Core

legacy .NET: .NET Framwork, Mono, Xamarin, .NET Standard

## Installation

Visual Studio
Visual Studio Code
.NET 6 SDK
.NET 7 SDK

## Definitions

.NET Framework: Common Language Runtime (CLR) - manages the execution of code
Base CLass Library (BCL) - provides a library of classes
Since .NET Framework 4.5.2, it has been an offical component of the Windows OS and is rarely updated

.NET Framwork is Windows only and a legacy platform. Do not create new apps using it (although I'm sure jobs have a requirement to maintain 
legacy applications using Framework)

Framework implementations:
Xamarin / Mono is a mobile development platform
Unity is a game engine

.NET (formally .NET Core) is the modern cross platform (Windows, Mac, Linux, Web) development env
.NET Core was the modernization product to separate Windows exclusiveity from .NET

Blazor WebAssembly - addon to .NET for building web components

ASP.NET - legacy web app platform

ASP.NET Core runs on modern .NET and bundles ASP.NET, MVC, ASP.NET Web API, SignalR, gRPC

Entity Framwork Core (formallyEntity Framework 6 (EF6)) (I'm assuming is an equilvant to Hibernate) is an ORM technology that is designed to work with data that is stored in relational databases such as Oracle and SQL Server. It also supports noSQL dbs like Azure Cosmos DB.

.NET Standard - a legacy API specification for all flavors of .NET. Enables developers to share code between any flavor of .NET. This is not really needed as modern .NET is for all platforms including web and mobile, but for legacy framework apps, there is backwards compatiblity

CoreCLR - (I'm assuming similar to the JVM) .NET's virtual machine

C# code is complied into an intermediate language > executed by CoreCLR > just-in-time complier (JIT) complies it into native CPU instructions. 

Top Level-Program: introduced in .NET 5, it generates boilerplate code to define a namepace, the `Program` class wrap its `Main` 
method around the statements you write.


<Main>$ is the entry point method of a .NET app when created by the complier

<projectname>\bin\Debug\net7.0 is the working directory for running programs in Visual Studio 2022

the `dotnet` CLI executes programs from the <projectname> folder
