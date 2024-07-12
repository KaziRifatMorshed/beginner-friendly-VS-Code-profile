# beginner-friendly-VS-Code-profile

### Current Version: v1.2 (13 July 2024)

### Current Releases: Windows and Linux (NOTE: MAC will be added later)

#### Supports C, C++, Python, Java, HTML, CSS

# How to install?

Don't panic! It is easy like a piece of cake ;)

Prerequisite (Do/confirm these first):  

- Make sure you have downloaded and installed VS-Code. You can download VS-Code from <https://code.visualstudio.com>.

- To compile C, C++, you need to install a compiler for C/C++: [MinGW]() or [MSYS2](https://www.msys2.org). We prefer MSYS2 for Windows users.

- Follow this [YouTube video](https://youtu.be/hmlv-zgRFDs) for installing MSYS2 and adding Environment Variable for Windows.

- For Linux Users, you should have `gcc` installed by default, but, you need to have "build-essential" installed (For Debian based UBUNTU, LINUX MINT users), please type `sudo apt get build-essential` in your terminal. 

- **If you have already a compiler (either MinGW or MSYS2 for Windows, and, GCC or clang for Linux) installed and the environment variable added successfully, YOU CAN SKIP THIS STEP and move forward.**

---

We'll continue with following easy steps to set up your coding environment in VS Code.

1. Download the configuration file (ended with `.code-profile`) by clicking the blue button:  

WINDOWS: [![Download zip](https://custom-icon-badges.demolab.com/badge/-Download-blue?style=for-the-badge&logo=download&logoColor=white "Download file")](https://github.com/KaziRifatMorshed/beginner-friendly-VS-Code-profile/releases/download/v1.2/tbtKU-VS_Code-profile-v1.2-Windows.code-profile).

Linux: [![Download zip](https://custom-icon-badges.demolab.com/badge/-Download-blue?style=for-the-badge&logo=download&logoColor=white "Download file")](https://github.com/KaziRifatMorshed/beginner-friendly-VS-Code-profile/releases/download/v1.2/tbtKU-VS_Code-profile-v1.2-Linux.code-profile).  

This file should be downloaded to the 'Downloads' folder (by Default, or, you should know/track your download location).

2. `Settings icon` (Bottom-Left corner of VS-Code window) > `Profile (Default)` > `Import Profile...`  
   ![](/img/img1.png)

3. click `Select File...`  
   ![](/img/img2.png)

4. Select the downloaded file (tbtKU-VS_Code-profile-...) and click `open`  
   ![](/img/img3.png)

5. click `Create Profile`  
   ![](/img/img4.png)

6. click `Create`  
   ![](/img/img5.png)

7. wait while VS Code downloads extensions and other files  
   ![](/img/img6.png)

8. If you notice something like "A pre-release version of ......", it is better to click `No` (pre-release version may lead buggy experience)  
   ![](/img/img7.png)

<!-- --- -->

# Description

Starting learning programming C/C++/Python? Want to use VS-Code? Use this beginner-friendly-VS-Code-profile (it easily configures your VS-Code ready for learning)  
Happy Coding `;)`

### Features

- (Almost) Everything is pre-configured. Just plug-and-play! (Download>install>EnjoyCoding)
- Default theme set to "One Dark". You can change the theme as you wish.
- Compile and Run functions are configured for `C`, `CPP`, `Python`, `Java` as "Code-Runner" extension has been configured (But you need to install Compiler/Interpreter on your own)
- Auto code formatting (Beautification and Indentation) while saving the file (`.c`,`.cpp`,`.py`,`.java`) with the keyboard shortcut "`Ctrl` + `c`"
- Snippet (initial code completion) for "C" (type `c` and hit 'Enter' for basic code structure/body, `pri` for `printf("");` and `scan` for `scanf("",&);`)
- Text Warp is enabled (Solves [this](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstackoverflow.com%2Fquestions%2F31025502%2Fhow-can-i-switch-word-wrap-on-and-off-in-visual-studio-code&psig=AOvVaw05koewMaISImJONV6njPwX&ust=1719605582459000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCNjaspbM_IYDFQAAAAAdAAAAABAE) issue)
- pre-added "Warm Up - Typing test" for practice typing inside VS-Code. Practice makes a man perfect. `;)`
- Most of the extensions from [this free-code-camp article](https://www.freecodecamp.org/news/best-vscode-extensions/) are added, please visit this site and explore all extensions and how they work, individually. List of these extensions are: Better Comments, Code Spell Checker, CodeSnap, and Material Icon Theme.
- For Web Development, HTML CSS Support, Auto Close Tag, Auto Complete Tag, and HTML End Tag Labels are pre-installed.
- `cph` (Competative Programming Helper for CodeForces) and `vjudge` extensions.
- `"editor.suggest.showWords": false,`, for this change in `settings.json`, IntelliSense in Visual Studio Code will not suggest words from your code.


### Fixes
- line-height is set to default where it was set to 1.5 in the first two releases(v1.1)


### WARNINGS

- this PERFECTLY works only with VS CODE (<https://code.visualstudio.com>); to use this profile without issues in `OSS CODE` and `vscodium`, manual modification needed
- Whenever you run C, C++, Python, or Java code in the VS Code terminal, **the entire terminal window clears. This means you will lose the history of previous outputs.**
- It does not override your previous profile or configurations. Just adds a new profile. You can switch your previous one any time from "`Settings icon` (Bottom-Left corner of VS-Code window) > `Profile (...)` > `Default`"

---

Kazi Rifat Morshed  
CSE KU 230220

Special thanks goes to IAS Seam (CSEKU 230201)
