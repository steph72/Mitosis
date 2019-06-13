# Mitosis

![Screenshot](/screenshot.jpg)

"Mitosis" is an attax clone for RISC OS, written in 100% Lua, using Gavin Wraith's excellent RiscLua package.

Perhaps of interest is the fact that Mitosis uses the RISC OS Toolbox (as opposed to event-based WIMP programming) by way of some nice toolbox wrapper classes. 

Also, it doesn't need Lua to run because it contains its own runtime via '!absolua'. The build script for achieving this is, of course, included in !Mitosis.source.build

Please note that Mitosis was written with rlua5.70... it hasn't been tested with newer versions of the language (which unfortunately make some radical and breaking changes, so chance is that it requires some modifications)...
