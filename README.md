# Wrestling Empire GIMP Templates

This is a collection of templates I've created for my use, as well as yours, in creating modded content for [Wrestling Empire](https://store.steampowered.com/app/1620340/Wrestling_Empire/). I've created these based on the existing assets ripped from the game, which can be found in the [Modding Discord](#modding-discord).

New templates will be added as I create content myself, but you're welcome to add your own with a pull request or by tagging me in the [Modding Discord](#modding-discord), so you can send them to me to be added.

**NOTE:** These templates are intended for [GIMP 2.10](https://www.gimp.org/downloads/) or newer.

## How to use custom content

Custom content created using these templates can be loaded using [WECCL](https://github.com/IngoHHacks/WECCL).

More details on installing BepInEx, WECCL, and where to place your custom content can be found on the [WECCL GitHub page](https://github.com/IngoHHacks/WECCL#readme), and you can get help in the [Modding Discord](#modding-discord).

### Donate to Ingo

The real credit goes to [Ingo](https://github.com/IngoHHacks) for kickstarting the Wrestling Empire modding community with the creation of WECCL and the Discord. You can donate to them on [Ko-Fi](https://ko-fi.com/IngoH).

## File structure

This repo is structured to mirror the actual file tree of the folders used by the [WECCL mod loader](#how-to-use-custom-content). This can also be used as a reference as to which content can be appended to the game's existing content (without replacing existing textures), and which content must replace existing textures.

Templates for content that can be added to the game are found under `Assets`. Templates for content that can only replace existing content is found under `Overrides`. This repo will be restructured if these limitations change.

Actual content should be placed in the the BepInEx plugins folder, in the corresponding location to the one they're found in this repo. For example, a file created using `Overrides\sprites\feds\FedLogo.xcf` would be placed in `Wrestling Empire\BepInEx\plugins\Overrides\sprites\feds`, with the same name as the specific logo you want to replace.

## Modding Discord

Join the [Modding Discord](https://discord.gg/mH56AhUwPR) to receive support and talk with other modders and content creators!
