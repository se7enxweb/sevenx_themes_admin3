## 7x Themes : Admin3 Responsive admin design supporting mobile devices for eZ Publish

sevenx_themes_admin3 is an extension that allows the integration of a new responsible admin siteaccesss design for the eZ Publish Administration UI. Supports mobile devices like cell phones and tablets!

Version: 1.0.0

## About 7x

7x is a web design, developement, support and hosting company from North America operating for over 24 years. Formerly known as Brookins Consulting a leader in both the eZ Publish Partner Community and eZ Publish Open Source Project. 7x supports cutting edge development and support for the eZ Publish Community and eZ Publish Ecosystem.

From: [https://se7enx.com/](https://se7enx.com/)

## Requirements of this extension

None; Only eZ Publish is required. This solution is compatible with any version of eZ Publish software (3.x -> 6.x)

## Use Cases

Here are some common use cases:

    Responsive design needs
    Tablet support.
    Mobile support.
    Android device support.
    iOS device suppport.


## Installation

Follow these steps to add the sevenx_themes_admin3 design extension to your eZ publish installation:

  1) Extract the archive into the extension/ directory

  2) Edit site.ini.append.php in settings/override/. Add the following to the file:

       [ExtensionSettings]
       ActiveExtensions[]=sevenx_themes_admin3

     If you already have the [ExtensionSettings] block, just add the second line.

  3) Edit extension/settings/valkey.ini.append.php and edit the default host IP Address and Port only if needed.

  4) Edit settings/siteaccess/sevenx_site_admin/site.ini.append.php and edit the default admin design used to be set at admin3.

     Note: this may be different on your specific ezpublish application installation configuration. Causion. 

  5) Clear Cache

## Usage

To use, simply login to the admin siteacess URL to use the new admin design features on your favorite mobile device! :)


## License

This file may be distributed and/or modified under the terms of the "GNU
General Public License" version 2 as published by the Free Software Foundation

This file is provided AS IS with NO WARRANTY OF ANY KIND, INCLUDING THE
WARRANTY OF DESIGN, MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.

The "GNU General Public License" (GPL) is available at
[http://www.gnu.org/copyleft/gpl.html](http://www.gnu.org/copyleft/gpl.html).
