# Dnevnici-po-ZDDS
also known as ДДС-документи, Дневници по ЗДДС
### Lutris YAML Configuration for Installing "Dnevnici po ZDDS" (NRA)
This guide explains how to install *Dnevnici po ZDDS*, an NRA tool, using Lutris. The integrated version of *Dnevnici po ZDDS* in this script is **v1301**.
#### Prerequisites
1. **Install Lutris** on your Linux distribution.
2. Download or clone the repository containing this YAML file.
#### Installation Steps in Lutris
1. **Open Lutris** and click on the **Add Game** button ( *+* icon in the top left corner).
2. Select **Install from a local script**.
3. Choose the **YAML script file path** for installation.
4. Follow the prompts to:
   - Select the **directory for the Wine prefix**.
   - Point to the **local setup file** downloaded from [NRA's website](https://nra.bg/wps/portal/nra/Programni-produkti/DD-dokumenti).
5. Wait for the installation to complete.
6. Launch *Dnevnici po ZDDS* from Lutris.
#### Wine Configuration
- This script uses the **lutris-7.2-2-x86_64** Wine version but should also be compatible with the latest staging versions. You can change this setting in Lutris if needed.
#### Manual Installation Option
If you prefer not to use this version, review the YAML script and manually execute the steps with Winetricks:
1. Create a **win32 prefix**.
2. Install the required components.
