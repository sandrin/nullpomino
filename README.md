patched slick.jar in /lib so that it doesn't crash on startup when more than 10 controllers are detected

---------------------------------------------------------------------------------------------------------

# Nullpomino

**NullpoMino** is an open-source action puzzle game that works on the Java platform. It has a wide variety of single-player modes and netplay to allow players to compete over the Internet or LAN.

### Current stable version
The current stable version is 7.5.0, which has the following new features: 
* Screen size option for Slick and Swing (320x240, 640x480, 800x600, 1024x768, etc) 
* "Dig Challenge" mode where garbage blocks will constantly rise 
* More single player modes in NetPlay 
* Much more stable NetServer 
* New icon 
* Installer for Windows (uses Inno Setup) 
* App Bundle for Mac OS X

### Download
* Windows (installer): [NullpoMino7.5.0.exe](https://github.com/nullpomino/nullpomino/releases/download/v7.5.0/NullpoMino7.5.0.exe)
* Mac OS X: [NullpoMino7.5.0.dmg](https://github.com/nullpomino/nullpomino/releases/download/v7.5.0/NullpoMino7.5.0.dmg)
* Linux: [NullpoMino7.5.0_linux.tar.gz](https://github.com/nullpomino/nullpomino/releases/download/v7.5.0/NullpoMino7.5.0_linux.tar.gz)
* Any OS (zip): [NullpoMino7.5.0.zip](https://github.com/nullpomino/nullpomino/releases/download/v7.5.0/NullpoMino7.5.0.zip)

### Building

#### Linux

Use maven to compile the project:

```bash
cd nullpomino-parent/
mvn package
cd ../nullpomino-run/target/install/
chmod +x ./play_swing
./play_swing
```
