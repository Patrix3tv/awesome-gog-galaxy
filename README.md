# Awesome GOG Galaxy

## Communication
* [GOG Café Discord](https://discord.gg/372vxnZ)

## Utilities

* Alternative clients
   * [MiniGalaxy](https://github.com/sharkwouter/minigalaxy) by @sharkwouter.
* Shortcut Creators
   * [GOG Galaxy 2.0 Shortcut Creator](https://github.com/Megalex42/GOG-Galaxy-2.0-Shortcut-Creator) by @Megalex42
* Integration Updaters
   * [GOG Integration Updater](https://github.com/Slashbunny/gog-galaxy-plugin-downloader) by @Slashbunny
   * [GOG Galaxy 2.0 Integrations Scoop Bucket](https://github.com/borger/scoop-galaxy-integrations) by @Borger
* Data import/export
   * [GOG Galaxy Export Script](https://github.com/AB1908/GOG-Galaxy-Export-Script) by @AB1908
* Library comparison
   * [GOG Galaxy Library Compare (gamatrix-gog)](https://github.com/eniklas/gamatrix-gog) by @eniklas

## Skins

* [GOG Violet](https://github.com/berryes/gog-violet) by @berryes

## Resources
* GOG Galaxy Integrations Python API
   * Github repository https://github.com/gogcom/galaxy-integrations-python-api
   * PyPi package https://pypi.org/project/galaxy.plugin.api/
   * Galaxy Utils from @tylerbrawl https://github.com/tylerbrawl/Galaxy-Utils
 * GOG Database https://www.gogdb.org/
 * Unofficial GOG.com API docs https://github.com/Yepoleb/gogapidocs

## Galaxy 2.0 Upcoming features

* Completed
  * Integrations search and management ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/20#issuecomment-511233784), [2](https://github.com/gogcom/galaxy-integrations-python-api/issues/49#issuecomment-522331088), [3](https://www.resetera.com/threads/gog-galaxy-2-0-is-a-game-changer.139162/page-3#post-24918760))
  * Game deduplication ([1](https://www.reddit.com/r/gog/comments/d5gzld/i_hope_we_can_get_a_better_solution_for/f0m2cb9/))
  * Adding tags from the API ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/49#issuecomment-522331088))
  * Parametrized game launch ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/52#issuecomment-523540588), [2](https://www.reddit.com/r/gog/comments/d43ab3/suggestion_gog_galaxy_20_mark_games_owned/f0ezmkc/))
* In backlog / In progress
  * Chat and friends list for integrations ([1](https://github.com/gogcom/galaxy-integrations-python-api/commit/223adf6a384c438552be697467c9495dc591c448#commitcomment-34429833))
  * DLC management ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/23#issuecomment-512730026))
  * Secret achievements ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/63#issuecomment-532543083))
* Will be considered
  * Custom platforms ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/66#issuecomment-532571531))
  * Game language management ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/8#issuecomment-510074658))

## Installation and Debugging

* Integrations location
   * Windows: `%LOCALAPPDATA%\GOG.com\Galaxy\plugins\installed`
   * macOS: `~/Library/Application\ Support/GOG.com/Galaxy/plugins/installed`

* Log location
   * Windows: `C:\ProgramData\GOG.com\Galaxy\logs\`
   * macOS: `/Users/Shared/GOG.com/Galaxy/Logs`

## Integrations
Below are the integrations (**11** in total) and its features. Hover over links to see the maintainer.
* ✅ implemented
* ⬜ not implemented
* ❌ unsupported by the platform
* ⚠ works with issues
* ⬛ insufficient information


Service                                           | [In built-in search] | Install & Launch | Achievements | Game Time | Friend Recmd. | Friend Presence
:------------------------------------------------ | --: | ---------------: | -----------: | --------: | ------------: | ---------------:
***Official (2)***
Epic Games Store                                  | ✅  | ✅               | ⬜           | ✅       | ✅           | ⬜
Xbox                                              | ✅  | ✅               | ✅           | ✅       | ✅           | ✅
***Community, Stores (9)***
[Amazon][amazon]                                  | ⬜  | ❌               | ❌           | ✅       | ❌           | ❌
[Battle.net][battlenet]                           | ✅  | ✅               | ❌           | ✅       | ❌           | ❌
[Humble Bundle][humble]                           | ✅  | ✅               | ❌           | ✅       | ❌           | ❌
[Itch.io (@melcom)][itch]                         | ⬜  | ❌               | ❌           | ✅       | ❌           | ❌
[EA App Origin][origin]                           | ✅  | ✅               | ✅           | ✅       | ✅           | ⬜
[Legacy Games][legacy] (showed as Kartridge)      | ⬜  | ⚠                | ❌           | ⬜       | ❌           | ❌
[Rockstar Games Launcher][rockstar]               | ✅  | ✅               | ✅           | ✅       | ✅           | ✅
[Steam][steam]                                    | ✅  | ✅               | ✅           | ✅       | ✅           | ✅
[Ubisoft Connect][uplay]                          | ✅  | ✅               | ⬜           | ✅       | ✅           | ⬜

[origin]: https://github.com/melcom-creations/galaxy-integration-ea/releases/tag/2.0.4-64bit "Melcom"
[psn]: ...
[steam]: https://github.com/melcom-creations/galaxy-integration-steam/releases/tag/v2.1.4-64bit "Melcom"
[uplay]: https://github.com/melcom-creations/galaxy-integration-uplay/releases/tag/2.0.5-64bit "Melcom"
[paradox]: ...
[battlenet]: https://github.com/melcom-creations/galaxy-integration-battlenet/releases/tag/v2.1.8-64bit "Melcom"
[bethesda]: ...
[dosbox]: ...
[ffxiv]: ...
[gw2]: ...
[humble]: https://github.com/melcom-creations/galaxy-integration-humble/releases/tag/2.0.6-64bit "Melcom"
[indiegala]: ...
[pathofexile]: ...
[twitch]: ...
[wargaming]: ...
[minecraft]: https://github.com/TouwaStar/Galaxy_Plugin_Minecraft "Maintainted by @TouwaStar"
[3ds]: https://github.com/LeonardFiedrowicz/galaxy-integration-citra "Maintainted by @LeonardFiedrowicz"
[nds]: https://github.com/TBemme/galaxy-integration-nds "Maintainted by @TBemme"
[ncube]: https://github.com/JTNDev/galaxy-integration-gc "Maintainted by @JTNDev"
[nwii]: https://github.com/JTNDev/galaxy-integration-wii "Maintainted by @JTNDev"
[ps2]: https://github.com/AHCoder/galaxy-integration-ps2 "Maintainted by @AHCoder"
[psp]: https://github.com/TBemme/galaxy-integration-psp "Maintainted by @TBemme"
[nwiiu]: https://github.com/LeonardFiedrowicz/galaxy-integration-cemu "Maintained by @LeonardFiedrowicz"
[ps3]: https://github.com/mpm11011/galaxy-integration-rpcs3 "Maintained by @mpm11011"
[itch]: https://github.com/melcom-creations/galaxy-integration-itch/releases/tag/2.1.3-64bit "Maintained by ??"
[rockstar]: https://www.dropbox.com/scl/fi/f3dhv8mwtpk9hjqvwntnf/galaxy-rockstar-plugin-v2.0.7-64bit.zip?rlkey=1vlw63asqjty24n6hkgb7npug&dl=1 "Melcom"
[touhou]: https://gitlab.com/PookaMustard/thcrap-plugin-for-galaxy-2.0 "Maintained by @PookaMustard"
[nes]: https://github.com/AHCoder/galaxy-integration-nes "Maintained by @AHCoder"
[gameboy]: https://github.com/AHCoder/galaxy-integration-ngameboy "Maintained by @AHCoder"
[snes]: https://github.com/AHCoder/galaxy-integration-snes "Maintained by @AHCoder"
[n64]: https://github.com/Riku55/galaxy-integration-n64-RetroArch- "Maintained by @Riku55"
[discord]: ...
[nswitch]: https://github.com/hyoretsu/galaxy-integration-switch "Maintained by @hyoretsu"
[retroarch]: https://github.com/jshackles/RetroGOG "Maintained by @jshackles"
[scummvm]: https://github.com/micpp42/gog-galaxy-scummvm "Maintained by @micpp42"
[osu]: https://github.com/UncleGoogle/galaxy-integration-osu "Maintained by @UncleGoogle"
[riot]: ...
[generic]: https://github.com/AndrewDWhite/GalaxyGenericImporterPlugin "Maintained by @AndrewDWhite"
[amazon]: https://github.com/melcom-creations/galaxy-integration-amazon/releases/tag/2.1.4-64bit "Melcom"
[fanatical]: ...
[legacy]: https://github.com/pippo-san/galaxy-integration-legacy-games "Maintained by @pippo-san"
