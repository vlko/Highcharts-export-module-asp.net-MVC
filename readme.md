## Tek4.Highcharts.Exporting assembly for Asp.NET MVC

Tek4 ASP.NET Exporting Module for Highcharts JS (http://highcharts.com/).
Version 1.0.3.0 (December 5, 2014)

* Updated for Asp.NET MVC usage and custom font override 
* Based upon ASP.NET Highcharts export module by Clément Agarini (June 15, 2011).
* Re-written by Kevin P. Rice (http://tek4.com/).
* Utilizes customized Svg.dll provided by OlgaD (https://github.com/imclem/Highcharts-export-module-asp.net/issues/1).


## Quick start

### Demo web site ###
* Visual Studio: Open the solution (.sln) and run the demo website.
* Asp.net MVC demo application.

### Your web site ###
* Copy the three .dll files from the demo website /bin directory to your website /bin directory (Tek4.Highcharts.Exporting.dll, itextsharp.dll, Svg.dll).
* Review the demo website and imlement custom Graph controller with Export action.


## Features

* Exports Highcharts JS charts to PNG/JPG/PDF/SVG.
* Uses three precompiled .DLL files in /bin directory and configuration via web.config.
* Supports Highcharts exporting 'width' option to generate high quality images of any size (PDF images are exported at 150 dpi).
* Supports Highcharts exporting 'filename' option to specify downloaded file name.
* Works with .NET 4.0 Framework and later.
* Visual Studio 2013 solution/project files included (targeted to .NET 4.0).


## Project Home

* https://github.com/vlko/Highcharts-export-module-asp.net-MVC


## License

Re-distributed works listed below are not subject to this license. These
works are separately licensed according to their terms.

Copyright (C) 2012 by Tek4(TM) - Kevin P. Rice

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


## Redistributed components (separately licensed):

* SVG Rendering Engine (Svg.dll): http://svg.codeplex.com/
* iTextSharp (itextsharp.dll): http://sourceforge.net/projects/itextsharp/
