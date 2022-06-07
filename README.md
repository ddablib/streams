# Stream Extension Classes

## Description

This class library contains two units that provide some classes that can be used to extend the functionality of Delphi's _TStream_ classes.

The _PJStreamWrapper_ unit provides a class that can wrap any _TStream_ descendant while the _PJIStreams_ unit provides classes that implement the _IStream_ interface for various _TStream_ descendants.

The classes are all documented [online](https://delphidabbler.com/url/streams-docs).

## Demo Projects

Three demo projects are provided in the download:

1. `IStreamWrap.dpr` in the `IStreamWrapDemo` sub-directory. This is a VCL project that demonstrates the _IStream_ wrapper classes in the _PJIStreams_ unit.
2. `IStreamWrapFMX.dpr` in the `IStreamWrapDemoFMX` sub-directory. This is a FireMonkey 2 project that demonstrates the _IStream_ wrapper classes in the _PJIStreams_ unit. It is similar, but not identical, to `IStreamWrap.dpr`.
3. `StreamWrap.dpr` in the `StreamWrapDemo` sub-directory. This is a VCL project that demonstrates the _PJStreamWrapper_ unit.

All the demo projects are stored in the `Demos` directory.

## Unit Tests

Unit tests are provided for all classes in the `Tests` directory.

Tests require the _DUnit_ unit testing framework, which must be installed in a location accessible to your Delphi compiler.

## Compatibility

The classes are compatible with the following:

* The Delphi 4 and later Win 32 compilers.
* The Delphi XE2 and later Win 64 compilers.
* Both ANSI and Unicode strings.
* The VCL and FireMonkey platforms (for Windows only).

## Installation

The _Stream Extension Classes_ units are provided in a zip file. Once the units are extracted you can use them as required. There are several ways you may wish to do this:

1. The simplest way is to add the units to your projects as you need them.
2. To make the units easier to re-use you can add the folder where you extracted them to your Delphi search path and then simply use the units as required without needing to add them to your project.
3. For maximum portability you can add the units to a package. [More info...](https://delphidabbler.com/url/install-comp).
4. If you use Git you can add the [`ddablib/streams`](https://github.com/ddablib/streams) GitHub repository as a Git submodule and add it to your project. Obviously, it's safer if you fork the repo and use your copy, just in case `ddablib/streams` ever goes away.

In addition to the above files, there are two directories included in the zip file:

1. The `Demos` directory contains the [demo projects](#demo-projects).
2. The `Tests` directory contains the [unit tests](#unit-tests).

## Update History

A complete change log is provided in [`CHANGELOG.md`](https://github.com/ddablib/streams/blob/main/CHANGELOG.md) that is included in the download.

## License

The _Stream Extension Classes_ are released under the terms of the [Mozilla Public License, v2.0](https://www.mozilla.org/MPL/2.0/).

## Bugs and Feature Requests

Bugs can be reported or new features requested via the project's [Issue Tracker](https://github.com/ddablib/streams/issues). A GitHub account is required.

Please check if an issue has already been created for a similar report or request. If so then please add a comment containing as much information as you can to the existing issue, or if you've nothing to add, just add a :+1: (`:+1:`) comment. If there is no suitable existing issue then please add a new issue and give as much information as possible.

## About the Author

I'm Peter Johnson – a hobbyist programmer living in Ceredigion in West Wales, UK, writing mainly in Delphi. My programs and other library code are available from: [https://delphidabbler.com/](https://delphidabbler.com/).

This document is copyright © 2000-2022, [P D Johnson](https://gravatar.com/delphidabbler).
