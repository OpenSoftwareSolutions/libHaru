#[libHaru](http://libharu.org)

libHaru is a free, cross platform, open source library for generating PDF files. At this moment libHaru does not support reading and editing existing PDF files and it's unlikely this support will ever appear.

It supports the following features:

- Generating PDF files with lines, text, images.
- Outline, text annotation, link annotation.
- Compressing document with deflate-decode.
- Embedding PNG, Jpeg images.
- Embedding Type1 font and TrueType font.
- Creating encrypted PDF files.
- Using various character sets (ISO8859-1~16, MSCP1250~8, KOI8-R).
- Supporting CJK fonts and encodings. You can add the feature of PDF creation by using HARU without understanding complicated internal structure of PDF. libHaru is written in ANSI C, so theoretically it supports most of the modern OSes.

This repo wraps the libHaru sources in iOS and macOS framework.

## Installation
### Using [Carthage](https://github.com/Carthage/Carthage)
To integrate `libHaru.framework` in your project specify it in your `Cartfile`:
```ogdl
github "OpenSoftwareSolutions/libHaru"
```
Run `carthage update` to build the framework and drag the built `Alamofire.framework` into your Xcode project.

##License

Copyright (C) 1999-2006 Takeshi Kanno
Copyright (C) 2007-2009 Antony Dovgal

This software is provided 'as-is', without any express or implied warranty.

In no event will the authors be held liable for any damages arising from the 
use of this software.

Permission is granted to anyone to use this software for any purpose,including 
commercial applications, and to alter it and redistribute it freely, subject 
to the following restrictions:

 1. The origin of this software must not be misrepresented; you must not claim 
    that you wrote the original software. If you use this software in a 
    product, an acknowledgment in the product documentation would be 
    appreciated but is not required.
 2. Altered source versions must be plainly marked as such, and must not be 
    misrepresented as being the original software.
 3. This notice may not be removed or altered from any source distribution.
