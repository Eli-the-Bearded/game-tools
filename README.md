game tools
==========

These are tools I've written to help play games. I'm not including stuff
I wrote to bot-play web games nor am I including stuff to help write
games.

Currently there are two tools I have that meet those requirements.

asciimapper
-----------

This is a tool I wrote in 2005 to help me play a MUD. I found myself
drawing a lot of crude maps, and decided to make a text graphic way to
do those, and for good measure have a way to convert those ASCII art
maps into nice clean maps. IFM is an _interactive fiction map_ drawing
tool that takes a text description of an area and makes postscript
(and similar vector output) versions. This program will convert my
ASCII map style into IFM input.

IFM hasn't been updated in a long time, but probably still works.
There's a tar-gzip version here:

http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html

And a source repo here:

https://bitbucket.org/zondo/ifm/src/default/

stat-timer
----------

This is a new tool written for comparing efficiency of strategies. Let's
say you are playing a game and trying to grind for the next level. Is it
better to use the Sword of Easy Kills Which Lowers Defense or the Dagger
of Several Stabs Needed with the Shield of Good Defense? Is it better to
fight big baddies that give a lot of XP infrequently or minor minions
that give a steady but small stream?

Enter `stat-timer`. You start it with your initial stats of interest,
it is very flexible about them, and periodically give updates. At the
end of the session it gives statistics scaled per second and per hour
so that you can easily compare the strategies. The periodic updates allow
you to quickly discard bad strategies while getting some data, and to
selectively update infrequent events as they happen.
