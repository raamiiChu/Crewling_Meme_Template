# Crewling_Meme_Template - 用 selenium 爬取迷因模板  
- 網址：https://imgflip.com/memetemplates  
- 可以用無頭模式執行（要將相關程式碼取消註解）  
- 爬蟲結果放在 meme_templates 資料夾  
- 共爬取 5 頁，186 個圖檔  

# Update_Firebase - 上傳至 firebase  
- 格式如下：
![image](https://github.com/raamiiChu/crewling_meme_template/assets/87169493/f31a0997-94a1-47c5-adb3-f791035ee858)


```
{"A train hitting a school bus": 
  {'canvas_size': {'height': 590, 'width': 500},
  'num_of_textareas': 2,
  'positions': [None, {'x': 0.6, 'y': 0.25}, {'x': 0.29, 'y': 0.71}],
  'source_path': 'meme_template/A train hitting a school bus.png',
  'url': 'https://imgflip.com/memegenerator/247113703/A-train-hitting-a-school-bus'},
 ......
 }
```
- canvas_size：圖片大小  
- num_of_textareas：幾個文本區塊  
- positions：各個文本區塊的 "中心座標"（None 的部分不用理會）  
- source_path：模板圖檔在資料庫的位置  
- url：模板網址  

# Meme_Generator - 用 selenium 製作迷因  
- 爬蟲結果放在 result_pictures 資料夾 
- 可以用無頭模式執行（要將相關程式碼取消註解）  
