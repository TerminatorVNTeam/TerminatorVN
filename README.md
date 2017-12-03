TerminatorVN
====================

[![TerminatorVN](http://i.imgur.com/R8gExma.jpg)](https://genisys.pro)

| ![Download icon](https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_file_download_black_18px.svg) PHAR    |

| [![Download](https://img.shields.io/badge/download-latest-blue.svg)](https://terminatorvn.github.io/TerminatorVNTeam/TerminatorVN.phar)


Introduction
-------------

__TerminatorVN is a feature-rich server software for *Minecraft: Pocket Edition* and *Minecraft: Windows 10 Edition*.__  
TerminatorVN is based on **[Genisys](https://github.com/iTXTech/Genisys)** with extended functionality. Most of the code was originally written by members of **[iTXTech](https://github.com/orgs/iTXTech/people)**.  

Some of the functionality that Genisys offers:
* Support for multiple client versions
* Extended API for plugins (GeniAPI)
* Optional Xbox Live authentication
* Support for Minecraft: Windows 10 Edition
* Global resource packs
* Generators for **ALL** world types i.e., **Overworld**, **Nether**, and **Ender**
* Integrated DevTools

Supported Version
-------------
Game versions supported by `master` branch:
- [x] Minecraft PE/Windows 10 v1.1.x

Get TerminatorVN
-------------
* Download the latest code from [GitHub](https://terminatorvn.github.io/TerminatorVNTeam/TerminatorVN.phar).  
* Get [PHP binaries](https://genisys.pro/info/download/) and other necessary components.
* Installation instructions can be found in the [Wiki](https://github.com/TerminatorVNTeam/TerminatorVN/wiki).


NOTE: **The `master` branch is the only officially-supported branch.**  
All other branches are in testing and may be unstable. Do not use builds from other branches unless you are sure you understand the risks.

TODO List
-------------

- [x] Modify file locations to `/src/pocketmine/network/mcpe/` for extended plugin compatibility.
- [ ] Discover all potential modifications that can enhance plugin backward compatibility.
- [ ] Re-work how async workers perform tasks to prevent them from hanging and not performing other tasks.
- [ ] Make modifications to handle Anvil worlds more efficiently to lower resource usage.
- [x] Add Ender generator.
- [ ] Add/Enhance Mob AI with option in yml.

TerminatorVN still has a long way to go. We are pleased to receive help from everybody and welcome contributors.  

Other Tools
-------------
* [Pocket Server](https://github.com/fengberd/MinecraftPEServer) - Run PocketMine-MP on Android devices

License
-------------
  	This program is free software: you can redistribute it and/or modify
  	it under the terms of the GNU General Public License as published by
  	the Free Software Foundation, either version 3 of the License, or
  	(at your option) any later version.

  	This program is distributed in the hope that it will be useful,
  	but WITHOUT ANY WARRANTY; without even the implied warranty of
  	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  	GNU General Public License for more details.

  	You should have received a copy of the GNU General Public License
  	along with this program.  If not, see <http://www.gnu.org/licenses/>.
