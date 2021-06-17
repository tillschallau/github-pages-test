//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[DelayAnimation](index.md)



# DelayAnimation  
 [jvm] class [DelayAnimation](index.md)(**duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Animation](../-animation/index.md)

An asynchronous delay that fires onFinished after given duration.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/DelayAnimation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/DelayAnimation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/DelayAnimation/DelayAnimation/#kotlin.Int/PointingToDeclaration/"></a>[DelayAnimation](-delay-animation.md)| <a name="tools.aqua.bgw.animation/DelayAnimation/DelayAnimation/#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun [DelayAnimation](-delay-animation.md)(duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)Animation duration in milliseconds.   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/DelayAnimation/duration/#/PointingToDeclaration/"></a>[duration](index.md#1747322913%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DelayAnimation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](index.md#1747322913%2FProperties%2F-1902411840): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/DelayAnimation/onFinished/#/PointingToDeclaration/"></a>[onFinished](index.md#1187174116%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DelayAnimation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](index.md#1187174116%2FProperties%2F-1902411840): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>? = nullEvent handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/DelayAnimation/running/#/PointingToDeclaration/"></a>[running](index.md#-1966677914%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DelayAnimation/running/#/PointingToDeclaration/"></a> [jvm] var [running](index.md#-1966677914%2FProperties%2F-1902411840): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = falseBoolean indicating whether the animation is currently playing.   <br>|

