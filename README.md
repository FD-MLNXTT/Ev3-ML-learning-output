# 當舊機器人撞上機器學習 成果展示
---

## KNN模型
訓練好的模型放在 [model](/model/) 資料夾

可利用 `Python` 的 `pickle` 套件讀取

```python
pickle.load(open('knn_model', 'rb'))
```

## 訓練用資料
訓練用資料放在 [trainning_data](/trainning_data/) 資料夾

## 預測用資料
預測用資料放在 [predict_data](/predict_data/) 資料夾

總共有兩組資料


## 資料與模型處理依據

### KNN鄰居個數
![plot_1](/asset/Plot_1.png)

### 資料處理-平均數或中位數的取用
![plot_2](/asset/Plot_2.png)


## 預測結果

## data_1
| 實際數字 | 預測結果 |
|---------|---------|
|    0    |    1    |
|    1    |    0    |
|    2    |    2    |
|    3    |    0    |
|    4    |    1    |
|    5    |    5    |
|    6    |    5    |
|    7    |    1    |
|    8    |    2    |
|    9    |    4    |


## data_2
| 實際數字 | 預測結果 |
|---------|---------|
|    0    |    8    |
|    1    |    2    |
|    2    |    2    |
|    3    |    1    |
|    4    |    1    |
|    5    |    4    |
|    6    |    5    |
|    7    |    0    |
|    8    |    8    |
|    9    |    2    |