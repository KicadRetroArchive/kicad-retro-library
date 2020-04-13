# KiCad Retro Library

This repository contains a set of KiCad libraries useful in the recreation of
old computers schematics and PCBs.

The criteria for adding symbols and footprints to this library are the following:

- The component should not be already available in the official KiCad Libraries.
- The component is interesting for recreating the schematic and PCB of an
  old computer. This criteria is not strict, send a PR and we'll figure it out.

The library is designed to work on KiCad v5.1.

## How to use

The best approach is having a single instance of this library somewhere on your
HD and add it as a **Project Specific Library** to each project.

To make the designs more portable it is highly recommended to follow these steps:

1. Open the main KiCad application and select the _"Preferences -> Configure Paths..."_
   menu entry. The current project is not important.
1. Click on the **+** button in the bottom left corner to add a new environment variable.
1. Define the `KICAD_RETRO_LIBRARY` variable pointing to the absolute path where
   this repository has been cloned. E.g. `/home/user/dev/github/kicad-retro-library`.
1. Click **OK** to confirm.
1. Exit the KiCad application.

## License

This library is released under the CERN Open Hardware Licence v2 license.

Please consider contributing back to this library or others to help the
open-source retro hardware community.
