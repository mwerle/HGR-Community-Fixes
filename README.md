#HGR Community Fixes

*Home-Grown Fixes for Home-Grown Rockets.*

![HGR Community Fixes logo](https://github.com/Kerbas-ad-astra/HGR-COmmunity-Fixes/raw/master/HGR%20Community%20Fixes%20logo.png)

##Features

I've been singing the praises of OrionKermin's Home Grown Rockets for a long time.  The jump from Size 1 to Size 2 parts is extremely steep -- a fourfold increase in thrust and an eightfold increase in mass.  Having a set of intermediate 1.875m parts and 2-seater command pods really helps smooth things out.  Unfortunately, Orion hasn't logged on since October 2015, so HGR hasn't kept up with the changes in the latter half of the 1.0.x releases, and there are also a few minor errors that haven't been corrected.  There are a couple of mods with 1.875m parts, but neither one is quite enough to substitute for HGR, so I and others have been sharing Module Manager patches to repair or improve various parts.  These patches were scattered about the latter pages of the HGR thread, but now they're all in one place.

The following patches are contained in this package (broken out into separate files so others can tinker and critque more easily):

* An AntennaRange adaptation patch for the solar panel -- if AntennaRange is installed, its range will match that of the Communotron 16 whip antenna (suitable for LKO with a level 1 tracking station).
	* There's also a RemoteTech patch as well.  (I don't use RT, so no comment on this one.)
	* There's also a patch to remove the obsolete "powerCurve" from the solar panel.  It's probably harmless, but why risk it?
* ModuleScienceLab is added to the Leek and Advanced Onion pods, so they can reset experiments and otherwise behave correctly.
* Heat shield updates for the discrete heat shield, the Radish, and the Spud, so they match stock heat shields now.  (They also properly support the 1.0.x updates for Deadly Reentry, I think.)
* Cost and mass fixes for the fuel tanks and fairing.
* Center of Pressure and Lift offsets for "descent" modules (the Type 45 Soy-Juice descent modules, the Lima, the Radish, and the Spud) and the heat shield, so capsules are passively aerodynamically stable.  Also, buoyancy parameters which match the stock capsules.
* A KIS patch to add an inventory to the Lima supply capsule.
* A "KAS" patch to remove deprecated KASModuleGrabs from RCS thrusters and the solar panels.
* Engine patches for the SoyJuice descent modules.	They now have Isp curves like Sepratrons, and their TWRs match.
* A "backup" RPM config, in case people forget (or rather, so that people aren't forced to remember) to change HGR/Spaces/SoyInt/internal2_RPM**.txt** to a **.cfg** file.

##Dependencies

HGR Community Fixes depends on [**Home Grown Rockets**](http://forum.kerbalspaceprogram.com/index.php?/topic/55521-102hgr-1875m-partsv130-released/) (v1.3.0), of course, and [**Module Manager**](http://forum.kerbalspaceprogram.com/index.php?/topic/50533-105-module-manager-2618-january-17th-with-even-more-sha-and-less-bug/).

##Recommended addons

If you're going to use 1.875m parts, you might as well get [**Filter Extension**](http://forum.kerbalspaceprogram.com/index.php?/topic/93955-105-filter-extensions-2412-nov-10/) so that the "size1p5" category gets a proper icon and description in the "Filter by Cross-Section" menu.

##Suggested addons

Crawling through the part configs and weeding out years' worth of accumulated cruft got me thinking about alternatives.  I love the "Pumpkin" 2-seater lander can too much to give up on HGR just yet, but in case 1.1 lands and breaks HGR completely (or I just get tired of making config repairs), here are a couple of other addons which add 1.875m parts:

* [**Socke's extension**](http://forum.kerbalspaceprogram.com/index.php?/topic/88780-wip-sockes-parts-1875m-extension/) only has fuel tanks and separators/decouplers, and Socke hasn't been around since last October either.  Thankfully, Merill has made [**an update**](http://forum.kerbalspaceprogram.com/index.php?/topic/88780-wip-sockes-parts-1875m-extension/&do=findComment&comment=1929389) for 1.0.x.
* Angel-125's [**Mark One Laboratory Extension**](http://forum.kerbalspaceprogram.com/index.php?/topic/94352-alpha-105-mark-one-laboratory-extensions-mole-v03/) is more complete and (more importantly) is actively developed and maintained.  It doesn't have a full range of engines, but there are enough adapters and multi-couplers to let stock engines fill in, and a 1.875m lab is coming soon. 

##Download and install

* [**GitHub**](https://github.com/Kerbas-ad-astra/HGR-Community-Fixes/releases)
* CurseForge
* KerbalStuff

From there, just unzip the "HGR" and "HGRCommunityFixes" folders into your GameData directory.  (If you've already renamed internal2_RPM.txt to internal2_RPM.cfg, you'll be asked if you want to replace it -- the files are identical, so it doesn't matter which you choose.)

##Version history and changelog

* 2016 02 XX (1.0): Initial release.

##Roadmap

Nothing much -- just keeping things up-to-date.  Unless somebody else makes an up-to-date 1.875m 2-seater lander can and 2-seater blunt capsule -- that's about all I'd need to be done with HGR!

##Credits

Thanks to speedwaystar for the RT patch, rasta013 for contributing to the lab patch, fatbrother for the fairing mass fix, pacbard for conributing to the engine patch, and ZentroCatson for contributing to the KIS patch.

And of course, thanks are owed to OrionKermin for HGR itself!  We wouldn't have anything to fix if not for him.  :wink:

##License

HGR Community Fixes is copyright 2016 Kerbas_ad_astra.  Configuration files are released under the [**Apache 2.0 license**](https://www.apache.org/licenses/LICENSE-2.0).  All other rights (e.g. the HGR Community Fixes logo) reserved.