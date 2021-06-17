---
title: Observable -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.observable](../index.md)/[Observable](index.md)



# Observable  
 [jvm] open class [Observable](index.md)

Basic observable.

   


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.observable/Observable/Observable/#/PointingToDeclaration/"></a>[Observable](-observable.md)| <a name="tools.aqua.bgw.observable/Observable/Observable/#/PointingToDeclaration/"></a> [jvm] fun [Observable](-observable.md)()   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.observable/Observable/addListener/#tools.aqua.bgw.observable.IObservable/PointingToDeclaration/"></a>[addListener](add-listener.md)| <a name="tools.aqua.bgw.observable/Observable/addListener/#tools.aqua.bgw.observable.IObservable/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListener](add-listener.md)(listener: [IObservable](../-i-observable/index.md))  <br>More info  <br>Adds a listener silently.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Observable/addListenerAndInvoke/#tools.aqua.bgw.observable.IObservable/PointingToDeclaration/"></a>[addListenerAndInvoke](add-listener-and-invoke.md)| <a name="tools.aqua.bgw.observable/Observable/addListenerAndInvoke/#tools.aqua.bgw.observable.IObservable/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addListenerAndInvoke](add-listener-and-invoke.md)(listener: [IObservable](../-i-observable/index.md))  <br>More info  <br>Adds a listener and calls update() on this new listener.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Observable/clearListeners/#/PointingToDeclaration/"></a>[clearListeners](clear-listeners.md)| <a name="tools.aqua.bgw.observable/Observable/clearListeners/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearListeners](clear-listeners.md)()  <br>More info  <br>Removes all listeners.  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Observable/notifyChange/#/PointingToDeclaration/"></a>[notifyChange](notify-change.md)| <a name="tools.aqua.bgw.observable/Observable/notifyChange/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [notifyChange](notify-change.md)()  <br>More info  <br>Notifies all listeners by calling update().  <br><br><br>|
| <a name="tools.aqua.bgw.observable/Observable/removeListener/#tools.aqua.bgw.observable.IObservable/PointingToDeclaration/"></a>[removeListener](remove-listener.md)| <a name="tools.aqua.bgw.observable/Observable/removeListener/#tools.aqua.bgw.observable.IObservable/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeListener](remove-listener.md)(listener: [IObservable](../-i-observable/index.md))  <br>More info  <br>Removes a listener.  <br><br><br>|


## Inheritors  
  
|  Name | 
|---|
| <a name="tools.aqua.bgw.elements/ElementView///PointingToDeclaration/"></a>[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)|
| <a name="tools.aqua.bgw.observable/ObservableList///PointingToDeclaration/"></a>[ObservableList](../-observable-list/index.md)|

