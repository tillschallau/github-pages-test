//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[ValueObservable](index.md)



# ValueObservable  
 [jvm] open class [ValueObservable](index.md)<[T](index.md)>

Basic observable with value.

   


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/ValueObservable/#/PointingToDeclaration/"></a>[ValueObservable](-value-observable.md)| <a name="tools.aqua.bgw.observable/ValueObservable/ValueObservable/#/PointingToDeclaration/"></a> [jvm] fun [ValueObservable](-value-observable.md)()   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[addListener](add-listener.md)| <a name="tools.aqua.bgw.observable/ValueObservable/addListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](add-listener.md)(listener: [IValueObservable](../-i-value-observable/index.md)<[T](index.md)>)  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#TypeParam(bounds=[kotlin.Any?])#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[addListenerAndInvoke](add-listener-and-invoke.md)| <a name="tools.aqua.bgw.observable/ValueObservable/addListenerAndInvoke/#TypeParam(bounds=[kotlin.Any?])#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](add-listener-and-invoke.md)(initialValue: [T](index.md), listener: [IValueObservable](../-i-value-observable/index.md)<[T](index.md)>)  <br>More info  <br>Adds a listener and calls update() on this new listener with given initial value.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](clear-listeners.md)| <a name="tools.aqua.bgw.observable/ValueObservable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[notifyChange](notify-change.md)| <a name="tools.aqua.bgw.observable/ValueObservable/notifyChange/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](notify-change.md)(newValue: [T](index.md))  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[removeListener](remove-listener.md)| <a name="tools.aqua.bgw.observable/ValueObservable/removeListener/#tools.aqua.bgw.observable.IValueObservable[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](remove-listener.md)(listener: [IValueObservable](../-i-value-observable/index.md)<[T](index.md)>)  <br>More info  <br>Removes a listener.  <br><br><br>|


## Inheritors  
  
|  Name | 
|---|
| <a name="tools.aqua.bgw.observable/Property///PointingToDeclaration/"></a>[Property](../-property/index.md)|

