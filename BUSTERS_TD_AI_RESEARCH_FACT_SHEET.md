# Buster's TD — AI Research Licensing Fact Sheet

**Robot Future · November 12, 2026 · robotfuturellc@gmail.com**

Buster's TD is a commercially released Unreal tower-defense game with physics-based combat, maze construction and a player-controlled combat drone. Available licensing material spans the original human-written UE4 Blueprint project, its AI-assisted UE5 C++ modernization, Git history, player feedback, product records and automated testing tools.

## Game and release

| Specification | Details |
|---|---|
| Developer and publisher | Robot Future |
| Platform | Windows / Steam |
| Steam app | **1316530** |
| Early Access release | **February 7, 2021** |
| Commercial release | **January 23, 2024** |
| Editions | Original **Unreal Engine 4.26** and modernized **Unreal Engine 5.8** |
| Gameplay length | **20 hours**, including all endless levels |
| Modes | Campaign, challenge levels and Endless survival |
| Full build map set | **23 maps: 22 gameplay maps and 1 main menu** |
| Objective | Protect the gravity well while defeating enemy waves |
| Gameplay loop | Build walls and towers, send waves, pilot the drone, repair and upgrade defenses, and revise the layout |
| Maze construction | Player-built walls and towers shape enemy routes; blocked enemies can attack defensive structures |
| Physics | Knockdown, knockback, ragdolls, physical vehicles, projectiles, collision and drone movement |
| Tower families | **6:** Pellet, Micro Laser, Magma, Rocket, Mortar and Slapper; wall construction complements the tower roster |
| Drone weapons | **4:** Pulse, Rockets, Railgun and Arc |
| Drone progression | Mission-based weapon purchases; free switching between owned weapons |
| Level progression | Up to **3 stars** per finite win: clear, at least 60% base health and at least 90% base health; saved best results and Endless records |
| Demo | Tutorial, first mission and City Endless; Steam demo app **1353580** |
| External promotion | Alienware Arena Steam-key giveaway for **Tier 5** members |
| Gameplay trailer | https://www.youtube.com/watch?v=Qi7vXZ7G5bg&t=9s |
| Steam page | https://store.steampowered.com/app/1316530/Busters_TD/ |

## Source code and Blueprint modernization

The UE4 edition contains the original human-written Blueprint gameplay. The UE5 edition combines retained Blueprints with native C++ systems for targeting, movement, drone combat, UI, collision, editor tooling and automated tests. Together, the editions provide a practical engine-migration and Blueprint-to-C++ development case study.

| Specification | Original UE4 | UE5 modernization |
|---|---|---|
| Engine version | **4.26.2**, CL 15973114 | **5.8.3**, CL 58210709 |
| Implementation | Blueprint-first gameplay with minimal native boilerplate | Blueprints integrated with native C++ gameplay, UI, tools and tests |
| Project C/C++ source and header files | **4** | **181** |
| Physical C/C++ lines | **39** | **30,794** |
| C/C++ code lines | **20** | **28,296** |
| Runtime code | **20** lines / **4** files | **17,999** lines / **119** files |
| Editor code | **0** | **3,092** lines / **23** files |
| Native test code | **0** | **7,205** lines / **39** files |
| Build/target C# code | **32** lines / **3** files | **74** lines / **5** files |
| Blueprint-family packages | **296** | **274** |
| Blueprint packages | **233** | **233** |
| Widget Blueprints | **50** | **28** |
| Animation Blueprints | **13** | **13** |
| Blueprint-family packages in `Content/TowerD` | **134** | **134** |

Code-line totals cover project source and exclude blank lines, comment-only lines, engine code, plugin code and generated intermediate files. Blueprint totals cover the full project library, including asset-pack content.

## Levels and environments

| Specification | Details |
|---|---|
| Full build map set | **22 gameplay maps** |
| Named menu/progression entries | **15**, including Tutorial |
| Additional gameplay maps | **7** |
| Full source-library map files | UE4: **63** · UE5: **62** |
| Maps within `Content/TowerD` | UE4: **32** · UE5: **31** |
| Environment variety | City streets, forest villages, snowy mountains, industrial platforms, space environments, tunnels, bridges and craters |
| Replay systems | Endless survival, alternate maze layouts, tower combinations, upgrades and drone loadouts |

