---
title: BidirectionalMap -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.util](../index.md)/[BidirectionalMap](index.md)



# BidirectionalMap  
 [jvm] class [BidirectionalMap](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>

A bidirectional map.

   


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.util/BidirectionalMap/BidirectionalMap/#/PointingToDeclaration/"></a>[BidirectionalMap](-bidirectional-map.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/BidirectionalMap/#/PointingToDeclaration/"></a> [jvm] fun [BidirectionalMap](-bidirectional-map.md)()   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.util/BidirectionalMap/add/#TypeParam(bounds=[kotlin.Any])#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[add](add.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/add/#TypeParam(bounds=[kotlin.Any])#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [add](add.md)(entity: [T](index.md), elementView: [R](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Adds a relation A -> B if domain does not contain A and coDomain does not contain B.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/backward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[backward](backward.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/backward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [backward](backward.md)(value: [R](index.md)): [T](index.md)  <br>More info  <br>Backward lookup for entry.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/clear/#/PointingToDeclaration/"></a>[clear](clear.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/clear/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clear](clear.md)()  <br>More info  <br>Clears map.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/contains/#TypeParam(bounds=[kotlin.Any])#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[contains](contains.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/contains/#TypeParam(bounds=[kotlin.Any])#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [contains](contains.md)(entity: [T](index.md), value: [R](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Returns whether relation A -> B exists.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/containsBackward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[containsBackward](contains-backward.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/containsBackward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [containsBackward](contains-backward.md)(value: [R](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Returns whether a relation * -> B exists.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/containsForward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[containsForward](contains-forward.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/containsForward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [containsForward](contains-forward.md)(entity: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Returns whether a relation A -> * exists.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/forward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[forward](forward.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/forward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [forward](forward.md)(entity: [T](index.md)): [R](index.md)  <br>More info  <br>Forward lookup for entry.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/getCoDomain/#/PointingToDeclaration/"></a>[getCoDomain](get-co-domain.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/getCoDomain/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [getCoDomain](get-co-domain.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[R](index.md)>  <br>More info  <br>Returns the coDomain as a set.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/getDomain/#/PointingToDeclaration/"></a>[getDomain](get-domain.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/getDomain/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [getDomain](get-domain.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[T](index.md)>  <br>More info  <br>Returns the domain as a set.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/remove/#kotlin.Pair[TypeParam(bounds=[kotlin.Any]),TypeParam(bounds=[kotlin.Any])]/PointingToDeclaration/"></a>[remove](remove.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/remove/#kotlin.Pair[TypeParam(bounds=[kotlin.Any]),TypeParam(bounds=[kotlin.Any])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [remove](remove.md)(pair: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[T](index.md), [R](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>fun [remove](remove.md)(entity: [T](index.md), value: [R](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Removes relation A -> B.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/removeBackward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[removeBackward](remove-backward.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/removeBackward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeBackward](remove-backward.md)(value: [R](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Removes by backward lookup.  <br><br><br>|
| <a name="tools.aqua.bgw.util/BidirectionalMap/removeForward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[removeForward](remove-forward.md)| <a name="tools.aqua.bgw.util/BidirectionalMap/removeForward/#TypeParam(bounds=[kotlin.Any])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeForward](remove-forward.md)(entity: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Removes by forward lookup.  <br><br><br>|

