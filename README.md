# steam-wrapper

A wrapper around the steam script which addresses commonly modified shared  
libraries, and offers an easy way to enable or disable the use of the Steam  
runtime.

## Requirements

+ **bash**, although it is a requirement for Steam itself and should already  
be installed.
+ **GNU coreutils** for the env binary, although it is generally considered  
safe to assume that some iteration of coreutils is installed on every modern 
Linux system.
+ **steam** itself, usually packaged in a distribution repository with a  
pre-packaged runtime. The wrapper can decide to either use the steam runtime,  
or attempt to load system native libraries. **Please Note:** The installation  
of relevant system libraries for use with Steam should be handled by the user  
prior to launching the steam wrapper script if the user wishes to use native  
libraries on his or her system.

## Usage
steam-wrapper can be invoked on the command line or via the  
steam-wrapper.desktop file.  Please note that the script is made with only  
ArchLinux support in mind, other distributions may need to look elsewhere or  
attempt manual modification of the script in order to achieve a successful  
wrapper.

Any actual issues that relate to Steam or the performance of games should be  
addressed to Valve Software directly, as the wrapper does not affect the  
actual performance of the game itself, other then removing libraries which may  
be considered outdated on systems which are not officially supported by Steam.

In short, if Steam launches, there is no problem with the wrapper. If Steam  
fails to launch after running the wrapper, then create an issue here and we  
as a community can address the situation together.

Please note that any issues with performance or compatability when attempting  
to use the native system libraries are left to the user and will not be  
supported by steam-wrapper.

## Questions

Please contact pyamsoft @ pyam(dot)soft(at)gmail(dot)com for any questions  
concerning the steam-wrapper script.

## License

The code which compromises the steam-wrapper script is licensed under the  
GPLv2 license, but the code for Steam itself is licensed under a custom  
license of the Valve Corporation. The wrapper code may be freely modified and  
redistributed, but the Steam program itself must comply to the licensing  
terms set forth in the original Steam license.

In short, the ability to edit this wrapper script does not give one the  
ability to modify anything about the Steam binary without the express consent  
of the Valve Corporation.

GPL2 v2

```

  Copyright (C) 2015 - 2016 Peter Kenji Yamanaka

  This program is free software; you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation; either version 2 of the License, or
  (at your option) any later version.

  This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License along
  with this program; if not, write to the Free Software Foundation, Inc.,
  51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

```

