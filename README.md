# Bear Extruder And X Axis

## Table of contents
  1. [Introduction](#introduction)
  1. [Features](#features)
  1. [Compatibility](#compatibility)
  1. [Download printed parts](#download-printed-parts)
  1. [Manual](#manual)
  1. [Optional parts](#optional-parts)
  1. [Community](#community)
  1. [Images](#images)
  1. [Support my work](#support-my-work)
  1. [Thank you](#thank-you)
  1. [Credit, sources and inspiration](#credit-sources-and-inspiration)

## Introduction

This is a better extruder and X axis for Prusa i3 printer MK2.5S and MK3S. It is a following of the [Bear Upgrade project](https://github.com/gregsaun/prusa_i3_bear_upgrade) and is still compatible with original Prusa's 3D printers.

The main goal of this extruder is to improve print quality, reliability and make maintenance easier.

:warning: The Bear X axis is **NOT** compatible with stock Prusa extruder!


## Features

Here is a list of improved features over stock Prusa extruder.

1. Improve print quality:
   * Better hotend cooling to improve consistency of layers deposition and to reduce clog, heatcreap and stringing (also check these [recommended hotend fans](optional_parts/hotend_fan))
   * Reduce flexing of X axis
   * Stiffer extruder uni-body to reduce vibration coming from Bondtech gears
   * Stiffer X axis and several improvements to reduce vibrations
   * Extruder is closer to X rods to reduce the lever arm and vibration
   * Bondtech drive gears closer to motor to reduce shaft flexing
   * Includes hotend collet clip to eliminate the risk of PTFE moving during retractions
   * More efficient part cooling thanks to nozzle fan duct and bottom shape of extruder
   * Belt path moved closer to top rod for smoother movements
   * Filament path is aligned according to Bondtech specifications (check [this issue](https://github.com/prusa3d/Original-Prusa-i3/issues/51))
   * Optional: X end idler for E3D Gates idler

1. Easier to maintain:
   * No need to disconnect cables from RAMBo to disassemble the extruder or access the belt
   * Z bearings installation made easier thanks to clamps
   * Simple and precise belt tensioning system with 3mm of adjustment
   * Self-centering of extruder motor
   * Easy installation and removing of E3D v6 hotend
   * Easier extruder assembly
   * No zip ties needed for X carriage bearings
   * Fewer screws

1. Improve reliability:
    * Parts designed to last
    * Better heat management
    * Reduce chance to melt extruder body
    * Vertical print fan to reduce bearing wear and noise
    * Reduce possible twist on X axis
    * Reduce chance of bad bearing alignment
    * Fewer screws
    * Extruder body in one piece

1. Support alternative extruders:
    * [E3D Hemera](https://e3d-online.com/e3d-hemera-175-kit)
    * [Bondtech Prusa Upgrade extruder](https://www.bondtech.se/en/product/prusa-i3-mk2-5-mk3-extruder-upgrade/)
    * [Bear extruder for MMU2S by vertigo235](https://www.thingiverse.com/thing:3472911)
    * [Gear box for Bear extruder by vertigo235](https://www.thingiverse.com/thing:3714978)

1. Several official and community optional parts
1. Open source by providing STL and Autodesk Fusion 360 files and STEP files



## Compatibility

Due to a different belt path, this extruder and X axis are matched to each other __and cannot be used separately__. As a unit, they are compatible with both Original Prusa and Bear Upgrade frames.

  * This Bear extruder version supports the new IR filament sensor introduced with latest Original Prusa MK2.5S/MK3S extruder.
  * This Bear extruder version is compatible with original Prusa firmware for daily use. However, (XY)Z calibration and selftest require a dedicated firmware for these steps only.
  * MK2.5 (non-S) and MK3 (non-S) is compatible with this Bear extruder version with the exception of the filament sensor.

In an effort to lengthen the Z axis, the original Prusa MK2.5S/MK3S hotend was raised by about 7 mm. This placement increases the ambient temperature around heatbreak and heatblock which could leads to print quality and reliability issues. We then have decided to not lengthen the Z axis in order to provide best printing experience. Because of this difference with original Prusa extruder, we provide a customized firmware to pass Selftest and (XY)Z Calibration. At the exception of these steps, the original Prusa firmware is completely compatible with our extruder.

The firmware is available here: https://github.com/bear-lab-3d/Prusa-Firmware/releases/



## Download printed parts

  * From Thingiverse: [thingiverse.com/thing:3716110](https://www.thingiverse.com/thing:3716110)
  * From this GitHub: [printed_parts/stl](printed_parts/)



## Manual

The manual contains bill of materials (BOM), print settings and assembly instructions.

[Read the manual on guides.bear-lab.com :book:](https://guides.bear-lab.com/c/Extruder_X_Axis)



## Optional parts

Official and community optional parts [are listed here](optional_parts)



## Community

Here are the places were the Bear project is the most active. Do not hesitate to ask if you have a question :

* Facebook group : [facebook.com/groups/PrusaBearUpgrade](https://www.facebook.com/groups/PrusaBearUpgrade)
* Discord server of "The 602 Wasteland" community : [discordapp.com/invite/hYUjSnW](https://discordapp.com/invite/hYUjSnW)
* GitHub : [github.com/gregsaun](https://github.com/gregsaun)
* Thingiverse : [thingiverse.com/pekcitron](https://www.thingiverse.com/pekcitron)
* Openbuilds community : [openbuilds.com/builds/prusa-i3-bear-upgrade-v2.6428](https://openbuilds.com/builds/prusa-i3-bear-upgrade-v2.6428/)



## Images

![Bear extruder and X axis](doc/photos/5D3_5336.jpg)

![Bear extruder](doc/photos/5D3_5340.jpg)

![Bear X end motor](doc/photos/5D3_5428.jpg)

![Bear X end idler](doc/photos/5D3_5600.jpg)

![Bear extruder X carriage back](doc/photos/bear_x_carriage_back_03.gif)

![Bear extruder filament sensor](doc/photos/bear_extruder_filament_sensor_02.gif)

![Bear X end idler](doc/photos/5D3_5431.jpg)

![Bear X end motor](doc/photos/5D3_5446.jpg)

![Bear X end motor](doc/photos/5D3_5407.jpg)

![Bear X end idler](doc/photos/5D3_5348.jpg)

![Bear X end idler](doc/photos/5D3_5436.jpg)

![Bear X end idler](doc/rendering/bear_heatblock_comparison.jpg)



## Support my work

The Bear project is made possible thanks supporters, you can participate via
<br/><br/>
[![become a patron](doc/icons/patreon_50px.png)](https://www.patreon.com/gregsaun)<br/>[patreon.com/gregsaun](https://www.patreon.com/gregsaun)
<br/><br/>
[![paypal.me](doc/icons/paypal_50px.png)](https://www.paypal.me/gregsaun)<br/>[paypal.me/gregsaun](https://www.paypal.me/gregsaun)
<br/><br/>
 You can also send me a tip via [Thingiverse](https://www.thingiverse.com/pekcitron/about) if you prefer that way.

Massive thank you in advance :heart:



## Thank you

Thank you to all my Patreon : 3D-Maniac, 3DPrintronics, Aaron Rieley, Ahmet Kocamese, Aki Juntunen, Alex Vasile, Anders Svendsen, Andrew Bingham, Asbjorn Mikkelsen, Austin Vojta, Bas Borgignons, Bastian Sembdner-Braun, Ben Langley, Bob Collinsworth, Borja Gutierez Yañez, Brad Craig, Brad Marreno, Carlos Varas, Chip, Chris Jackson, Chris Theberge, Chris Warkocki, Chris, Christopher Lee, Christos Goulas, Corey Dryja, Corrado, Cowen, Cristian Toma, D4rkH0ur, Danger Mause, Daniel Zittel, darkly spectre aka that one belgian cunt, Darren Furniss, David F Morrison II, David Pesce, David Tyra, Dejan Vozlic, Dominik Hahn, Doug Palmer, Doug Robertson, Dustin Lehmann, Elendil the tall, Emiliano Vignali, Eric Mathison, Erich Jermann, Ethan D Goodsell, Evan, Evgen, Fabian Bruse, Fake Patreon, Felix Ekman, Filament Frenzy, Filip Hronek, flobler, Garth Clardy, Gerd Jentz, Glen Brown, Greg3D, Grigori Palamartšuk, Harrison, Hector Gonzalez, Hobby Hoarder, Hugo Henry-garon, I've Seen Things, Illia Tsariuk, J.D. sloot, jac shakeab, Jacek Owczarek, Jack Emilsen, Jacob Leonard, Jake Hamlin, James ballan, Jan Andersen, Jason Bao, Jason Marcus, Jay Davis, JD, Jesper, Jim Jacques, Jimmy Lee, Joan Torner Corrons, Joe Mike T, Joel Weinberg, Jonathan Ryer, Joseph Quan, Josh Carter, Josheua R Mascote, Joshua Jones, JTa, Juan Rosario, Keith Beaul aka ciscokeb, Ken Waters, Kevin Smith, Kevin Tapper, Kim Schauss, Kristof Spiszak, Laurent Zender, Loïc Dumont, Magnus Pfeffer, Marc, Marie Barada Saunier, Mark Griesi, Markku Sinisalo, maroonds, Martin Majewski, Megan Cooper, Melissa LeBlanc-Williams, Merijn van Mourik, Michal Kapusnik, Miguel Castillo, Mike An, Mike Phelps, Moody Wood Carving, Morgan Jonasson, Name, Narasak Mansurang, Nawaf Al-Abdulrazak, Neofitos Papadopoulos, Nicholas Christopoulos, Nicolas Pottier, Orlando E Moran, Oscar Padilla, Owe Brekken, Palko Kupecz, Patrick Glyré, Patrick Hung, Patrick Wong, Peter Kelly, Peter Sanders, Phil S., Phillip Hartley, Przemek, QcRetro, ra100, Rasmus Baes, RC-CnC, Richard Bateman, robert veline, Rodney Ford, Ronny Olsen, Rubens Panfili, Ryan Lenny, Ryan Lobbins, SamE0717, Satoshi Takanashi, Scott Rini, Serkan Aksu, Settle, Shane Wallner, Shawn Chronister, Shawn England, Skyler Weinkauf, sleene, Staffsmith aka Thorben Plath, Stanislav Kljuhhin, Stephan Kohls, Stephen Pope, Steve Carter, Steve Peterson, Steven Daglish, Stian Aronsen, Stig Jøran Moen, Stuart Galloway, Stuflo, Ted Marsh, Ted Rathkopf, ThatIrishSOB, Thom Sturgill, Thomas Tuchan, Timothy Franke, tinyledmatrix, Toby @ 3D GeeksApp, Tom Kogut, Total Dramatist, Trae LaPole, Tyler Townes, Valentin Constantin, Valeria, Víctor Martínez, Warren Schultz, Wes Warner, Yann Gosteli.

Thank you to David Ogles, Flobler, Jason from LDO Motors, Matthew Humphrey, Nathan Denkin, Orlando from All3DMakers, Saiz, Sleene, Termlimit, Vertigo295 for helping me developing the Bear project.

Thank you to all that have send me a tip on Thingiverse and PayPal.

Thank you to everybody from Facebook group and The 602 Wasteland community.

Thank you for having purchased a kit from an official distributor.

Thank you to all official distributors for taking care of the kits and customers.

Thank you Jason from LDO Motors for the quality manufacturing and relationship.

Thank you Openbuilds for your hardware, community and state of mind.

Thank you for making the community alive with all your comments, issues, pull requests, optional parts, make, pictures, etc.


## Credit, sources and inspiration

Here is a list of sources and inspiration :

* Prusa : http://www.prusa3d.com
* Vecko Kojchevski for the help on some details of the X end clamps, X carriage and PTFE cutter : https://www.thingiverse.com/vekoj/designs
* Arnaud Rousseau for "its X-Ends clamped MK3 (Zaribo)" : https://www.thingiverse.com/thing:2964026
* Prusa i3 Solidworks parts from jzkmath : https://github.com/jzkmath/Original-Prusa-i3
* Prusa MK2/S X-Carriage Adjustable Tensioner by Jon Madden : https://www.thingiverse.com/thing:2770019
* Jan Imrich from [Kurzy Kocour](https://www.facebook.com/KurzyKocour/) maker space for all it's hard work on inconsistency issue
* The 602 Wasteland Discord community for their precious knowledge and advices
* [RH_Dreambox](https://www.thingiverse.com/RH_Dreambox/about) and [Robrps](https://www.thingiverse.com/robrps/designs) for their nozzle fan duct designs
* Joel from [Bondtech](https://www.bondtech.se/en/product/prusa-i3-mk2-5-mk3-extruder-upgrade/) for having pushed me to pursue the filament sensor idea

Massive thanks to these projects, without them this project can not exist!
