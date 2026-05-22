# TSV資料檔讀取程式

## 主要功能

本程式是一款專門用來讀取與解析 TSV 或純文字 (TXT) 格式的單字卡讀取軟體，使用者可載入包含單字、音標、音檔路徑與解釋的資料檔，介面採用客製化繪製的「藍色欄位標頭」與「白、淡藍灰交替」的條紋底色設計，提升大量資料的閱讀舒適度，底部狀態列會即時統計載入的單字數量，同時，程式內建「關於」視窗與「防呆關閉確認」機制。

## 使用方法
#### 1. 開啟資料檔案
程式啟動後會呈現乾淨的預設列表，點擊左上角選單「檔案(F)」底下的「開啟(O)」，系統會跳出「開啟檔案」的對話方塊，過濾條件預設為 .tsv 或 .txt 的文字檔案，選取單字資料檔（如 WordCards.txt）並點擊「開啟」

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/cc8a5221-98f5-42b9-b7ee-252e9a930f64" />
<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/20902d7a-f9d1-4e73-b29a-2d711151175e" />
<br>

#### 2. 瀏覽單字列表
檔案成功載入後，資料會自動填入「單字」、「音標」、「音檔路徑」與「解釋」欄位中，表格具備色彩交替的底色設計，有助於對齊閱讀每一列內容，左下角的狀態列也會同步更新，顯示目前共讀取了多少筆資料

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/a8fafe3c-1e37-4cb5-97ed-2f3dd2385f54" />
<br>

#### 3. 查看軟體版權資訊
需檢視系統版本、開發者資訊或版權聲明，可點擊上方選單的「幫助(H)」底下的「關於(A)」，系統會彈出「關於 TSV資料檔讀取」視窗

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/fec96912-cce5-4714-aa3f-4fe8140b16f8" />
<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/8bb0d9ef-8e48-4e49-b5bb-6e135131455a" />
<br>

#### 4. 安全結束程式
為防止使用者在瀏覽資料時誤觸關閉按鈕，系統加入了防護機制，點選右上角的「X」或從選單點擊離開時，畫面會彈出「確定要離開嗎？」的確認對話框，點選「是(Y)」系統才會真正結束運行，點選「否(N)」則會取消動作並回到單字列表

<img width="350" height="220" alt="螢幕擷取畫面 2026-05-22 221539" src="https://github.com/user-attachments/assets/a284d04f-5cb1-4c8e-b56a-355673e4c99b" />
<br>

#### 5. 快捷鍵操作功能
使用者同時按下鍵盤上的 Alt 鍵與介面文字後方括號內的對應英文字母（例如：按下 Alt + F 即可快速展開「檔案(F)」選單；按下 Alt + H 即可開啟「幫助(H)」選單），可省去滑鼠點擊的步驟，全程透過鍵盤快速操作

