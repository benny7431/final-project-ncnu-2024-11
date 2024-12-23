
# NCNU FPGA 
## 作者
- 112321020
- 112321017

---

## 輸入與輸出設備
1. **8x8 LED 矩陣**
   - 遊戲畫面會顯示在這個矩陣上，例如蛇的位置、牆壁或其他物件。
   - **圖片連結**: [8x8 LED 矩陣](https://github.com/fanboys2077/-final_project/blob/main/messageImage_1704354014732.jpg)

2. **七段顯示器**
   - 顯示玩家當前的遊戲分數。
   - **圖片連結**: [七段顯示器](https://github.com/fanboys2077/-final_project/blob/main/messageImage_1704354149012.jpg)

3. **指撥開關**
   - 用來控制遊戲的開始或重置。
     - `0`：開始遊戲
     - `1`：重置遊戲
   - **圖片連結**: [指撥開關](https://github.com/fanboys2077/-final_project/blob/main/messageImage_1704354034458.jpg)

4. **S1, S2, S3, S4 按鈕**
   - 藉由按鈕控制蛇的移動方向：
     - S1: 上移
     - S2: 下移
     - S3: 左移
     - S4: 右移
   - **圖片連結**: [方向按鈕](https://github.com/fanboys2077/-final_project/blob/main/messageImage_1704354088854.jpg)

---

## 功能介紹
1. **基本玩法**
   - 使用 FPGA 板上的按鈕（S1, S2, S3, S4）控制貪吃蛇移動。
   - 吃到目標物時，玩家的分數會隨之增加。

2. **特色功能**
   - **當分數達到 6 分時**：貪吃蛇的顏色會改變。
   - **當分數達到 8 分時**：玩家贏得遊戲。
   - **失敗條件**：貪吃蛇若撞到牆壁或自身，則遊戲結束。

3. **操作流程**
   - 撥動指撥開關開始遊戲。
   - 按下相應按鈕控制貪吃蛇移動，直到達成目標分數或失敗。

---

## Demo 影片
- [觀看遊戲操作影片](https://drive.google.com/file/d/1KHvB2gRJ43BFWeeUhImK6txOQVaZR8Ek/view?usp=sharing)

影片展示遊戲的實際運行情形，包括貪吃蛇的移動方式、得分效果、顏色變化以及勝利或失敗的畫面。

---
