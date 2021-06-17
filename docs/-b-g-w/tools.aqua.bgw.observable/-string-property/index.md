---
title: StringProperty -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[StringProperty](index.md)



# StringProperty  
 [jvm] class [StringProperty](index.md)(**initialValue**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Property](../-property/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> 

A String Property.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/StringProperty///PointingToDeclaration/"></a>initialValue| <a name="tools.aqua.bgw.observable/StringProperty///PointingToDeclaration/"></a><br><br>initial Value. Default: Empty string<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/StringProperty/StringProperty/#kotlin.String/PointingToDeclaration/"></a>[StringProperty](-string-property.md)| <a name="tools.aqua.bgw.observable/StringProperty/StringProperty/#kotlin.String/PointingToDeclaration/"></a> [jvm] fun [StringProperty](-string-property.md)(initialValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "")initial Value.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.String]/PointingToDeclaration/"></a>[addListener](index.md#-315471761%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.String]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](index.md#-315471761%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>)  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.String#tools.aqua.bgw.observable.IValueObservable[kotlin.String]/PointingToDeclaration/"></a>[addListenerAndInvoke](index.md#754552817%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#kotlin.String#tools.aqua.bgw.observable.IValueObservable[kotlin.String]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](index.md#754552817%2FFunctions%2F-302347323)(initialValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), listener: [IValueObservable](../-i-value-observable/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>)  <br>More info  <br>Adds a listener and calls update() on this new listener with given initial value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](../-value-observable/clear-listeners.md)| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](../-value-observable/clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.String/PointingToDeclaration/"></a>[notifyChange](index.md#1323490668%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#kotlin.String/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](index.md#1323490668%2FFunctions%2F-302347323)(newValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[notifyUnchanged](../-property/notify-unchanged.md)| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyUnchanged](../-property/notify-unchanged.md)()  <br>More info  <br>Notifies all listeners with current value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.String]/PointingToDeclaration/"></a>[removeListener](index.md#-1123049494%2FFunctions%2F-302347323)| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[kotlin.String]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](index.md#-1123049494%2FFunctions%2F-302347323)(listener: [IValueObservable](../-i-value-observable/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>)  <br>More info  <br>Removes a listener.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/StringProperty/value/#/PointingToDeclaration/"></a>[value](index.md#-1964562972%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.observable/StringProperty/value/#/PointingToDeclaration/"></a> [jvm] var [value](index.md#-1964562972%2FProperties%2F-302347323): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)Value of this property.   <br>|

