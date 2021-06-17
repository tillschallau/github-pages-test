//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[ObjectProperty](index.md)



# ObjectProperty  
 [jvm] class [ObjectProperty](index.md)<[T](index.md)>(**initialValue**: [T](index.md)) : [Property](../-property/index.md)<[T](index.md)> 

A Object Property with generic type.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObjectProperty///PointingToDeclaration/"></a>initialValue| <a name="tools.aqua.bgw.observable/ObjectProperty///PointingToDeclaration/"></a><br><br>initial Value.<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ObjectProperty/ObjectProperty/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[ObjectProperty](-object-property.md)| <a name="tools.aqua.bgw.observable/ObjectProperty/ObjectProperty/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a> [jvm] fun <[T](index.md)> [ObjectProperty](-object-property.md)(initialValue: [T](index.md))initial Value.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[addListener](../-value-observable/add-listener.md)| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](../-value-observable/add-listener.md)(listener: [IValueObservable](../-i-value-observable/index.md)<[T](index.md)>)  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#TypeParam(bounds=[kotlin.Any?])#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[addListenerAndInvoke](../-value-observable/add-listener-and-invoke.md)| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#TypeParam(bounds=[kotlin.Any?])#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](../-value-observable/add-listener-and-invoke.md)(initialValue: [T](index.md), listener: [IValueObservable](../-i-value-observable/index.md)<[T](index.md)>)  <br>More info  <br>Adds a listener and calls update() on this new listener with given initial value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](../-value-observable/clear-listeners.md)| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](../-value-observable/clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[notifyChange](../-value-observable/notify-change.md)| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](../-value-observable/notify-change.md)(newValue: [T](index.md))  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[notifyUnchanged](../-property/notify-unchanged.md)| <a name="tools.aqua.bgw.observable/Property/notifyUnchanged/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyUnchanged](../-property/notify-unchanged.md)()  <br>More info  <br>Notifies all listeners with current value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[removeListener](../-value-observable/remove-listener.md)| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](../-value-observable/remove-listener.md)(listener: [IValueObservable](../-i-value-observable/index.md)<[T](index.md)>)  <br>More info  <br>Removes a listener.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ObjectProperty/value/#/PointingToDeclaration/"></a>[value](index.md#-2050503946%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.observable/ObjectProperty/value/#/PointingToDeclaration/"></a> [jvm] var [value](index.md#-2050503946%2FProperties%2F-1902411840): [T](index.md)Value of this property.   <br>|

