In HOS 17.0.0 and after, blanking your PRODINFO using any method (exosphere/blanking PRODINFO on NAND) will cause a User Abort in the nim service. This repository has patch files that disable this abort, allowing you to use PRODINFO blanking on firmwares 17.0.0 and afterwards.

Supported Firmwares:
- 19.0.0
- 18.1.0
- 18.0.1
- 18.0.0
- 17.0.1
- 17.0.0
