//[BGW](../../../index.md)/[tools.aqua.bgw.elements.layoutviews](../index.md)/[GridLayoutView](index.md)/[grow](grow.md)



# grow  
[jvm]  
Content  
fun [grow](grow.md)(left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, right: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, top: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0)  
More info  


Grows grid by specified dimensions, filling new cells with NULL values. New rows and columns get automatic resizing behaviour, specified as COLUMN_WIDTH_AUTO and ROW_HEIGHT_AUTO. Therefore new empty rows and columns get rendered with height and width 0.0 e.g. invisible if not specified otherwise.



## See also  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>[tools.aqua.bgw.elements.layoutviews.GridLayoutView](remove-row.md)| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>|
  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>left| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>column count to be added to the left.<br><br>|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>right| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>column count to be added to the right.<br><br>|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>top| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>row count to be added on the top.<br><br>|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>bottom| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>row count to be added on the bottom.<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>[kotlin.IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html)| <a name="tools.aqua.bgw.elements.layoutviews/GridLayoutView/grow/#kotlin.Int#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>If any value passed was negative.<br><br>|
  



