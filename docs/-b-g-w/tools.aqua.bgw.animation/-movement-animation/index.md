---
title: MovementAnimation -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[MovementAnimation](index.md)



# MovementAnimation  
 [jvm] class [MovementAnimation](index.md)<[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>(**elementView**: [T](index.md), **fromX**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **toX**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **fromY**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **toY**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [ElementAnimation](../-element-animation/index.md)<[T](index.md)> 

A movement animation. Moves given ElementView relative to parents anchor point.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a><br><br>GameElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>fromX| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a><br><br>Initial X position. Default: current PosX<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>toX| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a><br><br>Resulting X position. Default: current PosX<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>fromY| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a><br><br>Initial X position. Default: current PosY<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>toY| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a><br><br>Resulting X position. Default: current PosY<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/MovementAnimation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>[MovementAnimation](-movement-animation.md)| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [MovementAnimation](-movement-animation.md)(elementView: [T](index.md), byX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = 0.0, byY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = 0.0, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)A movement animation.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>[MovementAnimation](-movement-animation.md)| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [MovementAnimation](-movement-animation.md)(elementView: [T](index.md), fromX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posX, toX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posX, fromY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posY, toY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posY, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)GameElementView to animate   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/MovementAnimation/duration/#/PointingToDeclaration/"></a>[duration](index.md#875488809%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.animation/MovementAnimation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](index.md#875488809%2FProperties%2F-302347323): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/element/#/PointingToDeclaration/"></a>[element](index.md#963053249%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.animation/MovementAnimation/element/#/PointingToDeclaration/"></a> [jvm] val [element](index.md#963053249%2FProperties%2F-302347323): [T](index.md)ElementView to animate   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/fromX/#/PointingToDeclaration/"></a>[fromX](from-x.md)| <a name="tools.aqua.bgw.animation/MovementAnimation/fromX/#/PointingToDeclaration/"></a> [jvm] val [fromX](from-x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Initial X position.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/fromY/#/PointingToDeclaration/"></a>[fromY](from-y.md)| <a name="tools.aqua.bgw.animation/MovementAnimation/fromY/#/PointingToDeclaration/"></a> [jvm] val [fromY](from-y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Initial Y position.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/onFinished/#/PointingToDeclaration/"></a>[onFinished](index.md#873222892%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.animation/MovementAnimation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](index.md#873222892%2FProperties%2F-302347323): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>?Event handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/running/#/PointingToDeclaration/"></a>[running](index.md#-1163517602%2FProperties%2F-302347323)| <a name="tools.aqua.bgw.animation/MovementAnimation/running/#/PointingToDeclaration/"></a> [jvm] var [running](index.md#-1163517602%2FProperties%2F-302347323): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Boolean indicating whether the animation is currently playing.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/toX/#/PointingToDeclaration/"></a>[toX](to-x.md)| <a name="tools.aqua.bgw.animation/MovementAnimation/toX/#/PointingToDeclaration/"></a> [jvm] val [toX](to-x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Resulting X position.   <br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/toY/#/PointingToDeclaration/"></a>[toY](to-y.md)| <a name="tools.aqua.bgw.animation/MovementAnimation/toY/#/PointingToDeclaration/"></a> [jvm] val [toY](to-y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Resulting Y position.   <br>|

