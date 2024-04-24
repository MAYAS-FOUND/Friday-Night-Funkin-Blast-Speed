![Logo](https://cdn.discordapp.com/attachments/1148636843341000744/1155485853519458334/Untitled234_20230924084801.png?ex=662a510f&is=6628ff8f&hm=3dfadbed5096ba2834cefe3d8f8b147f295eedb1ae38cdcf5ccf947d70c632a0&)

# Friday Night Funkin' Blast And Speed Engine :

# Download Last Version
[Here](https://gamebanana.com/mods/463354)

# For Build
 1. [Install Haxe 4.1.5](https://haxe.org/download/version/4.1.5/). You should use 4.1.5 instead of the latest version because the latest version has some problems with Friday Night Funkin': Kade Engine.
 2. After installing Haxe, [Install HaxeFlixel](https://haxeflixel.com/documentation/install-haxeflixel/).
 3. Install `git`.
	 - Windows: install from the [git-scm](https://git-scm.com/downloads) website.
	 - Linux: install the git package: `sudo apt install git` (ubuntu), `sudo pacman -S git` (arch), etc... (you probably already have it)
 4. Install and set up the necessary libraries:
	 - `haxelib install lime 7.9.0`
	 - `haxelib install openfl`
	 - `haxelib install flixel`
	 - `haxelib install flixel-tools`
	 - `haxelib install flixel-ui`
	 - `haxelib install hscript`
	 - `haxelib install flixel-addons`
	 - `haxelib install actuate`
	 - `haxelib run lime setup`
	 - `haxelib run lime setup flixel`
	 - `haxelib run flixel-tools setup`
	 - `haxelib git linc_luajit https://github.com/nebulazorua/linc_luajit.git`
	 - `haxelib git hxvm-luajit https://github.com/nebulazorua/hxvm-luajit`
	 - `haxelib git faxe https://github.com/uhrobots/faxe`
	 - `haxelib git polymod https://github.com/MasterEric/polymod.git`
	 - `haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc`

     # Visual Studio ( Bbligatory )
     1. [Install Visual Studio 19](https://visualstudio.microsoft.com/fr/vs/older-downloads/). For make sure the game build without any problem

     2. While installing it, don't click on any of the options to install workloads. Instead, go to the individual components tab and choose the following:

        MSVC v142 - VS 2019 C++ x64/x86 build tools
        Windows SDK (10.0.17763.0)

    # Build Game
    1. Go to source code folder and type cmd, it will open invite comands and type (`lime test windows`)
    
    (for the first time it will take some 10min yes i know it long)
