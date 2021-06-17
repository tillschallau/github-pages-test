---
title: subList -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[ObservableList](index.md)/[subList](sub-list.md)



# subList  
[jvm]  
Content  
fun [subList](sub-list.md)(fromIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), toIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  
More info  


Returns a view of the portion of this list between the specified fromIndex, inclusive, and toIndex, exclusive.  (If fromIndex and toIndex are equal, the returned list is empty.)  The returned list is backed by this list, so non-structural changes in the returned list are reflected in this list, and vice-versa. The returned list supports all of the optional list operations.



This method eliminates the need for explicit range operations (of the sort that commonly exist for arrays).  Any operation that expects a list can be used as a range operation by passing a subList view instead of a whole list.  For example, the following idiom removes a range of elements from a list:

<pre>
list.subList(from, to).clear();
</pre>

Similar idioms may be constructed for .indexOf and .lastIndexOf, and all of the algorithms in the [Collections](https://docs.oracle.com/javase/8/docs/api/java/util/Collections.html) class can be applied to a subList.



The semantics of the list returned by this method become undefined if the backing list (i.e., this list) is *structurally modified* in any way other than via the returned list.  (Structural modifications are those that change the size of this list, or otherwise perturb it in such a fashion that iterations in progress may yield incorrect results.)



#### Throws  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObservableList/subList/#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>[kotlin.IndexOutOfBoundsException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-index-out-of-bounds-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/subList/#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>{@inheritDoc}<br><br>|
| <a name="tools.aqua.bgw.observable/ObservableList/subList/#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>[kotlin.IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html)| <a name="tools.aqua.bgw.observable/ObservableList/subList/#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a><br><br>{@inheritDoc}<br><br>|
  



