滾輪 JSON 命名規則與資料夾結構

目前所有滾輪 JSON 檔案已重新命名，並依照遊戲別分資料夾管理。
每個 JSON 檔的命名格式如下：

<k8案件編號>-<代號>-<RTP指標>-<遊戲類型>.json

各欄位說明：
- k8案件編號：專案代碼，例如 K801
- 代號：遊戲對應簡寫，例如 SB、FT、FG
- RTP指標：
  s-high：特高
  high：高
  mid：中
  low：低
  s-low：特低
- 遊戲類型：
  FS：免費遊戲（Free Spins）

遊戲列表：
K801  森巴        SB
K802  喜氣臨門    FT
K803  魚(幸運魚)  FG
K804  驢子大冒險  DK
K805  楚河漢界    CH
K806  北極熊      PB
K807  武媚娘      WU
K808  舞獅        LD
K809  梭哈大轉盤  SW
K810  泡泡缸      BT   （暫時略過）
K811  成吉思汗    GK


檔案命名範例：
k807-WU-s-high-FS.json
代表 K807 武媚娘 (WU) 特高 RTP (s-high) 的免費遊戲滾輪表設定檔