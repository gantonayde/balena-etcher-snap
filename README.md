<div align="center">
<h1 align="center">
  <img src="https://raw.githubusercontent.com/balena-io/etcher/master/assets/icon.png" alt="balenaEtcher">
  <br />
  balenaEtcher
</h1>
</div>

<b>This is the snap for [balenaEtcher](https://github.com/balena-io/etcher)</b>. <i>"Flash OS images to SD cards & USB drives, safely and easily."</i> 
Etcher is a powerful OS image flasher built with web technologies 
to ensure flashing an SDCard or USB drive is a pleasant and safe experience.
It protects you from accidentally writing to your hard-drives, ensures every byte of
data was written correctly and much more. It can also flash directly Raspberry Pi
devices that support the usbboot protocol. 
The snap works on Ubuntu, Fedora, Debian, and other major Linux
distributions.

## Install

You can download the snap from [here](https://github.com/gantonayde/balena-etcher-electron/releases/download/v1.5.89-beta-snap/balena-etcher-electron_1.5.89_amd64.snap).
To install, please run:

`sudo snap install balena-etcher-electron_1.5.89_amd64.snap --dangerous --classic`

Etcher needs access to `pkexec` or `kdesudo` in order to write to the media, which means that the snap needs to be sideloaded with `--dangerous` and `--classic` tags.
