# unity-ugug


紀錄

將別人的sample copy來試做

★變動項目 ●有新功能尚未查詢

Image   (原先就有) 

    ★1.Source Image 圖片來源
	
		點擊⊙，會將所有Sprite(2D and UI)的檔案列出來讓你使用

	2.Color 是圖像的顏色，可以調節色度、明暗、透明度

	3.Material(紋理)，通常none是沒有紋理

	4.Image type
	
			Simple  預設是Simple，會延伸到RectTransform的大小
			
			Sliced  (切片)：將圖片切成9等份；會多出一個fill center選項可以填充中心
			
			Tiled	Tiled(磁磚)：則會重複顯示圖片像是磁磚一樣
			
     	   ●Filled  Filled(填滿)：則會將圖片填滿整個image物件                
					fill method(填充法)跟origin(填充原點)，
					Fill Amount則是填充的量，Clockwise則是順時鐘，類似車速表
					
			Preserve Aspect：保留長寬比，勾選的話，調整大小按鈕會保留比例
			
			Set Native Size：則是設定原始來源大小
	
	

Button  (原先就有)
	
	1.Transition
	
			none         : 不會有任何變換效果
			
			color tint   : 顏色模式，點擊時顏色的變化
			
			sprite swap  : 這個可以透過不同的sprite來呈現不同狀態，sprite通常是做為圖片型態的按鈕
			
		   ★Animation    : 這個模式則是透握大量的動畫來呈現按鈕不同的效果
			
	2.Navigation  (導航，指引)
			
		   ★Automatic    : 自動生成
			
			Explicit     : 指定按下鍵盤 “上”、”下”、”左”、”右” 要選取哪一個物件
			
	3.Onclick()右下角+號新增項目
	
	★editor and runtime     Function 
	
	你要加入的元件或腳本 	外加function 要先Add Component,要不然無法找到
	
	
Audio Source  (需要新增[Add Component]) 

實際講解

Animator      (需要新增[Add Component]) 

實際講解

