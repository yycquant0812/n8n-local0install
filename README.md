# n8n 安裝與啟動流程（同學自行照做）

以下步驟以老師已經下載好的 Node.js MSI 安裝檔為前提，請依序執行：

1. **取得 Node.js 安裝檔**： Node.js MSI 檔，桌面分享檔案中。
2. **安裝 Node.js**：
   - 直接開啟 MSI 檔，一路按「下一步」完成安裝。
   - 安裝完成後重新開啟終端機或命令提示字元。
   - ![cmd](https://github.com/yycquant0812/n8n-local0install/blob/main/1.png)

3. **切換到下載資料夾**：在終端機執行：
   ```bash
   cd Downloads
   ```
4. **建立專案資料夾**：
   ```bash
   mkdir n8n && cd n8n
   ```
5. **全域安裝 n8n**：
   ```bash
   npm install n8n@latest -g
   ```
6. **啟動 n8n**：安裝完成後直接執行：
   ```bash
   n8n
   ```

7. **開啟管理介面**：瀏覽器輸入 `http://localhost:5678`，即可進入 n8n 的管理頁面進行設定。

完成以上步驟後，n8n 會在本機啟動，依照終端機提示即可開啟使用。

8. **安裝社群節點
讓我們實際安裝一個社群節點來體驗看看，「隨機寶可夢產生器」節點。

安裝步驟：

進入 Settings → Community Nodes
點擊橘色的「Install a community node」按鈕
在輸入框中輸入套件名稱：n8n-nodes-random-pokemon
勾選「I understand the risks」（了解風險）
點擊「Install」