| # | Level / map | Unreal map ID |
|---|---|---|
| 1 | Tutorial | `Tutorial` |
| 2 | Fly Down | `Level1` |
| 3 | The Asteroid | `FlatGrass` |
| 4 | The Hangar | `TheHangar` |
| 5 | Snow Day | `TheFactory` |
| 6 | Space Dock | `Space_Level` |
| 7 | The Fall | `TheFall` |
| 8 | The Tunnel | `TheTunnel` |
| 9 | The Cube | `TheCube` |
| 10 | The Bridge | `TheBridge` |
| 11 | The Crater | `TheCrater` |
| 12 | The Circle | `TheCircle` |
| 13 | Big City | `City` |
| 14 | Little Town | `Town` |
| 15 | Village | `Village` |
| 16 | TheGrass | `TheGrass` |
| 17 | TheMountain | `TheMountain` |
| 18 | PogMap | `PogMap` |
| 19 | Endless | `Endless` |
| 20 | MainMenPlayable | `MainMenPlayable` |
| 21 | Level3 | `Level3` |
| 22 | Space_Glow | `Space_Glow` |

The main menu is `MainMenuLevel`. The full source libraries also contain sample showcases, menus, tests and unused map content.

## Development history and ownership

| Specification | Details |
|---|---|
| Original development history begins | **February 16, 2019** |
| Latest preserved original commit | **January 13, 2024** |
| Original UE4 branch history | **41 commits** |
| Original UE4 commits across saved references | **43 unique large commits** |
| UE5 branch history | **21 large commits** |
| UE5 commits across branches, remotes and tags | **28 unique commits** |
| Source control | Git, preserved UE4 archives, a UE5 modernization repository and development documentation |
| Backups | Project backups going back to **2019** |
| Earlier engine editions | UE4.22, UE4.23 and UE4.26 |
| Original developer | **One original developer** |
| Source publication | **The game source has never been public** |
| Licensing contact | **Robot Future — robotfuturellc@gmail.com** |

## Project assets and packaged game

| Specification | Original UE4 | UE5 |
|---|---|---|
| Full Content library | **27.474 GB** / 27,474,119,951 bytes | **27.257 GB** / 27,257,355,330 bytes |
| Unreal asset files | **9,985 `.uasset`** | **10,095 `.uasset`** |
| Map files | **63 `.umap`** | **62 `.umap`** |
| Total Unreal packages | **10,048** | **10,157** |
| Packages in `Content/TowerD` | **753 assets + 32 maps** | **886 assets + 31 maps** |
| Windows distribution size | **3.097 GB** / 3,097,085,098 bytes | **3.995 GB** / 3,994,942,143 bytes |
| Bundled Content reference | **2.802 GB** / 2,802,377,247 bytes | **3.759 GB** / 3,759,420,455 bytes |
| Asset-pack directory packages | **8,797** | **8,797** |

GB is decimal. Full Content libraries include unused asset-pack content and support files. Windows distributions and bundled Content figures describe packaged builds. The libraries include Marketplace assets used in the game. Source libraries, packaged distributions and bundled Content are separate size categories.

## AI testing and research tools

| Specification | Details |
|---|---|
| **AI level tester** | **Purpose-built AI gameplay tester for level verification**, including defense planning, tower purchases, upgrades, drone flight and weapon control |
| Gameplay verification | Exercises waves, objectives, resource spending and player input paths; records game state, outcomes and screenshots |
| **Unit and regression tests** | **Full tower-defense and UE5 test suite**, with **117 passing native tests** |
| Test implementation | **7,205 lines** across **39 native test files** |
| Test coverage areas | Targeting, objective damage, collision, physical interactions, construction, upgrades, drone systems, UI and gameplay regressions |
| Automated capture | Native screenshots with game-state and action logs |
| Development interface | JSON control/state inspection and capture tooling |
| Research integration | Reset/step interfaces, observation/action schemas, rewards and trajectory exports are integration workstreams |
| Research applications | Blueprint-to-C++ conversion, engine migration, code repair, refactoring, gameplay agents and behavior evaluation |

## Player feedback and product-development material

| Specification | Details |
|---|---|
| Player feedback and reviews | Available as training context showing how player observations fed back into development |
| Development logs | Engineering, build, gameplay and regression records |
| Survey responses | **46**, collected April–May 2021 |
| Feature preferences | Upgrades **35** · replayability **26** · level variety **24** · multiplayer **22** · customization **20** · story **13** · leaderboard **8** |
| Visual-tone preferences | **32** fun/comedic · **14** dark/serious |
| Product planning | Trello board with ideas, feedback, feature requests and versioned completion lists |
| Engineering documents | Migration, collision/navigation, upgrades, drone systems, UI, build and regression documentation |
| Editable authoring material | Tower/drone Blender sources and authoring/import scripts |
| **UE5 AI development chats** | **Available on request**, covering AI-assisted enhancements to the game |
| Licensing material | Source code, Blueprints, development history, product records, reference builds and gameplay media |

**Licensing enquiries: robotfuturellc@gmail.com**
