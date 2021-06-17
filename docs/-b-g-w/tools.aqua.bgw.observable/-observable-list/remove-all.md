//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[ObservableList](index.md)/[removeAll](remove-all.md)



# removeAll  
[jvm]  
Content  
fun [removeAll](remove-all.md)(elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  
More info  


Removes from this list all of its elements that are contained in the specified collection.



#### Return  


true if this list changed as a result of the call



## See also  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a>[kotlin.collections.Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/contains.html)| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a>|
  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a>elements| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a><br><br>collection containing elements to be removed from this list<br><br>|
  


#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a>[kotlin.ClassCastException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-class-cast-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a><br><br>if the class of an element of this list is incompatible with the specified collection (Collection.html#optional-restrictions)<br><br>|
| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a>[kotlin.NullPointerException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null-pointer-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/removeAll/#kotlin.collections.Collection[*]/PointingToDeclaration/"></a><br><br>if this list contains a null element and the specified collection does not permit null elements (Collection.html#optional-restrictions), or if the specified collection is null<br><br>|
  



