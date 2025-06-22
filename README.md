<div class="header" align="center">  
<img alt="Space Station 14" width="880" height="300" src="https://raw.githubusercontent.com/space-wizards/asset-dump/de329a7898bb716b9d5ba9a0cd07f38e61f1ed05/github-logo.svg">  
</div>

Space Station 14 is a remake of SS13 that runs on [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), our homegrown engine written in C#.

This is a fork of the primary repo for Space Station 14 called Weasel Station. To prevent people forking RobustToolbox, a "content" pack is loaded by the client and server. This content pack contains everything needed to play the game on one specific server.

If you want to host or create content for Weasel Station, this is the repo you need. It contains both RobustToolbox and the content pack for development of new content packs.

## Links

[Space Station 14's Website](https://spacestation14.io/) | [The Weasel's Discord](https://discord.gg/NfdHxejQQk) | [Forums are currently a W.I.P)] | [WizDen's hub via Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [WizDen's hub via Standalone Download](https://spacestation14.io/about/nightlies/)

## Documentation/Wiki

Space Station 14's [docs site](https://docs.spacestation14.io/) has documentation on SS14s content, engine, game design, and more. It also have lots of resources for new contributors to the project.

## Contributing

We are happy to accept contributions from anybody. Get in Discord if you want to help. We've got a [list of issues](https://github.com/The-Weasel-Flockmind/Weasel-Station/issues) that need to be done and anybody can pick them up. Don't be afraid to ask for help either!  
While Weasel Station doesn't use the [contribution guidelines,](https://docs.spacestation14.com/en/general-development/codebase-info/pull-request-guidelines.html) you can feel free to if you want to check your stuff.

We are not currently accepting translations of the game on our main repository. If you would like to translate the game into another language, consider creating a fork or contributing to a fork.

## Building

1. Clone this repo:
```shell
git clone https://github.com/space-wizards/space-station-14.git
```
2. Go to the project folder and run `RUN_THIS.py` to initialize the submodules and load the engine:
```shell
cd space-station-14
python RUN_THIS.py
```
3. Compile the solution:  

Build the server using `dotnet build`.

[More detailed instructions on building the project.](https://docs.spacestation14.com/en/general-development/setup.html)

## License

All code for the content repository is licensed under the [MIT license](https://github.com/space-wizards/space-station-14/blob/master/LICENSE.TXT).  

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and copyright specified in the metadata file. For example, see the [metadata for a crowbar](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).  

> [!NOTE]
> Some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.
