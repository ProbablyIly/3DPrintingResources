Welcome to my repository! I intend to compile and summarise a variety of 3D Printing related things. It will primarily revolve around FDM and DLP. If you have any suggestions or additions, feel free to message me!

# Table of Contents
- [Hardware](https://github.com/KingofDelusion/3DPrintingResources#hardware)
  - [3D Printers](https://github.com/KingofDelusion/3DPrintingResources#3d-printers)
    - [FDM](https://github.com/KingofDelusion/3DPrintingResources#fdm) 
      - [Open Source](https://github.com/KingofDelusion/3DPrintingResources#open-source)
  - [DLP](https://github.com/KingofDelusion/3DPrintingResources#dlp)
  - [Add-ons and Mods](https://github.com/KingofDelusion/3DPrintingResources#add-ons-and-mods)
  - [Multi-Material](https://github.com/KingofDelusion/3DPrintingResources#multi-material)
  - [Parts](https://github.com/KingofDelusion/3DPrintingResources#parts)
  - [Miscellaneous](https://github.com/KingofDelusion/3DPrintingResources#miscellaneous)
- [Software](https://github.com/KingofDelusion/3DPrintingResources#software)
  - [CAD/Modelling](https://github.com/KingofDelusion/3DPrintingResources#cadmodelling)
  - [Slicers](https://github.com/KingofDelusion/3DPrintingResources#slicers)
  - [Model Sharing](https://github.com/KingofDelusion/3DPrintingResources#model-sharing)
  - [Utility](https://github.com/KingofDelusion/3DPrintingResources#utility)
- [Materials](https://github.com/KingofDelusion/3DPrintingResources#materials)
- [Resources](https://github.com/KingofDelusion/3DPrintingResources#resources)
- [Terminology](https://github.com/KingofDelusion/3DPrintingResources#terminology)
- [3D Printable Projects](https://github.com/KingofDelusion/3DPrintingResources/#3d-printable-projects)

# Hardware

  ## 3D Printers
  
   ### FDM
   
   #### Open Source
   - [Voron](https://vorondesign.com/) - Voron is a line of DIY, no-compromise 3D Printers. You need to source and print the parts yourself.
      -[Voron 0.1](https://vorondesign.com/voron0.1) - The smallet of the lineup, it's a traditional CoreXY with a full enclosure and a 120mm^3 bed. You can fit all Trident/V2.4 parts on it. The price estimate is about 400-600 USD and some kits in that price range are available. 
      - [Voron Trident](https://vorondesign.com/voron_trident)
      - [Voron 2.4](https://vorondesign.com/voron2.4) - The Voron V2 is is a modified CoreXY with a static bed and a three axis moving gantry. The linear rails make the print size scalable, from 250mm^3 to 350mm^3. Its estimated cost is between 1500 to 1900 USD.
      - [Voron Switchwire](https://vorondesign.com/voron_switchwire) - Voron's take on a standard Cartesian design, with a bed size of 250×210. The estimated cost is between 700-900 USD
      - [Voron Legacy](https://vorondesign.com/voron_legacy) - A more classic CoreXY design using rods instead of rails, the bed size is 230mm^3 and the estimated price is 600-800 USD.
   - [EVA](https://eva-3d.github.io/eva-spec/) - EVA is a modular standard for easily replacable 3D printer parts that aims to allow to easily swap parts for quick testing and experimentation. While you can make most printers EVA Compatible, they have collaborated with Rat Rig to create EVA compatible printers out of the box.
      - [V-Core 3](https://v-core.ratrig.com/) - The V-Core 3 is a scalable CoreXY Printer that is EVA Compatible
      - [V-Minion](https://v-minion.ratrig.com/) - The V-Minion is a really small 180^3 EVA compatible printer.
   - [White Knight](https://github.com/NAK3DDesigns/White-Knight) - White Knight is a 45 degree belt printer.
   - [SnakeOil XY](https://github.com/SnakeOilXY/SnakeOil-XY) - SnakeOil is an affordable, small CoreXY printer.
   - [HevORT](http://docs.hevort.com/#%2Fpages%2Fhome=) - A big CoreXY printer with a 3 point self levelling bed.
   - [Annex Engineering](https://github.com/Annex-Engineering) - A line of open source CoreXY printers that utilise a very unique motion system.
      - [Masherbrum K1](https://github.com/Annex-Engineering/Masherbrum-K1) - The K1 is a Medium, Direct Drive, fully enclosed 3D printer. It uses an unconventional XY motion system inspired by the "Hypercube Overkill Project". The build volume can be between 200mm^3 to 500mm^3 and the Z axis can theoretically be up to 1 metre tall. The gantry moves while the bed is stationary.
      - [Chhogori K2](https://github.com/Annex-Engineering/Chhogori-K2) - Very similar to the K1 but with a minimum build volume of 250^3 (still up to 500^3) but with a moving bed and a fixed gantry. 
      - [Gasherbrum K3](https://github.com/Annex-Engineering/Gasherbrum-K3) - The K3 is incredibly similar to the K2 but smaller and more compact. The build volume is 180^3.
   - Jubilee [GitHub](https://github.com/machineagency/jubilee) or [Wiki](https://jubilee3d.com/index.php?title=Main_Page) - Jubilee is a heavily customisable and extensible "multi-tool motion platform capable of running G-code". It's compatible with the E3D toolchanger and is meant to allow the usage of a multitude of tools added and modified by the community. One of which, is 3D Printing.
   - [Sixti](https://www.thingiverse.com/thing:3494010) - Sixti is a six colour 3D Printer that doesn't use purge towers. It instead has six hotends on a wheel as they rotate for every material change.
   - [Mulbot](https://github.com/3dprintingworld/Mulbot) - The Mulbot, or "Mostly 3D Printed Printer" is a as the name suggests a 3D Printer that tries to minimise the mechanical and electronic parts for 3D printed parts.
   - [mini one](https://www.thingiverse.com/thing:3749961) - The mini one is a redundantly small 3D printer with a magnificently small bed size of 45x45x40mm.
   - Snappy RepRap [Thingiverse](https://www.thingiverse.com/thing:2780361) or [GitHub](https://github.com/revarbat/snappy-reprap/wiki/v3.0-Home) - is a Snap together 3D Printer that uses mostly 3D printed parts.
   - Tripteron [Thingiverse](https://www.thingiverse.com/thing:1903757) or [YouTube](https://www.youtube.com/c/Propter/featured) - A brilliantly silly concept for a new and innovative motion system.


   ### DLP
   
   - [DIY DLP Printer](https://youtu.be/c2OQyfeLn_w) - A video covering the basics of building a DLP Printer

  ## Add-ons and Mods
  
  - [Official GitHub Repo](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods)/[Voronmods](https://faked.org/voronmods/)/[TeamFDM](https://www.teamfdm.com/files/category/2-printable-voron-user-mods/#:~:text=Voron%20User%20Mods%2C%20or%20%22UserMods,0%20Licensing.) - Sites and repositories containing mods and add-ons for the Voron lineup of printers.
  - [EVA](https://eva-3d.github.io/eva-spec/) - EVA is a modular standard for easily replacable 3D printer parts that aims to allow to easily swap parts for quick testing and experimentation.
  - [Voron to EVA](https://github.com/majarspeed/Voron-EVA-conversion) This is a conversion mod that converts a Voron printer to be EVA compatible.
  
   ### Multi-Material
   - [Enraged Rabbit Project](https://github.com/EtteGit/EnragedRabbitProject) - A multi-material filament switcher for Direct Drive toolheads and printers running Klippr. Primarily made for the Voron printers but it is compatible with any printers that fit the above requirements.
   - [SMuFF](https://sites.google.com/view/the-smuff/) or [SMuFF on GitHub](https://github.com/technik-gegg/SMuFF-1.1) - SMuFF or Smart Multi Filament Feeder is a scalable multimaterial filament loader. It most commonly replaces a bowden setup and it runs on its own control board connected via a UART serial port.
      - [OctoPrint SMuFF](https://github.com/technik-gegg/OctoPrint-Smuff) - An OctoPrint plugin that handles SMuFF.
   - [3D Print Colorizer](https://github.com/Sakati84/3DPrintColorizer) - While not exactly a multi-material add-on, it is an add-on that paints each layer using sharpies.
   - See Sixti in the Open Source FDM section
  ## Parts
  
  ## Miscellaneous
  - [FreeLoader](https://www.creativemachineslab.com/freeloader.html) - An OpenSource material testing rig, it can apply tensile and compression loads.
  
  - [Prusa i3 Parts](https://github.com/prusa3d/Original-Prusa-i3) - STL Files for the printed parts of the Prusa i3.

# Software

  ## CAD/Modelling
   - [OpenSCAD](https://github.com/openscad/openscad) - A programming based CAD proram.
  - [FreeCAD](https://github.com/FreeCAD/FreeCAD) - A free and open source CAD program.

  ## Slicers

  ## Model Sharing
  - [PrintABrick](https://github.com/hubnedav/PrintABrick) - A repository of 3D printable Lego Bricks.
  
  ## Utility
  - [OctoPrint](https://octoprint.org/) - OctoPrint is a web interface for controlling FDM Printers remotely. It's usually hosted on a local Raspberry Pi, although it can be hosted on Android, Linux, Windows and MacOS.
      -[OctoLapse](https://github.com/FormerLurker/Octolapse) - An OctoPrint plugin that allows the creation of timelapses.
      -[Octo4a](https://github.com/feelfreelinux/octo4a) - An OctoPrint port for Android.
      -[OctoPrintTFT](https://github.com/mcuadros/OctoPrint-TFT) - An OctoPrint Plugin for using a TFT touchscreen to control prints.
  - [SVG to Gcode converter](https://sameer.github.io/svg2gcode) - SVG to Gcode Converter.
  - [Photonic3D](https://github.com/area515/Photonic3D) - Photonic 3D is a web interface for controlling DLP printers.
  - [mini map maker](https://github.com/furrysalamander/mini-map-maker) - Creates STLs out of LIDAR scans.

# Materials

# Resources

# Terminology

# 3D Printable Projects
- [Faze4 Robotic Arm](https://github.com/PCrnjak/Faze4-Robotic-arm) - A 3D Printable 6 Axis Robotic Arm.
- [openDog](https://github.com/XRobots/openDog) - A robotic dog.
- [RaspberryTurk](http://www.raspberryturk.com/) - A robotic arm that plays Chess.
