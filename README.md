<p align="center">
<img src="./distro/image.jpg">
</p>
<p align="center">
<img src="https://img.shields.io/badge/MADE%20IN-BANGLADESH-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge">
<img src="https://img.shields.io/badge/Version-2.0-blue?style=for-the-badge">
</p>
<p align="center">
<img src="https://img.shields.io/badge/Written%20In-Bash-darkgreen?style=flat-square">
<img src="https://img.shields.io/badge/Open%20Source-Yes-darkviolet?style=flat-square">
<img src="https://img.shields.io/github/stars/modded-ubuntu/modded-ubuntu?style=flat-square">
<img src="https://img.shields.io/github/issues/modded-ubuntu/modded-ubuntu?color=red&style=flat-square">
<img src="https://img.shields.io/github/forks/modded-ubuntu/modded-ubuntu?color=teal&style=flat-square">
</p>
<p align="center"><b>Run Ubuntu GUI on your termux with much features.</b></p>

### Features

- Fixed Audio Output
- Lightweight {Requires at least 4GB Storage}
- 2 Browsers (Chromium & Mozilla Firefox)
- Supports Bangla Fonts
- VLC Media Player and MPV media player
- Visual Studio Code (buggy on arm )
- Sublime Text Editor (only for arm64/aarch64)
- Easy for Beginners
- Comes with some cool themes.

### Installation
- Firstly install [Termux](https://termux.com) apk from [HERE](https://f-droid.org/repo/com.termux_118.apk)
- Secondly Clone the Repository & Run the setup File
```bash
yes | pkg up
pkg install git wget -y
git clone --depth=1 https://github.com/Hooleymass/modded-ubuntu.git
cd modded-ubuntu
bash setup.sh

```

- Then Restart your Termux & Type the following commands
```bash
ubuntu
```
```
bash user.sh

```

- Type your ubuntu root username. Must be lowercase & no space included.

- Then Again Restart your Termux & Type the following commands

```bash
ubuntu

```
```bash
sudo bash gui.sh
```

- **You have to note your VNC password !!**

- Ubuntu image is now successfully installed .

  - Type `vncstart` to run Vncserver
  - Type `vncstop` to stop Vncserver

- Install VNC VIEWER Apk on your Device. [Google Play Store](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android&hl=en)
- Install Termux-x11 Apk on your Device. [Termux-x11](https://github.com/termux/termux-x11/actions/runs/5481542732)

- Open VNC VIEWER & Click on + Button & Enter the Address `localhost:1` & Name anything you like
- Set the Picture Quality to High for better Quality
- Click on Connect & Input the Password 
- Enjoy :D

### NOTE :

- **Type `ubuntu` to run Ubuntu CLI.**
- **Type `vncstart` to run Vncserver**
- **Type `vncstop` to stop Vncserver**

- **Type `bash remove.sh` to remove Ubuntu Modded Os**

### Video Tutorial : 

[![Watch the Tutorial](./distro/image1.jpg)](https://youtu.be/rf2P80gA36U)

#
### Click to see the [Changelog](./CHANGELOG.md)
Licensed under [Apache License](./LICENSE)
#

### Credits : 

```
This Tool Uses the ubuntu image provided by the termux package `proot-distro` 

Full Credit of the Ubuntu image goes to them .

Termux Proot Distro - https://github.com/termux/proot-distro
```

### Maintainers

- [**Mustakim Ahmed**](https://github.com/BDhackers009)
- [**Tahmid Rayat**](https://github.com/htr-tech)
- [**0xBaryonyx**](https://github.com/Mahfuz-THBD)


### If you like our work then dont forget to give a Star :)

