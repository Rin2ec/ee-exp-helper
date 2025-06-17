# 伊伊經驗小幫手

🎮 一款為《**Artale**》遊戲打造的 EXP 統計工具，
透過即時 OCR 擷取畫面，自動分析經驗值增量與效率，
支援遊戲內 HUD 顯示，適用於 Windows。

![screenshot](https://media.discordapp.net/attachments/961270197409415282/1384530961714118656/image.png?ex=6852c470&is=685172f0&hm=b26220dd8fa2a4f50debaca72dc6ddb803bdf58f5993679c1aa82cd561621b1b&=&format=webp&quality=lossless)

![screenshot](https://media.discordapp.net/attachments/1365964640307380234/1384379485021011989/image.png?ex=6852375d&is=6850e5dd&hm=f29ff1faf486da483a5de9d475a9d5149837009dad0ecbf6d94a36758fd4d70b&=&format=webp&quality=lossless)

---

## ✨ 功能特色
- 📷 自訂畫面偵測區域（EXP 數值所在區塊）
- 🔍 即時 OCR 辨識畫面 EXP 數字
- 📈 實時統計：
  - EXP
  - 擊殺數（Kills）
  - 每分鐘 EXP（EXP / min）
  - 預估 10 分鐘 EXP
  - 10分鐘實際累積 EXP
- 🎮 遊戲模式浮動 UI（可拖曳、隱藏、模式切換）
- ⌨️ **快捷鍵支援**：
  - `F7`：開始統計  
  - `F8`：重置統計  
  - `F9`：切換遊戲模式（HUD 開/關）
- 💾 自動儲存設定（偵測區域、顯示模式、視窗位置）
- 📤 匯出功能：可將統計資料另存為 `.csv` 檔案
- 🛡️ 外部畫面偵測，無注入、零風險，安心使用

---

## 📦 下載與安裝

前往 [Releases 頁面](https://github.com/Rin2ec/artale-exp-detector/releases) 下載最新版本：

| 檔案類型 | 下載連結 |
|----------|-----------|
| 🗂️ 免安裝版 | [Artale EXP Detector-v1.0.4.zip](https://drive.google.com/file/d/1ax5r7E4upoPT4vJHxO7PAGCrgYSuh1Qv/view?usp=sharing) |

> 僅支援 Windows 10 / 11，建議使用全螢幕視窗模式執行遊戲。

---

## 🚀 快速開始

1. 執行應用程式
2. 點擊「選取範圍」框選 EXP 數值區塊  
   ⚠️ **請記得右邊留點空間（大約 2～3 位數）**，避免從 `99` 升到 `100` 時被裁掉，影響偵測。
3. 點選「開始統計」
4. 開啟「遊戲模式」以浮動 HUD 顯示統計資訊

---

## 🖥️ 系統需求

- ✅ 作業系統：Windows 10 / 11
- ✅ 顯示：100% 縮放比例建議
- ✅ 執行模式：Artale 建議使用視窗模式執行

---

## 🐞 已知問題

- 部分數值可能因字體渲染導致 OCR 誤判
- OCR 區域若選太小會漏字、選太大則辨識雜訊增加

---

## 🧩 其他工具

| 工具名稱           | 功能簡介                           | 連結 |
|--------------------|------------------------------------|------|
| ⏰ **BOSS 時間計算器** | 記錄並預測世界王出現時間               | [立即查看](https://rin2ec.github.io/ee-boss-respawn-timer/) |
| 🌐 **頻道紀錄查詢工具** | 簡易記錄遊戲頻道資訊       | [立即查看](https://rin2ec.github.io/ee-number-tool/)|
| 🐱 **伊伊接技小幫手** | 鍵盤接招練習工具  | [立即查看](https://github.com/Rin2ec/ee-combo-helper)|
---

## 🧑‍💻 開發者

由 Rin 開發  
📺 [Twitch 頻道](https://twitch.tv/shiyu2615)  
💬 Discord: `rin_ovob`  
歡迎在 [Discord](https://discord.com/invite/rpnsScZWpr) 上的「📊伊伊經驗小幫手」回報問題或提供建議 🙌  

---
