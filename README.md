# Dnevnici-po-ZDDS
also known as ДДС-документи, Дневници по ЗДДС (от НАП)
### Lutris YAML Configuration for Installing "Dnevnici po ZDDS" (NRA.bg)
This guide explains how to install *Dnevnici po ZDDS*, an NRA.bg tool, using Lutris. The integrated version of *Dnevnici po ZDDS* in this script is **v1301**.
#### Prerequisites
1. **Install Lutris** on your Linux distribution.
2. Download or clone the repository containing this YAML file.
```bash
git clone https://github.com/Naplifye/Dnevnici-po-ZDDS.git
```
#### Installation Steps in Lutris
1. **Open Lutris** and click on the **Add Game** button ( *+* icon in the top left corner).
2. Select **Install from a local script**.
3. Choose the **YAML script file path** for installation.
4. Follow the prompts to:
   - Select the **directory for the Wine prefix**.
   - Point to the **local setup file** downloaded from [NRA's website](https://nra.bg/wps/portal/nra/Programni-produkti/DD-dokumenti).
5. Wait for the installation to complete.
6. Launch *Dnevnici* from Lutris.
#### Wine Configuration
- This script uses the lutris-7.2-2-x86_64 wine version
- The script is also compatible with the latest stable/staging wine versions. 
- You can change the wine version in Lutris, if needed.

# Issues
```
## Problem 
```
On older versions of Lutris like 0.5.16, you may experience issues where the script cannot be installed because the required Wine version is either not found or mismatched with wine-ge-8-26
```
## Solution
```
To resolve this, install the latest version of Lutris, such as through Flatpak, to ensure compatibility.
