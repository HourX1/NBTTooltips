

# Nbt Tooltips 2.0    <img src="https://camo.githubusercontent.com/49b29197e2b4b615ec3fc9719a7898ef399be5df19ff35d0a430f417ed51fa4e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c616e6775616765732f746f702f4b6f70616d65642f526176656e2d62504c5553" alt="Youtube Badge"/>
  </a>

[![curseforge downloads](http://cf.way2muchnoise.eu/full_nbt-crafting_downloads.svg)](https://minecraft.curseforge.om/projects/nbt-crafting)
<p align="center">
<img alt="ViewCount" src="https://views.whatilearened.today/views/github/MShawon/YouTube-Viewer.svg">
<img alt="OS" src="https://img.shields.io/badge/OS-Windows%20/%20Linux / Mac-success">
<a href="https://github.com/MShawon/YouTube-Viewer/issues?q=is%3Aissue+is%3Aclosed"><img alt="Closed issues" src="https://img.shields.io/github/issues-closed/MShawon/YouTube-Viewer.svg"></a>
<a href="https://github.com/MShawon/YouTube-Viewer/issues?q=is%3Aissue+is%3Aopen"><img alt="Open issues" src="https://img.shields.io/github/issues/MShawon/YouTube-Viewer"></a>
</p>
<p align="center">
  <a href="https://github.com/MShawon/YouTube-Viewer/releases/latest"><img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/MShawon/YouTube-Viewer?color=success"></a>
  <a href="https://github.com/MShawon/YouTube-Viewer/releases/latest"><img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/MShawon/YouTube-Viewer?color=success"></a>
</p>

[![latest maven release](https://img.shields.io/maven-metadata/v?label=latest%20maven%20release&metadataUrl=https%3A%2F%2Fmaven.siphalor.de%2Fde%2Fsiphalor%2Fnbtcrafting-1.15%2Fmaven-metadata.xml)](https://maven.siphalor.de/de/siphalor/nbtcrafting-1.15/)

![logo](images/logo_2.0_big.png?raw=true)

## About
A forge mod which allows you to see an items nbt.

Everything is kept nicely visualized in the vanilla gui.

This can be achieved through the reintroduced /nbt attribute. 

**You can find more information in the [wiki](https://mcwor.de/nbt-crafting/v2).**

## Examples

You can find a datapack with some examples here: [Example Datapack](https://github.com/Siphalor/nbt-craftisuites/7385455218/artifacts/300475995)

A sample of some of the nicely writen code in this mod.

```json
{
  "type": "crafting_shapeless",
  "ingredients": [
    {
      "item": "minecraft:diamond_sword",
      "data": {
        "require": {
          "Damage": 2
        }
      }
    }
  ],
  "result": {
    "item": "minecraft:wooden_sword",
    "data": {
      "Damage": 2
       "nbt = 34678"
    }
  }
}
```

## Extra
Due to some additions made with this mod the nbt might some times not work - yay!

## License
This mod is available under the Apache 2.0 License.



 
