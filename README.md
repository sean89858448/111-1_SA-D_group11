# 111-1_SA-D_group11  

---  

### 組員名單：  

| 職位 | 學號 | 名字 | 任務 |
| :--: | :--: | :--: | :---: |
| **組長** | C109118254 |[羅睿宸](https://github.com/c109118254/noco) | 任務規劃與分配 |
| 組員 | C109118219 | [夏辰旭](https://github.com/sean89858448/SA-D) | 硬體開發 |
| 組員 | C109118210 | [王昱仁]() | 後端系統開發 |
| 組員 | C109118249 | [戴御軒](https://github.com/BEnser16/2022-3B.git) | 前端系統開發 |
| 組員 | C109118263 | [秦玟康](https://github.com/Wenkang99/C109118263) | 撰寫使用者手冊 |


---

## 專題題目： **智慧倉儲**
## 內容 : 透過室內定位尋找設備位置：
    1.UWB定位功能開發並建立座標。
    2.獲取Beacon定位位置。
    3.設計標籤系統，標記設備編號、時間、地點。
    4.資料自動上傳至遠端監控平台。

---

+ ### 任務清單
    
    | **步驟** | **說明** | **需時天數** | **前置步驟** |
    | :---: | :---: | :---: | :---: |
    | 1 | 擬定計畫 | 2 | - |
    |  2 | 任務分配 | 1 | 1 |
    |  3 | 評估可行性 | 20 | 2 |
    |  4 | 硬體設計與開發 | 20 | 2 |
    |  5 | 程式開發(前、後端) | 20 | 2 |
    |  6 | 程式測試(前、後端) | 10 | 3、4 |
    |  7 | 撰寫使用手冊 | 7 | 5 |
    |  8 | 系統整合 | 7 | 5 |
    |  9 | 系統測試 | 7 | 6 |
    | 10 | 使用者訓練 | 7 | 6 |
    | 11 | 使用者測試 | 7 | 8 |
   
  
  
**(1)PERT/CPM圖**
---
[PERT/CPM](https://hackmd.io/@wwXnxhdVTL6v14eGTSBJdg/BJaUE69Qs)
![PERT](PERT.jpg "PERT")
  
---
  
```mermaid
gantt
    title 甘特圖

    

    section 1.擬定計畫
    4       :a1,2022-10-11, 4d
   
    section 2.任務分配
    2       :a2, after a1  , 2d
    
    section 3.評估可行性
    10      :a3, after a1 , 10d
    
    section 4.硬體設計與開發
    25      :a4, after a2  , 25d
    
    section 5.程式開發(前、後端)
    5      :a5, after a3  , 5d
    
    section 6.程式測試(前、後端)
    12      :a6, after a5  , 12d
    
    section 7.撰寫使用手冊
    8      :a7, after a8  , 8d
    
    section 8.系統整合
    2      :a8, after a4  , 2d
    
    section 9.系統測試
    15      :a9, after a8  , 15d
    
    section 10.使用者訓練
    20      :a10, after a8  , 20d
    
    section 11.使用者測試
    25      :a11, after a7  , 25d
   
```

## WEEK6小組作業: 

## 功能性需求與非功能性需求
  
### 功能性需求
  1. 室內定位技術。
  2. Beacon位置。
  3. 標籤系統。
  4. 遠端監控平台。
  
### 非功能性需求
    1. 反應性: 提供監控人員隨時查詢資料
    2. 使用性: 標籤系統連結建築物室內架構
    3. 效能:   同步上傳定位位置至監控平台

# 功能分解表

  ![FDD](https://user-images.githubusercontent.com/113968282/197533557-36733d9f-87ee-447-9b53-8f43afa965.png)



# 需求分析文字描述
## 一個智慧倉儲系統的需求分析簡述如下 : 
1.管理者
2.管理者
3.工廠人員
4.工廠人員
5.
6.

# 案例圖及案例說明
## 案例圖

   ![USE CASE1](https://user-images.githubusercontent.com/73731793/197538691-6e00998d-05a1-435b-b406-ba2691dac2.png)
   
   ![USE CASE2](https://user-images.githubusercontent.com/73731793/197538691-6e00998d-05a1-435b-b406-ba2691dac2.png)
   
   ![USE CASE3](https://user-images.githubusercontent.com/73731793/197538691-6e00998d-05a1-435b-b406-ba2691dac2.png)


# Figma
  *  [Figma網址](https://www.figma.com/file/sNYb4JDbAHiJrGlYwz0DTv/%E5%AF%B5%E7%89%A9%E5%8D%94%EB1?node-id=0%3A1)

## WEEK7小組作業: 請各組新增 以下兩項工作
1.繪出系統環境圖 (DFD)

2.繪製DFD 圖0 (須至少有三項以上的程序)

---
### 繪出系統環境圖 (DFD)

---
### 繪製DFD圖0 (須至少有三項以上的程序)

