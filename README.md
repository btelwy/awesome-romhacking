<div align="center">

<!-- title -->

# Awesome Romhacking
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Lint](https://github.com/btelwy/awesome-romhacking/actions/workflows/main.yml/badge.svg)](https://github.com/btelwy/awesome-romhacking/actions/workflows/main.yml)

<!-- subtitle -->

A list of resources for all your romhacking needs!

<!-- image -->

<a href="https://problemkaputt.de/gba-dev.htm" target="_blank" rel="noopener noreferrer">
  <img src="https://problemkaputt.de/gba-1024.gif"/>
</a>

<!-- description -->

Romhacking is the practice of editing a video game's code — located in its *read-only memory*, or *ROM* — in order to modify the game.

**Legend:** 🐧 = for Linux, 🍎 = for Mac, 🪟 = for Windows, 💸 = paid software
</div>

<!-- TOC -->

## Contents
* [Where to Start](#where-to-start)
* [Subfields](#subfields)
* [Consoles](#consoles)
* [Prominent Games](#prominent-games)
* [Tools](#tools)
* [Assembly (ASM) Languages](#assembly-asm-languages)
* [General Communities](#general-communities)

<!-- CONTENT -->

## Where to Start
* [Getting Started](https://www.romhacking.net/start) - Romhacking Dot Net's page for beginners looking to get started with the various subfields of romhacking.
* [The Definitive Guide to Romhacking for Complete Beginners](https://github.com/btelwy/awesome-romhacking/blob/main/Media/The-Definitive-Guide-to-Rom-Hacking-for-Complete-Beginners.pdf) - A guide to romhacking that covers the basics of what romhacking is.
### Fundamental Concepts
* [Hexadecimal](https://www.youtube.com/watch?v=UCgTEzcUolk) - A YouTube video explaining number bases, binary, and hexadecimal.
* [Introduction to Programming Logic](https://dev.to/abbeymaniak/introduction-to-programming-logic-understanding-the-basics-of-coding-64a) - A short description of the basic mindset behind programming logic.
* [What is Debugging?](https://www.ibm.com/topics/debugging) - An explanation of debugging and the general debugging process.
### Advanced Concepts
* [Data Representation](https://cs61.seas.harvard.edu/site/2023/Datarep/#gsc.tab=0) - Harvard computer science course notes explaining how computers internally process data.
* [Reversing: Secrets of Reverse Engineering](https://github.com/btelwy/awesome-romhacking/blob/main/Media/Eldad%20Eilam%20-%20Reversing%20-%20Secrets%20of%20Reverse%20Engineering.pdf) - A book about practices, strategies, and rationale for reverse engineering.

## Subfields
### Text Editing and Translation
### Graphics Editing
### Music Editing
### Level Editing
### Cheat Codes

## Consoles
### Game Boy
### Game Boy Advance
* [GBATEK](https://problemkaputt.de/gbatek.htm) - More than everything you'll need to know about the hardware and software of the GBA, DS, and (to an extent) the 3DS.
* [FAST6196's GBA and DS Romhacking Guide (2016 Edition)](https://github.com/btelwy/awesome-romhacking/blob/main/Media/romhacking2016.pdf) - A thorough overview of GBA and DS romhacking with helpful examples.
### Nintendo Entertainment System
### Nintendo 3DS
### Nintendo 64
### Nintendo DS
* [The Ultimate Nintendo DS Romhacking Guide](https://gbatemp.net/threads/the-ultimate-nintendo-ds-rom-hacking-guide.291274) - A thread on GBATemp that goes over basic DS romhacking. Note that it uses some outdated tools.
* [Nitro Studio 2 Deluxe](https://www.romhacking.net/utilities/1639) - An all-in-one tool for editing music and sound effects in .sdat files. 🪟
### Nintendo GameCube
### PlayStation
### PlayStation 2
### PlayStation 3
### PlayStation Portable
### Sega Dreamcast
### Sega Game Gear
### Sega Genesis
### Sega Master System
### Sega Saturn
### Super Nintendo Entertainment System
### Wii
### Wii U
### Xbox
### Xbox 360

## Prominent Games
### *Doom* series
* [Doomworld](https://www.doomworld.com) - A forum for *Doom* discussion, including documentation and help with creating mods.
### *Pokémon* series
* [Pokecommunity Forums](https://www.pokecommunity.com) - A forum for sharing, discussing, and providing information on making Pokémon romhacks.
* [r/PokemonROMhacks](https://www.reddit.com/r/PokemonROMhacks) - A large subreddit for discussing and making Pokémon romhacks.
### *Metroid* series
* [Metroid Construction](https://metroidconstruction.com) - The hub for *Metroid* hacking and resources.
### *Super Mario 64*
* [Pannenkoek](https://www.youtube.com/user/pannenkoek2012) - A *Super Mario 64* YouTuber who makes in-depth technical explainer videos about the game's workings.
* [Kaze](https://www.youtube.com/@KazeN64) - A *Super Mario 64* YouTuber who creates mods and has optimized the entire source code.
### *Mario* series
* [New Super Mario Bros. Editor (NSMBE)](https://nsmbhd.net/download) - The main tool for modding *New Super Mario Bros.* (DS). 🪟
* [New Super Mario Bros. Hacking Domain (NSMBHD)](https://nsmbhd.net) - A forum for discussing everything about *New Super Mario Bros.* (DS) romhacking.
* [Super Mario World Central](https://smwcentral.net) - A community all about *Super Mario World*, but also may be relevant to other SNES hacking.
### *Super Smash Bros.* series
### *The Legend of Zelda: Ocarina of Time*

## Tools
### Patchers
* [beat](https://www.romhacking.net/utilities/893) - Creates and applies BPS patches, a format which is a spiritual successor to the IPS format. 🪟
* [Lunar IPS](https://www.romhacking.net/utilities/240) - Creates and applies IPS patches. 🪟
* [Online ROM Patcher](https://www.marcrobledo.com/RomPatcher.js) - An online app for applying patches of various formats. 🐧🍎🪟
* [XDelta](https://www.romhacking.net/utilities/598) - An app for creating and applying .xdelta patches. 🪟
### Hex Editors
* [Hex Workshop](http://www.hexworkshop.com) - A hex editor with many integrated tools, but doesn't do much more than free hex editors can do. 🪟💸
* [HxD](https://mh-nexus.de/en/hxd) - A classic hex editor for disk, RAM, and file editing. 🪟
* [ImHex](https://github.com/WerWolv/ImHex) - A newer, modular hex editor for reverse engineering and programming, with features suited to romhacking. 🐧🍎🪟
* [WindHex32](https://www.romhacking.net/utilities/291) - A hex editor with romhacking features, especially ones targeted for SNES games. 🪟
### Debugging Emulators
* [BGB](https://bgb.bircd.org) - A Game Boy and Game Boy Color debugging emulator. 🪟
* [FCEUX](https://fceux.com/web/home.html) - An NES and Famicom Disk System emulator including features for romhackers. 🐧🍎🪟
* [NO$GBA](https://problemkaputt.de/gba-dev.htm) - The "gold standard" emulator for working with GBA and DS games. 🪟
### Reverse Engineering Frameworks
* [Ghidra](https://ghidra-sre.org) - Free and open-source software by the National Security Agency for reverse-engineering binaries. 🐧🍎🪟
* [IDA Free](https://hex-rays.com/ida-free) - The free (and thus limited) version of IDA Pro, used for reverse engineering and development. 🐧🍎🪟
* [IDA Pro](https://hex-rays.com/ida-pro) - The fully-featured version of IDA Free. 🐧🍎🪟💸
### Graphics Editors
* [Crystal Tile 2](https://www.romhacking.net/utilities/818) - Contains many tools for DS hacking, but is also helpful as a general tile editor. 🪟
### Translation
* [Kuriimu2](https://github.com/FanTranslatorsInternational/Kuriimu2) - A "general purpose game translation project manager" for making fan translations. 🐧🍎🪟

## Assembly (ASM) Languages
### 6502
*Used by the NES.*
### 65816
*Used by the SNES.*
### 68000
*Used by the Genesis.*
* [68000 Assembly Programming for the Sega Genesis](https://www.chibiakumas.com/68000/genesis.php) - A detailed introduction to 68000 assembly.
### ARM
*Used by the GBA, DS, and 3DS.*
### MIPS
*Used by the PS1 and PS2.*
### PowerPC
*Used by the GameCube, Wii, Wii U, and Xbox 360.*
* [Basic ASM](https://www.wiicoding.info/basic-asm) - An introduction to assembly using PowerPC.
### x86
*Used by the original Xbox.*
### Z80
*Used by the Master System and Game Gear; the Game Boy uses a modified version called GBZ80.*

## General Communities
* [Romhacking Dot Net (RHDN)](https://www.romhacking.net) - The main site for sharing and finding romhacks. Also contains tools and documentation.
* [Romhacks Dot Org (RHDO)](https://www.romhacks.org) - A smaller, developing community similar to RHDN.
* [Romhack Hispano](https://www.romhackhispano.org) - A romhacking community for Spanish speakers.
* [GameHacking.org](https://www.gamehacking.org) - A site dedicated to storing and creating cheat codes; includes a Discord server.
* [GBATemp Forums](https://www.gbatemp.net) - A large gaming forum with subgroups about romhacking on various consoles. There's a lot of valuable information here.
* [Game Banana](https://www.gamebanana.com) - A place to find (and upload) all sorts of game mods.
* [r/romhacking](https://www.reddit.com/r/romhacking) - A small subreddit about creating and playing romhacks.

<!-- END CONTENT -->

## Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!
### Contributors
[Thanks goes to these contributors](https://github.com/btelwy/awesome-romhacking/graphs/contributors)!
