![Logo Electronic Nodes](https://user-images.githubusercontent.com/4563971/66260688-39befb80-e7c2-11e9-85c3-dcdaef506e84.png)

# Electronic Nodes
Wiring style for blueprint and material editors in Unreal Engine 4

## How to use

**Electronic Nodes** can be bought from the [Unreal Engine marketplace](https://www.unrealengine.com/marketplace/en-US/slug/electronic-nodes). Once you buy it, it will be automatically downloaded with compatible engine version.

You can find help on how to configure and use the plugin on the wiki: [Getting started](https://github.com/TheHerobrine/ElectronicNodes/wiki/Getting-started)
You can find answers for frequently questions on the wiki: [FAQ](https://github.com/TheHerobrine/ElectronicNodes/wiki/FAQ)

## Compatible Engine Version

Engine Version | Plugin Version | Support
-------------- | -------------- | ----
UE 4.20 | EN 1.1 | ❎*
UE 4.21 | EN 2.2 | ❎*
UE 4.22 | EN 2.2 | ❎*
UE 4.23 | EN 2.2 | ❎*
UE 4.24 | EN 2.4 | ✅
UE 4.25 | EN 2.6 | ✅
UE 4.26 | EN 2.7 | ✅

*(\* those versions will not receive updates, as Epic Game does not allow it for versions before the 3 last ones)*

You can make it work on any version (even before 4.20) by compiling it yourself.

## Changelog

**Version 2.7**
> - Features:
>   - Add compatibility with Unreal Engine 4.26
>   - Remove useless headers and files

**Version 2.6**
> - Features:
>   - Add compatibility with [VoxelPlugin](https://voxelplugin.com/)
>   - Add shortcut to master activate/deactivate

**Version 2.5**
> - Bugfixes:
>   - Solve a selection bug with Default wire style

**Version 2.4**
> - Bugfixes:
>   - Remove spamming logs "LogTemp: schematype Default__EdGraphSchema_K2"

**Version 2.3**
> - Bugfixes:
>   - Rename vars to avoid warning during compilation

**Version 2.2**
> - Features:
>   - Add activation checkbox for blueprints, materials and animation bps
>   - Add default wire to work with other features
>   - Add bubble display rules (always one, display on selection, move on selection)
>   - Add bubble selection rules (near nodes, far nodes)
> - Bugfixes:
>   - Fix bubbles on animation blueprints
>   - Add some more security to avoid crashes

**Version 2.1**
> - Features:
>   - Add documentation link
> - Bugfixes:
>   - Fix display with low angle
>   - *(experimental)* Fix ribbon not being offset

**Version 2.0**
> - Features:
>   - Completly rewritten algorithm to better handle edge cases
>   - Add wire alignment to float left or right
>   - Add wire alignment priority toward nodes or pins
>   - Add custom alignement for exec wires
>   - Add option to disable pin offset
>   - Improve bubbles draw on angles
>   - Add zoom threshold to display bubbles
>   - Make execution bubbles bigger than custom bubbles
> - Bugfixes:
>   - Fix edge cases where small wires does weird things
>   - *(experimental)* Make ribbons not split when coming from the same node

**Version 1.1**
> - Features:
>   - Change the horizontal offset of wires
>   - Bubbles customization (movement style, size, speed, space)
>   - Specify wirestyle for exec wire
>   - *(experimental)* Ribbon style (offset overlapping wires)
> - Bugfixes:
>   - Fix offset on junctions when zoom out

**Version 1.0**
> - Features:
>   - Simple wiring style (90° corners)
>   - Complex wiring style (45° corners)
>   - Draw moving bubbles on wires
>   - Change the radius or wires
