# test
test

1. .NET and related components

   a. For Windows, Linux and macOS, install [.NET 5.0 SDK](https://dotnet.microsoft.com/download/dotnet/5.0/) to build or run test suites.

   b. For those who work on Windows and prefer IDE, install [Visual Studio 2019](https://visualstudio.microsoft.com/downloads/) or higher ([Visual Studio 2019 Community](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16) recommended), together with these individual components from the installer:
 
      |Section|Individual Component in Visual Studio 2019|Run Windows Protocol Test Suites|Build Windows Protocol Test Suites from source code|
      |---|---|---|---|
      |.NET|.NET SDK|Required|Required|
      |Compilers, build tools, and runtime|C# and Visual Basic Roslyn compilers||Required|
      |Compilers, build tools, and runtime|MSVC v142 - VS 2019 C++ x64/x86 build tools (v14.27)||Required<sup>[1](#footnote1)</sup>|
      |Compilers, build tools, and runtime|C++/CLI support for v142 build tools (14.27)||Required<sup>[1](#footnote1)</sup>|
      |Compilers, build tools, and runtime|C++ 2019 Redistributable Update|Required<sup>[1](#footnote1)</sup>|Required<sup>[1](#footnote1)</sup>|
      |Development Activities|C++ core features||Required<sup>[1](#footnote1)</sup>|
      |SDKs, libraries, and frameworks|Windows 10 SDK (10.0.19041.0)||Required<sup>[1](#footnote1)</sup>|      

      Note:

<a name="footnote1">1</a>: This individual component is required by ADFamily and MS-SMBD which have C++ code.

1. [Protocol Test Framework v2.1 (build 2.1.0)](https://github.com/Microsoft/ProtocolTestFramework/releases/tag/2.1.0)

   Protocol Test Framework is referenced by projects of ProtoSDK and TestSuites as [NuGet packages](https://www.nuget.org/packages/Microsoft.Protocols.TestTools/2.1.0).
