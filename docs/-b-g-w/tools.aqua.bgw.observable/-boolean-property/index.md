---
title: BooleanProperty -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[BooleanProperty](index.md)



# BooleanProperty  
 [jvm] class [BooleanProperty](index.md)(**initialValue**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Property](../-property/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)> 

A Boolean Property.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/BooleanProperty///PointingToDeclaration/"></a>initialValue| <a name="tools.aqua.bgw.observable/BooleanProperty///PointingToDeclaration/"></a><br><br>initial Value. Default: false<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/BooleanProperty/BooleanProperty/#kotlin.Boolean/PointingToDeclaration/"></a>[BooleanProperty](-boolean-property.md)| <a name="tools.aqua.bgw.observable/BooleanProperty/BooleanProperty/#kotlin.Boolean/PointingToDeclaration/"></a> [jvm] fun [BooleanProperty](-boolean-property.md)(initialValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)initial Value.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Boolean]/PointingToDeclaration/"></a>[addListener](index.md#650178610%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Boolean]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](index.md#650178610%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>)  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.Boolean#tools.aqua.bgw.observable.IValueObservable[kotlin.Boolean]/PointingToDeclaration/"></a>[addListenerAndInvoke](index.md#405740353%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.Boolean#tools.aqua.bgw.observable.IValueObservable[kotlin.Boolean]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](index.md#405740353%2FFunctions%2F-302347323)(initialValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), listener: [IValueObservable](../-i-value-observable/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>)  <br>More info  <br>Adds a listener and calls update() on this new listener with given initial value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](../-value-observable/clear-listeners.md)| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](../-value-observable/clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.Boolean/PointingToDeclaration/"></a>[notifyChange](index.md#-453072931%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.Boolean/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](index.md#-453072931%2FFunctions%2F-302347323)(newValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[notifyUnchanged](../-property/notify-unchanged.md)| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyUnchanged](../-property/notify-unchanged.md)()  <br>More info  <br>Notifies all listeners with current value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Boolean]/PointingToDeclaration/"></a>[removeListener](index.md#1385072663%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Boolean]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](index.md#1385072663%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>)  <br>More info  <br>Removes a listener.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/BooleanProperty/value/#/PointingToDeclaration/"></a>[value](index.md#-120060113%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.observable/BooleanProperty/value/#/PointingToDeclaration/"></a> [jvm] var [value](index.md#-120060113%2FProperties%2F-302347323): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Value of this property.   <br>|

