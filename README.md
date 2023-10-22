
# What is this?
This is a collection of mods I have made for the game [Crab Champions](https://store.steampowered.com/app/774801/Crab_Champions/) using [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS). These mods use the unstable C++ API of UE4SS
# FAQ
1. Can I get banned when using these? No. The developer does not mind modding
2. How do I install the mods? [Click Here](https://www.google.com)
3. Do these mods work online? I make these mods with the intent they are used in solo play but I do use them with friends online sometimes so most should work but if they do not I will not look into it!
4. How can I make mods to? 
	1. Download and install [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS).
	2. Dump all the Lua and Cxx bindings for the game.
	3. Use the live viewer to find function/objects
	4. Experiment! This is a very new thing for this game. It is also new to me. I have never made mods for unity games outside of astroneer which has a modding SDK already
	5. Publish! Feel free to make a PR to this github page or make a page on a place like nexus or modDB if there isnt one already! 
	6. If you need any help feel free to DM me on discord at `duckos_mods`. While I'm not the best I hope I can be of some use!
5. Will you be making more mods? Yes I hope! I have many ideas  I want to try and i might even try and make a modding SDK to make mods more powerful. That's along ways away though.  
# Installing
You have two options!  
You can compile them your self or you can go to the release page of this repo and check if i have released a compiled version of the mod and UE4SS version you want
## Easy Install (Recommended)
1. Go to the release page and download the `UE4SS_build.zip` this is the UE4SS build that all the mods I make will use on that page!
2. Download any mods you would like from there
3. Navigate to your install of crab champions which is located at `C:\Program Files (x86)\Steam\steamapps\common\Crab Champions` If you have not changed your install directory.
4. Next navigate too the `CrabChampions` folder then the `Binaries` then `Win64` the whole path should look like `C:\Program Files (x86)\Steam\steamapps\common\Crab Champions\CrabChampions\Binaries\Win64`
5. Now extract the stuff from `UE4SS_build.zip` into this directory
6. Go to the `Mods` Folder and extract any mods you downloaded into there with there folders
7. Open the `mods.txt` and enable the mods that you want
8. Start the game and enjoy!

## Advanced Install
This expects you have some knowledge of making C++ mods for UE4SS. 
1. Clone this whole repo with `--recursive`
2. Navigate into folder you just cloned into and run `cmake -B build -S .`
3. Wait and hope your PC doesn't combust into flames (important)
4. Then navigate into the build folder
5. Open the folder of the mod your Interested in this example i will be using `CrabChampionsUtils`
6. Open the `.sln` 
7. Change the build configuration of the project too `Game__Shipping__Win64`
8. Click build and wait and pray your PC doesn't explode
9. Repeat steps 5 too 8 for all mods that you want to use
10. Then navigate to the install directory of your game this should be `C:\Program Files (x86)\Steam\steamapps\common\Crab Champions\CrabChampions\Binaries\Win64` if you have not changed anything related to your installs
11. Open the `Mods` folder then create a folder with the name of the mod you want to install in this case it is `CrabChampionsUtils`
12. Open this new folder and create a folder named `dlls` move the compiled DLL of the mod you would like to install to this new directory
13. Rename the dll to `main.dll`
14. Enable it in the `mods.txt`
15. Start the game and enjoy! 
Near the end of writing this I just gave up so if you need help DM me on Discord at `duckos_mods` Ill try and help you
# Resources
1. [UE4SS Discord](https://discord.gg/yw4W7UTJXu)
2. [Unreal Engine Modding Discord](https://discord.gg/VaqBmYgtT2)
# Modlist
1. None Right now sadly! But hopefully some will be added soon!
