//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[ObservableList](index.md)/[addAll](add-all.md)



# addAll  
[jvm]  
Content  
fun [addAll](add-all.md)(elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  
More info  


Appends all of the elements in the specified collection to the end of this list, in the order that they are returned by the specified collection's Iterator.  The behavior of this operation is undefined if the specified collection is modified while the operation is in progress.  (This implies that the behavior of this call is undefined if the specified collection is this list, and this list is nonempty.)



#### Return  


true if this list changed as a result of the call



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>elements| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a><br><br>collection containing elements to be added to this list<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[kotlin.NullPointerException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null-pointer-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a><br><br>if the specified collection is null<br><br>|
  


[jvm]  
Content  
fun [addAll](add-all.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  
More info  


Inserts all of the elements in the specified collection into this list, starting at the specified position.  Shifts the element currently at that position (if any) and any subsequent elements to the right (increases their indices).  The new elements will appear in the list in the order that they are returned by the specified collection's iterator.



#### Return  


true if this list changed as a result of the call



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>index| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a><br><br>index at which to insert the first element from the specified collection<br><br>|
| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>elements| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a><br><br>collection containing elements to be added to this list<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[kotlin.IndexOutOfBoundsException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-index-out-of-bounds-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a><br><br>{@inheritDoc}<br><br>|
| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[kotlin.NullPointerException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null-pointer-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a><br><br>if the specified collection is null<br><br>|
  



