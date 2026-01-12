# awesome-speleo

Awesome caving and speleology resources. Add new suggestions in [Issues](https://github.com/kravietz/awesome-speleo/issues)
or ready entries in [Pull Requests](https://github.com/kravietz/awesome-speleo/pulls).

## Caving chat

![Matrix](https://matrix.org/ecosystem/clients/element.svg)

* [#therion-general:matrix.org](https://matrix.to/#/#therion-general:matrix.org)
* [#cave-surveying:matrix.org](https://matrix.to/#/#cave-surveying:matrix.org)
* [#cave-comms:nitro.chat](https://matrix.to/#/#cave-surveying:matrix.org)
* [#cave-rigging:nitro.chat](https://matrix.to/#/#cave-rigging:nitro.chat)
* [#cave-rigging:nitro.chat](https://matrix.to/#/#cave-rescue:nitro.chat)

## Surveying hardware

Data collection:

* [BRIC](https://www.bricsurvey.com) BRIC5
* [DistoX2](https://paperless.bheeb.ch) discontinued
* [Disto XBLE](https://www.youtube.com/watch?v=6OvoH-lpF4c), DistoX2 redesigned by Siwei Tian (China)
* [SAP (Shetland Attack Pony)](https://www.shetlandattackpony.co.uk/index.php?route=common/home)
* [Cave Sniper](https://speleonews.pl/cave-sniper/)
* [CavWay X1](https://cavedevice.com/blogs/cave-survey/cavway-x1-the-next-generation-cave-survey-tools)

LIDAR:

* [Caveatron](http://www.caveatron.com)
* [Poor Man's Laser Scanner (PMLS)](https://github.com/poormanslaserscanner) continuous scanning firmware for DistoX2, discontinued
* [Prometheus](https://3dcavesurveys.com/index.php/prometheus/), upcoming
* [Mandeye](https://github.com/MapsHD/HDMapping), DIY Lidar design for cave mapping

Muon tomography:

* [Ideon Reveal](https://ideon.ai/reveal-platform-technology/), commercial muon tomography for underground surveys
* [CosmicWatch](https://github.com/spenceraxani/CosmicWatch-Desktop-Muon-Detector-v2), open-source low-cost underground muon detector

GNSS:

Software and hardware for precise (<1 m) object location:

* [Location fixing for cave surveys: How to obtain a fixed point for a cave survey](https://www.cavinguk.co.uk/info/locatingsurveys.html) tutorial on the challenges of precise cave entrance location
* [Trimble Catalyst](https://geospatial.trimble.com/en/products/software/trimble-catalyst) used Trimble DA1 can be purchased at reasonable prices
* [ArduSimple RTK Calibrated Surveyor Kit](https://www.ardusimple.com/product/rtk-surveyor-kit-accessories/)

## Surveying software

### Mobile

Mobile apps used underground for data collection and sketching:

* [Qave](https://play.google.com/store/apps/details?id=com.svist.qave), Android
* [SexyTopo](https://play.google.com/store/apps/details?id=org.hwyl.sexytopo), Android, open-source
* [TopoDroidX](https://sites.google.com/site/speleoapps/home/topodroid), Android, do not install app from Google Play Store as it's outdated

### Data management and sketching

Cave survey data management and sketching apps:

* [Compass](https://fountainware.com/compass/index.htm), Windows
* [GHTopo](https://ghtopo.blog4ever.com/ghtopo), Windows, Linux, open-source
* [Survex](https://survex.com), Windows, Linux, open-source
* [Therion](https://therion.speleo.sk), Windows, Linux, open-source
  * [Mapiah](https://github.com/rsevero/mapiah), new GUI for Therion
* [Tunnel](https://github.com/CaveSurveying/tunnelx), Java, open-source
* [Walls](https://www.texasspeleologicalsurvey.org/software/walls/tsswalls.php), Windows

### Other

* [CaveWhere](https://cavewhere.com), Windows, MacOS, Linux, open-source - visualise cave surveys as 3D models
* [TerrainTool](http://ubss.org.uk/terraintool/terraintool.php), Java, open-source create surface topographic data for the cave survey packages Survex and Therion

### Photogrammetry

Computing 3D models and cave surveys from cave videos.

* [Photogrammetry for 3D Mapping of Caves](https://ruuth.xyz/Photogrammetryfor3DMappingofCaves.html) tutorial
* [3D Cave Surveys](https://3dcavesurveys.com)
* [micmac](https://github.com/micmacIGN/micmac) photogrammetry software

## Caving gear

### Headlights

There's plenty of headlamps on the market, so only lighting designed or suitable for caving is listed here:

* [Earth Worm](https://earthwormcavelight.co.uk)
* [ElSpeleo](http://www.elwork-speleo.hr/Index.aspx?l=EN)
* [Fenix HM series](https://www.fenixlighting.com/collections/headlamps)
* [Little Monkey](https://littlemonkeycaving.co.uk/Rude-Nora-4/)
* [MidiLED](https://www.midiled.pl/)
* [Petzl Duo series](https://www.petzl.com/GB/en/Sport/Headlamps)
* [Scurion](https://www.scurion.ch/)
* [StenLight](http://www.stenlight.com)
* [Zebra Lights](https://www.zebralight.com/Headlamp_c_7.html) US only

## Cave communications

Please read [Through-the-earth mine communications](https://en.wikipedia.org/wiki/Through-the-earth_mine_communications) first for introduction to cave comms. Below only operational systems are listed:

* [HeyPhone](http://bcra.org.uk/creg/heyphone/introduction.html), through-the-earth at 87 kHz
* [Systeme Nicola](https://pe2bz.philpem.me.uk/Comm/-%20ELF-VLF/-%20ELF-Theory/-%20CaveTheory/CaveRadio1/System-Nicola-Mk2/SYTEME_NICOLA_Mk2.html), through-the-earth at 87 kHz
* [CaveLink](https://www.cavelink.com/cl3x_neu/index.php/en/), through-the-earth at 20-140 kHz
* [Sybet](https://sybet.eu/batnode/), relay-based, proprietary protocol at 868 MHz
* [Vangelis](https://github.com/semper-ad-fundum/vangelis), relay-based on open-source [Meshtastic](https://meshtastic.org) protocol and LoRa hardware
  * [MeshoCan](https://espeleosocorro.es/red-meshocan-de-comunicaciones-inalambricas-en-cueva/), Vangelis extension by ESOCAN (Spain)
  * [Flamingo](https://github.com/rbreesems/flamingo), Vangelis extension by Huntsville Cave Rescue Unit (HCRU), including RS485 serial cable link
* [Persefon](https://jaskinie.jaszczur.org/persefon/), single-wire underground telephone

Reading:

* [ECRA Communications Catalogue](https://caverescue.eu/documents/communication/communications-catalogue/) from European Cave Rescue Group (ECRA), listing deprecated and current cave communication systems
* [CREG Journal](https://bcra.org.uk/pub/cregj/index.html?j=) (British Caving Research Association: The Cave Radio & Electronics Group, requires subscription)
