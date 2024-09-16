# MC-b1.7.3-MumbleLink
A fork of an old version of Mumble Link for b1.7.3.

Based off of [this commit](https://sourceforge.net/p/modmumblelink/code/72/tree/) of the MumbleLink Minecraft mod.

# BIG BIG gotcha
You HAVE to put the ``natives`` in your ``.minecraft/mods`` folder. This old MumbleLink mod blindly assumes you are using a launcher that places its files there, so if it isn't working, COPY THE NATIVES FOLDER INTO ``.minecraft/mods/MumbleLink`` REGARDLESS OF IF YOU HAVE MINECRAFT INSTALLED THERE!!

I'll try to do some work soon to resolve this.

# Required:
- Risugami's mod loader
- Mumble with linking enabled
