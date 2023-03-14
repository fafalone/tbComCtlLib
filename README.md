# tbComCtlLib
twinBASIC Common Controls Definitions Library 2.2 (x86/x64)

Provides a complete set of Common Controls 6.0 definitions for 32bit and 64bit projects.

This is a TWINPACK package you can add as a Reference in the Settings page. It's compatible and doesn't conflict with tbShellLib. 

You can browse individual source files in the Export folder. The project source is provided in .twinproj form, and the package to add as a reference is tbComCtlLib.twinpack.

**Update (Mar 14 2024)**: Version 2.2 adds a number of ComCtl related interfaces from tbShellLib, and reduces conflicts with it when the `TB_SHELL_LIB_DEFINED` compiler constant is set.

**Update (Mar 13 2023)**: Version 2.1 removes a duplicate type, adds certain interfaces and enums, and improves conflict resolution with tbShellLib.

**Update (Mar 06 2023)**: Version 2.0 adds all Common Dialog definitions from comdlg.h and adds missing PropertySheet header UDTs.

**Update (Feb 06 2023)**: Version 1.2 fixes numerous hex literals that were defined in a way that would cause sign issues in bitwise operations.

**Update (Nov 17 2022)**: Version 1.1 adds all Visual Styles APIs, Enums, Stucts, and Consts.
