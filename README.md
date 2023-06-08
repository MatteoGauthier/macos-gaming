# macos-gaming

Play Windows games on macOS using [Game Porting Toolkit](https://developer.apple.com/videos/play/wwdc2023/10123/)

## Getting started

### Tools used

- [Homebrew](https://brew.sh/)
- macOS 13.4+
- [Command Line Tools for XCode 15 Beta](https://developer.apple.com/download/all/?q=Command%20line%20tools%20for%20XCode%2015%20beta)
- [Whisky : Nice GUI to use game-porting-tooklit](https://github.com/IsaacMarovitz/Whisky)

### Tutorial

- [Gaming Porting Toolkit tutorial](https://www.applegamingwiki.com/wiki/Game_Porting_Toolkit)
- [Recommended tutorial](https://t.co/uLSduBVpM8)
- [Instruction for Battle.net](https://www.reddit.com/r/macgaming/comments/14307be/comment/jn7dxzo/?utm_source=share&utm_medium=web2x&context=3)

## Compatibility Tables

<details open>
  <summary>M1</summary>

| Game           | Config                     | Notes                                                                                                             |
| -------------- | -------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Cyberpunk 2077 | 16 GB                      | [reddit post](https://www.reddit.com/r/macgaming/comments/142vjdz/i_got_cyberpunk_2077_running_on_an_m1_macbook/) |
| Diablo IV      | Macbook Air m1 (8GB/256GB) | [reddit post](https://www.reddit.com/r/macgaming/comments/143vwcy/diablo_iv_running_on_macbook_air_m1_8gb256gb/)  |

</details>

<details open>
  <summary>M1 Pro</summary>
  
| Game           | Config | Notes                                                                                                                                              |
| -------------- | ------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Skater XL      | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/143jo8c/skater_xl_running_on_m1_pro_base_model_wgame/)                                   |
| Outer Wilds    | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) low settings ~50 FPS      |
| Outer Wilds    | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) medium settings 35 FPS    |
| Elden Ring     | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) medium settings 35 FPS    |
| Journey        | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) ~100 FPS                  |
| Sekiro         | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) ~40 FPS                   |
| The Witcher 3  | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) ~40 FPS                   |
| Cyberpunk 2077 | base   | [reddit post](https://www.reddit.com/r/macgaming/comments/1439cpz/some_games_i_tested_through_porting_toolkit/?sort=new) low settings 1080p 30 FPS |

</details>

<details open>
  <summary>M1 Max</summary>
  
| Game      | Config         | Notes                                                                                                     |
| --------- | -------------- | --------------------------------------------------------------------------------------------------------- |
| Diablo IV | Ventura 13.3.1 | [reddit post](https://www.reddit.com/r/macgaming/comments/143aii6/diablo_4_on_m1_max_macos_ventura_1331/) |

</details>

<details open>
  <summary>M1 Ultra</summary>

| Game | Config | Notes |
| ---- | ------ | ----- |
|      |        | d     |

</details>

<details open>
  <summary>M2 Max</summary>

| Game            | Config      | Notes                                                                                                                                                                                               |
| --------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cyberpunk 2077  | GPU 38 core | [reddit post](https://www.reddit.com/r/macgaming/comments/1435ukq/cyberpunk_on_m2_max_wgame_porting_toolkit/)                                                                                       |
| Diablo IV       | 32gb        | [reddit post](https://www.reddit.com/r/macgaming/comments/14307be/diablo_iv_on_m2_max_using_macos_sonoma_and_game/) [tutorial](https://www.reddit.com/r/macgaming/comments/14307be/comment/jn7dxzo) |
| Hogwarts Legacy | 32gb        | [reddit post](https://www.reddit.com/r/macgaming/comments/14342uz/hogwarts_legacy_on_m2_max/)                                                                                                       |

</details>

## Troubleshooting and FAQ

<details>
  <summary>Which version of MacOS is supported ? / Can I play with Ventura ?</summary>

No it's not required, but Apple recommand to use the latest version of MacOS (Sonoma), in order to get the latest development tools.
However the Command Line Tools for XCode 15 Beta is required to use Game Porting Toolkit [source](https://www.reddit.com/r/macgaming/comments/14307be/comment/jn7str1/?utm_source=share&utm_medium=web2x&context=3)

</details>

<details>
  <summary>How to hide the game-porting-toolkit HUD ? </summary>
  Just use the `gameportingtoolkit-no-hud` binary instead of `gameportingtoolkit` binary.

</details>

<details>
  <summary>Do I need a Apple Developer Account to use Game Porting Toolkit</summary>
  No, but you might need an Apple Developer Account (free) if you choose to download Game Porting Toolkit from the <https://developer.apple.com> website.
</details>

## Related links

- <https://github.com/IsaacMarovitz/Whisky>
- [r/macgaming Reddit community](https://www.reddit.com/r/macgaming/)
- Apple Homebrew [formulae](https://github.com/apple/homebrew-apple)
- [Apple Gaming Wiki](https://www.applegamingwiki.com/wiki/Home), the wiki about gaming on M1 Apple silicon Mac
- Cool website with news, game perf reports, reviews [Apple Silicon Games](https://applesilicongames.com/)
