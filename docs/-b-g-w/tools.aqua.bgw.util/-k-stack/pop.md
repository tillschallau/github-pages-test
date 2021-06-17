---
title: pop -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.util](../index.md)/[KStack](index.md)/[pop](pop.md)



# pop  
[jvm]  
Content  
fun [pop](pop.md)(): [T](index.md)  
More info  


Pops the topmost element in this KStack.



#### Return  


topmost element in this KSTack.

  


[jvm]  
Content  
fun [pop](pop.md)(numToPop: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  
More info  


Pops the n topmost elements in this KStack, where n is specified by the parameter.



#### Return  


the popped elements in a List, with the last popped element at the highest index.



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.util/KStack/pop/#kotlin.Int/PointingToDeclaration/"></a>numToPop| <a name="tools.aqua.bgw.util/KStack/pop/#kotlin.Int/PointingToDeclaration/"></a><br><br>specifies how many elements to pop.<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.util/KStack/pop/#kotlin.Int/PointingToDeclaration/"></a>[java.lang.IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html)| <a name="tools.aqua.bgw.util/KStack/pop/#kotlin.Int/PointingToDeclaration/"></a><br><br>if numToPop is negative or greater than the KStack's size.<br><br>|
  



