# Stardew Access

## Description

An accessibility mod for Stardew Valley with screen reader and keyboard only support. Currently only for windows.

## Requirements

1. SMAPI - [smapi installation guide](#smpai-installation-guide)
1. AutoHotKey - [autohotkey installation guide]()

## SMAPI Installation Guide

1. Run Stardew Valley atleast once before following the steps ahead to generate necessary files.
1. Download the [latest version](https://smapi.io/)
1. Extract the zip file and run the ` Windows.bat ` file.
1. Follow the instructions and normally it will detect the game's folder automatically. Now you to configure your game client.
1. For Steam:-
    - Go to you library and right click on stardew valley and open `properties` from the drop down menu.
    - Navigate to `Launch Options` in the `General` tab
    - Now if you have installed Stardew Valley in the default steam downloads then copy and paste the following text into the Launch Options text box.

        "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%
    
    - Now for those who have installed the game in some other folder the format of the text you have to copy and paste should be:

        "\<SVPath\>\StardewModdingAPI.exe" %command%
    
        - Replace \<SVPath\>\ with the path of the Stardew Valley folder.
        - Note that `\<SVPath\>\StardewModdingAPI.exe` is surrounded by double-quotes.
        - This text is also shown in the SMAPI installer terminal window after the installation process is completed
        
*(Installation for GOG Galaxy and Xbox app will be added soon. For now you can refer to [this guide](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Windows))*

## AutoHotKey Installation Guide

1. Download the [latest version](https://www.autohotkey.com/)
1. Follow the steps in the installer and it's installed.