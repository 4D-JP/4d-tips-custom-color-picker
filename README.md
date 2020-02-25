# 4d-tips-custom-color-picker

自作したカラーピッカーを表示する例題

### 概要

標準コマンドの``Select RGB color``や``OPEN COLOR PICKER``では都合が悪いときのために。

#### 4D Chart スタイル

<img width="225" alt="Screen Shot 2020-02-25 at 13 04 00" src="https://user-images.githubusercontent.com/10509075/75213994-5c809980-57cf-11ea-8ebb-177a87470548.png">

#### 使い方

```
$select:=Custom_color_picker ($param)
```

* ``param``オブジェクトのプロパティ

``color``: 4D Chartカラーインデックス  
``x``: グローバル座標（省略可）  
``y``: グローバル座標（省略可）  
``scale``: 画面サイズ（省略可）  

* ``select``オブジェクトのプロパティ

``accept``: 入力したかどうか  
``color.value``: カラー （整数）  
``color.rgb``: カラー （文字列） e.g. rgb(r,g,b)  
``color.color``: カラー （文字列） e.g. #rrggbb  
  
