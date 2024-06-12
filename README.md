# Mood-based music recommender

* CNN model訓練臉部表情辨識模型
* Gaussian mixture model做音樂種類分類

> 在用Gussian mixture model之前，最一開始用的是K-means Clustering，再來是用Hierarchical clustering(HAC分類)。依分類結果來看，由好到壞的方法依序是:`Gussian -> K-means -> HAC`。故最後選擇用Guassian的結果來執行

## Guide

### part of emotion identification

### part of music classification
* download `chromedriver`
    * 下載完以後要根據自己本地的chromedriver路徑更改程式
    * 不想修改程式的話就是把chromedriver.exe放在根源程式同一個資料夾中
* `pip install selenium` 
    * 自動化 web 瀏覽器的工具

> 原本要接spotify API但spotipy這個套件一直使用失敗，所以就換成直接打開youtube頁面並寫腳本自動搜尋歌曲