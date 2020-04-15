Setting up the Visual Studio Code Whitcode Extension
====================================================
* Whitcode: This Visual Studio Code extension helps with setting up C++ and Assembler projects at Whitworth
* This tutorial provides additional information on using whitcode extension. You really should not be following this tutorial for installation, rather follow one of these tutorials (which includes the steps described here)  [quick start to vscode on a mac](https://whitgit.whitworth.edu/tutorials/quick-start-to-vscode-macos) or [quick start to vscode on a windows machine](https://whitgit.whitworth.edu/tutorials/quick-start-to-vscode-whitworth)

## Requirements:

> * You must have the latest versions of the following software:
> * On all platforms: Visual Studio Code, Version: 1.38.1 (user setup) or later for this to work properly. Don't install this with an older version of vscode on your system! It won't work properly. 
> * On windows: git version 2.23.0.windows.1 or later
> * On Windows: mingw-64 version (x86_64-posix-seh-rev0, Built by MinGW-W64 project) 8.1.0 or later



## 0. Start Visual Studio Code on your local machine.
![start vscode](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/0_start_vscode.png)

## 1. Download the following file to your local machine by using this link: [vscode-whitcode-extension-1.0.3.vsix](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/blob/master/whitcode-extension-1.0.6.vsix)

## 2. A download page will open, select the Download link...
![download](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/2_download_page.png "download whitlab explorer")

## 3. Once downloaded, (if you are using chrome), the dowload location will appear at the bottom of your web browser as shown in the folloing image. Click on the arrow and select "Show in folder".
![downshow in folder](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/3_show_in_folder.png "show in folder")

## 4. Explorer will open at the location to which the browser downloaded the .vsix file. Take special note of the location as shown in the following image, because you will have to find this folder location again in order to install the extension.
![note the download location](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/4_download_location.png "note the download location")

## 5. Switch back to Visual Studio Code and Install the VSIX as follows:
### a. Find the "Extensions Icon" located on the left hand menu bar of Visual Studio Code and select it as shown.
### b. At the top of Visual Studio code the EXTENSIONS indicator will appear. To the left of EXTENSIONS select More Actions (3 dots ...)
### c. A drop down actions menu will appear. From this menu locate the "Install from VSIX..." menu option and select it.
![install a vsix](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/5_install_a_vsix.png "install a vsix")

## 6. Using the explorer dialog windows that pops up, navigate to the location at which you downloaded the .vsix file. 
### a. Navigate to the downloaded file location. 
### b. Select the vscode-whitcode-extension-1.0.2.vsix file in the downloads folder
### c. Once found and selected, select the Install button at the bottom of the explorer window.
![find downloaded vsix and install](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/6_find_downloaded_vsix_and_install.png "find downloaded vsix and install")

## 7. Observe the successful installation of the Whitcode extension. 
### a. The main indicator of a successful installation is the **Whitworth icon** on the left side menu bar. 
### b. Other indicators of success are highlighted in the following illustration.
![indicators](https://whitgit.whitworth.edu/tutorials/installing-whitcode-extension/raw/master/images/7_indicators.png "indicators")


## 10. Optional Configuration Settings:  It may be you installed your C++ compiler in a different location than the default settings are looking for. You may override the default configuration locations by editing your personal Settings.json file and adding the appropriate settings as shown below: 

### Settings.json file example for MAC or Linux
```json
{
    "whitcode.comment" : "mac or linux options example",
    "whitcode.compiler-path" : "",
    "whitcode.compiler-exe" : "g++",
    "whitcode.exe-name" : "main",
    "whitcode.google-test-root" : "/usr/local/lib/googletest",
    "whitcode.test-exename" : "testmain",
    "whitcode.dbg-path" : "gdb"
}
```
### Settings.json file example for Windows
```json
{
    "whitcode.comment" : "windows options example",         
    "whitcode.compiler-path" : "C:/Program\ Files/mingw-w64/mingw64/bin",
    "whitcode.compiler-exe" : "g++.exe",
    "whitcode.exe-name" : "main.exe",
    "whitcode.google-test-root" : "C:/googletest",
    "whitcode.test-exename" : "testmain.exe",
    "whitcode.dbg-path" : "C:/Program\ Files/mingw-w64/mingw64/bin/gdb.exe"   	
}
```



## 9. Start using the extension. For details on how to actually use this extension to create projects see the Readme file for the extension itself located here: [Readme](https://whitgit.whitworth.edu/cslab/whitcode-extension/blob/master/README.md)










