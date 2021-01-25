# LinuxAudio

A project to build an audio amplifier. It runs Linux, and supports muliple auio input sources: Bluetooth, SPDIF, USB UAC and also native player. A USB DAC is used for audio output and amplified by a separed LM3668 based amp board.

## Configure Linux as Bluetooth audio sink.

I have tried to use Bluez + pulseaudio + pulseaudio-modules-bt. It works but the sound always has pops and great latancy. Finally, I settled on bluez + [bluealsa](https://github.com/Arkq/bluez-alsa). 
