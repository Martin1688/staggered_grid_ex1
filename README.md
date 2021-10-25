# staggered_grid_ex1
Practice for A customization of gridview is the StaggeredGridView, a version that renders staggered grid.
This type of widget seems more suitable to some type of apps,
especially those that list movies or products, as usually the images or even the descriptions of such items tend to be of different lengths.

StaggeredGridView最重要的特性是產生橫向及縱向大小不一樣的表格

1.	crossAxisCount: 4是指欄位的數量4表示有4個欄位
2.	crossAxisSpacing: 10 欄與欄的間隔
3.	mainAxisSpacing: 12,//列與列的間隔
4.	itemCount:項目總數，即格子(cell)的總數量
5.	StaggeredTile.count用來設定table的rowspan及columnspan，
    	例如StaggeredTile.count(1, 1.2)，表示此cell寬度佔1個欄位的寬度(rowspan=1)，高度佔1.2個欄位的寬度(columnspan=1.2)，
    	StaggeredTile.count(1, 1.8) ，表示此cell寬度佔1個欄位的寬度(rowspan=1)，高度佔1.8個欄位的寬度(columnspan=1.8)。
    	StaggeredTile.count(2, 1) ，表示此cell寬度佔2個欄位的寬度(rowspan=2)，高度佔1個欄位的寬度(columnspan=1)。

6.	itemBuilder用於建立格子(cell)的實際內容，在本例子是圖片。


