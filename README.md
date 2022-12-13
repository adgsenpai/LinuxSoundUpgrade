<p float="left">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/800px-Tux.svg.png" height="100px">


# Linux SoundUpgrade

a guide to enable SoundUpgrade on linux.

## Installation 

### i. Downloading Effect 
First lets get our `SoundUpgrade.irs` file.

you can download it by cloning the repo
`https://github.com/adgsenpai/LinuxSoundUpgrade`

or

you can [download the raw file directly](https://raw.githubusercontent.com/adgsenpai/LinuxSoundUpgrade/main/SoundUpgrade.irs)

### ii. Downloading `Pulse Effects` now called `Easy Effects`.

Installing Pulse Effects

Methods

a) Easy Way

go to `https://pkgs.org/download/pulseeffects`

Select your distro and then `download` and `install` the `PulseEffect` package for your distro.

b) Complex Way

go to `https://github.com/wwmm/easyeffects` and compile from source.

this wiki will help you with the complex way

`https://github.com/wwmm/easyeffects/wiki/Installation-from-Source`


### iii. Configuring Pulse Effects with the plugin file

- Launch the `PulseEffects App`

First thing you are going to do is allow the service to run when system boots you can do this in the `settings` by clicking on the hamburger icon as illustrated by this photo.

![Settings](./Screenshots/Settings.png)

Enable the SoundUpgrade Effect

on the left menu you see `Applications` or `Limiter` thats the menu im talking about. Scroll down until you see the `Convolver Effect` once there

You will see this screen

![Effect](./Screenshots/Effect.png)

now click on the `wave icon` and `import your effect` to the directory of `LinuxSoundUpgrade.irs` and `apply it` then `disable` and `enable` `Convolver`
 
This image will help you out

![Help](./Screenshots/ImportEffect.png)

Enjoy SoundUpgrade for Linux :-)
