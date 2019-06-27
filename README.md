# OUTDATED REPO #
new repo: https://github.com/JayJay1989/GameSenseSDK
download latest versions on: [Curseforge](https://www.curseforge.com/minecraft/mc-mods/steelseries-gamesense) or [Jenkins (Daily builds)](https://jenkins.lateur.pro/job/GamesenseSDK%20(Minecraft%201.14.x)/)

# SteelSeries GameSense™ SDK #
This repo is only for the Minecraft mod, and heavily edited and released on [curseforge](https://minecraft.curseforge.com/projects/steelseries-gamesense)
Bugs can be reported [here](https://github.com/JayJay1989/gamesense-sdk/issues/new?template=bug_report.md)

## Information ##
GameSense™ is a framework in SteelSeries Engine 3 that allows games to
send status updates to Engine, which can then drive illumination (and
potentially more) capabilities of SteelSeries devices. One simple
example would be displaying the player's health on the row of
functions keys as a bargraph that gets shorter and changes from green
to red as their health decreases, even flashing when it gets
critically low.

This repository contains documentation, tutorials, and examples for
developers wishing to support GameSense™ in their games or
applications.

## Documentation ##

[**`doc/api/sending-game-events.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/api/sending-game-events.md)
How a game can register and send events to GameSense™.

[**`doc/api/writing-handlers-in-json.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/api/writing-handlers-in-json.md)
How to specify event handlers in JSON from a game for an
out-of-the-box, user customizable experience.

[**`doc/api/writing-handlers-in-golisp.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/api/writing-handlers-in-golisp.md)
How to write handlers in the GoLisp language for the ultimate
flexibility and power.

[**`doc/api/standard-zones.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/api/standard-zones.md)
The list of standard zones that can be used in handlers.

[**`doc/api/csgo-customization.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/api/csgo-customization.md)
How to customize the builting CS:GO event handling using GoLisp. Read
the `doc/api/writing-handlers-in-golisp.md` first.

## Tutorials ##

[**`doc/tutorials/audiovisualizer_tutorial.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/tutorials/audiovisualizer_tutorial.md)
Turn your APEX M800 into an audio spectrum analyzer.

[**`doc/tutorials/minecraft-meet-sse.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/tutorials/minecraft-meet-sse.md)
Writing a mod for MineCraft to support GameSense™.

[**`doc/tutorials/minecraft-meet-sse-part2.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/tutorials/minecraft-meet-sse-part2.md)
Writing advanced handlers to work with the events being sent from the mod
presented in part 1.

[**`doc/tutorials/creating-a-minecraft-mod.md`**](https://github.com/SteelSeries/gamesense-sdk/blob/master/doc/tutorials/creating-a-minecraft-mod.md)
Support tutorial on modding MineCraft.

## Sample code ##

[**`examples/audiovisualizer`**](https://github.com/SteelSeries/gamesense-sdk/tree/master/examples/audiovisualizer)
Code to go with `doc/tutorials/audiovisualizer_tutorial.md`.

[**`examples/minecraftforge1.8`**](https://github.com/SteelSeries/gamesense-sdk/tree/master/examples/minecraftforge1.8)
Code for the [GameSense™ Minecraft mod](http://www.technicpack.net/modpack/steelseries-gamesensetm.675193)

