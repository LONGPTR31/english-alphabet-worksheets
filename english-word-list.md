# 算術鎖：英文題庫

每次解鎖或延長都要先答一題數學、再答一題英文。英文題是三選一，從下面六種題型隨機出（不會連續兩題同一種），
最近 8 題出過的答案不會馬上再出，正確答案也不會連續兩題在同一個位置。題庫來源：`app/src/main/java/tw/home/mathlock/English.java`。

## 六種題型

| 題型 | 畫面 | 英文題目（語音會念） | 選項 | 出現機率 |
|---|---|---|---|---|
| 看圖選單字 | 一個圖案 | What animal is this? / What shape is this? / What is this? | 3 個單字（念出單字） | 35% |
| 看單字選圖 | 大大的英文單字 | Where is the ___? | 3 個圖案（不念，避免洩漏答案） | 20% |
| 數一數 | 1–10 個同樣的圖案 | How many ___? | 3 個數字單字（念出單字） | 15% |
| 數字的英文 | 大大的阿拉伯數字 1–10 | What number is this? | 3 個數字單字（念出單字） | 10% |
| 看顏色選單字 | 一個色塊 | What color is this? | 3 個顏色單字（念出單字） | 12% |
| 看單字選顏色 | 大大的顏色單字 | Which one is ___? | 3 個彩色圓點（不念） | 8% |

「看圖選單字」和「看單字選圖」會從下面 7 個主題中隨機選一個，三個選項都來自同一個主題。

## 主題單字（共 106 個）

### 動物 Animals（30）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| cat | 🐱 | 貓 | dog | 🐶 | 狗 | fish | 🐟 | 魚 |
| bird | 🐦 | 鳥 | pig | 🐷 | 豬 | cow | 🐮 | 牛 |
| duck | 🦆 | 鴨子 | rabbit | 🐰 | 兔子 | lion | 🦁 | 獅子 |
| monkey | 🐵 | 猴子 | frog | 🐸 | 青蛙 | bear | 🐻 | 熊 |
| horse | 🐴 | 馬 | elephant | 🐘 | 大象 | chicken | 🐔 | 雞 |
| tiger | 🐯 | 老虎 | mouse | 🐭 | 老鼠 | sheep | 🐑 | 羊 |
| snake | 🐍 | 蛇 | turtle | 🐢 | 烏龜 | panda | 🐼 | 熊貓 |
| fox | 🦊 | 狐狸 | bee | 🐝 | 蜜蜂 | butterfly | 🦋 | 蝴蝶 |
| owl | 🦉 | 貓頭鷹 | penguin | 🐧 | 企鵝 | whale | 🐳 | 鯨魚 |
| giraffe | 🦒 | 長頸鹿 | zebra | 🦓 | 斑馬 | crab | 🦀 | 螃蟹 |

### 食物 Food（20）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| apple | 🍎 | 蘋果 | banana | 🍌 | 香蕉 | grapes | 🍇 | 葡萄 |
| orange | 🍊 | 柳橙 | strawberry | 🍓 | 草莓 | watermelon | 🍉 | 西瓜 |
| cherry | 🍒 | 櫻桃 | lemon | 🍋 | 檸檬 | pear | 🍐 | 梨子 |
| peach | 🍑 | 桃子 | carrot | 🥕 | 紅蘿蔔 | corn | 🌽 | 玉米 |
| cake | 🍰 | 蛋糕 | egg | 🥚 | 蛋 | bread | 🍞 | 麵包 |
| milk | 🥛 | 牛奶 | pizza | 🍕 | 披薩 | ice cream | 🍦 | 冰淇淋 |
| cookie | 🍪 | 餅乾 | candy | 🍬 | 糖果 | | | |

