# ![BSIPA](docs/images/banner_dark.svg) [![Build status](https://ci.appveyor.com/api/projects/status/1ruhnnfeudrrd097?svg=true)](https://ci.appveyor.com/project/nike4613/beatsaber-ipa-reloaded-9smsb)

Who adds anti piracy to open source software? Seriously.

## How To Install

1. [Download a release](https://github.com/BrandonLogandi/bsipa-nopiracy/releases)
2. [Download this fork of ModAssistant](https://github.com/BrandonLogandi/ModAssistant-NoPiracy/releases)
3. Install your mods with the ModAssistant
4. Open the IPA folder in the game directory and delete everything but the **Pending** folder
5. Delete **IPA.exe** and the **Libs** folder from the game folder
2. Extract the contents from the the NoPiracy release into the game folder
3. Run **IPA.exe**
4. Start the game as usual

A console window should open before the game starts if the installation was successful.

To disable this console window, pass `--no-console` to the game.

## How To Uninstall

1. Drag & drop the game exe onto **IPA.exe** while holding <kbd>Alt</kbd>
    - Or run `ipa -rn` in a command window

## Arguments

`IPA.exe file-to-patch [arguments]` 

- `--launch`: Launch the game after patching
- `--revert`: Revert changes made by IPA (= unpatch the game)
- `--nowait`: Never keep the console open
- See `-h` or `--help` for more options.

Unconsumed arguments will be passed on to the game in case of `--launch`.
