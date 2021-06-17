---
title: findPathToChild -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.core](../index.md)/[Scene](index.md)/[findPathToChild](find-path-to-child.md)



# findPathToChild  
[jvm]  
Content  
fun [findPathToChild](find-path-to-child.md)(elementView: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>  
More info  


Searches node recursively through the visual tree and logs path.



#### Return  


Path to child



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a><br><br>Child to find<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a>[kotlin.IllegalStateException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-state-exception/index.html)| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a><br><br>If child was not in contained in this scene<br><br>|
  



