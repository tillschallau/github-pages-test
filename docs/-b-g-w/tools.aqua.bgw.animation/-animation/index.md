//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[Animation](index.md)



# Animation  
 [jvm] sealed class [Animation](index.md)

Animation superclass.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/Animation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/Animation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/Animation/duration/#/PointingToDeclaration/"></a>[duration](duration.md)| <a name="tools.aqua.bgw.animation/Animation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](duration.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/Animation/onFinished/#/PointingToDeclaration/"></a>[onFinished](on-finished.md)| <a name="tools.aqua.bgw.animation/Animation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](on-finished.md): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>? = nullEvent handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/Animation/running/#/PointingToDeclaration/"></a>[running](running.md)| <a name="tools.aqua.bgw.animation/Animation/running/#/PointingToDeclaration/"></a> [jvm] var [running](running.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = falseBoolean indicating whether the animation is currently playing.   <br>|


## Inheritors  
  
|  Name | 
|---|
| <a name="tools.aqua.bgw.animation/DelayAnimation///PointingToDeclaration/"></a>[DelayAnimation](../-delay-animation/index.md)|
| <a name="tools.aqua.bgw.animation/ElementAnimation///PointingToDeclaration/"></a>[ElementAnimation](../-element-animation/index.md)|