### 物品 Things（20）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| ball | ⚽ | 球 | book | 📖 | 書 | hat | 👒 | 帽子 |
| shoe | 👟 | 鞋子 | house | 🏠 | 房子 | cup | ☕ | 杯子 |
| clock | ⏰ | 時鐘 | key | 🔑 | 鑰匙 | bed | 🛏️ | 床 |
| chair | 🪑 | 椅子 | door | 🚪 | 門 | bag | 🎒 | 書包 |
| phone | 📱 | 手機 | umbrella | ☂️ | 雨傘 | balloon | 🎈 | 氣球 |
| gift | 🎁 | 禮物 | kite | 🪁 | 風箏 | pencil | ✏️ | 鉛筆 |
| teddy bear | 🧸 | 泰迪熊 | glasses | 👓 | 眼鏡 | | | |

### 交通工具 Vehicles（10）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| car | 🚗 | 汽車 | bus | 🚌 | 公車 | train | 🚆 | 火車 |
| airplane | ✈️ | 飛機 | boat | ⛵ | 船 | bike | 🚲 | 腳踏車 |
| truck | 🚚 | 卡車 | rocket | 🚀 | 火箭 | taxi | 🚕 | 計程車 |
| helicopter | 🚁 | 直升機 | | | | | | |

### 身體 Body（8）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| eye | 👁️ | 眼睛 | ear | 👂 | 耳朵 | nose | 👃 | 鼻子 |
| mouth | 👄 | 嘴巴 | hand | ✋ | 手 | foot | 🦶 | 腳 |
| tooth | 🦷 | 牙齒 | leg | 🦵 | 腿 | | | |

### 大自然 Nature（12）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| sun | ☀️ | 太陽 | moon | 🌙 | 月亮 | star | ⭐ | 星星 |
| cloud | ☁️ | 雲 | rain | 🌧️ | 雨 | snow | ❄️ | 雪 |
| rainbow | 🌈 | 彩虹 | tree | 🌳 | 樹 | flower | 🌸 | 花 |
| leaf | 🍁 | 葉子 | fire | 🔥 | 火 | water | 💧 | 水 |

### 形狀 Shapes（6）
| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|---|---|---|
| circle | 🔵 | 圓形 | square | 🟦 | 正方形 | triangle | 🔺 | 三角形 |
| heart | ❤️ | 愛心 | star | ⭐ | 星形 | diamond | 🔷 | 菱形 |

## 顏色 Colors（10）

| 單字 | 中文 | 看顏色選單字 | 看單字選顏色 |
|---|---|---|---|
| red | 紅色 | ✔ | 🔴 |
| blue | 藍色 | ✔ | 🔵 |
| green | 綠色 | ✔ | 🟢 |
| yellow | 黃色 | ✔ | 🟡 |
| orange | 橘色 | ✔ | 🟠 |
| purple | 紫色 | ✔ | 🟣 |
| pink | 粉紅色 | ✔ | —（沒有粉紅色圓點圖案，所以不出這種） |
| brown | 咖啡色 | ✔ | 🟤 |
| black | 黑色 | ✔ | ⚫ |
| white | 白色 | ✔ | ⚪ |

## 數字 Numbers（1–10）

one、two、three、four、five、six、seven、eight、nine、ten

「數一數」會數的 12 種東西（題目念 How many ___?）：

| 單字 | 圖案 | 中文 | 單字 | 圖案 | 中文 |
|---|---|---|---|---|---|
| apples | 🍎 | 蘋果 | stars | ⭐ | 星星 |
| balls | ⚽ | 球 | cars | 🚗 | 汽車 |
| fish | 🐟 | 魚 | flowers | 🌸 | 花 |
| ducks | 🦆 | 鴨子 | cookies | 🍪 | 餅乾 |
| balloons | 🎈 | 氣球 | bananas | 🍌 | 香蕉 |
| hearts | ❤️ | 愛心 | bees | 🐝 | 蜜蜂 |

## 想新增或修改單字

改 `English.java` 裡對應主題的清單（每項是 `{"英文單字", "圖案"}`），重新建置安裝即可。
同一個主題至少要有 3 個單字，才湊得出三個選項。
