# Actions & Stuff RTX Patcher - Patches

This repository contains the patch files (`.xdelta`) used by the Community Patcher to update Minecraft with the "Actions & Stuff" resource pack.

## Available Patches

| Version | Description | Paths |
| :--- | :--- | :--- |
| **v1.8** | Actions & Stuff Update 1.8 | `Patches/v1.8/decrypted.vcdiff`<br>`Patches/v1.8/encrypted.vcdiff` |

## Repository Structure

-   `Patches/`: Contains the binary patch files organized by version.
    -   `vX.Y/`: Specific version folder.
        -   `decrypted.vcdiff`: Patch for the decrypted ZIP source.
        -   `encrypted.vcdiff`: Patch for the encrypted Marketplace source.
-   `tools/`: Helper scripts for maintaining patches.

## Usage
These patches are intended to be used with the **A&S RTX Community Patcher**.

### Creating New Patches
Use the tool in `tools/create_patch.py` to generate new patch files consistent with this structure.
