# System requirements for developing nopCommerce

## Operating System

### Windows

OS | Version
------------ | -------------
Windows Client | 7 SP1+, 8.1
Windows 10 Client | Version 1607+
Windows Server | 2008 R2 SP1+

### Linux

OS | Version
------------ | -------------
Red Hat Enterprise Linux | 6
CentOS, Oracle Linux | 7
Fedora | 29, 30
Debian | 9
Ubuntu | 16.04, 18.04, 18.10
Linux Mint | 17, 18
OpenSUSE | 15+
SUSE Enterprise Linux (SLES) | 12 SP2+
Alpine Linux | 3.7+

### MacOS

OS | Version
---|---
Mac OS X | 10.12+

> [!NOTE] For more information visit [Supported OS versions](xref:https://github.com/dotnet/core/blob/master/release-notes/2.2/2.2-supported-os.md)

## 1. Supported Browsers

* Microsoft Internet Explorer 9 and above (IE6 and IE7 were supported in versions prior 3.60, IE8 was support in versions prior 4.10)
* Mozilla Firefox 2.0 and above
* Google Chrome 1.x
* Apple Safari 2.x

## 2. Tools Required for Development

Since it is based on Microsoft’s ASP.NET framework we need to install a few tools before starting developing on top of nopCommerce.

### 2.1. [.NET Core 2.2 runtime & .NET Core SDK](xref:https://dotnet.microsoft.com/download/dotnet-core/2.2)

Since nopCommerce 4.2 is based on .NET Core 2.2 framework. We need to install .NET Core 2.2 runtime and .NET Core SDK before we start development on nopCommerce.

### 2.2. [Visual Studio 2017 or Above](xref:https://visualstudio.microsoft.com/) / [Visual Studio Code](xref:https://code.visualstudio.com)

As we know nopCommerce is based on ‘Microsoft’s ASP.NET framework’ and `Visual Studio` IDE is best for developing .NET based Applications. Since .NET Core is platform independent so we can develop and deploy .NET based application on any platform but `Visual Studio` is not available in other platforms than window. So we can use `Visual Studio Code` as the alternative of `Visual Studio` for developing on Windows as well as in other platform.

### 2.3. [Microsoft SQL Server 2012 or Above](xref:https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

nopCommerce uses Entity Framework as a ORM Framework. Entity Framework is an object-relational mapper (O/RM) that enables .NET developers to work with a database using .NET objects. It can map .NET objects to various numbers of Database providers.

### 2.4. [Internet Information Service (IIS) 7.0 or above](xref:https://www.howtogeek.com/112455/how-to-install-iis-8-on-windows-8/)

For hosting nopCommerce app/project we can use IIS. Which is Microsoft technology used to host Microsoft web based applications on windows platform. But since nopCommerce 4.2 is built on top of .NET core technology. Which enables .NET developers to create platform in depend applications. So due to which we can deploy nopCommerce on multi platform like: Windows, Linux, MacOs "To learn more visit [.Net Core OS Support](xref:https://docs.microsoft.com/en-gb/dotnet/core/install/dependencies)", And can host on various hosting tools like: IIS, Apache, NGINX etc.

> [!NOTE] You can learn more about this topic from [Technology & System Requirements](xref:https://docs.nopcommerce.com/user-guide/installing/technology-system-requirements.html)