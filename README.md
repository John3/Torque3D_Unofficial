# Torque3D_Unofficial
Torque3D Game Engine - Unofficial Repository.

[![GitHub tag](https://img.shields.io/github/tag/John3/Torque3D_Unofficial.svg)](https://github.com/John3/Torque3D_Unofficial/tags)
[![GitHub release](https://img.shields.io/github/release/John3/Torque3D_Unofficial.svg)](https://github.com/John3/Torque3D_Unofficial/releases/latest)
[![Github All Releases](https://img.shields.io/github/downloads/John3/Torque3D_Unofficial/total.svg)](https://github.com/John3/Torque3D_Unofficial/releases/latest)

[![IRC](https://img.shields.io/badge/irc-%23garagegames-green.svg)](https://kiwiirc.com/client/irc.maxgaming.net/?nick=wiki_user|?#garagegames)

Clean Torque3D dev builds.

- **SO:** Windows, Linux
- **GitHub Branch:** Development
- **Compressed:** [7zip](http://www.7-zip.org/) - [Xz](https://en.wikipedia.org/wiki/Xz)
- **Win Compiled:** default CMake options + VS14_2015 release Win32(x86)/Win64(x64)
- **Linux Compiled:** default CMake options + CodeBlock + Ninja release Linux x64
- **Template:** BaseGame and Full
- **Modules:** BlankGame(y), FPSGameplay(y), spectatorGameplay(y)
- **Graphics:** Direct3D 11, OpenGL 3.3
- **Physics:** Bullet(y) - PhysX(n)
- **Window and Input:** SDL(y) - DirectX(y)
- **Tools:** SQLite(n)

## Windows - How-To:
Use [7zip](http://www.7-zip.org/) 

Using the *BaseGame* and Module *FPSGameplay* template.  If you want the old *Full* template, see **"Linux - How-To"**.
1. Extract *Templates.tar.xz,* and rename BaseGame with your game name. **Ex:** `MyGame/`
2. Copy the folder *FPSGameplay* into data folder. **Ex:** `MyGame/game/data/FPSGameplay/`
3. Extract *t3d_x64.tar.xz* into the game folder of your project. **Ex:** `MyGame/game/t3d_x64.exe`
4. Run `t3d_x64.exe`

## Linux - How-To:
**From GUI:** use *Archive Manager*, doble click (Ubuntu Linux)
**From console:** `$ tar xJvf t3d_linux_x64.tar.xz`

Using the *Full* template. If you want the new template, see **"Windows - How-To"**.
1. Extract *Full.tar.xz* and rename Full with your game name. **Ex:** `MyGame/`
2. Extract *t3d_x64.tar.xz* into the game folder of your project **Ex:** `MyGame/game/t3d_x64.exe`
3. Run `t3d_x64`

**Legend:**

* **Templates.tar.xz:** Include BaseGame and Modules.
   * **BaseGame folder:** The basic for run the engine.
   * **Modules folder:** Included the official modules.
* **Full.tar.xz:** The old Full template.
* **t3d_x86.7z:** This will run your engine/game in Windows 32Bits only.
* **t3d_x64.tar.xz:** This will run your engine/game. Include Windows64 and Linux64.
* **t3d_x64_bullet.tar.xz:** This will run your engine/game with "Bullet physics" active. Include Windows64 and Linux64.
* **checksums.md5:** Checksum to verify data integrity. [MD5](https://en.wikipedia.org/wiki/MD5)

**Note:** If you have any problem with the new template **"BaseGame + Module"**, try using the old **"Full"** template.
**Note2:** If you don't have a custom main.cs, throw the content of the game folder into your game project folder and replace.

**Forum:** [Last development commit binary! 32bit & 64bit](http://forums.torque3d.org/viewtopic.php?f=2&t=665)

## Downloads in releases section

- Added commits of Feb 14, 2018 - [e079536](https://github.com/John3/Torque3D/commit/e0795361220283991408734ecd95cf2a6438727d) - [v1.24](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.24)
- Added commits of Feb 4, 2018 - [e4427b7](https://github.com/John3/Torque3D/commit/e4427b76548f41086043244ad5c944e870eb963f) - [v1.23](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.23)
- Added commits of Nov 27, 2017 - [74b7e4c](https://github.com/John3/Torque3D/commit/74b7e4cd89f4a0fee65d3f831c35df349d16f8c3) - [v1.22](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.22)
- Added commits of Oct 28, 2017 - [48f50d1](https://github.com/John3/Torque3D/commit/48f50d19c35d61d914bc641e7bddd7d89ff0bb60) - [v1.21](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.21)
- Added commits of Aug 24, 2017 - [a45a55a](https://github.com/John3/Torque3D/commit/a45a55ad6e2d639a644a8c5f84323d7cc41d6b78) - [v1.20](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.20)
- Added commits of Jun 10, 2017 - [64955e8](https://github.com/John3/Torque3D/commit/64955e8cfcd1242606ae10dfc5da7c8fdb4a6c63) - [v1.19](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.19)
- Added commits of Feb 04, 2017 - [5c8a821](https://github.com/John3/Torque3D/commit/5c8a82180b4e25c08449b2c0261541d08c9ff24b) - [v1.18](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.18) (T3D v3.10)
- Added commits of Jan 25, 2017 - [ac19e0e](https://github.com/John3/Torque3D/commit/ac19e0e84c98f682a7467789ae41017c38faf930) - [v1.17-rc.1](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.17-rc.1)
- Added commits of Jan 9, 2017 - [6164f36](https://github.com/GarageGames/Torque3D/commit/6164f36c473cc9f01fdd14b56fc0949422aff7f8) - [v1.0.16-rc.3](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.16-rc.3)
- Added commits of Dec 29, 2016 - [38554f7](https://github.com/GarageGames/Torque3D/commit/38554f7396f02fc1c8b6b13c00acd52178be205a) - [v1.0.16-rc.2](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.16-rc.2) (T3D v3.10-RC.2)
- Added commits of Dec 12, 2016 - [54456fa](https://github.com/GarageGames/Torque3D/commit/54456fa4fa13fc4a5ebfe28edcd921ad5c93e278) - [v1.0.15](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.15) (T3D v3.10-RC)
- Added commits of Dec 9, 2016 - 6309495 - [v1.0.14](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.14)
- Added commits of Nov 2, 2016 - 00a4a21 - [v1.0.13](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.13)
- Added commits of Sep 14, 2016 - c83efa5 - [v1.0.11](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.11)
- Added commits of Aug 21, 2016 - fcfe2d6 - [v1.0.10](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.10)
- Added commits of Aug 8, 2016 - 2794f18 - [v1.0.9](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.9)
- Added commits of Jul 11, 2016 - [5fa8504](https://github.com/GarageGames/Torque3D/commit/5fa8504568871e227c557a6a584f487b3bbce29f) - [v1.0.8](https://github.com/John3/Torque3D_Unofficial/releases/tag/v1.0.8) - (T3D v3.9)
- [...](https://github.com/John3/Torque3D_Unofficial/releases)


[![license](https://img.shields.io/github/license/John3/Torque3D_Unofficial.svg)](http://choosealicense.com/licenses/mit/)
