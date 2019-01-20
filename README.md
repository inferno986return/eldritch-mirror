# eldritch-mirror
*You can support Minor Key Games by purchasing Eldritch on [Steam](https://store.steampowered.com/app/252630/Eldritch/).*

A mirror for the source code of [Eldritch](http://eldritchgame.com/), a HP Lovecraft-inspired FPS roguelite game. The source code and scripts are licensed under the lenient zlib license, but content such as graphics and music are proprietary (like DOOM).

## ReadMe

Thanks for downloading this distribution of Eldritch's source code!

Please note that this is an unsupported, unmaintained release;
documentation is limited to this readme file and I will not be
integrating changes. Questions and bug reports are welcome at
david.pittman@gmail.com, but I cannot promise I will be able to
respond.

Note also that this will not compile out of the box; Eldritch
depends on the FMOD Ex Programmer's API, which is not licensed for
redistribution but can be downloaded at http://www.fmod.org/.
Eldritch was built with FMOD Ex 4.44.15, but any recent release
is likely to build fine.

It will be necessary for OS X and Linux users to download SDL 2.0
to build Eldritch. For Windows users, the library files included
here should suffice.

IDE project files are provided for Visual Studio 2005, Code::Blocks,
and Xcode, but it may be more desirable to rebuild your own project
file. This was my first time working with either Code::Blocks or
Xcode, and it is likely that they are configured poorly.

This distribution does not include most of the game's content, but
configuration, script, and room files are included and are licensed
the same as the source code. (All game content not included here is
not covered by these license terms and may not be redistributed.)

For Windows users, a precompiled Eldritch-Release.exe file is
provided for immediate access to the game's debug tools and level
editor. To access the editor, press Tab during gameplay.

The game's .cpk files (not included here; you must purchase a copy
of Eldritch to get them) can be unpacked with the FilePacker.exe tool.
Deleting, renaming, or moving the .cpk files will force the game to
load from loose files instead.

Configuration/script files (.config extension) are used to define
most aspects of the game: procedural generation parameters, entity
composition, AI behaviors, etc. They can be parsed at runtime or
precompiled with ConfigCompiler.exe.

The source code for the tools is included, but they have not been
ported to OS X or Linux.

Happy coding!
David

## Licensing

Eldritch's source code is released under the zlib license. Except as noted
below, the following terms apply to all files in this distribution.

/* ---------------------------------------------------------------- */

Copyright � 2013-2014 Minor Key Games, LLC

This software is provided 'as-is', without any express or implied
warranty.  In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgment in the product documentation would be
   appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be
   misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.

/* ---------------------------------------------------------------- */

Exceptions:
This distribution includes the following libraries, which are
licensed separately and redistributed under the terms of their
respective licenses:
zlib    (http://www.zlib.net/)
SDL 2.0 (http://www.libsdl.org/)
TinyXML (http://www.grinninglizard.com/tinyxml/)
GLEW    (http://glew.sourceforge.net/)

/* ---------------------------------------------------------------- */

/* zlib.h -- interface of the 'zlib' general purpose compression library
  version 1.2.8, April 28th, 2013

  Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler

  This software is provided 'as-is', without any express or implied
  warranty.  In no event will the authors be held liable for any damages
  arising from the use of this software.

  Permission is granted to anyone to use this software for any purpose,
  including commercial applications, and to alter it and redistribute it
  freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would be
     appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must not be
     misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.

  Jean-loup Gailly        Mark Adler
  jloup@gzip.org          madler@alumni.caltech.edu

*/

/* ---------------------------------------------------------------- */

The OpenGL Extension Wrangler Library
Copyright (C) 2002-2008, Milan Ikits <milan ikits[]ieee org>
Copyright (C) 2002-2008, Marcelo E. Magallon <mmagallo[]debian org>
Copyright (C) 2002, Lev Povalahev
All rights reserved.

Redistribution and use in source and binary forms, with or without 
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, 
  this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, 
  this list of conditions and the following disclaimer in the documentation 
  and/or other materials provided with the distribution.
* The name of the author may be used to endorse or promote products 
  derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF
THE POSSIBILITY OF SUCH DAMAGE.


