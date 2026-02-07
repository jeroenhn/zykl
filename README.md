# ReZyklus Project

## A clone of the Zyklus MPS-1

The **ReZyklus Project** is an open-source effort to recreate the original **Zyklus MPS-1**.

This repository contains everything required to build your own Zyklus MPS-1 clone, aptly named 'ReZyklus', including hardware design files, panel layouts, and supporting documentation.

See my blog for some more info on the project:
https://www.zyklus-mps.com

There is a Discord server you can join specifically for this project:
https://discord.gg/zFuuCRRDz4

This is also the place where we think and talk about a succesor, the V2 which is mainly carried by David Perbal and will be a system based on the Teensy platform most likely. 

So what is the Zyklus MPS-1? 
A Midi Performance System. It's more than just a sequencer, it's kinda like an 80's version of a launchpad. 
There's really no better way to understand than to have one of the original developers show it to you, so check out Pete Kellocks video demo's of the Zyklus:
https://zyklus-mps.com/videos


Shout out to the team:

Paul McMurray (Technical genius who did most of the actual cloning work)

Marcel Donné (Tester/builder who build one of the first clones)

David Perbal (Another tester/builder who build two of 'm and is carrying the V2 project for the succesor of the ReZyklus - a Teensy based modern implementation)

Panu Talus (Zyklus enthausiast who for years has accumulated all sorts of historical information on the various units. Owner of an original)

And I'm Jeroen (Vangelis gear nut, founder of this project, also owns 2 originals and is restoring Vangelis orignal 'Direct' system).

---

## What’s in this repository

- **Bill of Materials (BOM)**  
  Detailed BOM spreadsheets provide a complete shopping list for the build.

- **PCB & Panel Design Files**  
  All PCB designs and front-panel files are provided.  
  The boards and panels were manufactured using **JLCPCB**, noting that their minimum order quantity is typically **5 units per board or panel**.

- **Case Parts**  
  Some enclosure components are **3D-printed**.  
  The required STL files are included in the repository.

- **Aluminium Dials**  
  Custom aluminium dials were also produced through **JLCPCB**, a working stepfile is included. The Case Parts also contain a file for a 3d printed version. 
  The alu dials need the threads tapped for M4 grub screws. 
  
- **Resource Links**  

  To come: links to various shops for parts, such as the PB86 type switches etc. 


---

## Firmware / OS Status

The original Zyklus operating system is still being worked on. Once ready for publication, it will be added here. The codebase is z80 Assembly and written in a very specific, old assembler which you'll need to compile and link. 

In the meantime, prebuilt EPROM binary files are provided, allowing you to build a fully functional Zyklus clone today while development continues.

---

## Credits & Acknowledgements

### Original Zyklus MPS-1 (1986)

The original Zyklus MPS-1 was created in 1986 by:

- Bill Marshall  
- Pete Kellock  
- Graham Mair  

Bill Marshall and Pete Kellock have generously given their blessing for this clone project to be released as open source.

---

### ReZyklus Project — Primary Contribution

It cannot be overstated that the vast majority of the work on this project has been carried out by Paul McMurray.

This includes, but is not limited to:

- KiCad schematics and PCB layouts  
- Panel designs & lauouts 
- 3D-printed parts  
- Electronics debugging  

Without Paul’s expertise, dedication, and deep understanding of both the original and modern electronics, this project simply would not exist.

Paul McMurray is the MVP of this project and instrumental in helping restoring Direct as well.



---

## Disclaimer

This project is a community-driven, non-commercial recreation intended for educational, historical, and personal use.  
All trademarks and original design concepts remain the property of their respective owners.

## License & Disclaimer

### License

This project is open source and open hardware.

* **Software (firmware, tools, scripts, source code):**
  Licensed under the **GNU General Public License version 3 (GPLv3)** or later.
  You are free to use, modify, and redistribute this software under the terms of the GPL, provided that any distributed modifications remain under the same license.

* **Hardware (schematics, PCB layouts, Gerbers, BOM, and related design files):**
  Licensed under an open hardware copyleft license
  (either **CERN Open Hardware License Version 2 – Strongly Reciprocal (CERN-OHL-S)** *or* **TAPR Open Hardware License**).
  You may use, study, modify, and manufacture hardware based on these designs, provided that any distributed modifications or derivative works are made available under the same license.

The intent of this licensing is to ensure that improvements to this project remain available to the community and cannot be taken proprietary.


THIS PROJECT IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT.

The authors and contributors are not liable for any direct, indirect, incidental, or consequential damages arising from the use, modification, manufacture, or distribution of this hardware or software.

This project is intended for educational, experimental, and research purposes. Use in safety-critical systems (including but not limited to medical devices, life-support systems, or any system where failure could cause injury or death) is expressly discouraged and done entirely at your own risk.

By using, modifying, or manufacturing from this project, you agree that all responsibility for compliance with local laws, regulations, certifications, and safety requirements rests solely with you.

---

### Commercial Use

Commercial use is permitted **only under the terms of the applicable licenses**. Any distributed modifications, derivatives, or products based on this project must remain open and must provide access to corresponding source code and hardware design files under the same license terms.










