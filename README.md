# teleport

Move your character to everywhere in same zone.

## Commands

Toolbox(/8) | Description
--- | ---
**tp loc** | Show coordinates zone id and x, y, z, w.
**tp drop [x]** | Drop your HP to `x` percent for slaying.
**tp save [name]** | Save your location name.
**tp to [name]** | Teleport to your saved location `name` (if not have name will open GUI for your bookmark).
**tp remove [name]** | Remove your saved location `name`.
**tp blink [distance] [z]** | Blink to forward with `distance` and `z` (can ignore z if you are sure not underground).
**tp back** | Move back to your last location before teleport.
**tp [up/down] [z]** | Teleport to up or down by `z`.
**tp [x/y/z] [+/-] [distance]** | Teleport follow side +/- with `distance`.
**tp [x] [y] [z]** | Teleport with manually coordinates.
| 指令                      | 參數     | 功能說明                    | 範例                    |
| ----------------------- | ------ | ----------------------- | --------------------- |
| `/gat`                  | *(無)*  | 切換模組啟用 / 停用狀態，並刷新/移除標記  | `/gat`                |
| `/gat ui`               | *(無)*  | 開啟圖形設定介面（GUI 模式可用）      | `/gat ui`             |
| `/gat visit start`      | *(無)*  | 開始自動巡訪待採集點（依清單順序傳送並採集）  | `/gat visit start`    |
| `/gat visit stop`       | *(無)*  | 停止巡訪                    | `/gat visit stop`     |
| `/gat visit clear`      | *(無)*  | 清空待採集清單                 | `/gat visit clear`    |
| `/gat visit list`       | *(無)*  | 列出目前待採集的座標（最多顯示前 10 筆）  | `/gat visit list`     |
| `/gat visit dwell <秒數>` | `<秒數>` | 設定每個點停留時間（秒），最少 1 秒     | `/gat visit dwell 15` |
| `/gat visit dwell`      | *(無)*  | 顯示目前的停留時間設定             | `/gat visit dwell`    |
| `/gat visit addhere`    | *(無)*  | 將目前角色所在座標加入待採集清單        | `/gat visit addhere`  |
| `/gat visit`            | *(無)*  | 顯示 `visit` 子指令的用法（help） | `/gat visit`          |
