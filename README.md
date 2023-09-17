# Procon 1 #
Procon 1 is developed by [Myrcon](https://myrcon.net "Un-Official homepage of Myrcon").

## Mod Map ##
Modified Version for Load and Save Procon Maps List

## About Procon ##
Procon is a free remote control (RCON) tool for gameservers, currently supporting Battlefield: Bad Company 2, Battlefield 3, Medal of Honor: Warfighter, Battlefield 4 and Battlefield Hardline. It is developed by [Myrcon](https://myrcon.net "Un-Official homepage of Myrcon") and also available as open source software on [GitHub](https://github.com/AdKats/Procon-1 "Procon 1 on GitHub").

In addition to providing basic features to control your gameserver, users can extend Procon's functionality using plugins, which can control Procon's behavior and add additional possibilities for gameserver admins. Furthermore, Procon provides a layer system, which allows running plugins and managing admin accounts in a central location instead of distributing it to every admin connected to the gameserver.


## Support ##
Are you experiencing troubles while using Procon, would like to suggest a new feature or discuss settings and plugins with fellow admins? Feel free to pay our [Myrcon Community](https://myrcon.net "Myrcon Community") a visit!

If you are looking for a list of available plugins, head over to the [plugins section](https://myrcon.net/index.php?/forum/9-plugins/ "Procon 1 plugins") of our forums.

### 1.5.3.4 to 1.5.3.5 ###
#### Core ####
- Added ability to disable the new API check for player country info
- Updated GEOIP database file
- Removed usage sending stats
- Added EZRCON ad banner

If you are upgrading then you may need to add these two lines to your existing installation in the file `procon.cfg`. To enable these options just change `False` to `True`.

```
procon.private.options.UseGeoIpFileOnly False
procon.private.options.BlockRssFeedNews False
```

### 1.5.3.3 to 1.5.3.4 ###
#### Core ####
- Fixed GUI error with displaying country name

### 1.5.3.2 to 1.5.3.3 ###
#### Core ####
- Updated geodata code
- Updated the change log link in the procon menu.

### 1.5.2.1 to 1.5.3.2 ###
#### Core ####
- Insane Limits Fix

### 1.5.2.0 to 1.5.2.1 ###
#### Core ####
- Updated Automatic Updater to work with https://api.myrcon.net/procon/version
- Updated usage posting to https://api.myrcon.net/procon/usage
- Updated numerous references to myrcon.com and updated them to myrcon.net

### 1.5.1.1 to 1.5.2.0 ###
#### Core ####
- Added [UTF-8 support](https://github.com/I-MrFixIt-I/Procon-1/commit/0caaeadb06e04afedff9e02a42b2f893eb07beeb)
- Updated GeoIP database (20171006) used for displaying a user's country


### 1.4.2.4 to 1.5.1.1 ###
#### Battlefield 4 ####
- Updates and changes to BF4.def

#### Battlefield Hardline ####
- first compatible release
- Updates and changes to BFHL.def / au.loc / de.loc

#### Core ####
- Added BFHL compatibility

#### UI ####
- Added BFHL compatibility

#### Default plugins ####
- BFHL compatibility

## Credits & contributions ##
Procon and the Procon layer are developed by [Myrcon](https://myrcon.net "Un-Official homepage of Myrcon").

The Battlefield franchise is a product of [DICE](http://dice.se "Digital Illusions Creative Entertainment AB").

Plugins for Procon are developed by third parties, credits and responsibilities lie with the respective plugin author.
