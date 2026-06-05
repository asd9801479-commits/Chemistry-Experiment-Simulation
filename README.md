# 酸鹼滴定模擬器 Chemical Titration Simulator

一款免費的化學酸鹼滴定模擬器，使用 Unity（WebGL）開發。透過互動式操作，把抽象的中和反應與滴定曲線變得「看得見、調得動」，降低化學學習的門檻。

## 線上試玩

無須安裝，用瀏覽器直接開啟即可：

**https://asd9801479-commits.github.io/Chemistry-Experiment-Simulation/**

> 首次載入需要數秒，請等進度條跑完，看到短暫空白是正常現象。

## 簡介

This is a free chemistry experiment simulator I built on my own. I made it because chemistry felt too abstract to me, and I wanted something that lowers the learning curve. Since I don't know any programming languages, I created this simple simulator with the help of Claude AI for now. Feedback from users is very welcome!

本模擬器為畢業專題作品，目的是以視覺化、可互動的方式呈現酸鹼滴定實驗，讓學習者更直覺地理解 pH 變化與當量點。歡迎任何使用回饋。

## 功能特色

- **即時滴定曲線**：一邊加液、一邊繪製「pH 對加入體積」的變化曲線，並標示當量點位置。
- **滴定管與燒杯動態繪製**：含刻度、活栓與液面升降，溶液會隨 pH 變化呈現漸層變色。
- **長按快速加液**：按住加液按鈕即可連續快速加入，省去反覆點擊。
- **引導教學**：首次進入提供 5 步驟操作引導。
- **終點提示與結果摘要**：接近終點時給予提示，實驗完成後彈出結果摘要面板。

## 操作說明

| 操作 | 說明 |
| --- | --- |
| `+1.0 mL` / `+0.1 mL` | 增加鹼液體積（粗調 / 微調） |
| `-1.0 mL` / `-0.1 mL` | 減少鹼液體積 |
| 長按按鈕 | 連續快速加 / 減液 |
| 體積滑桿 | 直接拖曳調整加入的體積 |
| `重新實驗` | 將實驗歸零，重新開始 |
| pH 值 / 已加入體積 | 即時顯示目前的 pH 與已加入的鹼液量 |

## 實驗原理

燒杯中裝有**鹽酸（HCl）**溶液，透過滴定管逐滴加入**氫氧化鈉（NaOH）**進行中和。兩者皆為強酸／強鹼，反應式為：

```
HCl + NaOH → NaCl + H₂O
```

- 酸、鹼濃度均設定為 **0.1 M**。
- 一開始溶液呈酸性，pH 偏低；隨著鹼液加入，pH 緩慢上升。
- 接近**當量點**（酸與鹼恰好完全中和）時，pH 會在很小的體積範圍內**急遽跳升**——這是滴定曲線最關鍵的特徵。
- 通過當量點後繼續加鹼，溶液轉為鹼性，pH 逐漸趨近鹼液本身。

透過親手調整加入量、觀察曲線的「平緩 → 陡升 → 再平緩」，可以直覺理解為什麼滴定終點要抓得這麼精準。

## 開發資訊

- **引擎**：Unity 2022.3.62f3
- **平台**：WebGL
- **協助工具**：本專案由作者獨立發想與設計，並在 Claude AI 的協助下完成程式撰寫。

## 作者與授權

- **作者**：陳文昌 B0214634 中國文化大學-化學系
- **完成日期**：2026/6/5
- **授權**：本專案採用 MIT 授權，歡迎自由使用與修改，使用時請保留出處標示。
