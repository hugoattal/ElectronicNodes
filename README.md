![Logo Electronic Nodes](https://user-images.githubusercontent.com/4563971/114016838-8f6add00-986b-11eb-9d82-ba43fadf5692.jpg)

# Electronic Nodes
Wiring style for blueprint and material editors in Unreal Engine 4

## How to use

**Electronic Nodes** can be bought from the [Unreal Engine marketplace](https://www.unrealengine.com/marketplace/en-US/slug/electronic-nodes). Once you buy it, it will be automatically downloaded with compatible engine version.

You can find help on how to configure and use the plugin on the wiki: [Getting started](https://github.com/hugoattal/ElectronicNodes/wiki/Getting-started)
You can find answers for frequently questions on the wiki: [FAQ](https://github.com/hugoattal/ElectronicNodes/wiki/FAQ)

## Compatible Engine Version

Engine Version | Plugin Version | Support
-------------- | -------------- | ----
UE 4.20 | EN 1.1 | ❎*
UE 4.21 | EN 2.2 | ❎*
UE 4.22 | EN 2.2 | ❎*
UE 4.23 | EN 2.2 | ❎*
UE 4.24 | EN 2.4 | ❎*
UE 4.25 | EN 3.5 | ❎*
UE 4.26 | EN 3.6 | ❎*
UE 4.27 | EN 3.6 | ❎*
UE 5.00 | EN 3.7 | ❎*
UE 5.01 | EN 3.7 | ✅
UE 5.02 | EN 3.9 | ✅
UE 5.03 | EN 3.11 | ✅

*(\* those versions will not receive updates, as Epic Game does not allow it for versions before the 3 last ones)*

## Changelog

**Version 3.11**
> - Features:
>   - Add bubbles only on exec ([issue](https://github.com/hugoattal/ElectronicNodes/issues/73))
> - Bugfixes:
>   - Fix global config loading ([issue](https://github.com/hugoattal/ElectronicNodes/issues/67))
>   - Fix material graph crash ([issue](https://github.com/hugoattal/ElectronicNodes/issues/76))

**Version 3.10**
> - Features:
>   - Fix 5.3 compatibility ([issue](https://github.com/hugoattal/ElectronicNodes/issues/70))

**Version 3.9**
> - Features:
>   - Fix bubbles on animation blueprints (again) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/8))

**Version 3.8**
> - Features:
>   - Add spline type selection for wires bellow min distance ([issue](https://github.com/hugoattal/ElectronicNodes/issues/66))

**Version 3.7**
> - Bugfixes:
>   - Fix 5.1 compatibility ([issue](https://github.com/hugoattal/ElectronicNodes/issues/64))

**Version 3.6**
> - Bugfixes:
>   - Fix master activation with hotreload ([issue](https://github.com/hugoattal/ElectronicNodes/issues/52))

**Version 3.5**
> - Features:
>   - Add custom graph support ([issue](https://github.com/hugoattal/ElectronicNodes/issues/50))

**Version 3.4**
> - Features:
>   - Add Reference Viewer support ([issue](https://github.com/hugoattal/ElectronicNodes/issues/45))
>   - Add quick restart toast when updating "Use Hot Patch" setting
> - Bugfixes:
>   - Fix hover on short wires ([issue](https://github.com/hugoattal/ElectronicNodes/issues/46))
>   - Fix alignment bug on manhattan wires ([issue](https://github.com/hugoattal/ElectronicNodes/issues/42))
>   - Fix crash on headless mode ([issue](https://github.com/hugoattal/ElectronicNodes/issues/43))

**Version 3.3**
> - Features:
>   - Add a Force Outside option to Ribbon Style ([issue](https://github.com/hugoattal/ElectronicNodes/issues/38))
>   - Add experimental UE5 support ([issue](https://github.com/hugoattal/ElectronicNodes/issues/39))
>   - Add update popup (you're looking at it) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/41))
> - Bugfixes:
>   - Fix Manhattan alignment on Behavior Trees ([issue](https://github.com/hugoattal/ElectronicNodes/issues/35))
>   - Fix Global Settings save ([issue](https://github.com/hugoattal/ElectronicNodes/issues/40))

**Version 3.2**
> - Features:
>   - Add options to draw straight lines for close pins ([issue](https://github.com/hugoattal/ElectronicNodes/issues/34))
> - Bugfixes:
>   - Fix rare crashes with HotPatch ([issue](https://github.com/hugoattal/ElectronicNodes/issues/33))

**Version 3.1**
> - Features:
>   - Improve Behavior Tree display (only for Windows) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/30))
> - Bugfixes:
>   - Fix state machine invisible wires ([issue](https://github.com/hugoattal/ElectronicNodes/issues/28))
>   - Fix control rig disappearing wires ([issue](https://github.com/hugoattal/ElectronicNodes/issues/29))

**Version 3.0**
> - Features:
>   - Add support for Niagara (only for Windows) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/10))
>   - Add support for Control Rig (only for Windows) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/23))
>   - Add support for Gameplay Abilities (only for Windows) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/24))
>   - Add support for Behavior Tree (only for Windows) ([issue](https://github.com/hugoattal/ElectronicNodes/issues/27))
>   - Add global settings ([issue](https://github.com/hugoattal/ElectronicNodes/issues/26))
> - Bugfixes:
>   - Add missing ModuleInterface header ([issue](https://github.com/hugoattal/ElectronicNodes/issues/25))

**Version 2.9**
> - Features:
>   - Add a fallback setting to force activation wherever it can
> - Bugfixes:
>   - Re-add widget graphs

**Version 2.8**
> - Bugfixes:
>   - Re-add the animation graphs

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
