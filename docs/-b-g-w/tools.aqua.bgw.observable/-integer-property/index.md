---
title: IntegerProperty -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[IntegerProperty](index.md)



# IntegerProperty  
 [jvm] class [IntegerProperty](index.md)(**initialValue**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Property](../-property/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> 

An Integer Property.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/IntegerProperty///PointingToDeclaration/"></a>initialValue| <a name="tools.aqua.bgw.observable/IntegerProperty///PointingToDeclaration/"></a><br><br>initial Value. Default: 0<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/IntegerProperty/IntegerProperty/#kotlin.Int/PointingToDeclaration/"></a>[IntegerProperty](-integer-property.md)| <a name="tools.aqua.bgw.observable/IntegerProperty/IntegerProperty/#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun [IntegerProperty](-integer-property.md)(initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0)initial Value.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Int]/PointingToDeclaration/"></a>[addListener](index.md#1349706233%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Int]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](index.md#1349706233%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>)  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.Int#tools.aqua.bgw.observable.IValueObservable[kotlin.Int]/PointingToDeclaration/"></a>[addListenerAndInvoke](index.md#180164239%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.Int#tools.aqua.bgw.observable.IValueObservable[kotlin.Int]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](index.md#180164239%2FFunctions%2F-302347323)(initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), listener: [IValueObservable](../-i-value-observable/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>)  <br>More info  <br>Adds a listener and calls update() on this new listener with given initial value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](../-value-observable/clear-listeners.md)| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](../-value-observable/clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.Int/PointingToDeclaration/"></a>[notifyChange](index.md#-903821770%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.Int/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](index.md#-903821770%2FFunctions%2F-302347323)(newValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[notifyUnchanged](../-property/notify-unchanged.md)| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyUnchanged](../-property/notify-unchanged.md)()  <br>More info  <br>Notifies all listeners with current value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Int]/PointingToDeclaration/"></a>[removeListener](index.md#-425053090%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Int]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](index.md#-425053090%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>)  <br>More info  <br>Removes a listener.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/IntegerProperty/value/#/PointingToDeclaration/"></a>[value](index.md#-1743583911%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.observable/IntegerProperty/value/#/PointingToDeclaration/"></a> [jvm] var [value](index.md#-1743583911%2FProperties%2F-302347323): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Value of this property.   <br>|

