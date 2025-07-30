# theForger's Win32 API Tutorial

Archival repository for [theForger's Win32 API Tutorial](https://winprog.org/tutorial/).
 It includes the website, .pdfs, source code, binaries, and extras!

--------------------------------------------------------------------------------

[bin](/bin): Contains pre-built .exes of all the projects. All are 32 bit and capable of running on Windows XP SP2+:  
 - [rel](/bin/rel): Release builds.  
 - [dbg](/bin/dbg): Debug builds with .pdb symbols.

[pdfs](/pdfs): Contains .pdf versions of the older version 2.0 of the tutorial, in Chinese, Arabic, and English.

[source](/source): Contains the source code. The original Visual Studio 2008 .sln is in [source/Backup](/source/Backup), but the projects have
 been updated to Visual Studio 2022 + Windows XP support (Follow steps [Here](https://learn.microsoft.com/en-us/cpp/build/configuring-programs-for-windows-xp) to configure MSVS for that).

[website](/website): Contains a copy of the website for offline viewing. Simply open [index.html](website/tutorial/index.html) in your browser of choice.

## Considerations
The projects successfully compile, but the source code and compiler/linker settings are dated, and so may generate compiler and security warnings during the build. 
These warnings don't stop the builds, but I strongly recommend you heed them before using any code in production. Remember that this is decades old Win32 code;
  depending on what you're trying to do, more modern approaches such as [C++/WinRT](https://learn.microsoft.com/en-us/windows/uwp/cpp-and-winrt-apis/),
  [WinUI 3](https://docs.microsoft.com/en-us/windows/apps/winui/winui3/), [wxWidgets](https://www.wxwidgets.org/), [Qt](https://www.qt.io/),
  [Ultimate++](https://www.ultimatepp.org/), [Boost](https://www.boost.org/), [POCO C++](https://pocoproject.org/),
  and/or newer additions to the C++ standard library (i.e. C++11 onwards) may be more appropriate.

When using any win32 code from this repo in production, always consult the [Windows API Index](https://docs.microsoft.com/en-us/windows/win32/apiindex/windows-api-list)
 for relevant and updated API usage notes, as some APIs may have since been deprecated or had their behaviour modified in newer versions of Windows.

## Additional resources
* [Build desktop Windows apps using the Win32 API](https://docs.microsoft.com/en-us/windows/win32/)
* [Get Started with Win32 and C++](https://docs.microsoft.com/en-us/windows/win32/learnwin32/learn-to-program-for-windows)
* [Windows API Index](https://docs.microsoft.com/en-us/windows/win32/apiindex/windows-api-list)
* [COM and ATL](https://docs.microsoft.com/en-us/cpp/atl/introduction-to-com-and-atl)
* [C++/WinRT](https://docs.microsoft.com/en-us/windows/uwp/cpp-and-winrt-apis/)
* [Source code for Charles Petzold's Programming Windows 5th edition](https://github.com/yottaawesome/programming-windows-5th-edition)
* [Source code for Jeffrey Richter and Christophe Nasarre's Windows via C/C++ 5th edition](https://github.com/yottaawesome/windows-via-c-cpp)
* [ZetCode's Windows API tutorial](https://zetcode.com/gui/winapi/)

Source Code does not belong to me. Copyrights remain with [theForger a.k.a. forgey](https://winprog.org/regulars/).
Website thanks to [winprog.com](https://winprog.org).
