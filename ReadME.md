# GTA5-DismembermentMod-Repair

GTA5 中 [Dismemberment Mod](https://www.gta5-mods.com/scripts/dismemberment) 的修復版，該模組在今天已經無法使用。

本项目基于 [GTA5-DismembermentMod](https://github.com/0x-FADED/GTA5-DismembermentMod) 編譯而來，原作者並沒有將源代碼編譯為可直接在遊戲中運行的文件。

## 安裝Mod
1. 將 Dismemberment.dll 和 DismembermentWeapons.cfg 放入遊戲目錄下的 `scripts` 資料夾。
2. 將 DismembermentASI.asi 放入遊戲的根目錄。
3. 使用 OpenIV 工具，將 dlc.rpf 檔放入 `mods\update\x64\dlcpacks\dismemberment` 目錄。
4. 在 GTA V 的安裝目錄中，導航到路徑：
`mods\update\update.rpf\common\data`

5. 編輯 dlclist.xml 檔：在檔的末尾但在 `</Paths>` 之前，添加以下內容：`<Item>dlcpacks:/dismemberment/</Item>`

# ENG
**This content is translated by ChatGPT.**

The GTA5 [Dismemberment Mod](https://www.gta5-mods.com/scripts/dismemberment) repair version, this mod is no longer usable today.

This project is compiled based on [GTA5-DismembermentMod](https://github.com/0x-FADED/GTA5-DismembermentMod). The original author did not compile the source code into files that can be directly run in the game.

## Install the mod
1. Put Dismemberment.dll and DismembermentWeapons.cfg into the `scripts`  folder in the game directory.
2. Put DismembermentASI.asi into the root directory of the game.
3. Using the OpenIV, put the dlc.rpf file into the `mods\update\x64\dlcpacks\dismemberment`directory.
4. In the installation directory of GTA V, navigate to the path:
`mods\update\update.rpf\common\data`

5. Edit the dlclist.xml file: At the end of the file but before `</Paths>`, add the following: `<Item>dlcpacks:/dismemberment/</Item>`