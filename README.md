# Memory Matching Game

## 1.HTML結構
- 創建一個網頁標題為《翻牌遊戲》
- 在網頁中添加主要區塊，包含16個可點擊網格
- 在頁面顯示遊戲狀態信息

## 2.css模式
- 為所有元素字體設置為emogi
- 為網格設定灰色背景和點擊指示符
- 網格區塊居中顯示，每個網格項目均勻分佈

## 3.javascript的邏輯

初始化：
當每次重新開始遊戲emogi就會隨機翻牌

### 玩家操作
- 如果你點擊emo兩個相同就會停止翻轉
- 如果你點擊emo兩個不相同就會翻轉

### 檢查獲勝者
- 當所有emo不再反轉就勝利。

### 遊戲結束
- 當所有網格內的全部emogi高於50分就會結束並宣布你好厲害
- 當所有網格內的全部emogi低於50分就會結束宣布再接再厲

### 進階功能
設置一個計時得分追蹤器
- 設置分數為0～100
- 當在10秒內所有emogi不在翻轉就100分
- 當在10～20秒所有emogi不再翻轉就80分
- 當在20～30秒所有emogi不再翻轉就60分
- 當在30～40秒所有emogi不再翻轉就40分
- 當在40～50秒所有emogi不再翻轉就20分
- 當在50秒所有emogi不再翻轉就0分
設置翻牌音效
- 當兩個相同的牌不再翻轉就會說good
- 當兩個不同的牌翻轉後就會是說oooh


  




 

