# 第一屆 深度學習與電腦視覺馬拉松
<br>
<br>


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
<br> 
<br>  
  
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

### Day14 - [CNN分類器架構：Batch Normalization](./Day014_BatchNormalization)
- 理解 Batch Normalization 原理
- Batch Normalization 用來解決什麼問題

### Day15 - [訓練一個CNN分類器：Cifar10為例](./Day015_Cifar)
- 如何運⽤用前幾章概念？
- 如何建造一個CNN分類器？

### Day16 - [如何使用Data Augmentation](./Day016_Image%20Augmentation)
- 了解圖像增強的意義
- 了解如何使用 Keras 做 Image Augmentation
- 了解如何使用 Imgaug

### Day17&18 - [AlexNet & VGG](./Day017-018_VGG16)
- 了解Imagenet中CNN框架的演進
- 了解AlexNet、Vgg的優勢

### Day19 - [InceptionV1-V3](./Day019_Inception)
- 了解InceptionV1-V3的演進

### Day20 - [ResNetV1-V2、InceptionV4、Inception-ResNet](./Day020_Classic%20CNN-ResNet_InceptionV4_Inception-ResNet)
- 了解ResNet中殘差網路的概念
- 了解如何導入殘差網路於Inception Block 中

### Day21 - [Transfer learning](./Day021_Transfer%20Learning)
- 了解 Transfer Learning 的優勢
- 了解如何使用 Keras 做Transfer Learning

### Day22 - [Breaking Captchas with a CNN](./Day022_Captcha)
- 了解如何應用 CNN 在驗證碼識別
<br>
<br>

## Day23~41 - [CNN 應用案例學習](./Handout)

### Day23 - [Object detection原理](./Handout)
- Object Detection 用來解決怎麼樣的問題
- 如何設計 Object Detection 的 Loss
- One Stage 與 Two Stage 的差異

### Day24 - [Object detection基本介紹、演進](./Handout)
- 了解 Object Detection 的發展與各個模型的基本概念

### Day25 - [Region Proposal、IOU概念](./Day025_IOU)
- 了解 Intersection-over-union ( IOU ) 的原理與運用
- 如何計算 Intersection-over-union ( IOU ) 

### Day26 - [RPN架構介紹](./Day026_RPN)
- 了解Faster R-CNN 中的Region proposal network (RPN)結構

### Day27 - [Bounding Box Regression原理](./Day027_BBOX%20Regression)
- 如何設計 Bounding Box Loss Function
- 了解 Bounding Box Regression 的原理

### Day28 - [Non-Maximum Suppression (NMS)原理](./Day028_NMS)
- 為什麼我們需要Non-Maximum Suppression (NMS)？
- 不使⽤NMS會有什什麼影響？
- NMS具體是如何運作的？

### Day29-31 - [程式導讀、實作](./Day029-031_SSD%26RetinaNet)
- 了解 SSD 中每⼀個步驟
- 結合前幾章所學知識(IOU、Default BBOX、BBOX回歸、NMS )

### Day32 - [YOLO 簡介及算法理解](./Day032_YOLO_Prediction)
- 了解 YOLO 基本框架
- YOLO 如何做到直接預測 bounding box 及其類別

### Day33 - [YOLO 細節理解 - 網路輸出的後處理](./Day033_YOLO_Post-processing)
- YOLO 輸出層轉換成 bbox 資訊的過程
- NMS 在 YOLO 的實際運作
- NMS 在 YOLO 中採用的信心度為何

### Day34 - [YOLO 細節理解 - 損失函數](./Day034_YOLO_Loss%20Function)
- 定義什麼是損失函數
- YOLOv1 損失函數的設計架構
- YOLOv1 損失函數超參數的定義

### Day35 - [YOLO 細節理解 - 損失函數程式碼解讀](./Day035_YOLO_Loss_Code)
- 了解YOLO損失函數中每⼀個步驟

### Day36 - [YOLO 細節理解 - 網路架構](./Day036_YOLO_Network)
- 了解 YOLO 網絡架構的設計與原理

### Day37 - [YOLO 細節理解 - 網路架構程式碼解讀](./Day037_YOLO_Network_Code)
- 了解YOLOv1網絡架構的每一個步驟

### Day38 - [YOLO 演進](./Handout/Day38.pdf)
- 了解 YOLO 改進的思路
- YOLO 的優缺點及其極限

### Day39 - [使用 YOLOv3 偵測圖片及影片中的物件](./Day039_YOLO_Keras_Code)
- 了解本課程推薦的 YOLOv3 程式碼使用方式
- 使用 YOLOv3 偵測圖片及影片中的物件

### Day40 - [更快的檢測模型 - tiny YOLOv3](./Day040_YOLO_Tiny_Code)
- 如何評估檢測模型的執行速度
- 如何調用 tiny YOLOv3

### Day41 - [訓練 YOLOv3](./Day041_YOLO_Train)
- 如何訓練基於 VOC 資料集的檢測模型
- 如何使用開源的深度學習程式碼
<br>
<br>

## Day42~48 - [電腦視覺深度學習實戰](./Handout)

### Day42 - [人臉關鍵點-資料結構簡介](./Day042_Facial_Keypoint)
- Kaggle 臉部關鍵點資料結構

### Day43 - [人臉關鍵點-檢測網路架構](./Day043_Define_Network)
- 如何定義人臉關鍵點檢測相關的網路

### Day44 - [訓練人臉關鍵點檢測網路](./Day044_Train_Facial_Keypoint)
- 如何用 keras 訓練人臉關鍵點檢測點網路
- 如何通過左右翻轉增加訓練資料集

### Day45 - [人臉關鍵點應用](./Day045_Facial_Keypoint_Application)
- 如何應用人臉關鍵點的檢測結果來做人臉濾鏡

### Day46 - [Mobilenet](./Day046_MobileNet)
- 認識輕量化模型的方法
- MobileNet 架構設計 (Separable Convolution)

### Day47 - [Mobilenetv2](./Day047_MobileNetv2)
- MobileNet v2 核心思想
- Linear bottleneck
- Inverted residual block

### Day48 - [Tensorflow Object Detection API](./Day048_Tensorflow_object_detection_api_installation)
- Tensorflow Object Detection API 使用方式
- 如何⽤用來來做 training

## Day49~50 - [期末專題](./Handout)
### Day49~50 - [期末專題 - Raccoon & Kangaroo Detection浣熊與袋鼠辨識](https://www.cupoy.com/clubnews/ai_tw/0000016E62FABB7A000000016375706F795F72656C656173654B5741535354434C5542/0000017053CA3A7C0000002F6375706F795F72656C656173654B5741535354434C55424E455753)
