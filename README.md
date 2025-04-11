## 🌍 WorldWise
> 一個一頁式應用程式(SPA)，結合動態地圖與數據管理功能，用戶可以視覺化並操作地理資訊，適合地理記錄和探索。📌
### 🌟 功能介紹

- 動態地圖互動: 點擊地圖任意位置新增 Pin，記錄地理資訊、建立時間與說明文字。
- Pin 列表紀錄: 提供完整 Pin 資料的列表視圖，可快速瀏覽與管理已建立的地點。
- 地點跳轉功能: 點擊列表中的資料，地圖自動移動到相應位置。
- 模擬登入系統: 假登入功能，用於模擬用戶認證並限制部分功能。
  
<br>

![image](https://github.com/user-attachments/assets/555b4512-7855-400e-b317-14f4223de2c6)
![image](https://github.com/user-attachments/assets/b46ea7bf-a4ef-41ad-a038-3387aa77a6a2)




<br>

### 🛠技術棧

- **前端框架**: React 18 + Vite
- **地圖工具**: Leaflet + React-Leaflet
- **地理定位 API**: Geolocation API
- **模擬 API**:  JSON Server
- **日期選擇器**: React Datepicker
- **狀態管理**: Context API + Reducer
- **樣式**: Modular CSS
<br>

### 💻 安裝與啟動

1. clone 此專案：

```bash
git clone https://github.com/VOxOVb/worldwise.git
```

2. 安裝依賴:

```bash
 npm install
```

3. 啟動開發伺服器：

```bash
npm run dev
```
4. 啟動 JSON 模擬伺服器（供測試 API 使用）：
```bash
npm run server
```
5. 開啟瀏覽器並訪問：

```bash
http://localhost:5173
```

<br>

### 🔮 未來計劃
- 增加 Pin 的圖片上傳與編輯功能。
- 將 JSON Server 替換為實際後端 API。
- 第三方登入驗證
