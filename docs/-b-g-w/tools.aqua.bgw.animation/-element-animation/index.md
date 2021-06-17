//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[ElementAnimation](index.md)



# ElementAnimation  
 [jvm] sealed class [ElementAnimation](index.md)<[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> : [Animation](../-animation/index.md)

ElementAnimation superclass.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/ElementAnimation///PointingToDeclaration/"></a>element| <a name="tools.aqua.bgw.animation/ElementAnimation///PointingToDeclaration/"></a><br><br>ElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/ElementAnimation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/ElementAnimation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/ElementAnimation/duration/#/PointingToDeclaration/"></a>[duration](index.md#1362376584%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/ElementAnimation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](index.md#1362376584%2FProperties%2F-1902411840): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/ElementAnimation/element/#/PointingToDeclaration/"></a>[element](element.md)| <a name="tools.aqua.bgw.animation/ElementAnimation/element/#/PointingToDeclaration/"></a> [jvm] val [element](element.md): [T](index.md)ElementView to animate   <br>|
| <a name="tools.aqua.bgw.animation/ElementAnimation/onFinished/#/PointingToDeclaration/"></a>[onFinished](index.md#620939403%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/ElementAnimation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](index.md#620939403%2FProperties%2F-1902411840): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>? = nullEvent handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/ElementAnimation/running/#/PointingToDeclaration/"></a>[running](index.md#-1424906209%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/ElementAnimation/running/#/PointingToDeclaration/"></a> [jvm] var [running](index.md#-1424906209%2FProperties%2F-1902411840): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = falseBoolean indicating whether the animation is currently playing.   <br>|


## Inheritors  
  
|  Name | 
|---|
| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a>[DiceAnimation](../-dice-animation/index.md)|
| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a>[FlipAnimation](../-flip-animation/index.md)|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>[MovementAnimation](../-movement-animation/index.md)|
| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a>[RotationAnimation](../-rotation-animation/index.md)|

