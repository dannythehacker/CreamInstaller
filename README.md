### CreamInstaller: Automatic DLC Unlocker Installer & Configuration Generator

![Program Preview Image](https://raw.githubusercontent.com/pointfeev/CreamInstaller/main/preview.png)

###### **NOTE:** This is simply a preview image; this is not a list of supported games nor configurations!

##### The program utilizes the latest versions of [Koaloader](https://github.com/acidicoala/Koaloader), [SmokeAPI](https://github.com/acidicoala/SmokeAPI), [ScreamAPI](https://github.com/acidicoala/ScreamAPI), [Uplay R1 Unlocker](https://github.com/acidicoala/UplayR1Unlocker) and [Uplay R2 Unlocker](https://github.com/acidicoala/UplayR2Unlocker), all by the wonderful [acidicoala](https://github.com/acidicoala), and all downloaded from the posts above and embedded into the program itself; no further downloads necessary on your part!
---
#### Description:
Automatically finds all installed Steam, Epic and Ubisoft games with their respective DLC-related DLL locations on the user's computer,
parses SteamCMD, Steam Store and Epic Games Store for user-selected games' DLCs, then provides a very simple graphical interface
utilizing the gathered information for the maintenance of DLC unlockers.

The primary function of the program is to **automatically generate and install DLC unlockers** for whichever
games and DLCs the user selects; however, through the use of **right-click context menus** the user can also:
* automatically repair the Paradox Launcher
* open parsed Steam and/or Epic Games appinfo in Notepad(++)
* refresh parsed Steam and/or Epic Games appinfo
* open root game directories and important DLL directories in Explorer
* open SteamDB, ScreamDB, Steam Store, Epic Games Store, Steam Community, Ubisoft Store, and official game website links (where applicable) in the default browser

---
#### Features:
* Automatic download and installation of SteamCMD as necessary whenever a Steam game is chosen. *For gathering appinfo such as name, buildid, listofdlc, depots, etc.*
* Automatic gathering and caching of information for all selected Steam and Epic games and **ALL** of their DLCs.
* Automatic DLL installation and configuration generation for Koaloader, SmokeAPI, ScreamAPI, Uplay R1 Unlocker and Uplay R2 Unlocker.
* Automatic uninstallation of DLLs and configurations for Koaloader, CreamAPI, SmokeAPI, ScreamAPI, Uplay R1 Unlocker and Uplay R2 Unlocker.
* Automatic reparation of the Paradox Launcher (and manually via the right-click context menu "Repair" option). *For when the launcher updates whilst you have CreamAPI, SmokeAPI or ScreamAPI installed to it.*

---
#### Installation:
1. Click [here](https://github.com/pointfeev/CreamInstaller/releases/latest/download/CreamInstaller.zip) to download the latest release from [GitHub](https://github.com/pointfeev/CreamInstaller).
2. Extract the executable from the ZIP file to anywhere on your computer you want. *It's completely self-contained.*

If the program doesn't seem to launch, try downloading and installing [.NET Desktop Runtime 7.0.8](https://download.visualstudio.microsoft.com/download/pr/53868e57-c621-476a-885b-dea78ac6edba/f1d5957ba91bde28370f0e782b3d6177/windowsdesktop-runtime-7.0.8-win-x64.exe). Note that the program currently only supports Windows 8+ 64-bit machines, as .NET 7+ no longer support Windows 7.

---
#### Usage:
1. Start the program executable. *Read above under Installation if it doesn't launch.*
2. Choose which programs and/or games the program should scan for DLC. *The program automatically gathers all installed games from Steam, Epic and Ubisoft directories.*
3. Wait for the program to download and install SteamCMD (if you chose a Steam game). *Very fast, depends on internet speed.*
4. Wait for the program to gather and cache the chosen games' information & DLCs. *May take a good amount of time on the first run, depends on how many games you chose and how many DLCs they have.*
5. **CAREFULLY** select which games' DLCs you wish to unlock. *Obviously none of the DLC unlockers are tested for every single game!*
6. Choose whether or not to install with Koaloader, and if so then also pick the proxy DLL to use. *If the default version.dll doesn't work, then see [here](https://cs.rin.ru/forum/viewtopic.php?p=2552172#p2552172) to find one that does.*
7. Click the **Generate and Install** button.
8. Click the **OK** button to close the program.
9. If any of the DLC unlockers cause problems with any of the games you installed them on, simply go back to step 5 and select what games you wish you **revert** changes to, and instead click the **Uninstall** button this time.

##### **NOTE:** This program does not automatically download nor install actual DLC files for you; as the title of the program states, this program is only a *DLC Unlocker* installer. Should the game you wish to unlock DLC for not already come with the DLCs installed, as is the case with a good majority of games, you must find, download and install those to the game yourself. This process includes manually installing new DLCs and manually updating the previously manually installed DLCs after game updates.

---
##### Bugs/Crashes/Issues:
For reliable and quick assistance, all bugs, crashes and other issues should be referred to the [GitHub Issues](https://github.com/pointfeev/CreamInstaller/issues) page!

##### **HOWEVER**: Please read the template issue corresponding to your problem should one exist! Also, note that the [GitHub Issues](https://github.com/pointfeev/CreamInstaller/issues) page is not your personal assistance hotline, rather it is for genuine bugs/crashes/issues with the program itself. If you post an issue which has already been explained within the template issues and/or within this text, I will just close it.

---
##### More Information:
* SteamCMD installation and appinfo cache can be found at **C:\ProgramData\CreamInstaller**.
* The program automatically and very quickly updates from [GitHub](https://github.com/pointfeev/CreamInstaller) by choice of the user through a dialog on startup.
* The program source and other information can be found on [GitHub](https://github.com/pointfeev/CreamInstaller).
