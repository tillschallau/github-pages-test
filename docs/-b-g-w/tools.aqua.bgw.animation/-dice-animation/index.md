//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[DiceAnimation](index.md)



# DiceAnimation  
 [jvm] class [DiceAnimation](index.md)<[T](index.md) : [DiceView](../../tools.aqua.bgw.elements.gameelements/-dice-view/index.md)>(**dice**: [T](index.md), **toSide**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **speed**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [ElementAnimation](../-element-animation/index.md)<[T](index.md)> 

A dice roll animation.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a>dice| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a><br><br>DiceView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a>toSide| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a><br><br>Resulting side after roll<br><br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a>speed| <a name="tools.aqua.bgw.animation/DiceAnimation///PointingToDeclaration/"></a><br><br>Count of steps. Default: 50 steps<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/DiceAnimation/DiceAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.gameelements.DiceView])#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>[DiceAnimation](-dice-animation.md)| <a name="tools.aqua.bgw.animation/DiceAnimation/DiceAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.gameelements.DiceView])#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun <[T](index.md) : [DiceView](../../tools.aqua.bgw.elements.gameelements/-dice-view/index.md)> [DiceAnimation](-dice-animation.md)(dice: [T](index.md), toSide: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000, speed: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 50)DiceView to animate   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/DiceAnimation/duration/#/PointingToDeclaration/"></a>[duration](index.md#-1441825487%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DiceAnimation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](index.md#-1441825487%2FProperties%2F-1902411840): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation/element/#/PointingToDeclaration/"></a>[element](index.md#-1189908807%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DiceAnimation/element/#/PointingToDeclaration/"></a> [jvm] val [element](index.md#-1189908807%2FProperties%2F-1902411840): [T](index.md)ElementView to animate   <br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation/onFinished/#/PointingToDeclaration/"></a>[onFinished](index.md#-1272756236%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DiceAnimation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](index.md#-1272756236%2FProperties%2F-1902411840): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>?Event handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation/running/#/PointingToDeclaration/"></a>[running](index.md#978487638%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/DiceAnimation/running/#/PointingToDeclaration/"></a> [jvm] var [running](index.md#978487638%2FProperties%2F-1902411840): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Boolean indicating whether the animation is currently playing.   <br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation/speed/#/PointingToDeclaration/"></a>[speed](speed.md)| <a name="tools.aqua.bgw.animation/DiceAnimation/speed/#/PointingToDeclaration/"></a> [jvm] val [speed](speed.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 50Count of steps.   <br>|
| <a name="tools.aqua.bgw.animation/DiceAnimation/toSide/#/PointingToDeclaration/"></a>[toSide](to-side.md)| <a name="tools.aqua.bgw.animation/DiceAnimation/toSide/#/PointingToDeclaration/"></a> [jvm] val [toSide](to-side.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Resulting side after roll   <br>|

