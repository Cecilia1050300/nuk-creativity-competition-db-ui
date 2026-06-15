# 🏆 國立高雄大學激發學生創意競賽管理系統 (NUK Creativity Competition Management System)

本專案為**資料庫系統課程的期末專題作業**。旨在為學校舉辦的「激發學生創意競賽」設計一套完整的管理系統前端使用者介面（Frontend UI）。雖然本專案目前為純前端實作，但整體的頁面架構與欄位規劃皆嚴格對應後端關聯式資料庫（Relational Database）的資料表實體（Entities）關係。

---

## 🛠️ 技術棧與資源來源
- **網頁外殼與樣式**: 基於 [HTML5 UP](https://html5up.net/) 的免費響應式網頁模板（Forty）進行二次開發與內容改裝。
- **前端技術**: HTML5, CSS3 (SASS/SCSS), JavaScript (jQuery)。
- **架構設計**: 依循關聯式資料庫管理系統 (RDBMS) 的資料表邏輯進行子系統網頁切割。

---

## 📁 系統架構與資料庫實體規劃 (System Subsystems)

本系統依據競賽的核心業務邏輯，劃分為以下五大管理子系統，每個子系統皆對應資料庫中的主要資料表：

1. **User 管理子系統 (`User.html`)**
   - *資料庫對應*: 使用者/人員資料表 (Users Table)。
   - *功能*: 管理競賽參與人員、指導老師、評審委員及系統管理員的基本帳號與權限。

2. **Teams 管理子系統 (`Team.html`)**
   - *資料庫對應*: 參賽隊伍資料表 (Teams Table)。
   - *功能*: 處理參賽隊伍建立、隊員組成、隊伍編號與隊長關聯之資料維護。

3. **Project 管理子系統 (`Project.html`)**
   - *資料庫對應*: 參賽作品/專案資料表 (Projects Table)。
   - *功能*: 管理各隊伍提交的創意作品名稱、摘要、企劃書與所屬分類。

4. **Announcement 管理子系統 (`Announcement.html`)**
   - *資料庫對應*: 系統公告資料表 (Announcements Table)。
   - *功能*: 提供競賽最新消息、重要日程發布與維護的管理介面。

5. **Score 管理子系統 (`Score.html`)**
   - *資料庫對應*: 評分紀錄/成績資料表 (Scores Table)。
   - *功能*: 供評審委員針對各組 Project 進行評分、加權與名次結算之欄位展示。

---

## 🚀 快速啟動與線上預覽

### 本地執行
由於本專案為純前端（靜態網頁），無需安裝任何後端環境或套件：
1. 將本專案下載/Clone 到本地端。
2. 雙擊點開專案根目錄下的 `index.html`，即可直接在瀏覽器中開啟並操作管理系統介面。

### 🌐 線上展示 (GitHub Pages)
本專案已啟用 GitHub Pages。您可以直接透過以下網址進行線上預覽：
`https://<您的GitHub帳號>.github.io/nuk-creativity-competition-db-ui/`
*(備註：請在推上 GitHub 後，至 Repo Settings -> Pages 開啟 main 分支即可獲得專屬網址！)*
