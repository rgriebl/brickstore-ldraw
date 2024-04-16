## BrickStore ldraw packaging

This repository consists of a GitHub Actions workflow that regenerates BrickStore's version of LDraw's complete.zip.

The only difference to the upstream LDraw release is that this version incorporates an additional CBOR file that has mappings from BrickLink item ids to LDraw item ids.
The necessary data comes from the latest LDraw library itself, as well as the modified LDraw library packaged in the latest BrickLink Stud.io release.

A successful action run is automatically released on GitHub and is then instantly available for BrickStore clients to download.

Any data downloaded from
 * www.bricklink.com is owned by BrickLink (Stud.io).
 * www.ldraw.org is owned by LDraw.org (complete.zip).

Please see https://www.brickstore.dev for more information on the actual application.
