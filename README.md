# InstallPKG #

InstallPKG is a wrapper to the 'installer' tool on Mac OS X systems. The functionality is focused on allowing you to quickly and easily install multiple packages to the current boot drive.  InstallPKG is released under the GNU GPL licence.

Download the latest version (a compiled package installer) via the following URL : 
http://www.lucid.systems/download/installpkg

Use this GitHub project to build the OS X package installer for InstallPKG or download the .dig file which is also available from github. Pull requests to add useful features or bug fixes are also welcome.

Basic usage example to install all .pkg files found within a specific directory :

    installpkg /path/to/directory/of/packages/*


Full usage information and usage examples are available once installed by typing : 

    man installpkg


Support for the -u "install from URL" flag is provided by wget. If you do not have wget installed on your system and you would rather not install the developer tools, then [download wget for OS X as a package][3]. It is possible to install wget in a number of ways. Just a few installation approaches relating to installation of wget on OS X are listed below :
 * [rudix (pre-built wget binary with install package for OS X)][3] (note : installs to /usr/local/bin/wget).
 * [homebrew][2]
 * [macports][1]


Comments and suggestions regarding the InstallPKG project are very welcome.


  [1]: https://www.macports.org
  [2]: http://brew.sh
  [3]: http://rudix.org/packages/wget.html
  