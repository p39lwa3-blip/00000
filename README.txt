CT小舖交易機器人 V11

本版已加入：
- 幣號 / 代肝二選一
- 幣號價目表、代肝價目表頻道引導
- 50M 有33等 / 100M 無33等 / 100M 有33等 / 不死號（不會被官方掃幣號封）
- 幣號正常提供 / 暫停提供 / 缺貨
- 代肝 50M～1000M 獨立價格設定
- 代肝不需要數量
- 完成付款後進入「待確認付款」，管理端有「💰 確認付款」
- 代肝確認付款後要求客人在工單直接提供遊戲帳號
- 收到帳號後通知已排入處理，後續排隊進度由外部網站處理
- 非營業時間仍可下單、付款，只提示店長不在線

Discord Developer Portal：
Bot > Privileged Gateway Intents > 開啟 Message Content Intent。
因為機器人需要讀取客人在代肝工單中直接輸入的遊戲帳號。

環境變數：
DISCORD_TOKEN = Discord Bot Token
DB_PATH = 可選；Railway 若使用 /data 可持久化 SQLite
