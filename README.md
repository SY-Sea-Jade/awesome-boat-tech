<!--lint disable awesome-git-repo-age-->
# Awesome Boat Tech [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
<!--lint enable awesome-git-repo-age-->

> A curated list of boat tech stuff.

Boat tech includes NMEA 0183, NMEA 2000, Seatalk 1 and NG, OpenCPN, SignalK, Kip, OpenSeamap and the various vendor products
that support open networks such as Shipmodul, Yacht Devices, Actisense, Digital Yacht etc.


## Contents

<!--lint disable double-link-->
- [Blogs](#blogs)
- [Vlogs](#vlogs)
- [Charts](#charts)
- [Open Source Projects](#open-source-projects)
- [Hardware Vendors](#hardware-vendors)
- [Software Vendors](#software-vendors)
- [Consultants](#consultants)
- [Forums](#forums)
- [Education and Reference](#education-and-reference)
- [News](#news)
<!--lint enable double-link-->

### Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Blogs

- [Catalina 320 Log](https://www.yachtslog.com) - Raspberry Pi, NMEA, SignalK, VBA.
- [Cricalix](https://www.cricalix.net) - Ireland, Victoria 34, NMEA, Python, Solar, Shipmodul Miniplex.
- [Ole W. Saastad](https://www.homelinux.no) - Raspberry Pi boat integration.
- [Pyssel](https://pysselilivet.blogspot.com) - Boat projects and news, including Home Assistant, OpenPlotter, ESP32.
- [Seabits](https://seabits.com) - Pacific North West, Kristen 50 and Symbol Pilothouse motor yachts, SignalK, dashboards, Victron.
- [SY Sea Jade Boatstuff](https://sy-sea-jade.github.io/boatstuff/) - Checklists, equipment choices and other tabular data.
- [The Low Cost Sailor](https://www.thelowcostsailor.com) - Boat tech news and articles. English, French, Spanish.
- [Zapped Myself](https://zappedmyself.com/projects/nmea2000/) - NMEA 2000, AIS, ESP32 projects.

## Vlogs
- [Boating with the Baileys](https://www.youtube.com/@BoatingwiththeBaileys) -  Electrical and electronics projects on a 2000s Bavaria 36, including SignalK, KIP, Node-RED, OpenPlotter and SensESP.
- [Out Chasing Stars](https://www.youtube.com/@OutChasingStars) - OpenCPN and general boat electrics, electronics.
- [Pacific Yacht Systems](https://www.youtube.com/@PacificYachtSystems) - Last active in 2023, large back catalogue of instructional videos on marine electrics, electronics and networking.
- [Raspberry for Sailing](https://www.youtube.com/@Sir-Real) - OpenPlotter, SignalK, KIP projects on Raspberry Pi.
- [SV Apres](https://www.youtube.com/playlist?list=PLqHa5JFKHBLwxeCuc6uaa5TzAXVeqTyiD) - OpenPlotter, NMEA 2000 and general boat tech.
- [The Florida Captain](https://www.youtube.com/@TheFloridaCaptain) - Open source boat network and apps.

## Charts

- [Antares Charts](https://www.antarescharts.co.uk) - Volunteer project for charting and pilotage of West Coast Scotland.
- [OpenSeaMap](https://www.openseamap.org/index.php?id=openseamap&L=1) - Open sourced charts, in English, German, Spanish, French, Italian, Russian and Arabic.

## Open Source Projects

- [Bareboat Necessities](https://bareboat-necessities.github.io/my-bareboat/bareboat-os.html) - All in one operating system, incorporating OpenCPN, SignalK, PyPilot etc.
- [BlueBridge](https://github.com/miniwinwm/BlueBridge) - Android app integration with NMEA data via MQTT and Bluetooth.
- [CAN Boat](https://github.com/canboat/canboat) - NMEA 2000 and NMEA 0183 CLI utilities.
- [ESP32 NMEA2000](https://github.com/wellenvogel/esp32-nmea2000) - NMEA 2000 integration with USB, Wifi, 0183 on M5 Atom CAN and compatible with other ESP32.
- [GWeatherRouting](https://gweatherrouting.org) - Navigation and automated routing, Python/GTK4.
- [KPlex](https://www.stripydog.com/kplex/) - NMEA0183 multiplexer for Linux, Unix, macOS and OpenWRT.
- [NMEA2000_ais_wifi_gw](https://github.com/sailingfree/NMEA2000_ais_wifi_gw) -  ESP32 based NMEA 2000 gateway.
- [OpenCPN](https://opencpn.org) - Chart Plotter for macOS, Windows, Linux, Raspi and Android.
- [Open Boat Projects](https://open-boat-projects.org/en/) - DIY hardware and open source projects, English and German.
- [OpenPlotter](https://openplotter.readthedocs.io/) - Combined project of SignalK, OpenCPN, PyPilot etc.
- [PyGPSClient](https://github.com/semuconsulting/PyGPSClient) - Python GPS/GNSS testing, diagnostic and configuration, incl NMEA integration.
- [PyPilot](https://pypilot.org) - Python based auto-pilot.
- [Sens32](https://signalk.org/SensESP/) - ESP32 based sensors for SignalK.
- [SignalK](https://signalk.org) - Node.js pluggable framework for boat data distribution and analysis.
- [Smart Boat Innovations](https://smartboatinnovations.com) - Videos and articles on building a Raspberry Pi and Home Assistant based smart boat.
- [Venus](https://github.com/victronenergy/venus) - Victron Energy's open source OS for their GX products, available for self-hosting on Raspberry Pi.

### NMEA

#### ESP32

- [NMEA2000](https://github.com/ttlappalainen/NMEA2000) - Arduino NMEA 2000 interfacing library used in several commercial products.
- [NMEA2000_esp32](https://github.com/ttlappalainen/NMEA2000_esp32) - ESP32 objects for use with NMEA2000 library.

#### GoLang

- [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA 0183 sentence parser.
- [nmea0183](https://github.com/martinmarsh/nmea0183) - NMEA 0183 sentence parser, with Actisense integration examples.

#### Python

- [pynmea2](https://github.com/Knio/pynmea2) - NMEA 0183 sentence parser.
- [nmeasim](https://gitlab.com/nmeasim/nmeasim) - NMEA/GNSS receiver simulator.

#### Rust

- [nmea crate](https://crates.io/crates/nmea) - NMEA 0183 sentence parser.

#### Swift

- [NMEAParser](https://github.com/sindreoyen/NMEAParser) - iOS and macOS NMEA 0183 parser and validator.

## Hardware Vendors

### Full Integration
- [B&G](https://www.bandg.com) - Sensors, radars, plotters, displays for racing and cruising.
- [Garmin](https://www.garmin.com/) - Sensors, plotters, radars, sonar, displays, auto-pilots, charts, cameras and integration.
- [Humminbird](https://humminbird.johnsonoutdoors.com/us) - Plotter, sonar, charts, apps, One-Boat network.
- [Lowrance](https://www.lowrance.com) - Plotters, transducers, charts, trolling motors.
- [Raymarine](https://www.raymarine.com) - Sensors, radars, plotters, displays, VHF, AIS and Seatalk NG.
- [Simrad](https://www.simrad-yachting.com) - Plotters, auto-pilots, sonar, radar, AIS, VHF, transducers, charts, apps.

### NMEA Interfacing
See [NMEA Wifi Options](https://sy-sea-jade.github.io/boatstuff/nmea_wifi) for comparison of available products.

- [Actisense](https://actisense.com) - NMEA bridges and gateways.
- [Chetco](http://www.chetcodigital.com) - NMEA bridges, marine PC, SeaGauge and SeaSmart.NET for Bluetooth, 4G and Wifi.
- [Comar](https://comarsystems.com) - AIS focused with NMEA bridge, multiplexer and sensors.
- [Copperhill](https://copperhilltech.com) - Raspberry PI and ESP32 NMEA 2000 boards, simulators, HATs.
- [Digital Yacht](https://digitalyacht.co.uk) - NMEA multiplexers, sensors, gateways plus AIS and 4G/5G.
- [HAT Labs](https://hatlabs.fi) - Open Source NMEA 2000, ESP32 and RasPi hardware.
- [Luissa 351](https://www.ebay.co.uk/usr/luissa.351) - NMEA gateways, multiplexers and Wifi integration. Portugal selling internationally through eBay.
- [Onwa](https://www.onwamarine.com/NMEA_Devices.html) - NMEA converters and multiplexers, and general marine electronics.
- [OpenMarine](https://openmarine.net) - NMEA [MacArthur HAT](https://macarthur-hat-documentation.readthedocs.io)for Raspberry PI with OpenPlotter.
- [Quark](https://www.quark-elec.com) - NMEA devices, sensors, internet gateways, gauges and remote monitoring.
- [Rosuku](https://www.rusoku.com) - TouCAN Marine NMEA 2000 USB adaptor.
- [Shipmodul](https://shipmodul.com) - NMEA/Seatalk multiplexers and LAN gateways.
- [SK Pang Electronics](https://www.skpang.co.uk) - Raspberry Pi boards and HATs for CAN-Bus integration, NMEA 2000 simulators, GPS modules, LCD displays.
- [Tinley](https://www.tinleyelectronics.com/) - NMEA interfaces, sensors, multiplexers, converters.
- [Yacht Devices](https://www.yachtd.com) - NMEA bridges, gateways and sensors.
- [Yakbitz](https://yakbitz.com) - Seatalk, NMEA, AIS and Autopilot interfaces.

### Marine PCs and Components

- [Beetronics](https://www.beetronics.co.uk/c-marine?_gl=1*1f0b82j*_up*MQ..*_gs*MQ..&gbraid=0AAAAADm9gnpX9qEe0DYsgTxrXqGaGG_4d) - Marine monitors and touchscreens.
- [Bluestone](https://www.bluestonetechnology.co.uk/) - Marine LCD displays.
- [BVM](https://www.bvm.co.uk/industries-2/transport-solutions/marine-solutions/) - Marine displays and PCs.
- [Cybernet](https://www.cybernetman.com/) - Marine rackmount and mini PCs.
- [Impulse](https://www.impulse-embedded.co.uk/solutions/industrial-computing-solutions/marine-and-subsea) - Marine PCs and displays.

### Instruments

- [LCJ Capteurs](https://lcjcapteurs.com/en/categorie-girouette-anemometres-capteur-vent/marine-en/) - Wind and weather instruments, StatMETEO wind data recording software.
- [NASA Marine](https://www.nasamarine.com) - Instruments, monitors, AIS, displays.
- [Safiery](https://safiery.com/marine-new/) - Digital switching, monitoring, Victron and NMEA integration.
- [Veratron](https://veratron.com/pages/marine) - NMEA instruments, gateways and sensors, displays.

### Boat Integration and Remote Monitoring

- [BoatMonitor32](https://www.boatmonitor32.co.uk) - Mobile app and boat hardware hub with Victron integration.
- [Hello Sailor](https://hello-sailor.co.uk) - LTE/SMS based remote boat monitoring, subscription-free.
- [iNav4u](https://www.inav4u.com) - **Zora** integrated monitoring, navigation, dashboards.
- [Maretron](https://www.maretron.com) - Integrated monitoring and visualization, NMEA bridges and sensors.
- [Navigation Laptops](https://navigationlaptops.com) - Laptops setup for navigation with instrument packages.
- [Orca](https://getorca.com/orca-core/) - Data hub for NMEA, auto-pilot, radar with chart plotter and remote monitoring.
- [PredictWind DataHub](https://www.predictwind.com/datahub) - Data logging, remote monitoring, internet data, NMEA and auto-pilot interface.
- [Renogy](https://www.renogy.com/) - Power management and monitoring.
- [Siren Marine](https://sirenmarine.com/) - Remote boat monitoring.
- [Vesscomm](https://vesscomm.com) - Mobile data (2G/4G) based monitoring hubs and mobile apps.
- [Victron](https://www.victronenergy.com) - Power devices with associated monitoring, integration, power sensors, displays.
- [Vircru](https://www.vircru.com) - Remote boat monitoring with mobile app.

### Accessories

- [Aquatic AV](https://www.aquaticav.com/pages/environments-marine) - Speakers, amplifiers, head units.
- [Cruising Solutions](https://www.cruisingsolutions.com/collections/communication) - 'Marriage Savers' intercom headsets.
- [Kicker Audio](https://kickeruk.com/pages/boat-audio) - Speakers, amplifiers, cables.
- [Yacht Controller](https://www.yachtcontroller.com) - Handheld engine & steering remote control for docking.


## Software Vendors

- [DeepBlue](https://deepblue.app/) - Yacht management app.
- [LuckGRIB](https://luckgrib.com) - Weather data download, view and routing.
- [Meltemus](https://www.meltemus.com/index.php/en/) - Navigation, weather and charts for Android, iOS, Windows, macOS and Linux. **qtVLM** weather and chart viewer free on some platforms.
- [Maintenance ROS](https://maintenanceros.com) - Boat maintenance management.
- [Navstation](https://navstation.net) - **MacENCx64Integrate** plotting, navigation, charts and NMEA integration for macOS.
- [NMEA 2000 Solutions](https://www.nmea2000solutions.com) - NMEA BridgeBuilder and NMEA Gateway packages, consultancy.
- [Sail Logger](https://saillogger.com) - Logbook for mobiles, with NMEA integration.
- [SailTrack](https://www.angelnav.co.uk) - **AngelNav** plotter app for mobile and PC with charts and traditional charting techniques and NMEA integration.
- [SavvyNavvy](https://www.savvy-navvy.com) - Plotter app for mobile with integrated weather, AIS, charting and NMEA integration.
- [Vessel Vault](https://vesselvault.app) - Boat maintenance management.
- [WilhemSK](https://www.wilhelmsk.com) - SignalK dashboard app for iPhone, iPad, macOS, Apple Watch and Apple TV.

## Consultants

- [Nautibus](https://nautibus.de) - NMEA 2000 design, testing, installation. German and English.
- [Seatech Systems](https://seatech.systems) - Marine electronics consultancy, with free advice articles on marine internet.

## Forums
*All active as of 2026*

- [boatdesign.net](https://www.boatdesign.net/forums/onboard-electronics-controls/) - Electronics and Controls forum.
- [NMEA 2000 Support Group](https://www.facebook.com/groups/380510566227511/) - Public Facebook group.
- [NMEA 2000 Technical Forum](https://www.facebook.com/groups/699562237256639/) - Private Facebook group.
- [OpenMarine](https://forum.openmarine.net) - Marine electronics and networking, focus on Macarthur HAT, PyPilot, OpenPlotter and Node RED.
- [Panbo](https://panbo.com/marineelectronicsforum/) -  Marine electronics and networking.
- [Raspberry Pi for Boats](https://www.facebook.com/groups/1666364153609573/) - Private Facebook group.
- [The Hull Truth](https://www.thehulltruth.com/marine-electronics-forum-19/) - Marine electronics forum.

## Education and Reference

- [Actisense Hub](https://actisense.com/actisense-hub/) - Free tutorials, online books and reference from Actisense.
- [Attainable Adventure Cruising](https://www.morganscloud.com) - Articles on [electronics and software](https://www.morganscloud.com/category/electronics-software/) and [Navigation and Marine Electronics](https://www.morganscloud.com/category/navigation/book-navigation-electronics/) on-line book.
- [Boat HowTo](https://boathowto.com) - Online courses and articles for marine electrics, NMEA networking and engines.
- [GPS NMEA 0183 Messaging Protocol 101](https://docs.arduino.cc/learn/communication/gps-nmea-data-101/) - Arduino tutorial with general applicability.
- [Meco Training](https://www.mecotraining.com) - On-line marine electrics and electronics courses.
- [Mr Lopez](https://www.mrlopezclasses.com) - Books and online classes on marine electrics, Spanish and English.
- [NMEA Certification and Training](https://www.nmea.org/training.html) - Official NMEA organization courses.
- [NMEA Conference and Expo](https://expo.nmea.org) - Annual vendor event in USA.
- [Ocean Science Technology](https://www.oceansciencetechnology.com/suppliers/data-communication-systems/) - NMEA 0183 and 2000 tutorials.
- [Seably](https://www.seably.com/explore/topics/electronics-2) - Electronics courses, including Actisense accreditation.
- [Seatalk Technical Reference](http://www.thomasknauf.de/seatalk.htm) - Unofficial documentation of Seatalk 1 protocol.

## News

- [Actisense Media](https://actisense.com/media/) - Vendor blog, with self-help and industry news.
- [Panbo](https://panbo.com) - Marine tech news.

(DISCLAIMER: the term 'awesome' is used here in its American sense, and because 'awesome list' is a thing, and not in its British sense of actually involving awe)
