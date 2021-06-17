---
title: setRowHeights -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.elements.layoutviews](../index.md)/[GridLayoutView](index.md)/[setRowHeights](set-row-heights.md)



# setRowHeights  
[jvm]  
Content  
fun [setRowHeights](set-row-heights.md)(rowHeights: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html))  
More info  


Manually set row height of all rows. Overrides automatic resizing based on content from this row.



## See also  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setRowHeights/#kotlin.DoubleArray/PointingToDeclaration/"></a>[tools.aqua.bgw.elements.layoutviews.GridLayoutView](set-auto-row-heights.md)| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setRowHeights/#kotlin.DoubleArray/PointingToDeclaration/"></a>|
  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setRowHeights/#kotlin.DoubleArray/PointingToDeclaration/"></a>rowHeights| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setRowHeights/#kotlin.DoubleArray/PointingToDeclaration/"></a><br><br>New row heights. Array index 0 get applied for the first row etc. Use ROW_HEIGHT_AUTO to restore automatic resizing behaviour.<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setRowHeights/#kotlin.DoubleArray/PointingToDeclaration/"></a>[kotlin.IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html)| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/setRowHeights/#kotlin.DoubleArray/PointingToDeclaration/"></a><br><br>Thrown if Array size does not match row count or values were negative.<br><br>|
  



