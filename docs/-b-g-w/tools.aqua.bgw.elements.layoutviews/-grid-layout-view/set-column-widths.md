//[BGW](../../../index.md)/[tools.aqua.bgw.elements.layoutviews](../index.md)/[GridLayoutView](index.md)/[setColumnWidths](set-column-widths.md)



# setColumnWidths  
[jvm]  
Content  
fun [setColumnWidths](set-column-widths.md)(columnWidths: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html))  
More info  


Manually set column width of all columns. Overrides automatic resizing based on content from this column.



## See also  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setColumnWidths/#kotlin.DoubleArray/PointingToDeclaration/"></a>[tools.aqua.bgw.elements.layoutviews.GridLayoutView](set-auto-column-widths.md)| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setColumnWidths/#kotlin.DoubleArray/PointingToDeclaration/"></a>|
  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setColumnWidths/#kotlin.DoubleArray/PointingToDeclaration/"></a>columnWidths| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setColumnWidths/#kotlin.DoubleArray/PointingToDeclaration/"></a><br><br>New column widths. Array index 0 get applied for the first column etc. Use COLUMN_WIDTH_AUTO to restore automatic resizing behaviour.<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setColumnWidths/#kotlin.DoubleArray/PointingToDeclaration/"></a>[kotlin.IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html)| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setColumnWidths/#kotlin.DoubleArray/PointingToDeclaration/"></a><br><br>Thrown if Array size does not match column count or values were negative.<br><br>|
  



