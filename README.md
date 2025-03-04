# Markdown

LibreOffice is an integrated office suite based on copyleft licenses and compatible with most document formats and standards. Libreoffice is backed by The Document Foundation, which represents a large independent community of enterprises, developers and other volunteers moved by the common goal of bringing to the market the best software for personal productivity. LibreOffice is open source, and free to download, use and distribute.

A quick overview of the LibreOffice code structure.

## Overview

You can develop for LibreOffice in one of two ways, one recommended and one much less so. First the somewhat less recommended way: it is possible to use the SDK to develop an extension, for which you can read the [API docs][1] and [Developers Guide][2]. This re-uses the (extremely generic) UNO APIs that are also used by macro scripting in StarBasic.

The best way to add a generally useful feature to LibreOffice is to work on the code base however. Overall this way makes it easier to compile and build your code, it avoids any arbitrary limitations of our scripting APIs, and in general is far more simple and intuitive - if you are a reasonably able C++ programmer.

## The Build Chain and Runtime Baselines

These are the current minimal operating system and compiler versions to run and compile LibreOffice, also used by the TDF builds:

- Windows:
    - Runtime: Windows 10
    - Build: Cygwin + Visual Studio 2019 version 16.10
-
-
-
-



[1]: https://api.libreoffice.org/
[2]: https://wiki.documentfoundation.org/Documentation/DevGuide