<h1 align="center">
  <img src="https://raw.githubusercontent.com/jnsdrtlf/bitwarden-menubar/main/Bitwarden/Assets.xcassets/AppIcon.appiconset/icon%4032.png"/>
  Bitwarden Menu
</h1>

**This project is not associated with the Bitwarden project nor 8bit Solutions LLC.**

**Note**: This application **no longer recieves updates** to the
latest version of the Bitwarden Browser Extension as it
uses the Safari Web Extension API starting from version 1.49.0.
For more information see
[`jnsdrtlf/bitwarden-menubar#2`](https://github.com/jnsdrtlf/bitwarden-menubar/issues/2)
and [my post on community.bitwarden.com](https://community.bitwarden.com/t/full-fledged-menu-bar-mode/2587/18).
**The app currently uses a very old version (v1.48.1) of the extension. This will
probably not change in the foreseeable future. Use at your own risk!**

**Bitwarden Menu** is a simple application for macOS that puts the
[Bitwarden Browser Extension](https://github.com/bitwarden/browser)
right into your menu bar.

<p align="center">

  ![](artwork/screenshot.png)

</p>

## Installation
As I am not enrolled in the Apple Developer Program, I cannot sign this
Application. However, you may still download the `Bitwarden Menu.app`
from the [Releases](https://github.com/jnsdrtlf/bitwarden-menubar/releases).

Alternatively, you can build it yourself by cloning this project
using `git clone --recurse-submodules` and opening it in XCode.  
One part of the build process is to copy (a slightly modified version of)
the Bitwarden Browser Extension into the app. This is done using the
`Bitwarden/build.sh` script. You therefore have to make sure the
submodule (in `Bitwarden/browser`) is initialized and updated.

## License

The Bitwarden Browser Extension is licensed under the 
**GNU General Public License v3.0** and so is this project.

The App Icon is based on [this template](https://www.figma.com/community/file/857303226040719059/macOS-Big-Sur-Icon-Template)
by [**Vaclav Vancura**](http://vancura.design/) which is licensed under
**CC BY 4.0**.

## Trademark Notice

"Bitwarden" is a registered trademark of Bitwarden Inc.
