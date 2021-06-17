---
title: DoubleProperty -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[DoubleProperty](index.md)



# DoubleProperty  
 [jvm] class [DoubleProperty](index.md)(**initialValue**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Property](../-property/index.md)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> 

A Double Property.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/DoubleProperty///PointingToDeclaration/"></a>initialValue| <a name="tools.aqua.bgw.observable/DoubleProperty///PointingToDeclaration/"></a><br><br>initial Value. Default: 0.0<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/DoubleProperty/DoubleProperty/#kotlin.Double/PointingToDeclaration/"></a>[DoubleProperty](-double-property.md)| <a name="tools.aqua.bgw.observable/DoubleProperty/DoubleProperty/#kotlin.Double/PointingToDeclaration/"></a> [jvm] fun [DoubleProperty](-double-property.md)(initialValue: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0)initial Value.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Double]/PointingToDeclaration/"></a>[addListener](index.md#1236083759%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Double]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](index.md#1236083759%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.Double#tools.aqua.bgw.observable.IValueObservable[kotlin.Double]/PointingToDeclaration/"></a>[addListenerAndInvoke](index.md#919816177%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.Double#tools.aqua.bgw.observable.IValueObservable[kotlin.Double]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](index.md#919816177%2FFunctions%2F-302347323)(initialValue: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), listener: [IValueObservable](../-i-value-observable/index.md)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)  <br>More info  <br>Adds a listener and calls update() on this new listener with given initial value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](../-value-observable/clear-listeners.md)| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](../-value-observable/clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.Double/PointingToDeclaration/"></a>[notifyChange](index.md#-843216468%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.Double/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](index.md#-843216468%2FFunctions%2F-302347323)(newValue: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[notifyUnchanged](../-property/notify-unchanged.md)| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyUnchanged](../-property/notify-unchanged.md)()  <br>More info  <br>Notifies all listeners with current value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Double]/PointingToDeclaration/"></a>[removeListener](index.md#428506026%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.Double]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](index.md#428506026%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)  <br>More info  <br>Removes a listener.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/DoubleProperty/value/#/PointingToDeclaration/"></a>[value](index.md#1633767972%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.observable/DoubleProperty/value/#/PointingToDeclaration/"></a> [jvm] var [value](index.md#1633767972%2FProperties%2F-302347323): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Value of this property.   <br>|

