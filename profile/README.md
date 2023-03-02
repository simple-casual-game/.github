# simple casual game 簡單線上博奕遊戲 - by Josh Tsai

這是一個使用tcp連線的博奕遊戲伺服器，用來練習tcp連線遊戲伺服器的開發。
可以在這個系統中開發多個遊戲，目前僅開發第一個遊戲翻硬幣(flip coin)

### 簡介
本系統為用來練習`tcp`的side project，程式由Josh獨立開發完成，目前僅剛開始開發後端部份。

### 遊戲

simple casual game 包含以下遊戲：

* `flip coin` 翻硬幣遊戲，遊戲規則為翻硬幣，有50%機率贏或輸，贏的話獲得2倍賭注，輸的話就歸零。

### 伺服器架構

simple casual game 系統預計有以下伺服器：

* `game` 遊戲伺服器，處理遊戲邏輯
	- 目前僅完成`flip coin`
* `gate` 統一對外開放tcp連線，供前端連接
	- （未完成）
* `center` 集中管理各個伺服器
	- （尚未開發）
* `management` 提供後台管理api去讓後台人員管控各個遊戲
	- （尚未開發）

---

## 開發者
以上程式開發來自 [Josh](https://github.com/lisyaoran51)

