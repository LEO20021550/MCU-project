---
layout: post
title: Innovative project proposal
author: [Leo Lee]
category: [Lecture]
tags: [jekyll, ai]
---

This homework is to specify a Future Home application and describe the key features, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
## Futre Home Applications
### Homework Report
**Contents:**<br>
* **應用與功能說明**
  - Specify the future home application, and Describe the key features
  - Describe the key features which may be applied to the home space (kitchen, living room, play room, study room, bed room)
* **設計考量與所需相關技術**
  - List all design considerations and the required technologies
* **系統方塊圖**
  - Draw a System Block Diagram
## 料理機器人
### 應用功能說明
1. 操作廚具：咖啡機＋果汁機＋烤麵包機＋微波爐+烤箱+氣炸鍋
2. 存取冰箱：辨識食物, 存放食材，或取出食材, 送至廚具

### 設計考量與相關技術
**系統設計考量：**<br>
1. 操作方式:垂直升降式手臂 or 懸吊式手臂
2. 移動方式:兩輪 or 滑軌懸吊
3. 供電方式:鋰電池
4. 聯網方式:WiFi或BT to 手機

**所需相關技術：**
1. 滑軌式機器手臂 ＆ 軟式夾具
2. 食物辨識分類：Jetson-Nano + IMX219
3. 電子鼻：氣味感測與辨識 MQ2

### 系統方塊圖
![](https://github.com/rkuo2000/MCU-course/blob/main/images/FutureHome_kitchen_robot.png?raw=true)

### Subject:智能衣櫃
### Key features:
連接手機搜尋今日想要怎樣的穿搭，並搭配當日要來往地方的天氣預報做出適合的搭配，並且依據每個人的需求可以設定固定的套件1（工作）、套件2（出遊）…等等。

### Design consideration:
衣櫃的空間大小可能會是個問題，因為想到的方法是衣服放置固定的位置，然後依據所需要的搭配亮出指定的數字，這樣一來衣櫃裡的空間可能就不能塞很滿了。

### Required tchnologies:
因此，考慮改良後的智能衣櫃可能是用顏色辨識感應器來去辨識各種衣服，然後搭配一個在衣櫃門外的螢幕來顯示搭配出的衣服，還需要一個輸入端去連結Google資料庫搜索各地天氣預報以及潮流搭配等等的選擇。

### System Block Diagram:


<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


