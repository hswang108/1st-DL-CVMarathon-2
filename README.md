# 第一屆 深度學習與電腦視覺馬拉松




## Day01~10 - [基本影像處理](./Handout)

### Day01 - [OpenCV簡介 + 顯示圖片](./Day001_Read%20Image)
- 如何開始使用 OpenCV
- 如何透過 OpenCV 讀取圖片

### Day02 - [Color Presentation 介紹(RGB, LAB, HSV)](./Day002_Color%20Space)
- Color presentation 的概念
- 各種 Color presentation 表現的差異

### Day03 - [顏色相關的預處理(改變亮度, 色差)](./Day003_Histogram%20Equalization)
- Color space 的轉換與改圖的相關操作
- Histogram equalization 的概念

### Day04 - [ 以圖片為例作矩陣操作 (翻轉, 縮放, 平移)](./Day004_Geometric%20Transform)
- 翻轉與縮放的操作
- Transformation 的概念與平移操作

### Day05 - [透過 OpenCV 做圖並顯示 (長方形, 圓形, 直線, 填色)](./Day005_Draw)
- 熟悉透過 OpenCV 來畫圖的過程

### Day06 - [Affine Transformation 概念與實作](./Day006_Affine)
- 仿射變換包含的重要特性與概念
- 以旋轉變換為例了解仿射變換矩陣的設計

### Day07 - [Perspective Transformation 概念與實作](./Day007_Perspective)
- 進一步了解齊次座標與轉換矩陣的細節與概念
- 透視變換的概念

### Day08 - [Filter 操作 (Sobel edge detect, Gaussian Blur)](./Day008_Sobel%20Gaussian%20Blur)
- 了解 Filter 的基本操作與其他影響最後結果的因素
- 了解模糊圖片跟邊緣偵測的概念與操作

### Day09 - [SIFT 介紹與實作 (feature extractor)](./Day009_SIFT)
- 了解 SIFT 是基於甚麼觀念進行改進
- 了解 SIFT 演算法的物理意義

### Day10 - [SIFT 其他應用 (keypoint matching)](./Day010_SIFT%20Application)
- 了解圖片抽取特徵後的泛用性
- 了解如何透過特徵去配對
  * 透過距離來判斷特徵的相似程度
  * 配對演算法
  
  
  
## Day11~22 - [電腦視覺深度學習基礎](./Handout)

### Day11 - [CNN分類器架構：卷積層](./Day011_CNN-Convolution)
- 卷積神經網路 (CNN) 能用來解決怎樣的問題?
- 全連接神經網路與卷積神經網路 (CNN) 的差異?
- 卷積神經網路 (CNN) 的原理與優勢

### Day12 - [CNN分類器架構：步長、填充](./Day012_CNN-Strides%20%26%20Padding)
- 步長( Strides )與填充( Padding )的原理
- 如何透過步長( Strides )與填充( Padding) 控制卷積大小
- 輸出 Feature map 大小的計算

### Day13 - [CNN分類器架構：池化層、全連接層](./Day013_Pooling%20%26%20FC%20Layer)
- 池化 ( Pooling ) 的原理
- 池化的方式與優缺點
- 為何 CNN 需要連結全連接層？
