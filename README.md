# 3D Studio Max VTA export plug-in
A plug-in for Autodesk 3D Studio Max for exporting VTA format files as used by Source engine based games.

## Overview
This plug-in allows 3D Studio Max to export VTA vertex animation files used primarily in Source engine based games. It's mostly used for animating face flexes used to build up facial animations in games such as Half-Life 2 and TF2.

## Supported versions

* 3DS Max 9 - 32/64bit
* 3DS Max 2008 - 32/64bit
* 3DS Max 2009 - 32/64bit
* 3DS Max 2010 - 32/64bit
* 3DS Max 2011 - 32/64bit
* 3DS Max 2012 - 32/64bit
* 3DS Max 2017 - 64bit
* 3DS Max 2018 - 64bit
* 3DS Max 2019 - 64bit
* 3DS Max 2020 - 64bit

## Installation
Copy the `VTAExport.dle` or `VTAExportx64.dle` file for the correct edition of 3D Studio Max into your 3DS Max plug-ins folder (i.e. `C:\Program Files\Autodesk\3ds Max 2020\Plugins`) and re-start. You can check it's loaded via the Plug-ins Manager.

## Basic usage

Instruction with diagrams can be found at the [Valve Developer Wiki](http://developer.valvesoftware.com/wiki/Creating_Flex_VTA_files_with_3D_Studio_Max).

For those migrating from Cannonfodder's exporter, the process is the same with the following small differences.

* You do not need to delete anything before export.
* You need to have both the bones and base mesh selected before exporting.
* Use Export Selected rather than just export.

**NOTE:** If you have previously exported your reference SMDs using Canonfodder's exporter it might be wise to re-export them using the Wunderboy SMD exporter. This is because the latter uses a higher degree of accuracy and there may be issues lining up and indexing vertices in the VTA.

## Legal

### Author
This software was created by and is &copy; 2018 Neil "Jed" Jedrzejewski

### License & Warranty
The content owner grants a non-exclusive, perpetual, personal use license to view, download, display, and copy the content, subject to the following restrictions:

1. The content is licensed for personal and non-profit use only, not commercial use. The content may not be used in any way whatsoever in which you charge money, collect fees, or receive any form of remuneration for commercial gain. The content may not be resold, relicensed, sub-licensed, rented, leased, or used in advertising.

2. Title and ownership, and all rights now and in the future, of and for the content remain exclusively with the content owner.

3. This software is provided 'as-is', without any express or implied warranty.

4. The content owner will not be liable for any third party claims or incidental, consequential, or other damages arising out of this license or the use of the content.

5. This notice must NOT be removed or altered from any distribution of this software.
