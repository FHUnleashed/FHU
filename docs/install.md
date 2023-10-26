# Installation

The public release of FeralHeart Unleashed is obtained exclusively through the official [website downloads page](https://feralheart-unleashed.com/download.php). FeralHeart Unleashed currently only has a native Windows version, however you are able to play on Mac and Linux with the linked tutorials in their respective sections. <!-- There are plans for a native Mac version of the game in the future. -->

# Windows Installation

## Itch.io App Installation

The Itch.io App is the recommended method for installing FeralHeart Unleashed.

- [Register](https://itch.io/register) on Itch.io if you haven't already.
- Download the [Itch.io App](https://itch.io/app)
- Run itch-setup.exe

> :warning: Do not install FeralHeart Unleashed to Program Files or other protected Windows folders. FeralHeart Unleashed does not have the permission to create the necessary configuration files there. The default itch location in AppData is fine, or select/make a folder like C:\Games

- Login with your Itch account.
- Select the Search Bar on the left and search: `FeralHeart Unleashed`
- Click the `Install` button on the bottom right.
- Change your install location if you need to, remember no Program Files!
- Click Install once more.
- itch will now install the game. If you never had VCRedist or DirectX installed before, you may be prompted to accept their installation. Please install them.
- Click `Launch` where the install button used to be.
- Select Direct3D9 from the Ogre dropdown menu.
- Press OK and from there you can begin your experience!

Should you have any issues with your install or wish to remove the game, simply click the Gear icon next to Launch, select Manage, and choose the needed option.

## Archive Installation

There is also a Zip Archive option, should you wish to avoid the Itch App. Please note this option does not have any form of installer, launcher or auto-updater.

- From the [website downloads page](https://feralheart-unleashed.com/download.php), select the Zip Archive button. This will lead to the Itch FHU Homepage. 
- On this page, scroll down and select the `Download` button.
- Extract the game to an empty folder.

> :warning: Do not extract FeralHeart Unleashed to Program Files or other protected Windows folders. FeralHeart Unleashed does not have the permission to create the necessary configuration files there.

- Run the two files in the `redistributables` folder.
- Launch the game using `fhugame.exe`.
- Select Direct3D9 from the Ogre dropdown menu.
- Press OK and from there you can begin your experience!

# Playing on Mac

''This section was [originally written by Yugi, and was modified for use in this wiki.](https://feralheart-unleashed.com/static/assets/FHUMacLinuxTutorial.pdf )''

FeralHeart Unleashes does not have native macOS support, however it is possible to play the Windows version of FeralHeart on macOS! There are currently two different methods you can use to play FeralHeart Unleashed: Boot Camp and Crossover.
Currently, we have not found a way to get FeralHeart Unleashed to work with Wine.

## Using Boot Camp

### What is Boot Camp?

Boot Camp is a utility that comes with your Mac that lets you switch between macOS and Windows. With Boot Camp, you can install Microsoft Windows 10 on your Mac, then switch between macOS and Windows when restarting your Mac.
Boot Camp requires a Mac with an Intel processor. You can see what type of processor you have by clicking on the Apple symbol located on the top left of your screen. From there, click on the option that says About This Mac.
Using Boot Camp involves messing with your partition table, so please keep in mind that if you do not follow the instructions provided on Apple’s website, it may result in loss of data. Please refer to [Apple’s official website](https://support.apple.com/en-us/HT201468) for more information on how to set up Boot Camp on your Mac.

## Using CrossOver

### What is CrossOver?

CrossOver is a software developed by CodeWeavers that serves as a Windows compatibility layer. With CrossOver you can run Windows programs on your Mac without creating a separate partition for Windows. Unlike Boot Camp which is free, Crossover costs $60 USD. However, they do have a free trial on their website.

### CrossOver Intallation

- First, you need to install [CrossOver](https://www.codeweavers.com/crossover/download).
- Once the file is downloaded, [go to your downloads tab in your browser and right click on CrossOver, and then show in finder.](https://i.imgur.com/U9V4wot.png)
- In Finder, you will see the CrossOver application. Open it, and if you are prompted [with this screen, just click open.](https://i.imgur.com/Whjwk9g.png)

  >  :warning: If you are having trouble here, be sure to check your security & privacy settings to make sure that your Mac can open applications from both the App Store and other identified developers.
- After clicking open, you will be prompted with an option to [move CrossOver into the Applications folder.](https://i.imgur.com/CsdWT1W.png) Go ahead and let CrossOver move itself to the Applications folder.
- Upon opening CrossOver, click the button that says [Install a Windows Application.](https://i.imgur.com/pt7Iu2L.png)
- After you clcik Install a Windows Application, you will be prompted with a search menu. Search [DirectX for Modern Games](https://i.imgur.com/EX7pOCE.png) and then click continue.
- Next, to create a new Bottle, click [New Windows 8 64-bit Bottle](https://i.imgur.com/qH8cRCN.png ).

  >  :warning: On the next page, just click install and let CrossOver create the new prefix.
- When prompted with the [DirectX Installer,](https://i.imgur.com/npHZavJ.png ) go ahead and click yes and agree to their terms to finish setting up your new Bottle.
- After you finished making your new Bottle, [right click on it and then click on Install Software into "DirectX for Modern Games".](https://i.imgur.com/nFurF5U.png)

  >  :warning: If this option is unavailable to you, click Run Command and next to the word Command you should see a Browse button. Locate the Microsoft Visual C++ 2015 redistributable that comes with FeralHeart Unleashed in the redistributables folder and run that as a command. Go through the installer and once it is done, move on to step 11.
- You will be prompted to search for another application to install. [Look up Microsoft Visual C++ 2015 and click on the 64-bit option and install it.](https://i.imgur.com/CYwNSkz.png)
- To run FeralHeart Unleashed, click on the Run... command, and the next to the word command you should see a browse button. [Click that, and then locate your FeralHeart Unleashed folder, and click on FeralHeart Unleashed.exe to choose that as your command and run it.](https://i.imgur.com/Ma6Ix8n.png)
- From the launcher, you are going to want to [click on the S.](https://i.imgur.com/H3VhAEL.png) This will bring up your settings menu. Save your settings and click play.
- Choose Direct3D9 and your rendering system on the OGRE menu, and after that FeralHeart Unleashed should launch, and you will be able to play!

  >  :warning: If you get the 544 error just open it again, or try to run fhugame.exe as a command.

# Playing on Linux

''This section was [originally written by Yugi, and was modified for use in this wiki.](https://feralheart-unleashed.com/static/assets/FHUMacLinuxTutorial.pdf )''

FeralHeart Unleashed does not have a native linux version either. However, it is possible to play the Windows version of FeralHeart Unleashed on most Linux distros using Lutris.

## What is Lutris?

Lutris is an open gaming platform for Linux. Lutris helps you install and play video games from all eras and most gaming systems. By leveraging and combining existing emulators, engine re-implementations and compatibility layers, it gives you a central interface to launch all your games.
To install Lutris, open your terminal and type in the commands corresponding to whichever distro you are using. The more popular distros are listed here, however if you are using something else, please refer to the [Lutris website](https://lutris.net/downloads) for more information on how to install it to your distro of choice.

### ; Ubuntu, Linux Mint, Pop! OS, Elementary OS

```bash
sudo add-apt-repository ppa:lutris-team/lutris
sudo apt update
sudo apt install lutris
```

### ; Debian

```bash
echo "deb http://download.opensuse.org/repositories/home:/strycore/Debian_11/ ./" | sudo tee /etc/apt/sources.list.d/lutris.list

wget -q https://download.opensuse.org/repositories/home:/strycore/Debian_11/ Release.key -O- | sudo apt-key add -
sudo apt update
sudo apt install lutris
```

### ; Fedora

```bash
sudo dnf install lutris
```

### ; openSUSE

```bash
sudo zypper in lutris
```

### ; Arch Linux, Manjaro

```bash
sudo pacman -S lutris
```

## Lutris Installation

- Once you have Lutris installed, you are going to want to [hover your mouse over the section on the left that says Wine.](https://i.imgur.com/9GRa61Z.png) There should be a little clock there - click it.
- When you click on the clock, a long list of all the different versions of Wine available to use with Lutris will appear. [Scroll down to Lutris 5.0 and click the check box to install it.](https://i.imgur.com/iDvpZYZ.png)
- After Lutris has finished installing version 5.0, click on the plus to add a game and [select Wine to be your runner for FeralHeart Unleashed.](https://i.imgur.com/VT7aJCD.png)
- Next, unzip FeralHeart Unleashed and place it in /home/'''insertyourusernamehere'''/.wine/drive_c/
- In Lutris, click game options, and [for the Executable, use the directory to the fhugame executable.](https://i.imgur.com/bYruGGk.png) For the WIne prefix, put in the directory to your wine prefix, and make sure you select 64-bit.
- Your wine prefix is usually /home/'''insertyourusernamehere'''/.wine, if you can't find it, make sure your file manager is showing hidden files.
- Next, for Runner Options, choose [Lutris 5.0 as your Wine version and make sure you have DXVK enabled for FeralHeart Unleashed to work properly before you save it as a new game.](https://i.imgur.com/deymxzp.png )
- Once you are done setting up Lutris, click on FeralHeart Unleashed and click Play.
- When you first run FearlHeart Unleashed, Lutris will [prompt you to install Mono and Gecko.](https://i.imgur.com/fRp9rWU.png) Go ahead and let those install.
- Once Mono and Gecko are finished installing to your Wine prefix, you will be prompted to choose a rendering subsystem from the OGRE menu. Choose Direct3D9 and FeralHeart Unleashed should launch, and you will be able to play!

> :warning: If you get the 544 error, just open it again.

> :warning: If your FeralHeart Unleashed lags when you move your mouse around, try opening it from the Wine prefix itself by locating the FeralHeart Unleashed folder, right clicking on fhugame.exe, and choose open with Wine Windows Program Loader. Even if you run FeralHeart Unleashed with just Wine, you would still need to set it up with Lutris to configure the Wine prefix properly.

## PDF Visual Guide

```pdf
https://feralheart-unleashed.com/static/assets/FHUMacLinuxTutorial.pdf
```
