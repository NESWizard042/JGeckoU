## Overview
`JGecko U` is a replacement for [`TCP Gecko.NET`](https://github.com/Chadderz121/tcp-gecko-dotnet) as a platform independent Wii U RAM debugger and cheat code manager for Wii U titles.

It is the most advanced Wii U game hack/cheat development tool which is used by almost all mod developers and end users across all Wii U titles.

## Setup
**PC side:**
* Install [`Java 8+`](https://www.java.com/en/download)
* Download `JGecko U.jar` from [here](JGecko%20U.jar?raw=true)*
* Double-click `JGecko U.jar` **OR** type `java -jar "JGecko U.jar"` on the command line/Terminal to launch `JGecko U`

**Wii U side:**
* Download the [`TCP Gecko Installer`](https://github.com/BullyWiiPlaza/tcpgecko/blob/master/tcpgecko.elf?raw=true). Extract it to your SD Card into the folder `E:\wiiu\apps\TCPGecko`*
* Proceed to run the [`Homebrew Launcher`](https://github.com/dimok789/homebrew_launcher) by visiting `http://u.wiidb.de` with your Wii U. Finally, load the `TCP Gecko Installer` app and confirm the desired `TCP Gecko Installer` installation mode.

*Alternatively: Use the [`Gecko U Updater`](https://github.com/BullyWiiPlaza/Gecko-U-Updater) application.

A YouTube video visually showing the full setup guide can be found [here](https://www.youtube.com/watch?v=Uk7DhEdSfxA).

## Donator features
Since the application took months or even years to develop and I worked on it alone, I made some features of JGecko U donator only. If you appreciate this application and want to unlock extra features (mainly useful for code creation and development), feel free to become a donator on the Donator tab in JGecko U. The following features will become available after donator license activation:

**Disassembler**
* Add Dump Registers Hook: Adds an assembly hook to dump values of registers of interest
* Add Dump Structures Hook: Adds an assembly hook dump structures of interest
* Insert Hook: Allows inserting assembly instructions at the current address in the disassembler (performs a jump to the injected assembly and a jump to safely return after execution)
* Delete Hook: Removes an inserted hook again
* Parse Immediate: Finds corresponding lis/ori or lis/addi etc. pairs (which setup the same register) and gets the address referenced by both of them

**Cafe Code Creation**
* Code Wizard: Supports creating all codetypes via easy to use dialogs and input components

**General**
* Watchlist: Allows watching the current values of multiple addresses (including pointer support and view modes)

**Assembly**
* Obfuscate Assembly: Allows obfuscating assembly sources with mathematical tricks to make reverse engineering hard (note: this feature is experimental and may not be completely stable. Intended to be used on simple and short assembly RAM writes)
* Parse IDA Pro ASM File: Allows loading assembly instructions from an IDA Pro .asm file

**View Modes**
* Memory Viewer View Mode: Allows switching the view mode of all data in the memory viewer
* Search Tab View Mode: Allows switching the view mode of all results in the search tab

## Feature Requests/Problems
You can post them in one of the following places:
* [GitHub issues](https://github.com/BullyWiiPlaza/JGeckoU/issues)
* [`Discord`](https://discord.gg/XVA6SjJyC8)

**Note:** 

The following types of requests will **NOT** be answered:
* Requests for code creation or sharing codes (-> this is not related to bugs or features of `JGecko U`)
* Reports regarding codes not working correctly (-> unless you can prove that there is a code handler bug)
* Requests regarding connection problems (-> follow the setup guide and verify your network/IP address(es))
* Requests regarding learning how to get started with making codes (-> watch/read tutorials like [`the ones on my YouTube channel`](https://www.youtube.com/playlist?list=PLKHNWhJawkhgisx0p0Fmv0E3UvwFWTADN) first)

## Credits
Check the `About` tab in `JGecko U`.
