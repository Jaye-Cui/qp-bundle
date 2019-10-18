![QP ecosystem](https://www.state-machine.com/img/ql_products.png)

---------------------------------------------------------------------------
# About qp-bundle
This repository contains a comprehensive suite of modern embedded software
and host-based tools wrapped around the QP Real-Time Embedded Frameworks
(RTEFs) — the unique reactive platform designed to provide the architectural
reuse and enforcement of the best practices of concurrent programming.

The qp-bundle contains the following components located in the
subdirectories:

```<qp>         - qp-bundle installation directory
 |
 +-qpc\      - QP/C    real-time embedded framework (RTEF)
 +-qpcpp\    - QP/C++  real-time embedded framework (RTEF)
 +-qpn\      - QP-nano real-time embedded framework (RTEF)
 +-qm\       - QM model-based design tool
 +-qtools\   - QTools collection
 | +-bin\    - QTools executables
 | +-qclean\ - Source code white space cleaner
 | +-qspy\   - QSPY host application and utilities
 | | +-py\   - Python support (QUTest)
 | |
 | | (the following subfolders are present on Windows only)
 | |
 | +-MinGW\             - GNU C/C++ toolchain for Windows
 | +-gnu_arm-none-eabi\ - GNU-ARM C/C++ toolset for ARM Cortex-M/R
 | +-Python37\          - Python 3.7 (for QUTest)
 | +-tcl_8.6\           - Tcl/Tk 8.6
```

> NOTE: A description of each component is provided in the README.md
files inside the project sub-directories.


---------------------------------------------------------------------------
### Version Compatibility and Revision History

The version of each component is encoded in the file "version-X.Y.Z",
which is provided in the component sub-directory.

The revision history of each component is provided in the Reference
Manual for each component (see the next section). 


---------------------------------------------------------------------------
### Reference Manuals

- https://www.state-machine.com/qpc     - QP/C Reference Manual
- https://www.state-machine.com/qpcpp   - QP/C++ Reference Manual
- https://www.state-machine.com/qpn     - QP-nano Reference Manual
- https://www.state-machine.com/qm      - QM Reference Manual
- https://www.state-machine.com/qtools  - QTools Reference Manual


---------------------------------------------------------------------------
### Help and Support

Community support for the project is provided at:
- https://sourceforge.net/p/qpc/discussion/668726

Commercial technical support is described at:
- https://www.state-machine.com/licensing/#Support


---------------------------------------------------------------------------
### Bug Reports and Feature Requests

Please use the Tickets menu.
- Bug reports:      https://sourceforge.net/p/qpc/bugs
- Feature requests: https://sourceforge.net/p/qpc/feature-requests/


---------------------------------------------------------------------------
### Contact Information:

- https://www.state-machine.com
- mailto:info@state-machine.com

