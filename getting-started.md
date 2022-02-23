---
title: Getting Started
permalink: /getting-started/
---

# Getting Started

## Other Pages

- [Setup](/setup)
- [Mod Details](/mod-details)
- [Useful Coords](/useful-coords)
- [Home](/)

## Table of Contents

1. [Video walkthroughs and guides](#video-walkthroughs-and-guides)
1. [Feature Guides](#feature-guides)
1. [Game Guides](#game-guides)
    - [Creating a New Game](#creating-a-new-game)
    - [Creating your first character](#creating-your-first-character)
    - [Useful keys](#useful-keys)
    - [Menu navigation](#menu-navigation)
    - [Movement](#movement)
    - [The first days. Getting Started](#the-first-days-getting-started)
    - [Cleaning your farm with your tools](#cleaning-your-farm-with-your-tools)
    - [how to travel around the SV world](#how-to-travel-around-the-sv-world)
    - [How to find NPCs](#how-to-find-npcs)
    - [How to shop](#how-to-shop)
    - [How to sell](#how-to-sell)
    - [How to plant seeds](#how-to-plant-seeds)
    - [How to mine](#how-to-mine)
    - [How to fight monsters](#how-to-fight-monsters)
    - [Mods that work with Stardew Access](#Mods that work with Stardew Access)
    - [How to customize your character](#How-to-customize-your-character)


## Video walkthroughs and guides

- [By vol4life8657 or Access4All](https://youtube.com/playlist?list=PLExWgQUB-QT7tWumVTjAJETmgi6aWDJXs)
- [By Story of A Blind Life](https://youtube.com/playlist?list=PLr-oqzdwNQ3w4gRQQMgDWK-5e8p7Q7F2A)

## Feature Guides

### Constructing buildings

To construct buildings like silos, coops, barns, etc. you need to visit the Carpenter's shop, run by Robin in the Science house.

Steps:-
1. First we have to go to the farm and mark the position where you want to construct the building. Make sure the area is clear and big enough for the building you want to construct.
1. Go to the `Science House`, you can use debug ws robin to teleport both the player and Robin to the shop.
Now you can press `W` to make the player face the shop's cabin and then press `X` to open a dialogue box with options for `Shop`, `Upgrade House` and `Construct Farm Buildings`.
1. Right now we are going to construct a building so we will select the 3rd option, use `w` and `a` to cycle through the options and `[` or `Ctrl Enter` to select it.
1. Now the `Carpenter Menu` is opened, there are six buttons in this menu, from right to left, cancel, demolish, construct, move, next blueprint and previous blueprint buttons. 
1. Select the blueprint which you want to construct using the next/previous blueprint buttons. It will speak the info about the blueprint when we change it but you can also press `B` to speak the info of the currently selected blueprint.
Note that the info will also contain the dimensions of the building on farm.
1. Once selected, you can navigate to the `construct` button and select it via `[` or `Ctrl enter`.
1. Now the menu transitions to our farm and we can now open the command menu with `/` and enter the command
`marklist`. This will list all positions that you have saved with `mark` command in different lines, open the command menu again with `/` and use `pageup` and `pagedown` to cycle through the list. Note the index of the position you want to construct the building at.
1. Now open the command menu and enter the
`buildsel` command followed by the index, for example, the index of the position where I wanted to construct a building was 0, so I entered `buildsel 0` , for you it could be different depending on what you entered with the `mark` command.
1. If you had enough resources and the area you chose was clear of debris, then you will get a dialogue from Robin saying she will start the construction from tomorrow.

### Upgrade or Paint or Demolish Buildings

1. Go to the `Science House`, you can use debug ws robin to teleport both the player and Robin to the shop and now you can press `W` to make the player face the shop's cabin and then press `X` to open a dialogue box with options for `Shop`, `Upgrade House` and `Construct Farm Buildings`.
1. Right now we are going to construct a building so we will select the 3rd option, use `w` and `a` to cycle through the options and `[` or `Ctrl Enter` to select it.
1. Now the `Carpenter Menu` is opened, there are six buttons in this menu, from right to left, cancel, demolish, construct, move, next blueprint and previous blueprint buttons. 
1. To upgrade, select the appropriate blueprint using the next/previous blueprint buttons, for example, big coop. Once again, you can press `B` to speak the info of the currently selected blueprint. Now select the `construct` button.
1. For Demolishing, you don't have to select the blueprint, you can select the `demolish` button right away.
1. Now the menu transitions to our farm and we can now open the command menu with `/` and enter the command `buildlist`. This will list all buildings on your farm in different lines, open the command menu again with `/` and use `pageup` and `pagedown` to cycle through the list. Note the index of the building you want to upgrade/demolish.
1. Now open the command menu and enter `buildsel` command following with the index, for example, the index of the `coop` was 3 for me, so I entered `buildsel 3` , for you it could be different depending on what you entered with the `mark` command.
1. If all goes well, Robin will once tell you that she will start working on the upgrade tomorrow or you will hear a sound explosion sound for demolishing.

### Moving Buildings

Moving buildings is similar to constructing and upgrading buildings. In this, you have to first mark the position where you want to move a building then go to Robin, open the `Carpenter Menu` and select the `Move` button.
Then find the index of the building you wnat to move with `buildlist` command and then enter the `buildsel` command like this, `buildsel 3 0`.
Here `3` is the index of the building we want to move and `0` is the index of the position we save with `mark` command.
It will then move the building if possible.

## Game Guides

### Creating a New Game

Before we get into how to create a game and character, we want to remind you that the accessibility mod is now out of beta, but it's still being worked on.  
There may be bugs so please report them and try not to get mad when sometimes things don't work.

With that disclaimer out of the way, let's start.  
Now that your game and mods are set up, the next thing you should do is... Yes you guessed. Play.

To do this, you can go in your steamapps folder,
click on the common folder,
then on the Stardew Valley folder.
Once you're there, press enter on the StardewModdingAPI.exe file.
That will open a console window and the game window.
Keep both of them open, you will need the console too.

Alt tab until you find the game window.
There, press W or s.  
If nothing shows up, press left square bracket [.
You should hear a sound once left square bracket is pressed.  
If it still doesn't work, make sure that your keyboard is set to the english layout.

Now try to use A and D.  
Your screenreader should say: New Button. Load Button.  
If this is your first character, you will want to press left square bracket on new.

### Creating your first character
Great job so far, let's get your first character started.  
In this menu, you navigate using the arrows.  
When you press right arrow, it will ask you to write your farmer's name. Press left bracket then write it.  
You figured out the name? Good, follow the same steps to write the farm name by pressing right arrow again.  
The next thing you should write is favorite thing. Here write whatever comes to your mind.

The next button that you will see is skip intro.  
It's up to you if you want to go through it. Basically it's your character's introduction to the farm.  
If you want to skip it just press left bracket on it.  
If you want to listen to the tutorial, don't press it and continue.
Just A warning, the tutorial doesn't have spoken dialogue, so don't worry if things don't read, the game is working.  
To advance through the tutorial just keep pressing left bracket until the game dialogue is read by your screenreader of choice.

If you keep going right you will be able to select your gender.  
Male or female. Choose it the usual way, left bracket then keep going to the right.  
You will see a list of farm layouts that you can have, listen to their descriptions and choose the one you like.

And now what you've been waiting for, the okay button.  
Press it!  
If you decided to go forward with the intro, all you have to do is to wait and listen.  
When the dialogue is read by your screenreader of choice, press left square brace to move forward.  
Once the intro is done, you will find yourself inside your farmhouse.

Nicely done, you just created your first Stardew Valley character.  

### Useful keys 
Before you start playing, here are the keys that you will use:  
W to move north.  
S to move south.  
D to move east.  
A to move west.  
W, S, D and A are also the keys you will use when you navigate through your inventory, crafting skills or the shop menus and so on.  
Q narrates the time of day and the season.  
E opens the inventory, you can get out of the menu by pressing e again or escape.  
R narrates your money.  
X is used to open doors, chests, menus in shops or when you complete quests that ask you to bring someone something. This  is the key you need for example when you want to open the door to your farmhouse to get back inside.  
C is used when you use your tools. So when you want to use your fishing pole, you select it from your hotbar and press c.  
The same rule applies to the other tools or things that can be used from your inventory.  
F opens your journal menu. Here you will be able to see your quests.  
H is used to check your health and stamina.  
J is the key that you use to check what tile you're facing.
K is a key that you will need a lot, because it is the one that reads your coordinates.  
I | Selects the first item in chest inventory/crafting recipe/item to buy.  
Shift I, select the first item in the player's inventory.  
C (Only in the crafting page) Cycles through the available recipes in the current recipe lists.  
Numbers 1 through 9 and 0, minus and equal are your hotbar keys. If you press 4 you select your axe for example and by pressing c you use it on whatever's in front of you.  
Left  bracket [ is the key that becomes left click. You use it to accept quests, navigate through dialogues, buy things from shops, organise your inventory and much more. To give you an example on how it works in the inventory, for example, let's say that on the right you have your water can, number 4 and to the left you have an axe, number 3. But you want the axe to be on the right, and the can on the left.  
So you press left click on the axe, and you will hear a sound. you press d to move to the right where your can is. By pressing left click again you dropped the axe there and picked up the can.  
Now you press a to go to the left and drop the water can.

### Menu navigation
Navigating menus is done in different ways which will be covered in other sections of this guide, but right now I want to focus on the inventory menu.  
You open it with e, but there's more to your inventory than the row of tools and objects that you will collect during your playtime.  
To the right of your tools you will find the trashcan.  
If you want to throw away something to make more space, all you have to do is to select the object with left click, then to go to the trash and press the same key again.  
You will hear a sound and your object is gone.

Besides that, if you press w once focused on your inventory, you will find some more tabs.  
They are: inventory, skills, social, map, crafting, collections, options and exit game.

In the skills inventory you will see your skills.  
At first there will be nothing, you have to forage, fish, farm and so on for text to appear.  
The social menu will tell you how many hearts you have with an NPC, if it's single or married and how many gifts you gave him or her.  
The map can't tell you what's going on, but it can tell you what places are in the game and when they're open, so it's worth a look.  
The crafting menu is accessible. To select it, use the left bracket, and press s to see what recipes you have unlocked.  
Your screenreader will tell you what you can craft and what materials you need.  
So if for a chest you need 50 pieces of wood and you have the wood all you have to do to craft it is to press left click.  
If you have enough space in your inventory, the crafted chest will appear.
In the collections menu you will see what things have been shipped and in what quantities.  
The options menu contains the game options.  
And the exit game button is self explanatory. You can press on it and use s to see the options you have to quit.

### Movement
Movement in Stardew Valley is done, how I already mentioned using A, S, W and D.  
If you want to move tile by tile, you press s and release your key.  
To move continuously in a direction you hold the key pressed.  
If you couldn't move that means that there's something blocking your path.  
We recommend using your tools one by one to try to get rid of the obstacle.  
Usually using your hoe or scythe works, so try those first.  

### The first days. Getting Started
Now that you're in the game, you can start being a farmer.  
To do this, you have to plant and to clean your farmland.

But being your first day, you can explore a little the farm, if you want.  
To do this first you check your coords with k and move to the left, because most likely you are next to your bed.  
What you're looking for is the exit to the farmhouse, which is around the coordinates 3 11.  
Once you find that press s and you will be out of the farmhouse.  
Your coordinates changed probably to 64 15 or 64 18.  
Note them down so you don't get lost.

What you do now is up to you, you can try to clean south of your farm. So press s twice and listen to what your screenreader says.  
If it says grass, press 5 and c a few times. then 2 and c to till your soil.  
You should have now a patch of soil.  
Using the tools is easy.  
The axe cuts trees and anything wood related,  
the pickaxe stones, metals from the mine, boulders if upgraded,  
the water can waters crops,  
the hoe is used to till soil,  
and the scythe cuts grass and weeds, and it helps you harvest some of the seeds you plant when they're ready to be harvested.

If you're done exploring and experimenting, go back to your farm, 64 15, and press x.  
You should hear a door sound.  
You are back in your farmhouse.  
Now go east until you find your bed.  
A dialog should pop-up asking you if you want to sleep.  
If you select yes, you will start the next day and the game will save. Going to sleep is the only way you save your current day so make sure that if you have to stop playing, you go to sleep.

### Cleaning your farm with your tools
Using tools should be easy to understand.
You have a farm and you need to clean it.  
The easiest way is to go south of your farm until your coordinates stop changing, around 64, 61.  
So starting from 64 18, start using your tools on each tile and keep moving south.  
Then once you cleared that, move to the left or to the right and move up to 63 15 or 65 15 and keep repeating the process until you have enough plots cleared and enough crafting materials.  
Remember to keep track of the time with q to be inside the house before midnight.  

### how to travel around the SV world  
While some of us will like to note down the coordinates of the maps and learn our way around the game and its various places, others will like to move fast and use teleport commands.  
Remember when we said not to close the Smapi console that opens with the game?  
One of the reasons is closing that console closes the game, but even more important, that console is great for many things, such as teleporting, finding npc coordinates and much more.  
There are lots of cheat commands, but most of us would rather play the game naturally without cheating, only using commands that make the game more accessible.  
Before I explain how you can use them, I'd like to add that these commands aren't blind specific, everyone uses them.  
Some of these great commands, when it comes to teleporting are:  
debug warphome (it will bring you inside your farm house close to the bed)
Debug warp farm (will bring you in front of your house)  
debug warp sam house  (you will need this for a quest at some point)
debug warp community center  
debug warp mountain lake  
Debug warp beach  
debug warp shop (It will warp you to the seed shop)  
debug warp science (will warp you to Robin's shop)  
debug warp mine shaft (once the mine unlocks in the game, you can type this command to trigger the scene where your character will receive a sword that is needed to kill the monsters in the mine.)

### How to find NPCs
All you have to do, if you need someone's coordinates is to type  
debug where name.  

Some of the names you will probably need are:  
Pierre, Robin, Krobus, Sandy, Marnie, Clint, Gus, Willy, Pam, Dwarf, and Wizard.

### How to shop
For the moments when you will need more inventory space, seeds or farm buildings, you will want to go to one of the NPC run shops.  
To find the shops you can use the commands above or explore the town.  

When you are in the shop, you bring up the shop menu by pressing x.  
When that is pressed, you use w and s to choose whatever you want to buy then press left click to buy what you need.  
Have fun!

### How to sell
You've been fishing, planting, harvesting and maybe even mining, so why not make some money?  
You can sell things by going to X72,Y17.  
There you will hear a sound like a door opening.  
What you have to do once you're there is press x and then navigate the same way you do in your inventory.  
If you find something that you want to sell, left click on it to sell all of it or right click to add things one by one.  
Once you're done, press e or escape to exit the menu then get out of there by walking.  
You will get the money when you click to start  the next day, so don't worry.

### How to plant seeds
This being a farming game, you will need to plant things.  
Luckily, that is pretty easy.  
In your house you should find a chest.  
Open it with x.  
You should have received some seeds.  
If you have some cleared and tilled soil, all you have to do is to get out of your farm,  
look for your seeds using numbers 1 through 9 and 0, minus and equal and once you found your seeds,
press c when your screenreader says soil and your seed will be planted.  
Don't forget to water it once it's planted and keep watering it daily.  
If you think that you may forget where your seed is, note down the coordinates somewhere.  
Repeat the process until you have no more seeds.  
You can plant one seed per tilled soil.  

### How to mine
Locate the mine by walking or warping to trigger the cut scene that will give your character a sword.  
That will be required in the mine to kill mobs.

Friendly advice:  
Take some food or fish that you can eat to replenish your stamina and keep track of the time in the mine by pressing q.  
Also, make sure that you have some space in the inventory for the stones, gems and metals that you will find plus drops from the monsters that you will kill and Of course, don't forget to bring your pickaxe along.

Mining isn't hard once you try to follow a pattern that you like.  
The trick is to move in rows from top to bottom or from right to left to try to mine all the stone.  
To do the mining itself, just select your pickaxe from your inventory and press c.  
Sometimes you may need to press more than once to break a rock.

If you installed the  
[Accessible Tiles Mod](https://github.com/GrumpyCrouton/SDV-AccessibleTiles),  
You will have an even easier time navigating in the mines and the game in general. Read the readme in the link above, it will explain how the mod works.

The mine has levels, and to move from one level to another you will use ladders.  
These ladders sometimes spawn when you kill a monster, when you mine stone or they may be somewhere on the level already.  

Sometimes you will find barrels. To open them, break them with a tool from your inventory. I recommend the scythe, it doesn't use your stamina.

### How to fight monsters
You will find some monsters in the mine and in some other places later in the game and you can kill them.  
That's why you should go through the cutscene to get the sword, it helps.  
It's true that the damage on it isn't that big, but it's a good weapon when you begin.  

When they attack you there will be a sound.
Just check your health if you haven't heard the sound before.  
If your health is dropping, it means that a monster picked you as its victim.  
Fight back by selecting your sword and pressing c until that sound can't be heard anymore.

When you succeed killing it, check your health and eat some food to bring it back up if you're badly hurt.  
Side note, using the sword or the scythe doesn't drain your stamina.

### Mods that work with Stardew Access
Here are more mods that are accessible or that were created specifically to work with this mod.
For beginners, We highly recommend the  
[Accessible Tiles Mod by GrumpyCrouton](https://github.com/GrumpyCrouton/SDV-AccessibleTiles),  
and the
[Glue Your Furniture down mod by violetlizabet](https://www.nexusmods.com/stardewvalley/mods/10374)

Here are even more mods that you may enjoy.
They aren't required, just useful. It's your choice if you want to use them or not.  
[Wasteless Watering by GrumpyCrouton](https://stardew.grumpycrouton.com/releases/WastelessWatering.zip)
[Auto fishing](https://www.nexusmods.com/stardewvalley/mods/5235) 
[Chat Commands by CatCattyCat](https://www.nexusmods.com/stardewvalley/mods/2092)
[Time speed by cantorsdust and Pathoschild](https://www.nexusmods.com/stardewvalley/mods/169)

Please note, downloading mods from Nexus requires an account.  
Also, when you start the game for the first time once the mods are installed, they will generate config files.  
Each mod will have its file in the folder.  
The config files will allow you to change the keys they use if you want, or to set up the glue your furniture mod.  
Have fun playing!

### How to customize your character
Currently  customizing your character in game isn't accessible, so until that is made accessible, here's how you can add some personal touches to your farmer.  
By typing in the console player_changecolor and adding eyes or hair then an RGB color, you will change the color of your character's eyes or hair.  
For example: player_changecolor eyes 255,0,0 would make your character's eyes red.