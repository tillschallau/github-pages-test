//[BGW](../../../index.md)/[tools.aqua.bgw.util](../index.md)/[KStack](index.md)



# KStack  
 [jvm] class [KStack](index.md)<[T](index.md)>

KStack represents a Last In First Out (LIFO) data structure. It provides useful functions to manipulate the KStack.

   


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.util/KStack/KStack/#/PointingToDeclaration/"></a>[KStack](-k-stack.md)| <a name="tools.aqua.bgw.util/KStack/KStack/#/PointingToDeclaration/"></a> [jvm] fun [KStack](-k-stack.md)()   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.util/KStack/clear/#/PointingToDeclaration/"></a>[clear](clear.md)| <a name="tools.aqua.bgw.util/KStack/clear/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clear](clear.md)()  <br>More info  <br>Clears this KStack.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/indexOf/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[indexOf](index-of.md)| <a name="tools.aqua.bgw.util/KStack/indexOf/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [indexOf](index-of.md)(element: [T](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br>More info  <br>Returns the index of the first occurrence of the specified element in the KStack, or -1 if the specified element is not contained in the KStack.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/isEmpty/#/PointingToDeclaration/"></a>[isEmpty](is-empty.md)| <a name="tools.aqua.bgw.util/KStack/isEmpty/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [isEmpty](is-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Returns whether this KStack is empty or not.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/peek/#/PointingToDeclaration/"></a>[peek](peek.md)| <a name="tools.aqua.bgw.util/KStack/peek/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [peek](peek.md)(): [T](index.md)  <br>More info  <br>Returns the topmost element in this KStack but does not pop it.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/peekAll/#/PointingToDeclaration/"></a>[peekAll](peek-all.md)| <a name="tools.aqua.bgw.util/KStack/peekAll/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [peekAll](peek-all.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br>More info  <br>Returns all elements in this KStack, with the last pushed Element at the highest index.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/pop/#/PointingToDeclaration/"></a>[pop](pop.md)| <a name="tools.aqua.bgw.util/KStack/pop/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [pop](pop.md)(): [T](index.md)  <br>More info  <br>Pops the topmost element in this KStack.  <br><br><br>[jvm]  <br>Content  <br>fun [pop](pop.md)(numToPop: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br>More info  <br>Pops the n topmost elements in this KStack, where n is specified by the parameter.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/popAll/#/PointingToDeclaration/"></a>[popAll](pop-all.md)| <a name="tools.aqua.bgw.util/KStack/popAll/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [popAll](pop-all.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br>More info  <br>Pops all elements in this KStack and returns them in a List, with the last pushed element at the highest index.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/push/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[push](push.md)| <a name="tools.aqua.bgw.util/KStack/push/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [push](push.md)(element: [T](index.md))  <br>More info  <br>Pushes the supplied element onto the KStack.  <br><br><br>[jvm]  <br>Content  <br>fun [push](push.md)(elements: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>)  <br>More info  <br>Pushes all the supplied elements onto the KStack.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/shuffle/#/PointingToDeclaration/"></a>[shuffle](shuffle.md)| <a name="tools.aqua.bgw.util/KStack/shuffle/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [shuffle](shuffle.md)()  <br>More info  <br>Shuffles this KStack.  <br><br><br>|
| <a name="tools.aqua.bgw.util/KStack/size/#/PointingToDeclaration/"></a>[size](size.md)| <a name="tools.aqua.bgw.util/KStack/size/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br>More info  <br>Returns the size of this KStack.  <br><br><br>|

