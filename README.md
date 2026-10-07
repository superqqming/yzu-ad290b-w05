# AD290B W05 學生頁（四語）

元智大學 AD290B「設計製圖與 AI 表現法」第 5 週學生用單檔網頁。
每一頁都是**單一自包含 HTML**：不使用外部 CDN、第三方字型、分析碼、cookie、登入或表單，不蒐集任何資料。

## 兩個頁面

| 頁面 | 網址 | 內容 |
|---|---|---|
| 圖學基本知識速查表 | <https://superqqming.github.io/yzu-ad290b-w05/> | 製圖流程、第一角法／第三角法、線型與尺寸標註、交件前六項自查 |
| AI 平台比較 | <https://superqqming.github.io/yzu-ad290b-w05/ai-platform-comparison/> | 對話面／執行面／驗收面、三個平台生態、免費帳號決策路徑、Markdown 交接閉環、同一驗收門 |

### 四語深連結

兩頁都支援 `?lang=`，未知值會安全回到繁體中文：

- 繁體中文：`?lang=zh-Hant`
- English：`?lang=en`
- Bahasa Indonesia：`?lang=id`
- Tiếng Việt：`?lang=vi`

例：<https://superqqming.github.io/yzu-ad290b-w05/ai-platform-comparison/?lang=vi>

## 事實查核日期

AI 平台比較頁的平台事實**查核日期為 2026-10-07**，官方來源連結列在該頁頁尾。
可用功能會隨方案、帳號、地區、額度、學校管理設定與執行環境改變；頁面刻意不寫即時價格、模型名稱或用量數字。
**重新使用前請重新查核一次官方頁面，並同步更新頁尾的查核日期。**

圖學速查表頁不含平台事實，不受此查核日期影響。

## 更新方式

```bash
cd <這個 repo 的 checkout>
git pull
# 編輯 index.html 或 ai-platform-comparison/index.html
git add -A && git commit -m "更新內容" && git push
```

GitHub Pages 約 1–2 分鐘後更新。頁面若已嵌入課程協作平台，**嵌入端不需要再改**，推送後會自動顯示新版。

## 語言說明

繁體中文與英文為教師定稿內容。**印尼文與越南文是課堂翻譯稿**，專業術語仍以教師指定為準；兩種語言的頁尾都有對應聲明。
